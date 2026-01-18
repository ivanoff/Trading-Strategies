# Trading Strategies

Documento disponible en español: [Estrategias comerciales](./README_SP.md)
Document disponible en français : [Stratégies de trading](./README_FR.md)
Documento disponibile in italiano: [Strategie di trading](./README_IT.md)
日本語版: [取引戦略](./README_JP.md)
中文版本: [交易策略](./README_CN.md)
Документ доступен на русском: [Стратегии торговли](./README_RU.md)


- [Trading Strategies](#trading-strategies)
  - [Strategies](#strategies)
    - [RSI + Bollinger Bands (rsi\_bb)](#rsi--bollinger-bands-rsi_bb)
    - [MACD (macd)](#macd-macd)
    - [RSI Basic (rsi\_basic)](#rsi-basic-rsi_basic)
    - [SMA Crossover (sma\_cross)](#sma-crossover-sma_cross)
    - [Bollinger Band Squeeze (bb\_squeeze)](#bollinger-band-squeeze-bb_squeeze)
    - [Donchian Channel Breakout / Turtle Trading (donchian)](#donchian-channel-breakout--turtle-trading-donchian)
    - [Ichimoku Cloud Breakout (ichimoku)](#ichimoku-cloud-breakout-ichimoku)
    - [ADX + DMI (adx\_dmi)](#adx--dmi-adx_dmi)
    - [OBV Trend (obv\_trend)](#obv-trend-obv_trend)
    - [SuperTrend Strategy (supertrend)](#supertrend-strategy-supertrend)
    - [EMA Trend + Stochastic RSI (ema\_stoch)](#ema-trend--stochastic-rsi-ema_stoch)
    - [Parabolic SAR Strategy (psar)](#parabolic-sar-strategy-psar)
    - [Money Flow Index (MFI) (mfi\_div)](#money-flow-index-mfi-mfi_div)
    - [TEMA Crossover (tema\_cross)](#tema-crossover-tema_cross)
    - [Keltner Channel Pullback (keltner\_pullback)](#keltner-channel-pullback-keltner_pullback)
    - [Awesome Oscillator (ao\_saucer)](#awesome-oscillator-ao_saucer)
    - [CCI Correction (cci\_correction)](#cci-correction-cci_correction)
    - [VWAP Trend (vwap\_cross)](#vwap-trend-vwap_cross)
    - [Stochastic RSI (stoch\_rsi)](#stochastic-rsi-stoch_rsi)
    - [Elder's Force Index (elder\_force)](#elders-force-index-elder_force)
    - [Williams %R (williams\_r)](#williams-r-williams_r)
    - [Kaufman's Adaptive MA (kama\_trend)](#kaufmans-adaptive-ma-kama_trend)
    - [Rate of Change (roc)](#rate-of-change-roc)
    - [ATR Channel Breakout (volty\_channel)](#atr-channel-breakout-volty_channel)
    - [Linear Regression Slope (lin\_reg)](#linear-regression-slope-lin_reg)
    - [Chaikin Money Flow (cmf\_trend)](#chaikin-money-flow-cmf_trend)
    - [Vortex Indicator (vortex)](#vortex-indicator-vortex)
    - [Aroon Strategy (aroon)](#aroon-strategy-aroon)
    - [TRIX (Triple Exponential Average) (trix\_strat)](#trix-triple-exponential-average-trix_strat)
    - [Coppock Curve (coppock)](#coppock-curve-coppock)
    - [Commodity Channel Index (cci\_trend)](#commodity-channel-index-cci_trend)
    - [Hull Moving Average Trend (hma\_trend)](#hull-moving-average-trend-hma_trend)
    - [Z-Score Strategy (z\_score)](#z-score-strategy-z_score)
    - [VWMA vs SMA (vwma\_cross)](#vwma-vs-sma-vwma_cross)
    - [Connors RSI 2 (rsi\_2)](#connors-rsi-2-rsi_2)
    - [Williams Fractals (fractal\_breakout)](#williams-fractals-fractal_breakout)
    - [Fibonacci Bollinger Bands (fib\_bands)](#fibonacci-bollinger-bands-fib_bands)
    - [Chandelier Exit Strategy (chandelier\_trend)](#chandelier-exit-strategy-chandelier_trend)
    - [Inside Bar Breakout (inside\_bar)](#inside-bar-breakout-inside_bar)
    - [TD Sequential (Simplified) (td\_seq)](#td-sequential-simplified-td_seq)
    - [Ehlers Fisher Transform (fisher\_trans)](#ehlers-fisher-transform-fisher_trans)
    - [RSI Divergence (rsi\_div)](#rsi-divergence-rsi_div)
    - [Heikin Ashi Trend (ha\_trend)](#heikin-ashi-trend-ha_trend)
    - [Standard Deviation Channel (std\_channel)](#standard-deviation-channel-std_channel)
    - [Pivot Points Reversal (pivot\_rev)](#pivot-points-reversal-pivot_rev)
    - [Williams Alligator (alligator)](#williams-alligator-alligator)
    - [Engulfing Pattern (engulfing\_candle)](#engulfing-pattern-engulfing_candle)
    - [McGinley Dynamic (mcginley)](#mcginley-dynamic-mcginley)
    - [Dual Thrust (dual\_thrust)](#dual-thrust-dual_thrust)
    - [Chande Momentum Oscillator (cmo\_strat)](#chande-momentum-oscillator-cmo_strat)
    - [Ease of Movement (eom\_trend)](#ease-of-movement-eom_trend)
    - [Know Sure Thing (KST) (kst\_momentum)](#know-sure-thing-kst-kst_momentum)
    - [Schaff Trend Cycle (stc\_cycle)](#schaff-trend-cycle-stc_cycle)
    - [Choppiness Index Filter + EMA (chop\_ema)](#choppiness-index-filter--ema-chop_ema)
    - [Fractal Adaptive Moving Average (frama\_trend)](#fractal-adaptive-moving-average-frama_trend)
    - [Volume Price Trend (vpt\_cross)](#volume-price-trend-vpt_cross)
    - [Laguerre RSI (laguerre\_rsi)](#laguerre-rsi-laguerre_rsi)
    - [Pinbar (Hammer/Shooting Star) (pinbar\_reversal)](#pinbar-hammershooting-star-pinbar_reversal)
    - [Detrended Price Oscillator (dpo\_cycle)](#detrended-price-oscillator-dpo_cycle)
    - [Opening Range Breakout (orb\_strat)](#opening-range-breakout-orb_strat)
    - [Market Facilitation Index (bw\_mfi)](#market-facilitation-index-bw_mfi)
    - [Psychological Line (psy\_line)](#psychological-line-psy_line)
    - [Fibonacci Golden Pocket (fib\_golden)](#fibonacci-golden-pocket-fib_golden)
    - [Three White Soldiers / Three Black Crows (candle\_patterns)](#three-white-soldiers--three-black-crows-candle_patterns)
    - [Random Walk Index (rwi\_trend)](#random-walk-index-rwi_trend)
    - [Ulcer Index Strategy (ulcer\_strat)](#ulcer-index-strategy-ulcer_strat)
    - [k-Nearest Neighbors (kNN) Pattern Matching (knn\_ml)](#k-nearest-neighbors-knn-pattern-matching-knn_ml)
    - [Darvas Box Theory (darvas\_box)](#darvas-box-theory-darvas_box)
    - [Elder-Ray Index (elder\_ray)](#elder-ray-index-elder_ray)
    - [Center of Gravity (cog\_ehlers)](#center-of-gravity-cog_ehlers)
    - [Shannon Entropy (entropy\_chaos)](#shannon-entropy-entropy_chaos)
    - [Relative Vigor Index (rvi\_trend)](#relative-vigor-index-rvi_trend)
    - [VSTOP (Volatility Stop) (vstop\_trend)](#vstop-volatility-stop-vstop_trend)
    - [What to pick next?](#what-to-pick-next)
    - [Squeeze Momentum Indicator (lazybear\_squeeze)](#squeeze-momentum-indicator-lazybear_squeeze)
    - [Hurst Exponent Strategy (hurst\_exponent)](#hurst-exponent-strategy-hurst_exponent)
    - [Synthetic Renko Trend (renko\_synthetic)](#synthetic-renko-trend-renko_synthetic)
    - [Gann Hi-Lo Activator (gann\_hilo)](#gann-hi-lo-activator-gann_hilo)
    - [Volume Profile POC Rejection (vpvr\_poc)](#volume-profile-poc-rejection-vpvr_poc)
    - [DCA Rebound (Dollar Cost Averaging) (dca\_martingale)](#dca-rebound-dollar-cost-averaging-dca_martingale)
    - [Triple Screen Trading (triple\_screen)](#triple-screen-trading-triple_screen)
  - [Combined Strategies](#combined-strategies)
    - [Triple Screen Method (triple\_screen\_custom)](#triple-screen-method-triple_screen_custom)
    - [Bollinger Breakout + MFI (bb\_mfi\_breakout)](#bollinger-breakout--mfi-bb_mfi_breakout)
    - [Ichimoku Cloud + MACD (ichimoku\_macd)](#ichimoku-cloud--macd-ichimoku_macd)
    - [ADX + Parabolic SAR (adx\_psar)](#adx--parabolic-sar-adx_psar)
    - [SMA 50/200 Pullback (golden\_cross\_pullback)](#sma-50200-pullback-golden_cross_pullback)
    - [Linear Regression + Z-Score (stats\_arbitrage)](#linear-regression--z-score-stats_arbitrage)
    - [Triple Screen Method (triple\_screen\_ema)](#triple-screen-method-triple_screen_ema)
    - [SMA Golden Cross Pullback (sma\_pullback)](#sma-golden-cross-pullback-sma_pullback)
    - [SuperTrend + StochRSI (super\_stoch)](#supertrend--stochrsi-super_stoch)
    - [Bollinger Breakout + MFI (bb\_mfi)](#bollinger-breakout--mfi-bb_mfi)
    - [Linear Regression + Z-Score (linreg\_zscore)](#linear-regression--z-score-linreg_zscore)
    - [The "Fortress" Trend System (trend\_momentum\_volatility\_volume)](#the-fortress-trend-system-trend_momentum_volatility_volume)
    - [The "Perfect Scalp" (heikin\_ashi\_ema\_stochrsi\_atr)](#the-perfect-scalp-heikin_ashi_ema_stochrsi_atr)
    - [Divergence Hunter Pro (rsi\_cci\_mfi\_ema)](#divergence-hunter-pro-rsi_cci_mfi_ema)
    - [Advanced Squeeze (bollinger\_keltner\_momentum\_adx)](#advanced-squeeze-bollinger_keltner_momentum_adx)
    - [Ichimoku "Full House" (tenkan\_kijun\_cloud\_chikou\_rsi)](#ichimoku-full-house-tenkan_kijun_cloud_chikou_rsi)
    - [VWAP Institutional Strategy (vwap\_ema\_volume\_profile\_rsi)](#vwap-institutional-strategy-vwap_ema_volume_profile_rsi)
    - [The "Trend Sniper" (parabolic\_sar\_adx\_ema\_macd)](#the-trend-sniper-parabolic_sar_adx_ema_macd)
    - [The "Whale Trail" System (volume\_trend\_value)](#the-whale-trail-system-volume_trend_value)
    - [The "Elastic Band" Reversal (mean\_reversion\_trend\_filter)](#the-elastic-band-reversal-mean_reversion_trend_filter)
    - [The "Guppy Tsunami" (gmma\_adx)](#the-guppy-tsunami-gmma_adx)
    - [The "Quant Regression" Channel (linear\_reg\_pearson\_r\_atr)](#the-quant-regression-channel-linear_reg_pearson_r_atr)
    - [The "Golden Chaos" (ichimoku\_bill\_williams\_fractals\_ao)](#the-golden-chaos-ichimoku_bill_williams_fractals_ao)
    - [The "Velocity" System (hull\_ma\_laguerre\_rsi\_volatility\_stop)](#the-velocity-system-hull_ma_laguerre_rsi_volatility_stop)
    - [The "Fibonacci Confluence" (auto\_fibs\_ema\_50\_stochastic)](#the-fibonacci-confluence-auto_fibs_ema_50_stochastic)
  - [Recommendations](#recommendations)
  - [Strategy Implementation](#strategy-implementation)

## Strategies

### RSI + Bollinger Bands (rsi_bb)
A hybrid strategy that aims to catch an ideal reversal point while filtering false signals.
*   **Type:** Mean Reversion.
*   **Logic:** Combines volatility (Bollinger Bands) and momentum (RSI). Bollinger Bands tell us the price is statistically “too low” (deviated from the norm), and RSI confirms sellers are exhausted.
*   **Entry:** The close breaks the **Lower** BB band, and at the same time RSI is in oversold (< 30).
*   **Exit:** Price returns to the **Middle** BB line (SMA 20). We don’t wait for the upper band, because in a down market the safest mean-reversion target is the middle.
*   **Edge:** Solves the classic “catching falling knives” problem. You don’t buy just because it’s cheap; you buy when the deviation is extreme and there is confirmation of seller weakness.

### MACD (macd)
The most classic indicator strategy in the world.
*   **Type:** Trend Following / Momentum.
*   **Logic:** MACD measures the spread between the fast (12) and slow (26) EMAs. The histogram shows the rate of change of that spread.
*   **Entry:** MACD crosses the Signal line bottom-up (or the histogram goes from negative to positive), meaning short-term momentum has overtaken long-term.
*   **Exit:** The opposite cross (top-down).
*   **Edge:** Captures the “meat” of the trend (the middle of the move). Performs poorly in chop, but on strong BTC/ETH moves can generate reliable signals.

### RSI Basic (rsi_basic)
A basic counter-trend strategy.
*   **Type:** Counter-Trend.
*   **Logic:** The market swings like a pendulum. If it goes too far one way, it tends to swing back.
*   **Entry:** RSI drops below 30 (oversold). You bet on a bounce.
*   **Exit:** RSI rises above 70 (overbought).
*   **Edge:** The simplest to understand; works well in a wide range (sideways market).
*   **Downside:** Dangerous in strong trends. In a crash RSI can sit at 20 for a week while price drops another 50%. Requires a mandatory stop loss.

### SMA Crossover (sma_cross)
The “Golden Cross” strategy.
*   **Type:** Trend Following.
*   **Logic:** Uses two simple moving averages. The Fast SMA reacts to price quicker; the Slow SMA reflects the broader direction.
*   **Entry:** Fast SMA crosses above Slow SMA. A mathematical confirmation that the trend has flipped bullish.
*   **Exit:** Fast SMA crosses below Slow SMA (“Death Cross”).
*   **Edge:** Keeps you on the right side of major trends. You won’t miss a “to the moon” move—at the cost of laggy entries and exits.

### Bollinger Band Squeeze (bb_squeeze)
A breakout-after-calm strategy. Uses Bollinger Bands differently than `rsi_bb`.
*   **Type:** Volatility Breakout.
*   **Logic:** Markets are cyclical: low volatility is followed by high volatility. Look for a “squeeze” where Bollinger Bands contract to a minimum and the Keltner Channel sits inside the Bollinger Bands.
*   **Entry:** As bands start expanding and price breaks the upper boundary — go Long.
*   **Exit:** Price returns to the middle line or the bands contract again.
*   **Why it’s cool:** Lets you enter at the start of a powerful impulse before it becomes obvious to everyone.

### Donchian Channel Breakout / Turtle Trading (donchian)
The classic “Turtles” strategy. Simple, but effective on higher timeframes (4h, 1d).
*   **Type:** Breakout.
*   **Logic:** Donchian Channel is the highest High and lowest Low over the last N periods (e.g., 20).
*   **Entry:** Price breaks the upper channel (new 20-candle high) — Long.
*   **Exit:** Price touches the lower channel (or the middle line for faster profit-taking).
*   **Why it’s cool:** Catches all major trends. Downside: many false entries in ranges (drawdowns can be large).

### Ichimoku Cloud Breakout (ichimoku)
A complex Japanese system showing support, resistance, and trend at the same time.
*   **Type:** Trend Following.
*   **Logic:** The core is the “Cloud” (Kumo).
*   **Entry:** Close above the Cloud + Tenkan crosses Kijun bottom-up (golden cross) — strong Long signal.
*   **Exit:** Close below Kijun or price enters the cloud.
*   **Why it’s cool:** The cloud filters noise well. If price is inside the cloud — don’t trade. Saves capital in uncertainty.

### ADX + DMI (adx_dmi)
Trades only when the market has strength.
*   **Type:** Trend Strength Filter.
*   **Logic:** ADX measures trend strength (no direction). DMI (+DI and -DI) provides direction.
*   **Entry:** If ADX > 25 (strong trend) **and** +DI crosses -DI bottom-up — Long. If ADX < 20 — ignore signals (dead market).
*   **Exit:** When +DI crosses back below -DI.
*   **Why it’s cool:** Helps avoid “chop” where fees and whipsaws do the most damage.

### OBV Trend (obv_trend)
Using volume to confirm price movement.
*   **Type:** Volume Trend.
*   **Logic:** OBV (On-Balance Volume) accumulates candle volumes. If price rises but OBV falls, that’s divergence. For a bot, it’s easier to trade the OBV trend itself.
*   **Entry:** Compute an MA of OBV. If OBV breaks above its MA — money is flowing in — Long.
*   **Exit:** OBV drops below its MA.
*   **Why it’s cool:** Price can lie; volume (money) usually can’t. OBV often starts rising before price pumps.

### SuperTrend Strategy (supertrend)
One of the most popular crypto strategies thanks to the built-in trailing stop mechanism.
*   **Type:** Trend Following.
*   **Logic:** SuperTrend is based on ATR (average volatility). It draws a line below price in uptrends and above price in downtrends.
*   **Entry:** Close above the SuperTrend line — Long. Close below — Short (or close the Long).
*   **Exit:** Indicator flips color/direction.
*   **Why it’s cool:** Captures big moves and automatically trails the stop loss with price. Works great in strong BTC/ETH trends.

### EMA Trend + Stochastic RSI (ema_stoch)
A hybrid strategy that fixes the main issue of `rsi_basic`: buying “falling knives”.
*   **Type:** Trend-Filtered Oscillator.
*   **Logic:** Uses a “long” moving average (EMA 200) to define the global trend.
*   **Entry:**
    *   Buy ONLY if price is **above** EMA 200 (uptrend) **and** Stochastic RSI crosses up out of oversold (e.g., < 20).
    *   Ignore buy signals if price is below EMA 200.
*   **Exit:** Stochastic RSI enters overbought (> 80) or crosses down.
*   **Why it’s cool:** Filters out ~80% of false against-trend signals.

### Parabolic SAR Strategy (psar)
The classic “always in the market” (Stop and Reverse) strategy.
*   **Type:** Trend Following / Reversal.
*   **Logic:** The indicator plots dots below price (uptrend) or above price (downtrend). Dots tighten to price as the trend matures.
*   **Entry:** Price crosses a Parabolic SAR dot. If dots flip **below** price — Long.
*   **Exit:** Dots flip **above** price — close Long (and optionally open Short).
*   **Pros:** Great for strong trends; it forces you to hold until there’s an explicit break.
*   **Cons:** In ranges, frequent flips can bleed the account.

### Money Flow Index (MFI) (mfi_div)
“RSI with volume”. Tries to detect smart money.
*   **Type:** Volume Momentum.
*   **Logic:** Price can rise by inertia, but if volume drops the trend is running out of fuel. MFI accounts for both price and volume.
*   **Entry:** MFI drops below 20 (oversold) and turns up — Long. Divergence (price down, MFI up) works even better.
*   **Exit:** MFI above 80 (overbought).
*   **Pros:** Filters “empty” price moves not supported by volume. Often leads RSI.

### TEMA Crossover (tema_cross)
Uses Triple EMA (TEMA) to reduce lag.
*   **Type:** Fast Trend.
*   **Logic:** Regular SMA/EMA lag. TEMA reacts almost instantly.
*   **Entry:** Fast TEMA (e.g., 9) crosses above slow TEMA (e.g., 21).
*   **Exit:** The opposite cross.
*   **Pros:** Enters earlier than SMA cross and exits faster on reversals.
*   **Cons:** More false signals (“noise”) in calm markets.

### Keltner Channel Pullback (keltner_pullback)
Trading pullbacks in strong trends. An alternative to BB.
*   **Type:** Pullback Trend.
*   **Logic:** Keltner Channel is built on ATR (volatility). If price stays above the *upper* band for a long time, the trend is very strong.
*   **Entry:**
    1. Confirm uptrend (Price > EMA 20 or channel midline).
    2. Wait for pullback to the **lower** or **middle** channel line.
    3. Go Long on touch/bounce.
*   **Exit:** Price reaches the upper channel band.
*   **Pros:** “Buy the dip” inside an uptrend. Good risk/reward.

### Awesome Oscillator (ao_saucer)
Bill Williams’ “Saucer” strategy.
*   **Type:** Momentum.
*   **Logic:** AO histogram shows market driving force.
*   **Entry (the “Saucer” pattern):** Histogram above zero. Look for 3 bars: Red -> Red (lower than the first) -> Green (higher than the second). The correction ended and the rise resumes.
*   **Exit:** Color flips red or histogram drops below zero.
*   **Pros:** A “microscope” for entry timing inside waves.

### CCI Correction (cci_correction)
Commodity Channel Index, popular in forex and crypto.
*   **Type:** Cyclical.
*   **Logic:** CCI measures deviation of price from its statistical mean.
*   **Entry:** Wait for CCI to drop below -100 (strong oversold) and then cross back above -100.
*   **Exit:** CCI rises above +100 or crosses 0 top-down.
*   **Pros:** Clear levels (-100/+100), simple mechanical logic.

### VWAP Trend (vwap_cross)
A strategy used by institutional traders. VWAP (Volume Weighted Average Price) shows the asset’s “fair” price with volume taken into account.
*   **Type:** Trend Following / Volume.
*   **Logic:** If price is above VWAP — buyers control the market (bullish). If below — sellers.
*   **Entry:** Price crosses VWAP bottom-up.
*   **Exit:** Price crosses VWAP top-down.
*   **Note:** Very effective intraday (5m, 15m, 1h) because institutions often anchor to VWAP.

### Stochastic RSI (stoch_rsi)
A more sensitive, faster version of RSI. Helps capture short-term swings within a trend.
*   **Type:** Scalping / Oscillator.
*   **Logic:** StochRSI applies the Stochastic formula to RSI values, not price, making it very reactive.
*   **Entry:** StochRSI lines cross in oversold (< 20) and move up.
*   **Exit:** Cross in overbought (> 80) and move down.
*   **Note:** Generates many signals. Needs a filter (e.g., only trade with EMA trend), otherwise it will whipsaw in ranges.

### Elder's Force Index (elder_force)
Alexander Elder’s strategy. Combines price and volume to measure “bull” and “bear” power.
*   **Type:** Momentum.
*   **Logic:** Force Index = (Close - PrevClose) * Volume, then smoothed (EMA).
*   **Entry:** Global trend up (e.g., price above EMA 22), and Force Index (period 2) drops below zero (short-term pullback). Buy the dip.
*   **Exit:** Force Index turns positive again (momentum returns).
*   **Note:** Great for catching pullback entries in strong trends.

### Williams %R (williams_r)
Larry Williams’ indicator. Similar to Stochastic, but inverted. Great in ranges.
*   **Type:** Mean Reversion.
*   **Logic:** Measures how close the close is to the range highs/lows.
*   **Entry:** Value falls below -80 (oversold) and starts rising.
*   **Exit:** Value rises above -20 (overbought).
*   **Note:** Good at highlighting seller exhaustion.

### Kaufman's Adaptive MA (kama_trend)
A strategy based on Kaufman’s Adaptive Moving Average.
*   **Type:** Adaptive Trend.
*   **Logic:** Unlike a regular EMA, KAMA slows down in noisy ranges (flattens) and speeds up in trends. This reduces false entries.
*   **Entry:** Price crosses KAMA bottom-up.
*   **Exit:** Price crosses KAMA top-down.
*   **Note:** A “smart” moving average that filters chop.

### Rate of Change (roc)
Trading the speed of price change. Pure market physics.
*   **Type:** Velocity / Momentum.
*   **Logic:** ROC shows percent change over N periods. Rising ROC means the trend is accelerating.
*   **Entry:** ROC crosses above zero (upside acceleration).
*   **Exit:** ROC crosses below zero (deceleration).
*   **Note:** A leading indicator; often signals reversals before MAs cross.

### ATR Channel Breakout (volty_channel)
Volatility channel breakout.
*   **Type:** Breakout.
*   **Logic:** Build a channel around price: `Close + (N * ATR)` and `Close - (N * ATR)`.
*   **Entry:** Close above the upper channel. An abnormally strong move beyond normal volatility.
*   **Exit:** Price returns to the middle.
*   **Note:** Captures the strongest pumps/dumps while ignoring minor noise.

### Linear Regression Slope (lin_reg)
Trading based on the mathematical slope of a trend line.
*   **Type:** Statistical / Trend.
*   **Logic:** Instead of averaging prices (like SMA), fit a Linear Regression line over the last N candles and use its slope.
*   **Entry:** Slope turns positive and exceeds a threshold (noise filter). Statistically, the trend has flipped upward.
*   **Exit:** Slope turns negative.
*   **Why it’s cool:** Reacts faster than MAs because it tries to model direction, not just average the past.

### Chaikin Money Flow (cmf_trend)
Accumulation/distribution strategy. Similar to MFI, but uses a deeper analysis of the close location within the candle range.
*   **Type:** Volume Flow.
*   **Logic:** CMF estimates buying/selling pressure. CMF > 0 means accumulation (money flows in); CMF < 0 means distribution (money flows out).
*   **Entry:** CMF crosses above zero.
*   **Exit:** CMF crosses back below zero.
*   **Why it’s cool:** Helps separate a real reversal from a “dead cat bounce” — if price rises while CMF < 0, the move is likely weak.

### Vortex Indicator (vortex)
An indicator inspired by natural flow patterns (vortices).
*   **Type:** Trend Following.
*   **Logic:** Two lines: VI+ and VI-. They measure directional movement based on distances between current High and previous Low (and vice versa).
*   **Entry:** VI+ crosses above VI-.
*   **Exit:** VI+ crosses below VI-.
*   **Why it’s cool:** Reliable for detecting the start of longer trends, though it can lag in ranges.

### Aroon Strategy (aroon)
A strategy that measures *time* since the last high/low.
*   **Type:** Trend Strength.
*   **Logic:** Aroon Up shows how many days since a High; Aroon Down since a Low. Values range 0–100.
*   **Entry:** Aroon Up crosses above Aroon Down **and** Aroon Up > 50. New highs appear more often than lows.
*   **Exit:** Aroon Up drops below 50 or crosses below Aroon Down.
*   **Why it’s cool:** A unique time-based approach instead of pure price-based signals.

### TRIX (Triple Exponential Average) (trix_strat)
A very smooth momentum oscillator.
*   **Type:** Momentum.
*   **Logic:** Triple-smoothed EMA (often on log price), which removes most market noise.
*   **Entry:** TRIX crosses above zero.
*   **Exit:** Cross back below zero or signal-line cross.
*   **Why it’s cool:** Few but high-quality signals; works well on higher timeframes (4h, 1d).

### Coppock Curve (coppock)
An indicator designed to catch long-term market bottoms (originally for S&P 500), but works in crypto too.
*   **Type:** Long-term Swing / Investment.
*   **Logic:** Sum of two ROC values with different periods, smoothed by a weighted moving average.
*   **Entry:** Coppock curve starts turning up while below zero.
*   **Exit:** Curve turns down (or crosses 0).
*   **Why it’s cool:** Psychologically comfortable: rare entries, often near the start of a broader bull market.

### Commodity Channel Index (cci_trend)
Using CCI for trend trading (not counter-trend as earlier).
*   **Type:** Trend.
*   **Logic:** CCI is often used for reversals, but here we use it as a breakout/momentum signal.
*   **Entry:** CCI rises above +100 — a strong upward impulse.
*   **Exit:** CCI falls back below +100 (or below 0).
*   **Why it’s cool:** Captures the “fattest” part of a move when an asset goes “to the moon”.

### Hull Moving Average Trend (hma_trend)
A strategy based on the Hull Moving Average (HMA).
*   **Type:** Low Lag Trend Following.
*   **Logic:** Alan Hull created a formula that reduces lag typical for SMA/EMA while keeping a smooth curve.
*   **Entry:** Price crosses above HMA (or HMA slope flips from down to up).
*   **Exit:** The opposite cross or slope flip.
*   **Edge:** Reacts to reversals almost instantly; great on volatile pairs where regular MAs are too slow.

### Z-Score Strategy (z_score)
Pure mathematical statistics without “magic lines”.
*   **Type:** Mean Reversion.
*   **Logic:** Z-Score measures how many standard deviations (sigmas) price is away from its mean — like “digital” Bollinger Bands.
*   **Entry:** Z-Score drops below -2 (2-sigma downside deviation). Buy expecting reversion.
*   **Exit:** Z-Score returns to 0 (mean) or rises above +2.
*   **Edge:** Works on any asset because it normalizes volatility.

### VWMA vs SMA (vwma_cross)
Validating trend strength via volume.
*   **Type:** Trend + Volume Confirmation.
*   **Logic:** Compare SMA to VWMA (volume-weighted MA).
    *   If VWMA > SMA, volume is stronger on up candles (bigger players buying).
    *   If VWMA < SMA while price rises, the move is on weak volume (possible trap).
*   **Entry:** VWMA crosses above SMA.
*   **Exit:** VWMA crosses below SMA.
*   **Edge:** Filters “inflated” pumps with no real money behind them.

### Connors RSI 2 (rsi_2)
Larry Connors’ famous scalping strategy.
*   **Type:** Aggressive short-term Mean Reversion.
*   **Logic:** Standard RSI(14) is too slow; Connors uses RSI with period 2.
*   **Entry:** RSI(2) drops below 10 (or 5) — extreme oversold. Go Long.
*   **Exit:** Close above the 5-day SMA. Don’t wait for RSI > 90; exit on the first bounce.
*   **Edge:** Very high win rate (often > 80%), but trades are short and per-trade profit is small.

### Williams Fractals (fractal_breakout)
Trading breakouts of local levels (Price Action).
*   **Type:** Breakout.
*   **Logic:** A Williams fractal is a 5-candle formation where the middle candle has the highest High (up fractal) or lowest Low (down fractal). These are local peaks/troughs.
*   **Entry:** Price breaks the level of the latest up fractal (the fractal candle High).
*   **Exit:** Price breaks the level of the latest down fractal (trailing stop).
*   **Edge:** Trades real support/resistance levels the market sees, not derived formulas.

### Fibonacci Bollinger Bands (fib_bands)
A modified Bollinger Bands approach to catch more precise bounces.
*   **Type:** Mean Reversion / Trend.
*   **Logic:** Instead of standard deviation multipliers (x2, x3), Fibonacci ratios (1.618, 2.618, 4.236) are used for band widths.
*   **Entry:** Price touches an inner band (Fib 1.618) or outer band (Fib 2.618) and bounces.
*   **Exit:** Return to the midline.
*   **Edge:** Crypto often respects Fibonacci levels more than a perfect Gaussian model.

### Chandelier Exit Strategy (chandelier_trend)
A strategy built from the opposite direction: exit management (stop loss).
*   **Type:** Trend Following.
*   **Logic:** Chandelier Exit hangs a stop loss at a distance (ATR * 3) below the highest high over a lookback. If price doesn’t hit the “chandelier”, you stay in.
*   **Entry:** Close above the Chandelier Exit line (trend flipped bullish).
*   **Exit:** Price touches the line (trailing stop hit).
*   **Edge:** Designed to let profits run and avoid exiting on small pullbacks.

### Inside Bar Breakout (inside_bar)
A classic Price Action strategy without indicators.
*   **Type:** Volatility Breakout / Pattern.
*   **Logic:** Find an Inside Bar — a candle whose high/low is fully inside the previous “mother” candle. Market compresses before expansion.
*   **Entry:** Price breaks the Inside Bar high (for longs).
*   **Exit:** Fixed take profit or trailing stop. Stop loss is placed behind the Inside Bar low.
*   **Edge:** Very tight stops with high upside potential (risk/reward).

### TD Sequential (Simplified) (td_seq)
A simplified version of Thomas DeMark’s legendary strategy.
*   **Type:** Counter-Trend / Reversal.
*   **Logic:** Markets get tired of moving in one direction. DeMark counts sequential closes.
*   **Entry (Setup):** If you see **9 consecutive** candles where each close is below the close 4 candles earlier (Bearish Setup) — sellers are exhausted. Enter Long on the open of candle 10.
*   **Exit:** On the opposite setup or after a fixed number of candles.
*   **Edge:** Popular in crypto for catching local bottoms.

### Ehlers Fisher Transform (fisher_trans)
John Ehlers’ strategy using digital signal processing concepts.
*   **Type:** Reversal / Cyclical.
*   **Logic:** Transforms price movement into a (near) normal distribution, making turning points sharp and clear by removing noise.
*   **Entry:** Fisher line crosses above its signal line (often when exiting a lower zone).
*   **Exit:** The opposite cross.
*   **Edge:** A “turbo” oscillator, reacting faster and cleaner than RSI or MACD.

### RSI Divergence (rsi_div)
Trading RSI divergences instead of RSI levels.
*   **Type:** Reversal.
*   **Logic:** If price makes a Lower Low, but RSI makes a Higher Low — that’s **bullish divergence**. Downside momentum is exhausted even if price still drifts lower.
*   **Entry:** After confirming bullish divergence.
*   **Exit:** RSI rises above 70 or crosses 50.
*   **Edge:** One of the most reliable TA signals; lets you enter near the bottom (catch “falling knives” professionally).

### Heikin Ashi Trend (ha_trend)
Using modified Heikin Ashi candles to filter noise.
*   **Type:** Visual Trend.
*   **Logic:** Heikin Ashi candles are computed from averaged open/close prices. They smooth the chart and hide small pullbacks.
*   **Entry:** After a series of red candles, a green candle appears without a lower wick (strong bullish impulse).
*   **Exit:** A color-change candle (red) appears, or a candle with long wicks on both sides (doji/uncertainty).
*   **Edge:** Psychologically comfortable; helps you sit through long trends without overreacting to small red candles on a normal chart.

### Standard Deviation Channel (std_channel)
Trading within a linear regression channel.
*   **Type:** Mean Reversion.
*   **Logic:** A linear regression midline plus two parallel lines at 2 standard deviations. ~95% of moves occur inside.
*   **Entry:** Price touches the lower channel (oversold relative to the trend).
*   **Exit:** Return to the regression line (midline).
*   **Edge:** Unlike Bollinger Bands, this channel has slope, so you mean-revert **in the direction** of the trend.

### Pivot Points Reversal (pivot_rev)
Trading from mathematical support levels.
*   **Type:** Bounce.
*   **Logic:** Use yesterday’s High/Low/Close to calculate Pivot (P), Supports (S1, S2), and Resistances (R1, R2).
*   **Entry:** Price falls into S1 or S2, tests it, and closes above (bounce).
*   **Exit:** Next pivot level (e.g., buy at S1, target P).
*   **Edge:** These are self-fulfilling levels many traders watch; works well on 1h/4h.

### Williams Alligator (alligator)
Bill Williams’ classic trend strategy.
*   **Type:** Trend Following.
*   **Logic:** Three smoothed moving averages shifted forward (Jaws, Teeth, Lips). They mimic an alligator’s behavior.
*   **Entry:** When lines are tangled — “alligator is sleeping” (range, don’t trade). When they open in the right order (Lips > Teeth > Jaws) — trend started — Long.
*   **Exit:** Lines tangle again or price closes below the “Teeth”.
*   **Edge:** Helps trade only strong moves and ignore noisy ranges.

### Engulfing Pattern (engulfing_candle)
Trading the pure candlestick “Engulfing” pattern.
*   **Type:** Price Action / Reversal.
*   **Logic:** Two candles. The second (bullish) candle fully engulfs the body of the previous (bearish) candle, showing a sharp sentiment shift from selling to buying.
*   **Entry:** A Bullish Engulfing appears after a series of down candles.
*   **Exit:** Fixed profit target or an opposite pattern.
*   **Edge:** No lag; the signal is available right at candle close.

### McGinley Dynamic (mcginley)
Trading with an “ideal” moving average.
*   **Type:** Advanced Trend.
*   **Logic:** John McGinley created an indicator that looks like an EMA but automatically speeds up in fast markets and slows in slow markets, avoiding whipsaws better than standard MAs.
*   **Entry:** Price crosses above the McGinley line.
*   **Exit:** Price crosses below the line.
*   **Edge:** Solves the eternal question: “Which MA period should I use?” McGinley adapts automatically.

### Dual Thrust (dual_thrust)
A famous breakout system, often used in futures.
*   **Type:** Range Breakout.
*   **Logic:** Take the range over the last N candles (High - Close or High - Low) and multiply by K.
*   **Entry:** If price breaks `Open + (Range * K)` — Long. If it breaks below — Short.
*   **Exit:** End-of-day close or stop-and-reverse.
*   **Edge:** Catches strong impulses out of consolidation; popular in algo trading.

### Chande Momentum Oscillator (cmo_strat)
A pure momentum indicator, different from RSI.
*   **Type:** Momentum.
*   **Logic:** CMO is the difference between sums of up moves and down moves divided by total movement. Range: -100 to +100.
*   **Entry:** CMO crosses +50 bottom-up (strong bull impulse) or turns up from oversold (< -50).
*   **Exit:** CMO drops back below +50.
*   **Edge:** Unlike RSI smoothing, CMO reacts directly to each move, showing raw speed.

### Ease of Movement (eom_trend)
A strategy combining Price and Volume to find the “path of least resistance”.
*   **Type:** Volume + Price.
*   **Logic:** Richard Arms’ EVM shows how easily price moves. Strong price rise on small volume is “easy”; huge volume with little movement is “hard” (a fight).
*   **Entry:** EVM crosses above 0.
*   **Exit:** EVM drops below 0.
*   **Edge:** Helps spot “healthy” trends and avoid markets where there’s heavy battle (big volume, no movement).

### Know Sure Thing (KST) (kst_momentum)
“Know sure thing” — a composite momentum indicator.
*   **Type:** Cycle Momentum (longer-term).
*   **Logic:** A sum of four ROC components with different smoothing; effectively a “MACD for cycles”.
*   **Entry:** KST crosses above its signal line.
*   **Exit:** The opposite cross.
*   **Edge:** Designed to catch major market cycles while ignoring small corrections. Works well on 4h and 1d.

### Schaff Trend Cycle (stc_cycle)
An improved MACD variant that moves faster and more precisely.
*   **Type:** Cycle / Momentum.
*   **Logic:** Doug Schaff combined MACD and Stochastic into an oscillator from 0 to 100 that, unlike Stochastic, is less jittery in chop and holds positions better.
*   **Entry:** STC rises above 25 (exits oversold).
*   **Exit:** STC drops below 75 (exits overbought).
*   **Note:** Finds trends earlier than MACD and gives fewer false signals in ranges.

### Choppiness Index Filter + EMA (chop_ema)
A strategy with a “market quality” filter.
*   **Type:** Trend with filter.
*   **Logic:** Choppiness Index (CHOP) indicates whether the market is trending or ranging. CHOP > 61.8 means range (don’t trade). CHOP < 38.2 means strong trend.
*   **Entry:** Price crosses above an EMA (e.g., 50) **and** CHOP < 50 (trend confirmation).
*   **Exit:** Price crosses back below the EMA.
*   **Note:** The main goal is to avoid trades in dead markets and save fees and nerves.

### Fractal Adaptive Moving Average (frama_trend)
Using fractal geometry to adapt to the market.
*   **Type:** Adaptive Trend.
*   **Logic:** FRAMA uses “fractal dimension”. In chaos (range), FRAMA slows and flattens. In directional movement, it accelerates.
*   **Entry:** Price crosses above FRAMA.
*   **Exit:** Price crosses below FRAMA.
*   **Note:** Unlike a regular EMA, FRAMA can stay nearly flat during corrections, preventing false stop-outs.

### Volume Price Trend (vpt_cross)
A more advanced OBV-like indicator.
*   **Type:** Volume.
*   **Logic:** VPT accounts not only for direction (like OBV), but for *percent* price change. Big volume with small price change has small impact; big volume with big move has big impact.
*   **Entry:** VPT crosses above its moving average (MA).
*   **Exit:** VPT falls below its MA.
*   **Note:** Very sensitive to “smart money” accumulation.

### Laguerre RSI (laguerre_rsi)
“RSI from the future” — using the Laguerre filter.
*   **Type:** Trend oscillator.
*   **Logic:** John Ehlers applied time-warp filtering to build a minimal-lag RSI with only 4 smoothing components.
*   **Entry:** Laguerre RSI crosses above 0.2 (20%).
*   **Exit:** Crosses below 0.8 (80%).
*   **Note:** Reacts much faster than classic RSI, capturing more of the move.

### Pinbar (Hammer/Shooting Star) (pinbar_reversal)
Pure Price Action — reversal candles.
*   **Type:** Candlestick Pattern (Reversal).
*   **Logic:** A “pin bar” (hammer or shooting star) has a very long wick and a small body. The wick shows price moved one way and was sharply rejected.
*   **Entry:** A bullish pin bar (long lower wick) appears at a local low.
*   **Exit:** Fixed risk/reward (e.g., 1:3) or exit on an opposite signal.
*   **Note:** Works best at support levels; often marks seller capitulation.

### Detrended Price Oscillator (dpo_cycle)
Trading short-term cycles without the global trend bias.
*   **Type:** Short-term Cyclical.
*   **Logic:** DPO removes the longer-term trend, leaving only shorter-term oscillations (“micro-waves”).
*   **Entry:** DPO crosses above 0.
*   **Exit:** DPO crosses below 0.
*   **Note:** Helps trade intraday swings even when the global market is in a strong bull/bear regime.

### Opening Range Breakout (orb_strat)
Classic day-trader strategy adapted to a 24/7 market.
*   **Type:** Time-based Breakout.
*   **Logic:** The first hour (or 4 hours) of a new day/week sets the tone; the market “chooses” direction.
*   **Entry:** Define High and Low of the first daily candle (00:00 UTC). If price breaks the High — Long.
*   **Exit:** End of day (23:59) or a fixed stop loss at the range midpoint.
*   **Edge:** Uses the opening-session impulse. Very simple, but statistically effective on high-volatility assets.

### Market Facilitation Index (bw_mfi)
Bill Williams’ strategy (not Money Flow Index). Measures price movement efficiency relative to volume.
*   **Type:** Volume + Price Efficiency.
*   **Logic:** Compares Range to Volume.
    *   *Green Bar:* Volume up + strong move = true trend.
    *   *Squat Bar:* Volume up + price flat = bull/bear fight (possible reversal).
*   **Entry:** 2–3 consecutive “Green bars”.
*   **Exit:** A “Squat” bar appears — the move is running out of fuel.
*   **Edge:** Helps distinguish a weak pump (low volume) from a real move.

### Psychological Line (psy_line)
Crowd sentiment indicator.
*   **Type:** Sentiment / Counter-Trend.
*   **Logic:** Ratio of up candles to total candles over a period (e.g., 12). If PSY > 75%, 9 out of 12 candles were green — euphoria (overbought).
*   **Entry:** PSY drops below 25% (panic) and turns up.
*   **Exit:** PSY rises above 75%.
*   **Edge:** A market thermometer that ignores absolute prices and focuses on bull vs bear “wins”.

### Fibonacci Golden Pocket (fib_golden)
Automated trading of Fibonacci pullbacks.
*   **Type:** Dip Buying.
*   **Logic:** Finds the last meaningful swing High/Low and draws Fibonacci retracement. The zone between 0.618 and 0.65 is the “Golden Pocket”, where bounces often happen.
*   **Entry:** Price touches the 0.618 retracement level.
*   **Exit:** New high (0 level) or stop below 0.786.
*   **Edge:** One of the most popular discretionary strategies; the bot automates finding these levels.

### Three White Soldiers / Three Black Crows (candle_patterns)
Trading strong candle formations that often continue the trend.
*   **Type:** Pattern Recognition.
*   **Logic:** “Three White Soldiers” are three consecutive green candles, each closing higher than the previous, preferably with short wicks. Indicates buyer dominance.
*   **Entry:** Close of the 3rd candle.
*   **Exit:** First bearish candle appears, or trailing stop by candle lows.
*   **Edge:** If three powerful candles print in a row, continuation probability is often high.

### Random Walk Index (rwi_trend)
A statistical test: “Is this a trend or randomness?”
*   **Type:** Statistical filter.
*   **Logic:** RWI compares price movement to what you’d expect from a random walk (coin flips).
*   **Entry:** RWI High > 1 (up move is statistically meaningful).
*   **Exit:** RWI High drops below 1.
*   **Edge:** Saves you from trading noisy, chaotic markets.

### Ulcer Index Strategy (ulcer_strat)
A strategy that minimizes stress (and drawdowns).
*   **Type:** Risk Adjusted / Risk Management.
*   **Logic:** Ulcer Index measures depth and duration of drawdowns. Unlike standard deviation, it accounts only for *down moves* (bad volatility).
*   **Entry:** Price is rising while Ulcer Index is extremely low (smooth, calm uptrend).
*   **Exit:** A sharp spike in Ulcer Index (turbulence begins).
*   **Edge:** Great for conservative account growth; exits early on instability without waiting for a crash.

### k-Nearest Neighbors (kNN) Pattern Matching (knn_ml)
Simple machine learning without heavy neural nets.
*   **Type:** Pattern Matching.
*   **Logic:** The algorithm memorizes the shape of the last N candles (e.g., 5), then searches the historical chart for the most similar shapes.
*   **Entry:** If in 70% of found historical matches price moved up afterward — buy.
*   **Exit:** Fixed holding period (e.g., 3 candles) or when the forecast changes.
*   **Edge:** The bot doesn’t use indicators; it “looks” at history: “This happened before — here’s what came next.”

### Darvas Box Theory (darvas_box)
Nicholas Darvas’ legendary strategy that made him $2M in the 1950s.
*   **Type:** Breakout / Trend Following.
*   **Logic:** When price ranges, it builds a “Box” with a clear ceiling (High) and floor (Low).
*   **Entry:** Price breaks above the box ceiling. It’s a signal the asset moved to a “new floor”. Immediately set a stop under the new box floor.
*   **Exit:** Price breaks below the box floor.
*   **Edge:** Excellent for parabolic trends while ignoring minor shakeouts inside boxes.

### Elder-Ray Index (elder_ray)
Alexander Elder’s “market X-ray” strategy.
*   **Type:** Trend Following + Momentum.
*   **Logic:** Uses EMA(13) as a value consensus and two components: `Bull Power` (High - EMA) and `Bear Power` (Low - EMA).
*   **Entry:** Uptrend (EMA slope up) **and** `Bear Power` is below zero but rising (bears weakening). Buy the pullback.
*   **Exit:** `Bull Power` reaches a historic high and starts falling.
*   **Edge:** Separates bull and bear internal strength.

### Center of Gravity (cog_ehlers)
John Ehlers’ zero-lag oscillator.
*   **Type:** Reversal.
*   **Logic:** Ehlers used a physics center-of-gravity formula to find turning points. The indicator looks like a smooth sine wave and can “predict” reversals with minimal lag.
*   **Entry:** COG crosses above its signal line (Lag 1).
*   **Exit:** The opposite cross.
*   **Edge:** One of the most precise tools for sideways markets. In trends it can exit early, so a trend filter is recommended.

### Shannon Entropy (entropy_chaos)
Using information theory to measure market chaos.
*   **Type:** Market regime filter.
*   **Logic:** Shannon entropy measures uncertainty.
    *   High entropy = chaos; price is unpredictable (range/noise).
    *   Low entropy = order; strong directional trend.
*   **Entry:** Entropy drops below a threshold (market became ordered) + price is above a moving average.
*   **Exit:** Entropy spikes (chaos starts).
*   **Edge:** A mathematically grounded way to say: “I don’t trade because the market is drunk right now.”

### Relative Vigor Index (rvi_trend)
Energy of price movement.
*   **Type:** Momentum.
*   **Logic:** Based on the idea that in up markets closes tend to be above opens. RVI smooths these values and resembles Stochastic, but is based on candle “energy” rather than range.
*   **Entry:** RVI crosses above its signal line.
*   **Exit:** Cross below.
*   **Edge:** Confirms trend sustainability. If price rises but RVI falls (divergence), the trend may be weak.

### VSTOP (Volatility Stop) (vstop_trend)
Volatility-based trailing strategy.
*   **Type:** Trailing (Trend).
*   **Logic:** Compute a stop line at `N * ATR` away from price extremes. The line only moves in the trend direction, never backward.
*   **Entry:** Close above the VSTOP line (it flips under price and becomes support).
*   **Exit:** Price touches or closes below VSTOP.
*   **Edge:** A pure exit-management approach that keeps you in trend until volatility breaks protection. Similar to SuperTrend, but with a different maxima math.

### What to pick next?

For the next implementation phase (to round out your portfolio), I recommend:

1.  **k-Nearest Neighbors (knn_ml)** — adds simple **AI logic** to your bot without heavy libraries. A very modern approach.
2.  **Darvas Box** — a **breakout classic** that works well on “hype” coins during strong upside moves.
3.  **Center of Gravity** — a powerful weapon for **range markets**, where trend strategies tend to lose money.

### Squeeze Momentum Indicator (lazybear_squeeze)
The legendary TradingView strategy (by LazyBear) based on John Carter’s ideas.
*   **Type:** Volatility Breakout + Momentum.
*   **Logic:** Combines Bollinger Bands and Keltner Channels.
    *   **“Squeeze” phase:** Bollinger Bands are inside the Keltner Channel (black dots). The market stores energy.
    *   **“Release” phase:** Bands move outside the channel.
*   **Entry:** Squeeze ends (exit from range) **and** momentum histogram is above zero and rising.
*   **Exit:** Momentum histogram changes color (starts falling) or drops below zero.
*   **Edge:** A visually simple system that captures the strongest post-compression moves.

### Hurst Exponent Strategy (hurst_exponent)
A mathematical strategy that determines the market’s “memory”.
*   **Type:** Adaptive (Regime switcher).
*   **Logic:** Hurst exponent (H) identifies market nature:
    *   H > 0.5: Trending (persistent).
    *   H < 0.5: Ranging (mean reverting).
*   **Entry:**
    *   If H > 0.6: Use breakout logic (e.g., break High of last N days).
    *   If H < 0.4: Use counter-trend logic (buy lows, sell highs).
*   **Exit:** Hurst regime changes.
*   **Edge:** A “strategy of strategies”: it doesn’t guess direction, it determines *how* to trade right now.

### Synthetic Renko Trend (renko_synthetic)
Using Renko “bricks” instead of candles to remove time noise.
*   **Type:** Price Action (time-independent).
*   **Logic:** Virtually build fixed-size bricks (e.g., 1% of price). A new brick appears only if price travels that distance; small fluctuations are ignored.
*   **Entry:** Two green bricks in a row after a series of red bricks (trend reversal up).
*   **Exit:** One red brick appears (reversal down).
*   **Edge:** Lets the bot hold trends for weeks, ignoring sideways chop that looks scary on candles but is a flat line on Renko.

### Gann Hi-Lo Activator (gann_hilo)
Simple but effective trend-following strategy inspired by Gann.
*   **Type:** Trend / Trailing Stop.
*   **Logic:** A simple SMA(3) built on Highs in downtrends and on Lows in uptrends.
*   **Entry:** Close above the Gann Activator line (it flips under price).
*   **Exit:** Close below the line.
*   **Edge:** A strict mechanical trailing stop. Great for altcoins with sharp pumps.

### Volume Profile POC Rejection (vpvr_poc)
Trading from horizontal volume levels.
*   **Type:** Support/Resistance levels.
*   **Logic:** Compute Volume Profile over the last N days. Find the POC (Point of Control) — the price with the most traded volume — the “fair price”.
*   **Entry:**
    1. Price approaches POC from above.
    2. Price touches POC and bounces (candle closes higher).
    3. It’s a support test — go Long.
*   **Exit:** Fixed percentage profit or reaching the next Low Volume Node.
*   **Edge:** Trade alongside large players defending accumulated positions at POC.

### DCA Rebound (Dollar Cost Averaging) (dca_martingale)
Capital management strategy popular in bot platforms (3Commas, etc.).
*   **Type:** Averaging / Grid.
*   **Logic:** Uses re-buys instead of a stop loss.
*   **Entry:** RSI < 30 (first entry with 20% of capital).
*   **Management:** If price drops 2%, buy another 30%. If it drops another 3%, buy 50% (martingale/averaging).
*   **Exit:** When average entry price + 1% profit is reached (on the rebound).
*   **Edge:** Can close trades in profit even in a down market (via bounces), but liquidation risk is high if price falls without pullbacks (you need a stop loss for the whole “bag”).

### Triple Screen Trading (triple_screen)
Alexander Elder’s classic system.
*   **Type:** Multi-timeframe (Trend + Correction).
*   **Logic:** Uses three “screens” (or timeframe multipliers on one chart).
    1.  **Tide (Long term):** MACD on timeframe x5 shows the uptrend.
    2.  **Wave (Mid term):** StochRSI on current timeframe is overbought (a pullback down against trend).
    3.  **Ripple (Entry):** Breakout of the previous candle high (when the pullback ends).
*   **Entry:** When the “Tide” is up and the “Wave” stops falling.
*   **Exit:** Based on lower-timeframe signals.
*   **Edge:** One of the most reliable trade filters: trade with the long-term trend, but buy temporary dips.

## Combined Strategies

Great idea. **Combined strategies** are the next evolution level for a trading bot. Single indicators often produce false signals: trend-following strategies bleed in ranges, and oscillators (RSI) exit too early in trends.

Combining signals lets you filter entries using a simple principle: **“Filter (global trend) + Trigger (entry timing)”**.

### Triple Screen Method (triple_screen_custom)
An Elder-style adaptation combining Trend, Wave, and Momentum.
*   **Components:** EMA (200) + RSI (14) + MACD.
*   **Logic:**
    1.  **Filter:** Price must be **above** EMA 200 (global uptrend).
    2.  **Pullback:** RSI must fall below 50 (local correction, “discount”).
    3.  **Trigger:** MACD histogram starts rising (momentum reversal up).
*   **Why it’s cool:** You buy with the trend, not at the top, and only after the pullback is confirmed to be over.

### Bollinger Breakout + MFI (bb_mfi_breakout)
Volatility breakout confirmed by money flow.
*   **Components:** Bollinger Bands + Money Flow Index.
*   **Logic:** BB breakouts can fake out; volume helps.
    1.  **Trigger:** Close above the Upper Bollinger Band.
    2.  **Filter:** MFI > 60 and rising (money flowing in). If price breaks BB but MFI falls — it’s likely a fakeout.
*   **Exit:** Price returns inside the Bollinger channel.
*   **Why it’s cool:** Filters “empty” pumps without real buyer volume.

### Ichimoku Cloud + MACD (ichimoku_macd)
Japanese classic with western confirmation.
*   **Components:** Ichimoku Kinko Hyo + MACD.
*   **Logic:**
    1.  **Filter (Kumo breakout):** Close **above** the Ichimoku Cloud.
    2.  **Trigger:** MACD lines cross up (golden cross).
*   **Exit:** Price enters the cloud again.
*   **Why it’s cool:** Cloud breakouts often mean a long-term trend shift; MACD helps enter early.

### ADX + Parabolic SAR (adx_psar)
Hunts strong trends: “Don’t trade if there’s no strength.”
*   **Components:** ADX + Parabolic SAR.
*   **Logic:** Parabolic SAR fires constantly (including in ranges). ADX fixes that.
    1.  **Filter:** ADX > 25 (active phase; no range).
    2.  **Trigger:** SAR dots flip **below** price.
*   **Exit:** SAR dots flip above price.
*   **Why it’s cool:** You ignore weak markets and engage only when the “rocket” starts.

### SMA 50/200 Pullback (golden_cross_pullback)
Smarter “Golden Cross” trading.
*   **Components:** SMA 50 + SMA 200.
*   **Logic:** Buying the cross often gets followed by a pullback that stops you out. Instead:
    1.  **Condition:** SMA 50 is above SMA 200 (cross already happened).
    2.  **Trigger:** Price touches SMA 50 from above and closes back above (support bounce).
*   **Exit:** Close below SMA 200.
*   **Why it’s cool:** Lower-risk entry with a tighter stop: buy the correction, not the hype.

### Linear Regression + Z-Score (stats_arbitrage)
A mathematical combine (mean reversion on steroids).
*   **Components:** Linear Regression Slope + Z-Score.
*   **Logic:**
    1.  **Filter:** Regression slope > 0 (positive expectancy).
    2.  **Trigger:** Z-Score < -2 (2-sigma downside deviation from the regression line).
*   **Exit:** Z-Score returns to 0.
*   **Why it’s cool:** A scientific approach: buy an asset that grows *globally* but is *locally* unfairly cheap.

### Triple Screen Method (triple_screen_ema)
An algo adaptation of Elder’s “Triple Screen” method.
*   **Logic:** Uses three indicator types:
    1.  **Tide (Long term):** Price must be **above** EMA 200 (or EMA 100). Global uptrend.
    2.  **Wave (Pullback):** RSI (14) must drop below 50 (or 45). Temporary correction.
    3.  **Ripple (Entry):** MACD histogram starts rising (or MACD lines cross). Pullback ends; up move resumes.
*   **Exit:** RSI > 70 or MACD crosses down.
*   **Why it’s cool:** Conservative and robust. Filters most dangerous counter-trend trades.

### SMA Golden Cross Pullback (sma_pullback)
Smarter MA crossover trading: not on the cross, but on the retest.
*   **Logic:**
    1.  **Condition:** SMA 50 is above SMA 200 (Golden Cross already happened).
    2.  **Trigger:** Price touches SMA 50 from above and bounces (next candle green).
*   **Exit:** Close below SMA 200 (trend break) or a fixed take profit.
*   **Why it’s cool:** Buying right at the cross often loses because the market is already overheated. The retest gives tighter risk and better odds.

### SuperTrend + StochRSI (super_stoch)
Combines a top trend indicator with a fast oscillator for “sniper” entries.
*   **Logic:**
    1.  **Filter (Trend):** SuperTrend (ATR-based) must be green (price above the line). No shorts.
    2.  **Trigger (Entry):** StochRSI drops into oversold (< 20) and crosses up (K crosses D).
*   **Exit:** StochRSI enters overbought (> 80) or SuperTrend flips red.
*   **Why it’s cool:** Trades with the trend but enters on local pullbacks, improving risk/reward.

### Bollinger Breakout + MFI (bb_mfi)
Volatility breakout with volume confirmation (“smart money”).
*   **Logic:**
    1.  **Trigger:** Close above the **Upper** Bollinger Band (volatility expansion).
    2.  **Filter (Volume):** MFI > 60 and rising. Confirms the breakout is supported by real inflows.
*   **Exit:** Close back inside the channel (below upper band) or MFI falls.
*   **Why it’s cool:** Helps distinguish a real pump from a market-maker trap (fakeout).

### Linear Regression + Z-Score (linreg_zscore)
Mean reversion 2.0 (pure stats).
*   **Logic:**
    1.  **Filter (Direction):** Regression slope (over 50–100 candles) is positive.
    2.  **Trigger (Deviation):** Z-Score drops below -2 (statistically cheap vs its own trend).
*   **Exit:** Z-Score returns to 0 (midline).
*   **Why it’s cool:** Not candle-guessing — pure statistics. Buy a globally rising asset that is locally discounted.

### The "Fortress" Trend System (trend_momentum_volatility_volume)
The “Fortress” system: four layers of protection from dumb trades.
*   **Components:** EMA 200 + MACD + Bollinger Bands + OBV.
*   **Logic:**
    1.  **Global filter:** Price > EMA 200 (trade only the uptrend).
    2.  **Volatility:** Price touches or breaks the BB midline (pullback to fair price).
    3.  **Volume:** OBV is above its MA (money isn’t leaving during the pullback).
    4.  **Trigger:** MACD histogram flips from red to green (momentum returns).
*   **Exit:** Touch the upper BB or MACD crosses down.
*   **Why it’s cool:** You buy only volume-confirmed pullbacks inside a reinforced uptrend.

### The "Perfect Scalp" (heikin_ashi_ema_stochrsi_atr)
Noise-filtered scalping.
*   **Components:** Heikin Ashi (virtual) + EMA 50 + EMA 100 + StochRSI + ATR.
*   **Logic:**
    1.  **Tunnel:** EMA 50 is above EMA 100, and the distance is increasing (strong trend).
    2.  **Pattern:** Heikin Ashi candle flips from red to green.
    3.  **Trigger:** StochRSI crosses up below 40.
    4.  **Stop loss:** Fixed at 2xATR from entry.
*   **Exit:** Heikin Ashi flips to red.
*   **Why it’s cool:** Heikin Ashi removes noise; dual EMA prevents scalping against a train.

### Divergence Hunter Pro (rsi_cci_mfi_ema)
Hunting reversals with triple confirmation (oscillator convergence).
*   **Components:** EMA 200 + RSI (14) + CCI (20) + MFI (14).
*   **Logic:**
    1.  **Context:** Price above EMA 200 (looking for a local correction bottom).
    2.  **Synchronization:**
        *   RSI < 30 (price oversold).
        *   CCI < -100 (abnormal deviation).
        *   MFI < 20 (volume oversold / panic).
    3.  **Entry:** All three indicators turn up together.
*   **Exit:** Any of the three reaches overbought.
*   **Why it’s cool:** The chance that three different math oscillators (price, deviation, volume) all fail at once is low.

### Advanced Squeeze (bollinger_keltner_momentum_adx)
An advanced TTM Squeeze variant for explosive moves.
*   **Components:** Bollinger Bands + Keltner Channels + Momentum + ADX.
*   **Logic:**
    1.  **Squeeze:** Bollinger Bands fully inside the Keltner Channel — volatility at a critical low.
    2.  **Accumulation:** ADX < 20 (market is “sleeping”).
    3.  **Trigger:** Bollinger Bands exit the Keltner Channel + ADX starts rising sharply.
    4.  **Direction:** Momentum > 0.
*   **Exit:** Momentum starts falling.
*   **Why it’s cool:** Big money is made when the market shifts from sleep to explosion; this combo targets that transition.

### Ichimoku "Full House" (tenkan_kijun_cloud_chikou_rsi)
Using the full Ichimoku signal set plus an overbought filter.
*   **Components:** Ichimoku Cloud (all lines) + RSI.
*   **Logic:**
    1.  **Breakout:** Close above the Cloud (Kumo breakout).
    2.  **Cross:** Tenkan crosses Kijun bottom-up (TK Cross).
    3.  **Lagging confirm:** Chikou Span is above price 26 periods back (trend confirmation).
    4.  **Filter:** RSI < 70 (market not overheated).
*   **Exit:** Tenkan crosses below Kijun or price enters the cloud.
*   **Why it’s cool:** One of the oldest and most respected Japanese systems. Using all parts makes entries rarer but stronger.

### VWAP Institutional Strategy (vwap_ema_volume_profile_rsi)
Trading “like a whale” using volume-weighted price.
*   **Components:** VWAP + EMA 50 + Fixed Volume Profile (POC) + RSI.
*   **Logic:**
    1.  **Trend:** Price > EMA 50.
    2.  **Value:** Price pulls back toward VWAP (return to the day’s “fair” price).
    3.  **Level:** Price is in a high-volume zone (Volume Profile POC protection).
    4.  **Trigger:** RSI bounces up from 40–50.
*   **Exit:** Price moves too far from VWAP (standard deviation move).
*   **Why it’s cool:** VWAP is used by institutional algos. Trading VWAP means trading with them, not against them.

### The "Trend Sniper" (parabolic_sar_adx_ema_macd)
Capturing runaway trends (parabolic runs).
*   **Components:** Parabolic SAR + ADX + EMA 100 + MACD.
*   **Logic:**
    1.  **Global:** Price > EMA 100.
    2.  **Strength:** ADX > 30 and rising (very strong trend).
    3.  **Trigger:** SAR dots are below price.
    4.  **Filter:** MACD > 0 and histogram rising.
*   **Special rule:** While ADX is rising, ignore small sell signals.
*   **Exit:** ADX starts falling (trend weakens) OR SAR flips.
*   **Why it’s cool:** Squeezes maximum out of parabolic rallies (e.g., BTC 20k→30k) without exiting on the first red candle.

### The "Whale Trail" System (volume_trend_value)
Following the big player (“whale”).
*   **Components:** VWAP + Chaikin Money Flow (CMF) + EMA 200 + Pivot Points.
*   **Logic:**
    1.  **Global trend:** Price > EMA 200.
    2.  **Fair price:** Price is above (or retesting from above) VWAP — buyers control the intraday auction.
    3.  **Money flow:** CMF > 0 and rising (accumulation).
    4.  **Trigger:** Breakout of the nearest Pivot resistance (R1/R2).
*   **Exit:** CMF falls below zero or price closes below VWAP.
*   **Why it’s cool:** You don’t trade “patterns”; you trade real institutional money flow.

### The "Elastic Band" Reversal (mean_reversion_trend_filter)
Catching deep pullbacks in a strong uptrend (the “slingshot”).
*   **Components:** Keltner Channels + RSI (2) + SMA 100 + Engulfing Pattern.
*   **Logic:**
    1.  **Filter:** SMA 100 slope strictly up (strong uptrend).
    2.  **Stretch:** Price breaks below the lower Keltner line (extreme deviation).
    3.  **Oversold:** RSI(2) drops below 5.
    4.  **Trigger:** Candle closes back inside the channel + a bullish Engulfing forms.
*   **Exit:** Price touches the middle or upper Keltner line.
*   **Why it’s cool:** Very high win rate. You buy fear (dump) against a backdrop of greed (uptrend).

### The "Guppy Tsunami" (gmma_adx)
A visual trend strategy using multiple moving averages (GMMA).
*   **Components:** GMMA (12 MAs: 6 fast, 6 slow) + ADX.
*   **Logic:**
    1.  **Compression:** Fast and slow MA groups converge (volatility drops; market compresses).
    2.  **Tsunami (Expansion):** Fast MAs separate sharply upward from slow MAs.
    3.  **Confirmation:** Slow MAs also start expanding (trend becomes sustainable).
    4.  **Filter:** ADX > 20 and rising.
*   **Exit:** Fast MAs start crossing down through slow MAs (compression).
*   **Why it’s cool:** Captures explosive trend phases and ignores minor pullbacks while the MA “school” points up.

### The "Quant Regression" Channel (linear_reg_pearson_r_atr)
Mathematically grounded channel trading.
*   **Components:** Linear Regression Channel (100) + Pearson Correlation Coefficient (r) + ATR Trailing Stop.
*   **Logic:**
    1.  **Trend quality:** Pearson r > 0.7 (price behaves like an upward line — stable growth without chaos).
    2.  **Buy cheap:** Price touches the lower regression channel boundary (2 standard deviations).
    3.  **Trigger:** Price bounces from the lower boundary.
*   **Exit:** Price touches the upper boundary or ATR stop triggers.
*   **Why it’s cool:** Trades only “beautiful”, stable trends and filters out messy charts with math.

### The "Golden Chaos" (ichimoku_bill_williams_fractals_ao)
A combo of eastern wisdom and chaos theory.
*   **Components:** Ichimoku Cloud + Fractals + Awesome Oscillator (AO).
*   **Logic:**
    1.  **Safety zone:** Price > Ichimoku Cloud.
    2.  **Energy:** AO is green and above zero.
    3.  **Trigger:** Price breaks the last up fractal (local high).
*   **Exit:** Close below Ichimoku Tenkan or AO turns red (in sequence).
*   **Why it’s cool:** Fractals give precise entry price (pending order), and Ichimoku ensures you don’t fight the global trend.

### The "Velocity" System (hull_ma_laguerre_rsi_volatility_stop)
An ultra-fast scalping system for volatile pairs (ETH, SOL).
*   **Components:** Hull Moving Average (HMA) + Laguerre RSI + Volatility Stop (VSTOP).
*   **Logic:**
    1.  **Speed:** HMA flips green (instant reaction to upside).
    2.  **Momentum:** Laguerre RSI crosses above 0.2 (exit the bottom).
    3.  **Protection:** Price is above VSTOP.
*   **Exit:** HMA flips red or VSTOP breaks.
*   **Why it’s cool:** Classic indicators lag. This combo uses minimal-lag tools to be first into the move.

### The "Fibonacci Confluence" (auto_fibs_ema_50_stochastic)
Automated pullback trading into the “golden ratio”.
*   **Components:** Auto Fibonacci Retracement + EMA 50 + Stochastic.
*   **Logic:**
    1.  **Context:** Price > EMA 50.
    2.  **Level:** Price corrects to Fib 0.5 or 0.618 (“Golden Pocket”) of the last impulse.
    3.  **Trigger:** Stochastic is oversold and crosses up.
*   **Exit:** Target at 0 (previous high) or -0.27 (Fib extension).
*   **Why it’s cool:** One of the most popular discretionary setups — the bot automates finding ideal entries.

## Recommendations

**General recommendation:**
Focus on 3–5 strategies that cover different market regimes (trend, range, momentum, volume). Prioritize multi-factor systems, then strong combined filters, and only then single indicators and patterns.

## Strategy Implementation

- [X] **RSI + Bollinger Bands** (rsi_bb)
- [X] **MACD** (macd)
- [X] **RSI Basic** (rsi_basic)
- [X] **SMA Crossover** (sma_cross)
- [X] **The "Fortress" Trend System** (trend_momentum_volatility_volume)
- [X] **Divergence Hunter Pro** (rsi_cci_mfi_ema)
- [X] **The "Whale Trail" System** (volume_trend_value)
- [X] **The "Elastic Band" Reversal** (mean_reversion_trend_filter)
- [X] **The "Guppy Tsunami"** (gmma_adx)
- [X] **Triple Screen (EMA+RSI+MACD)** (triple_screen_ema)
- [X] **SuperTrend + StochRSI** (super_stoch)
- [X] **ADX + Parabolic SAR** (adx_psar)
- [X] **Choppiness Index + EMA** (chop_ema)
- [X] **EMA + StochRSI** (ema_stoch)
- [X] **Schaff Trend Cycle** (stc_cycle)
- [X] **VWAP Trend** (vwap_cross)
- [ ] **Chaikin Money Flow (CMF)** (cmf_trend)
- [ ] **Linear Regression Slope** (lin_reg)
- [ ] **Z-Score** (z_score)
- [ ] **SuperTrend** (supertrend)
- [ ] **Donchian Channel Breakout** (donchian)
- [ ] **Parabolic SAR** (psar)
- [ ] **Dual Thrust** (dual_thrust)
- [ ] **Opening Range Breakout** (orb_strat)
- [ ] **Fibonacci Golden Pocket** (fib_golden)
- [ ] **Squeeze Momentum** (lazybear_squeeze)
- [ ] **DCA Rebound** (dca_martingale)
- [ ] **Gann Hi-Lo** (gann_hilo)
- [ ] **McGinley Dynamic** (mcginley)
- [ ] **Kaufman's Adaptive MA** (kama_trend)
- [ ] **Vortex** (vortex)
- [ ] **Money Flow Index (MFI)** (mfi_div)
- [ ] **Stoch RSI** (stoch_rsi)
- [ ] **TEMA Cross** (tema_cross)
- [ ] **Hull MA** (hma_trend)
- [ ] **Connors RSI 2** (rsi_2)
- [ ] **RSI Divergence** (rsi_div)
- [ ] **Inside Bar** (inside_bar)
- [ ] **Pinbar** (pinbar_reversal)
- [ ] **Engulfing Pattern** (engulfing_candle)
- [ ] **Three White Soldiers / Three Black Crows** (candle_patterns)
- [ ] **Heikin Ashi Trend** (ha_trend)
- [ ] **Bollinger Band Squeeze** (bb_squeeze)
- [ ] **Ichimoku Cloud Breakout** (ichimoku)
- [ ] **ADX + DMI** (adx_dmi)
- [ ] **OBV Trend** (obv_trend)
- [ ] **Keltner Channel Pullback** (keltner_pullback)
- [ ] **Awesome Oscillator** (ao_saucer)
- [ ] **CCI Correction** (cci_correction)
- [ ] **Elder's Force Index** (elder_force)
- [ ] **Williams %R** (williams_r)
- [ ] **Rate of Change** (roc)
- [ ] **ATR Channel Breakout** (volty_channel)
- [ ] **Aroon Strategy** (aroon)
- [ ] **TRIX (Triple Exponential Average)** (trix_strat)
- [ ] **Coppock Curve** (coppock)
- [ ] **Commodity Channel Index** (cci_trend)
- [ ] **VWMA vs SMA** (vwma_cross)
- [ ] **Williams Fractals** (fractal_breakout)
- [ ] **Fibonacci Bollinger Bands** (fib_bands)
- [ ] **Chandelier Exit Strategy** (chandelier_trend)
- [ ] **TD Sequential (Simplified)** (td_seq)
- [ ] **Ehlers Fisher Transform** (fisher_trans)
- [ ] **Standard Deviation Channel** (std_channel)
- [ ] **Pivot Points Reversal** (pivot_rev)
- [ ] **Williams Alligator** (alligator)
- [ ] **Chande Momentum Oscillator** (cmo_strat)
- [ ] **Ease of Movement (EOM)** (eom_trend)
- [ ] **Know Sure Thing (KST)** (kst_momentum)
- [ ] **Fractal Adaptive Moving Average (FRAMA)** (frama_trend)
- [ ] **Volume Price Trend (VPT)** (vpt_cross)
- [ ] **Laguerre RSI** (laguerre_rsi)
- [ ] **Detrended Price Oscillator (DPO)** (dpo_cycle)
- [ ] **Market Facilitation Index** (bw_mfi)
- [ ] **Psychological Line** (psy_line)
- [ ] **Random Walk Index** (rwi_trend)
- [ ] **Ulcer Index Strategy** (ulcer_strat)
- [ ] **k-Nearest Neighbors (kNN) Pattern Matching** (knn_ml)
- [ ] **Darvas Box Theory** (darvas_box)
- [ ] **Elder-Ray Index** (elder_ray)
- [ ] **Center of Gravity** (cog_ehlers)
- [ ] **Shannon Entropy** (entropy_chaos)
- [ ] **Relative Vigor Index** (rvi_trend)
- [ ] **VSTOP (Volatility Stop)** (vstop_trend)
- [ ] **Hurst Exponent Strategy** (hurst_exponent)
- [ ] **Synthetic Renko Trend** (renko_synthetic)
- [ ] **Volume Profile POC Rejection** (vpvr_poc)
- [ ] **Triple Screen Trading** (triple_screen)
- [ ] **Triple Screen Method** (triple_screen_custom)
- [ ] **Bollinger Breakout + MFI** (bb_mfi_breakout)
- [ ] **Ichimoku Cloud + MACD** (ichimoku_macd)
- [ ] **SMA 50/200 Pullback** (golden_cross_pullback)
- [ ] **Linear Regression + Z-Score** (stats_arbitrage)
- [ ] **SMA Golden Cross Pullback** (sma_pullback)
- [ ] **Bollinger Breakout + MFI** (bb_mfi)
- [ ] **Linear Regression + Z-Score** (linreg_zscore)
- [ ] **The "Perfect Scalp"** (heikin_ashi_ema_stochrsi_atr)
- [ ] **Advanced Squeeze** (bollinger_keltner_momentum_adx)
- [ ] **Ichimoku "Full House"** (tenkan_kijun_cloud_chikou_rsi)
- [ ] **VWAP Institutional Strategy** (vwap_ema_volume_profile_rsi)
- [ ] **The "Trend Sniper"** (parabolic_sar_adx_ema_macd)
- [ ] **The "Quant Regression" Channel** (linear_reg_pearson_r_atr)
- [ ] **The "Golden Chaos"** (ichimoku_bill_williams_fractals_ao)
- [ ] **The "Velocity" System** (hull_ma_laguerre_rsi_volatility_stop)
- [ ] **The "Fibonacci Confluence"** (auto_fibs_ema_50_stochastic)
