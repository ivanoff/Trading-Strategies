# Strategie di trading
- [Strategie](#strategies)
  - [RSI + Bande di Bollinger (rsi_bb)](#rsi--bollinger-bands-rsi_bb)
  - [MACD (macd)](#macd-macd)
  - [RSI Base (rsi_basic)](#rsi-basic-rsi_basic)
  - [SMA Crossover (sma_cross)](#sma-crossover-sma_cross)
  - [Spremitura delle bande di Bollinger (bb_squeeze)](#bollinger-band-squeeze-bb_squeeze)
  - [Evasione del canale Donchian/Commercio di tartarughe (donchian)](#donchian-channel-breakout--turtle-trading-donchian)
  - [Ichimoku Cloud Breakout (ichimoku)](#ichimoku-cloud-breakout-ichimoku)
  - [ADX + DMI (adx_dmi)](#adx--dmi-adx_dmi)
  - [Tendenza OBV (obv_trend)](#obv-trend-obv_trend)
  - [Strategia SuperTrend (supertrend)](#supertrend-strategy-supertrend)
  - [Trend EMA + RSI stocastico (ema_stoch)](#ema-trend--stochastic-rsi-ema_stoch)
  - [Strategia SAR parabolica (psar)](#parabolic-sar-strategy-psar)
  - [Indice dei flussi di denaro (MFI) (mfi_div)](#money-flow-index-mfi-mfi_div)
  - [TEMA Crossover (tema_cross)](#tema-crossover-tema_cross)
  - [Pullback del canale Keltner (keltner_pullback)](#keltner-channel-pullback-keltner_pullback)
  - [Fantastico oscillatore (ao_saucer)](#awesome-oscillator-ao_saucer)
  - [Correzione CCI (cci_correction)](#cci-correction-cci_correction)
  - [Tendenza VWAP (vwap_cross)](#vwap-trend-vwap_cross)
  - [RSI stocastico (stoch_rsi)](#stochastic-rsi-stoch_rsi)
  - [Indice della Forza degli Anziani (elder_force)](#elders-force-index-elder_force)
  - [Williams %R (williams_r)](#williams-r-williams_r)
  - [MA adattivo di Kaufman (kama_trend)](#kaufmans-adaptive-ma-kama_trend)
  - [Tasso di variazione (ROC)](#rate-of-change-roc)
  - [Separazione canale ATR (volty_channel)](#atr-channel-breakout-volty_channel)
  - [Pendenza di regressione lineare (lin_reg)](#linear-regression-slope-lin_reg)
  - [Flusso di denaro Chaikin (cmf_trend)](#chaikin-money-flow-cmf_trend)
  - [Indicatore vortice (vortice)](#vortex-indicator-vortex)
  - [Strategia Aroon (aroon)](#aroon-strategy-aroon)
  - [TRIX (Tripla media esponenziale) (trix_strat)](#trix-triple-exponential-average-trix_strat)
  - [Curva Coppock (coppock)](#coppock-curve-coppock)
  - [Indice del canale delle materie prime (cci_trend)](#commodity-channel-index-cci_trend)
  - [Andamento della media mobile dello scafo (hma_trend)](#hull-moving-average-trend-hma_trend)
  - [Strategia Z-Score (z_score)](#z-score-strategy-z_score)
  - [VWMA contro SMA (vwma_cross)](#vwma-vs-sma-vwma_cross)
  - [Connors RSI 2 (rsi_2)](#connors-rsi-2-rsi_2)
  - [Frattali Williams (fractal_breakout)](#williams-fractals-fractal_breakout)
  - [Bande di Bollinger di Fibonacci (fib_bands)](#fibonacci-bollinger-bands-fib_bands)
  - [Strategia di uscita dal lampadario (chandelier_trend)](#chandelier-exit-strategy-chandelier_trend)
  - [Interruzione della barra interna (inside_bar)](#inside-bar-breakout-inside_bar)
  - [TD sequenziale (semplificato) (td_seq)](#td-sequential-simplified-td_seq)
  - [Trasformazione Ehlers Fisher (fisher_trans)](#ehlers-fisher-transform-fisher_trans)
  - [Divergenza RSI (rsi_div)](#rsi-divergence-rsi_div)
  - [Trend Heikin Ashi (ha_trend)](#heikin-ashi-trend-ha_trend)
  - [Canale deviazione standard (std_channel)](#standard-deviation-channel-std_channel)
  - [Inversione punti pivot (pivot_rev)](#pivot-points-reversal-pivot_rev)
  - [Williams Alligator (alligatore)](#williams-alligator-alligator)
  - [Modello inghiottente (engulfing_candle)](#engulfing-pattern-engulfing_candle)
  - [McGinley Dinamico (mcginley)](#mcginley-dynamic-mcginley)
  - [Doppia spinta (dual_thrust)](#dual-thrust-dual_thrust)
  - [Oscillatore Chande Momentum (cmo_strat)](#chande-momentum-oscillator-cmo_strat)
  - [Facilità di movimento (eom_trend)](#ease-of-movement-eom_trend)
  - [Conosci le cose sicure (KST) (kst_momentum)](#know-sure-thing-kst-kst_momentum)
  - [Ciclo di tendenza di Schaff (stc_cycle)](#schaff-trend-cycle-stc_cycle)
  - [Filtro indice di discontinuità + EMA (chop_ema)](#choppiness-index-filter--ema-chop_ema)
  - [Media mobile adattiva frattale (frama_trend)](#fractal-adaptive-moving-average-frama_trend)
  - [Andamento dei prezzi in volume (vpt_cross)](#volume-price-trend-vpt_cross)
  - [Laguerre RSI (laguerre_rsi)](#laguerre-rsi-laguerre_rsi)
  - [Pinbar (Martello/Stella cadente) (pinbar_reversal)](#pinbar-hammershooting-star-pinbar_reversal)
  - [Oscillatore del prezzo detrendizzato (dpo_cycle)](#detrended-price-oscillator-dpo_cycle)
  - [Intervallo intervallo di apertura (orb_strat)](#opening-range-breakout-orb_strat)
  - [Indice di facilitazione del mercato (bw_mfi)](#market-facilitation-index-bw_mfi)

- [Linea psicologica (psy_line)](#psychological-line-psy_line)
  - [Fibonacci Tasca d'oro (fib_golden)](#fibonacci-golden-pocket-fib_golden)
  - [Tre soldati bianchi/Tre corvi neri (candle_patterns)](#three-white-soldiers--three-black-crows-candle_patterns)
  - [Indice camminata casuale (rwi_trend)](#random-walk-index-rwi_trend)
  - [Strategia sull'indice Ulcer (ulcer_strat)](#ulcer-index-strategy-ulcer_strat)
  - [k-Vicini più vicini (kNN) Corrispondenza modello (knn_ml)](#k-nearest-neighbors-knn-pattern-matching-knn_ml)
  - [Teoria della scatola di Darvas (darvas_box)](#darvas-box-theory-darvas_box)
  - [Indice Elder-Ray (elder_ray)](#elder-ray-index-elder_ray)
  - [Centro di gravità (cog_ehlers)](#center-of-gravity-cog_ehlers)
  - [Entropia di Shannon (entropy_chaos)](#shannon-entropy-entropy_chaos)
  - [Indice di vigore relativo (rvi_trend)](#relative-vigor-index-rvi_trend)
  - [VSTOP (arresto della volatilità) (vstop_trend)](#vstop-volatility-stop-vstop_trend)
  - [Cosa scegliere dopo?](#what-to-pick-next)
  - [Indicatore Squeeze Momentum (lazybear_squeeze)](#squeeze-momentum-indicator-lazybear_squeeze)
  - [Strategia dell'esponente di Hurst (hurst_exponent)](#hurst-exponent-strategy-hurst_exponent)
  - [Tendenza Renko sintetico (renko_sintetico)](#synthetic-renko-trend-renko_synthetic)
  - [Attivatore Gann Hi-Lo (gann_hilo)](#gann-hi-lo-activator-gann_hilo)
  - [Rifiuto POC profilo volume (vpvr_poc)](#volume-profile-poc-rejection-vpvr_poc)
  - [Rimbalzo DCA (media del costo del dollaro) (dca_martingale)](#dca-rebound-dollar-cost-averaging-dca_martingale)
  - [Trading su triplo schermo (triple_screen)](#triple-screen-trading-triple_screen)
- [Strategie combinate](#combined-strategies)
  - [Metodo triplo schermo (triple_screen_custom)](#triple-screen-method-triple_screen_custom)
  - [Breakout di Bollinger + MFI (bb_mfi_breakout)](#bollinger-breakout--mfi-bb_mfi_breakout)
  - [Ichimoku Cloud + MACD (ichimoku_macd)](#ichimoku-cloud--macd-ichimoku_macd)
  - [ADX + SAR parabolico (adx_psar)](#adx--parabolic-sar-adx_psar)
  - [Ritiro SMA 50/200 (golden_cross_pullback)](#sma-50200-pullback-golden_cross_pullback)
  - [Regressione lineare + punteggio Z (stats_arbitrage)](#linear-regression--z-score-stats_arbitrage)
  - [Metodo triplo schermo (triple_screen_ema)](#triple-screen-method-triple_screen_ema)
  - [SMA Golden Cross Pullback (sma_pullback)](#sma-golden-cross-pullback-sma_pullback)
  - [SuperTrend + StochRSI (super_stoch)](#supertrend--stochrsi-super_stoch)
  - [Breakout di Bollinger + MFI (bb_mfi)](#bollinger-breakout--mfi-bb_mfi)
  - [Regressione lineare + punteggio Z (linreg_zscore)](#linear-regression--z-score-linreg_zscore)
  - [Il sistema di trend "Fortezza" (trend_momentum_volatility_volume)](#the-fortress-trend-system-trend_momentum_volatility_volume)
  - [Il "cuoio capelluto perfetto" (heikin_ashi_ema_stochrsi_atr)](#the-perfect-scalp-heikin_ashi_ema_stochrsi_atr)
  - [Divergence Hunter Pro (rsi_cci_mfi_ema)](#divergence-hunter-pro-rsi_cci_mfi_ema)
  - [Compressione avanzata (bollinger_keltner_momentum_adx)](#advanced-squeeze-bollinger_keltner_momentum_adx)
  - [Ichimoku "Tutto esaurito" (tenkan_kijun_cloud_chikou_rsi)](#ichimoku-full-house-tenkan_kijun_cloud_chikou_rsi)
  - [Strategia istituzionale VWAP (vwap_ema_volume_profile_rsi)](#vwap-institutional-strategy-vwap_ema_volume_profile_rsi)
  - [Il "cecchino delle tendenze" (parabolic_sar_adx_ema_macd)](#the-trend-sniper-parabolic_sar_adx_ema_macd)
  - [Il sistema "Sentiero delle balene" (volume_trend_value)](#the-whale-trail-system-volume_trend_value)
  - [L'inversione della "banda elastica" (mean_reversion_trend_filter)](#the-elastic-band-reversal-mean_reversion_trend_filter)
  - [Lo "Tsunami Guppy" (gmma_adx)](#the-guppy-tsunami-gmma_adx)
  - [Il canale "Regressione quantistica" (linear_reg_pearson_r_atr)](#the-quant-regression-channel-linear_reg_pearson_r_atr)
  - [Il "Caos d'oro" (ichimoku_bill_williams_fractals_ao)](#the-golden-chaos-ichimoku_bill_williams_fractals_ao)
  - [Il sistema "Velocity" (hull_ma_laguerre_rsi_volatility_stop)](#the-velocity-system-hull_ma_laguerre_rsi_volatility_stop)
  - [La "Confluenza di Fibonacci" (auto_fibs_ema_50_stochastic)](#the-fibonacci-confluence-auto_fibs_ema_50_stochastic)
- [Consigli](#recommendations)
- [Attuazione della strategia](#strategy-implementation)
## Strategie
### RSI + Bande di Bollinger (rsi_bb)
Una strategia ibrida che mira a cogliere un punto di inversione ideale filtrando i falsi segnali.
* **Tipo:** Reversione alla media.
* **Logica:** Combina volatilità (bande di Bollinger) e momentum (RSI). Le bande di Bollinger ci dicono che il prezzo è statisticamente “troppo basso” (deviato dalla norma) e l’RSI conferma che i venditori sono esausti.
* **Entrata:** La chiusura rompe la banda BB **Inferiore** e allo stesso tempo l'RSI è in ipervenduto (< 30).
* **Uscita:** Il prezzo ritorna sulla **linea centrale** BB (SMA 20). Non aspettiamo la fascia superiore, perché in un mercato al ribasso l’obiettivo di ritorno alla media più sicuro è quello centrale.
* **Edge:** Risolve il classico problema di "afferrare i coltelli che cadono". Non compri solo perché è economico; si acquista quando la deviazione è estrema e c'è la conferma della debolezza del venditore.
### MACD (macd)
La strategia di indicatori più classica al mondo.
* **Tipo:** Segui tendenza/Momentum.
* **Logica:** Il MACD misura lo spread tra le EMA veloci (12) e quelle lente (26). L'istogramma mostra il tasso di variazione di tale spread.
* **Voce:** Il MACD attraversa la linea del segnale dal basso verso l'alto (o l'istogramma passa da negativo a positivo), il che significa che lo slancio a breve termine ha superato quello a lungo termine.
* **Esci:** La croce opposta (dall'alto verso il basso).
* **Edge:** Cattura la “carne” del trend (la parte centrale del movimento). Si comporta male in caso di choc, ma in caso di movimenti forti di BTC/ETH può generare segnali affidabili.
### RSI Base (rsi_basic)
Una strategia di base in controtendenza.
* **Tipologia:** Controtendenza.
* **Logica:** Il mercato oscilla come un pendolo. Se va troppo lontano in una direzione, tende a tornare indietro.
* **Entrata:** L'RSI scende sotto 30 (ipervenduto). Scommetti su un rimbalzo.
* **Uscita:** L'RSI sale sopra 70 (ipercomprato).
* **Bordo:** Il più semplice da capire; funziona bene in un ampio intervallo (mercato laterale).
* **Svantaggio:** Pericoloso nei trend forti. In un crollo l'RSI può restare fermo a 20 per una settimana mentre il prezzo scende di un altro 50%. Richiede uno stop loss obbligatorio.
### SMA Crossover (sma_cross)
La strategia della “Croce d’Oro”.
* **Tipo:** Segui tendenza.
* **Logica:** Utilizza due medie mobili semplici. La SMA veloce reagisce al prezzo più rapidamente; la SMA lenta riflette la direzione più ampia.
* **Entrata:** La SMA veloce supera la SMA lenta. Una conferma matematica che il trend è diventato rialzista.
* **Uscita:** La SMA veloce passa sotto la SMA lenta (“Croce della morte”).
* **Edge:** ti mantiene dalla parte giusta delle principali tendenze. Non ti perderai una mossa "sulla luna", a costo di entrate e uscite lente.
### Squeeze delle bande di Bollinger (bb_squeeze)
Una strategia di ripresa dopo la calma. Utilizza le bande di Bollinger in modo diverso da `rsi_bb`.
* **Tipo:** Breakout di volatilità.
* **Logica:** I mercati sono ciclici: una bassa volatilità è seguita da un'elevata volatilità. Cerca uno “squeeze” in cui le Bande di Bollinger si contraggono al minimo e il Canale Keltner si trova all'interno delle Bande di Bollinger.
* **Entrata:** Quando le bande iniziano ad espandersi e il prezzo supera il limite superiore, vai Long.
* **Uscita:** Il prezzo ritorna sulla linea mediana oppure le bande si contraggono nuovamente.
* **Perché è bello:** Ti permette di entrare all'inizio di un potente impulso prima che diventi evidente a tutti.
### Breakout del canale Donchian/Scambio di tartarughe (donchian)
La classica strategia delle “Tartarughe”. Semplice, ma efficace su tempi più lunghi (4h, 1d).
* **Tipo:** Breakout.
* **Logica:** Il Canale Donchian è il massimo più alto e il minimo più basso negli ultimi N periodi (ad es. 20).
* **Entrata:** Il prezzo rompe il canale superiore (nuovo massimo a 20 candele) — Long.
* **Uscita:** Il prezzo tocca il canale inferiore (o la linea mediana per una presa di profitto più rapida).
* **Perché è bello:** Cattura tutte le principali tendenze. Unico inconveniente: molte voci false negli intervalli (i prelievi possono essere elevati).
### Ichimoku Cloud Breakout (ichimoku)
Un complesso sistema giapponese che mostra supporto, resistenza e tendenza allo stesso tempo.
* **Tipo:** Segui tendenza.
* **Logica:** Il nucleo è la “Nuvola” (Kumo).
* **Entrata:** Chiudi sopra la Nuvola + Tenkan incrocia Kijun dal basso verso l'alto (croce d'oro) — segnale lungo e forte.
* **Uscita:** Chiusura sotto Kijun oppure il prezzo entra nel cloud.
* **Perché è bello:** La nuvola filtra bene il rumore. Se il prezzo è all’interno del cloud, non fare trading. Risparmia capitale nell'incertezza.
### ADX + DMI (adx_dmi)
Commercia solo quando il mercato è forte.
* **Tipo:** Filtro intensità tendenza.
* **Logica:** L'ADX misura la forza del trend (nessuna direzione). DMI (+DI e -DI) fornisce la direzione.
* **Entrata:** Se ADX > 25 (tendenza forte) **e** +DI incrocia -DI bottom-up — Long. Se ADX < 20 — ignora i segnali (mercato morto).
* **Esci:** Quando +DI torna sotto -DI.
* **Perché è interessante:** Aiuta a evitare "tagli" laddove commissioni e trucchetti causano i maggiori danni.
### Tendenza OBV (obv_trend)
Utilizzo del volume per confermare il movimento dei prezzi.
* **Tipo:** Andamento del volume.
* **Logica:** L'OBV (On-Balance Volume) accumula i volumi delle candele. Se il prezzo aumenta ma l’OBV diminuisce, si parla di divergenza. Per un bot, è più semplice scambiare il trend OBV stesso.
* **Voce:** Calcola un MA di OBV. Se l'OBV supera la sua MA, il denaro affluisce. Long.
* **Uscita:** L'OBV scende al di sotto della sua MA.
* **Perché è bello:** Il prezzo può mentire; il volume (denaro) di solito non può. L’OBV spesso inizia a salire prima che i prezzi aumentino.
### Strategia SuperTrend (supertrend)
Una delle strategie crittografiche più popolari grazie al meccanismo di trailing stop integrato.
* **Tipo:** Segui tendenza.
* **Logica:** SuperTrend si basa sull'ATR (volatilità media). Traccia una linea sotto il prezzo nei trend rialzisti e sopra il prezzo nei trend al ribasso.
* **Inserimento:** Chiusura sopra la linea SuperTrend — Long. Chiudi sotto: Short (o chiudi Long).
* **Esci:** L'indicatore cambia colore/direzione.
* **Perché è interessante:** Cattura i movimenti più importanti e segue automaticamente lo stop loss con il prezzo. Funziona alla grande con forti trend BTC/ETH.
### Trend EMA + RSI stocastico (ema_stoch)
Una strategia ibrida che risolve il problema principale di `rsi_basic`: acquistare “coltelli che cadono”.
* **Tipo:** Oscillatore con filtro di tendenza.
* **Logica:** Utilizza una media mobile “lunga” (EMA 200) per definire la tendenza globale.
* **Inserimento:**
    * Acquista SOLO se il prezzo è **sopra** EMA 200 (trend rialzista) **e** l'RSI stocastico supera l'ipervenduto (ad es. < 20).
    * Ignora i segnali di acquisto se il prezzo è inferiore a EMA 200.
* **Uscita:** L'RSI stocastico entra in ipercomprato (> 80) o attraversa al ribasso.
* **Perché è interessante:** Filtra circa l'80% dei falsi segnali contrari alla tendenza.
### Strategia SAR parabolica (psar)
La classica strategia “sempre nel mercato” (Stop and Reverse).
* **Tipo:** Seguire/Invertire il trend.
* **Logica:** L'indicatore traccia i punti sotto il prezzo (trend al rialzo) o sopra il prezzo (trend al ribasso). I punti si restringono al prezzo man mano che il trend matura.
* **Inserimento:** Il prezzo attraversa un punto SAR parabolico. Se i punti si ribaltano **sotto** il prezzo — Long.
* **Uscita:** i punti si ribaltano **sopra** il prezzo: chiudi Long (e facoltativamente apri Short).
* **Pro:** Ottimo per trend forti; ti costringe a trattenere finché non c'è una pausa esplicita.
* **Contro:** Negli intervalli, i lanci frequenti possono prosciugare il conto.
### Indice dei flussi di denaro (MFI) (mfi_div)
“RSI con volume”. Cerca di rilevare il denaro intelligente.
* **Tipo:** Momento del volume.
* **Logica:** Il prezzo può aumentare per inerzia, ma se il volume diminuisce il trend è a corto di carburante. Le IFM rappresentano sia il prezzo che il volume.
* **Entrata:** L'MFI scende sotto 20 (ipervenduto) e sale — Long. La divergenza (prezzo in ribasso, MFI in rialzo) funziona ancora meglio.
* **Uscita:** MFI superiore a 80 (ipercomprato).
* **Pro:** Filtra i movimenti di prezzo “vuoti” non supportati dal volume. Spesso guida l'RSI.
### TEMA Crossover (tema_cross)
Utilizza Triple EMA (TEMA) per ridurre il ritardo.
* **Tipo:** Trend veloce.
* **Logica:** Lag SMA/EMA regolare. TEMA reagisce quasi istantaneamente.
* **Ingresso:** La TEMA veloce (ad esempio, 9) incrocia sopra la TEMA lenta (ad esempio, 21).
* **Esce:** La croce opposta.
* **Pro:** Entra prima del cross SMA ed esce più velocemente in caso di inversioni.
* **Contro:** Più falsi segnali (“rumore”) in mercati calmi.
### Pullback del canale Keltner (keltner_pullback)
Trading sui pullback in trend forti. Un'alternativa al BB.
* **Tipo:** Tendenza pullback.
* **Logica:** Keltner Channel è basato sull'ATR (volatilità). Se il prezzo rimane a lungo al di sopra della banda *superiore*, il trend è molto forte.
* **Inserimento:**
    1. Conferma il trend rialzista (Prezzo > EMA 20 o linea mediana del canale).
    2. Attendere il pullback sulla linea del canale **inferiore** o **medio**.
    3. Vai a lungo al tocco/rimbalzo.
* **Uscita:** Il prezzo raggiunge la fascia del canale superiore.
* **Pro:** “Acquista durante il calo” all'interno di un trend rialzista. Buon rischio/rendimento.
### Fantastico oscillatore (ao_saucer)
La strategia del “piattino” di Bill Williams.
* **Tipo:** Slancio.
* **Logica:** L'istogramma AO mostra la forza trainante del mercato.
* **Inserimento (il modello “Saucer”):** Istogramma sopra lo zero. Cerca 3 barre: Rossa -> Rossa (inferiore alla prima) -> Verde (superiore alla seconda). La correzione è terminata e la crescita riprende.
* **Esci:** il colore diventa rosso o l'istogramma scende sotto lo zero.
* **Pro:** Un “microscopio” per i tempi di ingresso all'interno delle onde.
### Correzione CCI (cci_correction)
Commodity Channel Index, popolare nel forex e nelle criptovalute.
* **Tipo:** Ciclico.
* **Logica:** Il CCI misura la deviazione del prezzo dalla sua media statistica.
* **Entrata:** Attendi che il CCI scenda sotto -100 (forte ipervenduto) e poi superi -100.
* **Uscita:** Il CCI sale sopra +100 o incrocia lo 0 dall'alto verso il basso.
* **Pro:** Livelli chiari (-100/+100), logica meccanica semplice.
### Tendenza VWAP (vwap_cross)
Una strategia utilizzata dai trader istituzionali. Il VWAP (Prezzo medio ponderato per il volume) mostra il prezzo “equo” dell’asset tenendo conto del volume.
* **Tipo:** Segui tendenza/Volume.
* **Logica:** Se il prezzo è superiore al VWAP, gli acquirenti controllano il mercato (rialzista). Se di seguito - venditori.
* **Inserimento:** Il prezzo incrocia il VWAP dal basso verso l'alto.
* **Uscita:** Il prezzo incrocia il VWAP dall'alto verso il basso.
* **Nota:** Intraday molto efficace (5 minuti, 15 minuti, 1 ora) perché le istituzioni spesso si ancorano al VWAP.
### RSI stocastico (stoch_rsi)
Una versione più sensibile e più veloce dell'RSI. Aiuta a catturare le oscillazioni a breve termine all'interno di una tendenza.
* **Tipo:** Scalping/Oscillatore.
* **Logica:** StochRSI applica la formula stocastica ai valori RSI, non al prezzo, rendendolo molto reattivo.
* **Entrata:** Le linee StochRSI si incrociano in ipervenduto (< 20) e salgono.
* **Esci:** Entra in ipercomprato (> 80) e scendi.
* **Nota:** Genera molti segnali. Necessita di un filtro (ad esempio, scambia solo con il trend EMA), altrimenti si muoverà negli intervalli.
### Indice della Forza dell'Anziano (elder_force)
La strategia di Alexander Elder. Combina prezzo e volume per misurare il potere “rialzista” e “ribasso”.
* **Tipo:** Slancio.
* **Logica:** Indice di forza = (Close - PrevClose) * Volume, quindi livellato (EMA).
* **Entrata:** Tendenza globale al rialzo (ad esempio, prezzo superiore all'EMA 22) e l'indice di forza (periodo 2) scende sotto lo zero (pullback a breve termine). Compra la salsa.
* **Uscita:** L'indice di forza torna di nuovo positivo (ritorna lo slancio).
* **Nota:** Ottimo per individuare le voci di pullback in trend forti.
### Williams %R (williams_r)
Indicatore di Larry Williams. Simile allo stocastico, ma invertito. Ottimo nelle gamme.
* **Tipo:** Reversione alla media.
* **Logica:** Misura quanto è vicina la chiusura all'intervallo massimi/minimi.
* **Entrata:** Il valore scende sotto -80 (ipervenduto) e inizia a salire.
* **Uscita:** Il valore sale sopra -20 (ipercomprato).
* **Nota:** Bravo a evidenziare l'esaurimento del venditore.
### MA adattiva di Kaufman (kama_trend)
Una strategia basata sulla media mobile adattiva di Kaufman.
* **Tipo:** Tendenza adattiva.
* **Logica:** A differenza di un normale EMA, KAMA rallenta negli intervalli rumorosi (si appiattisce) e accelera nei trend. Ciò riduce le voci false.
* **Inserimento:** Il prezzo incrocia KAMA dal basso verso l'alto.
* **Uscita:** Il prezzo incrocia KAMA dall'alto verso il basso.
* **Nota:** Una media mobile “intelligente” che filtra i risultati.
### Tasso di variazione (ROC)
Negoziare la velocità del cambiamento dei prezzi. Pura fisica del mercato.
* **Tipo:** Velocità/Momento.
* **Logica:** ROC mostra la variazione percentuale su N periodi. L’aumento del ROC significa che il trend sta accelerando.
* **Voce:** Il ROC supera lo zero (accelerazione al rialzo).
* **Esci:** Il ROC passa sotto lo zero (decelerazione).
* **Nota:** Un indicatore anticipatore; spesso segnala inversioni prima che le MA si incrocino.
### Breakout del canale ATR (volty_channel)
Rottura del canale di volatilità.
* **Tipo:** Breakout.
* **Logica:** Costruisci un canale attorno al prezzo: `Close + (N * ATR)` e `Close - (N * ATR)`.
* **Inserimento:** Chiude sopra il canale superiore. Un movimento anormalmente forte oltre la normale volatilità.
* **Esci:** Il prezzo ritorna al centro.
* **Nota:** Cattura le pompe/scarico più potenti ignorando il rumore minore.
### Pendenza di regressione lineare (lin_reg)
Trading basato sulla pendenza matematica di una linea di tendenza.
* **Tipo:** Statistico/Trend.
* **Logica:** Invece di calcolare la media dei prezzi (come la SMA), adatta una linea di regressione lineare sulle ultime N candele e utilizza la sua pendenza.
* **Inserimento:** La pendenza diventa positiva e supera una soglia (filtro rumore). Statisticamente la tendenza si è invertita verso l’alto.
* **Esci:** La pendenza diventa negativa.
* **Perché è interessante:** Reagisce più velocemente delle MA perché cerca di modellare la direzione, non solo di fare una media del passato.
### Flusso di denaro Chaikin (cmf_trend)
Strategia di accumulazione/distribuzione. Simile all'MFI, ma utilizza un'analisi più approfondita della posizione di chiusura all'interno dell'intervallo della candela.
* **Tipo:** Portata volumetrica.
* **Logica:** CMF stima la pressione di acquisto/vendita. CMF > 0 significa accumulo (afflusso di denaro); CMF < 0 significa distribuzione (il denaro esce).
* **Voce:** Il CMF incrocia sopra lo zero.
* **Esci:** CMF torna sotto lo zero.
* **Perché è interessante:** Aiuta a separare una vera inversione da un “rimbalzo del gatto morto”: se il prezzo aumenta mentre CMF < 0, il movimento è probabilmente debole.
### Indicatore di vortice (vortice)
Un indicatore ispirato ai modelli di flusso naturale (vortici).
* **Tipo:** Segui tendenza.
* **Logica:** Due linee: VI+ e VI-. Misurano il movimento direzionale in base alle distanze tra il massimo attuale e il minimo precedente (e viceversa).
* **Inserimento:** VI+ incrocia sopra VI-.
* **Esci:** VI+ incrocia sotto VI-.
* **Perché è interessante:** Affidabile per rilevare l'inizio di trend più lunghi, anche se può ritardare negli intervalli.
### Strategia Aroon (aroon)
Una strategia che misura il *tempo* trascorso dall'ultimo massimo/minimo.
* **Tipo:** Intensità del trend.
* **Logica:** Aroon Up mostra quanti giorni sono trascorsi da un livello elevato; Aroon Down dal minimo. I valori sono compresi tra 0 e 100.
* **Voce:** Aroon Up incrocia sopra Aroon Down **e** Aroon Up > 50. Nuovi massimi appaiono più spesso dei minimi.
* **Uscita:** Aroon Up scende sotto 50 o supera Aroon Down.
* **Perché è interessante:** Un approccio unico basato sul tempo anziché su semplici segnali basati sul prezzo.
### TRIX (Tripla media esponenziale) (trix_strat)
Un oscillatore di momento molto fluido.
* **Tipo:** Slancio.
* **Logica:** EMA triplo livellato (spesso sul prezzo di registro), che rimuove la maggior parte del rumore del mercato.
* **Inserimento:** TRIX incrocia sopra lo zero.
* **Uscita:** Ritorno sotto lo zero o incrocio della linea di segnale.
* **Perché è bello:** Pochi ma segnali di alta qualità; funziona bene su tempi più lunghi (4h, 1d).
### Curva di Coppock (coppock)
Un indicatore progettato per individuare i minimi di mercato a lungo termine (originariamente per S&P 500), ma funziona anche nel settore delle criptovalute.
* **Tipo:** Oscillazione/Investimento a lungo termine.
* **Logica:** Somma di due valori ROC con periodi diversi, livellati da una media mobile ponderata.
* **Nota:** La curva di Coppock inizia a salire mentre è sotto lo zero.
* **Esci:** La curva gira verso il basso (o attraversa lo 0).
* **Perché è bello:** Psicologicamente confortevole: voci rare, spesso vicine all'inizio di un mercato rialzista più ampio.
### Indice del canale delle materie prime (cci_trend)
Utilizzo del CCI per il trading di tendenza (non controtendenza come prima).
* **Tipo:** Tendenza.
* **Logica:** Il CCI viene spesso utilizzato per le inversioni, ma qui lo utilizziamo come segnale di breakout/momentum.
* **Entrata:** Il CCI sale sopra +100 — un forte impulso al rialzo.
* **Uscita:** il CCI torna sotto +100 (o sotto 0).
* **Perché è bello:** Cattura la parte "più grassa" di una mossa quando una risorsa va "sulla luna".
### Tendenza della media mobile dello scafo (hma_trend)
Una strategia basata sulla media mobile dello scafo (HMA).
* **Tipo:** Segue tendenza con ritardo basso.
* **Logica:** Alan Hull ha creato una formula che riduce il ritardo tipico di SMA/EMA mantenendo una curva uniforme.
* **Inserimento:** Il prezzo supera l'HMA (o la pendenza dell'HMA si ribalta dal basso verso l'alto).
* **Esci:** La croce opposta o il ribaltamento inclinato.
* **Edge:** Reagisce alle inversioni quasi istantaneamente; ottimo su coppie volatili in cui le MA regolari sono troppo lente.
### Strategia Z-Score (z_score)
Pura statistica matematica senza “linee magiche”.
* **Tipo:** Reversione alla media.
* **Logica:** Il punteggio Z misura quante deviazioni standard (sigma) il prezzo si discosta dalla sua media, come le bande di Bollinger "digitali".
* **Voce:** Il punteggio Z scende sotto -2 (deviazione al ribasso di 2-sigma). Acquista aspettandoti una reversione.
* **Esci:** Il punteggio Z ritorna a 0 (media) o sale sopra +2.
* **Edge:** Funziona su qualsiasi asset perché normalizza la volatilità.
### VWMA vs SMA (vwma_cross)
Convalidare la forza del trend tramite il volume.
* **Tipo:** Trend + Conferma volume.
* **Logica:** Confronta SMA con VWMA (MA ponderata per il volume).
    * Se VWMA > SMA, il volume è più forte sulle candele al rialzo (acquisto da parte degli operatori più grandi).
    * Se VWMA < SMA mentre il prezzo sale, il movimento avviene su un volume debole (possibile trappola).
* **Entrata:** La VWMA supera la SMA.
* **Uscita:** La VWMA supera la SMA.
* **Edge:** Filtra le pompe "gonfiate" senza soldi veri alle spalle.
### Connors RSI 2 (rsi_2)
La famosa strategia di scalping di Larry Connors.
* **Tipo:** Reversione alla media aggressiva a breve termine.
* **Logica:** L'RSI(14) standard è troppo lento; Connors usa l'RSI con il periodo 2.
* **Entrata:** L'RSI(2) scende sotto 10 (o 5) — estremo ipervenduto. Vai a lungo.
* **Uscita:** Chiusura sopra la SMA a 5 giorni. Non aspettare RSI > 90; esci al primo rimbalzo.
* **Vantaggio:** Tasso di vincita molto elevato (spesso > 80%), ma le operazioni sono brevi e il profitto per operazione è piccolo.
### Frattali Williams (fractal_breakout)
Breakout commerciali a livello locale (Price Action).
* **Tipo:** Breakout.
* **Logica:** Un frattale Williams è una formazione a 5 candele in cui la candela centrale ha il massimo più alto (frattale verso l'alto) o il minimo più basso (frattale verso il basso). Questi sono picchi/valli locali.
* **Voce:** Il prezzo rompe il livello dell'ultimo frattale ascendente (la candela frattale Alta).
* **Uscita:** Il prezzo rompe il livello dell'ultimo frattale ribassista (trailing stop).
* **Edge:** Negozia livelli di supporto/resistenza reali rilevati dal mercato, non formule derivate.
### Bande di Bollinger di Fibonacci (fib_bands)
Un approccio modificato alle Bande di Bollinger per catturare rimbalzi più precisi.
* **Tipo:** Inversione media/tendenza.
* **Logica:** Invece dei moltiplicatori della deviazione standard (x2, x3), per le larghezze di banda vengono utilizzati i rapporti di Fibonacci (1,618, 2,618, 4,236).
* **Entrata:** Il prezzo tocca una banda interna (Fib 1.618) o una banda esterna (Fib 2.618) e rimbalza.
* **Esci:** Ritorna alla linea mediana.
* **Edge:** Le criptovalute spesso rispettano i livelli di Fibonacci più di un modello gaussiano perfetto.
### Strategia di uscita da Chandelier (chandelier_trend)
Una strategia costruita dalla direzione opposta: gestione dell'uscita (stop loss).
* **Tipo:** Segui tendenza.
* **Logica:** Chandelier Exit sospende uno stop loss a una distanza (ATR * 3) al di sotto del massimo più alto durante un lookback. Se il prezzo non raggiunge il “lampadario”, rimani dentro.
* **Entrata:** Chiusura sopra la linea di uscita di Chandelier (trend invertito rialzista).
* **Uscita:** Il prezzo tocca la linea (trailing stop hit).
* **Edge:** Progettato per lasciar correre i profitti ed evitare di uscire in caso di piccoli pullback.
### Breakout all'interno della barra (inside_bar)
Una classica strategia di Price Action senza indicatori.
* **Tipo:** Breakout/modello di volatilità.
* **Logica:** Trova una barra interna: una candela il cui massimo/minimo sia completamente all'interno della precedente candela “madre”. Il mercato si comprime prima dell’espansione.
* **Entrata:** Il prezzo rompe il massimo della barra interna (per i long).
* **Uscita:** Take profit o trailing stop fissi. Lo stop loss è posizionato dietro il minimo della barra interna.
* **Edge:** Stop molto stretti con elevato potenziale di rialzo (rischio/rendimento).
### TD sequenziale (semplificato) (td_seq)
Una versione semplificata della leggendaria strategia di Thomas DeMark.
* **Tipologia:** Controtendenza/Inversione.
* **Logica:** I mercati si stancano di muoversi in una direzione. DeMark conta le chiusure sequenziali.
* **Entrata (Setup):** Se vedi **9 candele consecutive** in cui ciascuna chiusura è inferiore alla chiusura delle 4 candele precedenti (Setup ribassista) — i venditori sono esausti. Inserisci Long all'apertura della candela 10.
* **Uscita:** Nel setup opposto o dopo un numero fisso di candele.
* **Edge:** Popolare nelle criptovalute per catturare i fondi locali.
### Trasformazione di Ehlers Fisher (fisher_trans)
La strategia di John Ehlers che utilizza concetti di elaborazione del segnale digitale.
* **Tipo:** Inversione/Ciclico.
* **Logica:** Trasforma il movimento dei prezzi in una distribuzione (quasi) normale, rendendo i punti di svolta netti e chiari rimuovendo il rumore.
* **Entrata:** La linea Fisher attraversa sopra la sua linea di segnale (spesso quando si esce da una zona inferiore).
* **Esce:** La croce opposta.
* **Edge:** Un oscillatore “turbo”, che reagisce più velocemente e in modo più pulito rispetto a RSI o MACD.
### Divergenza RSI (rsi_div)
Trading sulle divergenze dell'RSI invece che sui livelli dell'RSI.
* **Tipo:** Inversione.
* **Logica:** Se il prezzo segna un minimo più basso, ma l'RSI fa un minimo più alto, si tratta di **divergenza rialzista**. Lo slancio al ribasso è esaurito anche se il prezzo continua a scendere.
* **Inserimento:** Dopo aver confermato la divergenza rialzista.
* **Uscita:** L'RSI sale sopra 70 o supera 50.
* **Edge:** Uno dei segnali TA più affidabili; permette di entrare vicino al fondo (catturare professionalmente i “coltelli che cadono”).
### Tendenza Heikin Ashi (ha_trend)
Utilizzo di candele Heikin Ashi modificate per filtrare il rumore.
* **Tipo:** Tendenza visiva.
* **Logica:** Le candele Heikin Ashi sono calcolate dalla media dei prezzi di apertura/chiusura. Levigano il grafico e nascondono piccoli pullback.
* **Inserimento:** Dopo una serie di candele rosse, appare una candela verde senza stoppino inferiore (forte impulso rialzista).
* **Esci:** Appare una candela che cambia colore (rossa), oppure una candela con lunghi stoppini su entrambi i lati (doji/incertezza).
* **Edge:** Psicologicamente confortevole; ti aiuta a superare trend lunghi senza reagire in modo eccessivo alle piccole candele rosse su un grafico normale.
### Canale di deviazione standard (std_channel)
Trading all'interno di un canale di regressione lineare.
* **Tipo:** Reversione alla media.
* **Logica:** Una linea mediana di regressione lineare più due linee parallele a 2 deviazioni standard. Circa il 95% delle mosse avviene all'interno.
* **Entrata:** Il prezzo tocca il canale inferiore (ipervenduto rispetto al trend).
* **Esci:** Ritorna alla linea di regressione (linea mediana).
* **Bordo:** A differenza delle bande di Bollinger, questo canale ha una pendenza, quindi intendi invertire **nella direzione** del trend.
### Inversione dei punti pivot (pivot_rev)
Trading da livelli di supporto matematico.
* **Tipo:** Rimbalzo.
* **Logica:** Utilizza il massimo/basso/chiusura di ieri per calcolare il pivot (P), i supporti (S1, S2) e le resistenze (R1, R2).
* **Entrata:** Il prezzo cade in S1 o S2, lo testa e chiude sopra (rimbalzo).
* **Esci:** Livello pivot successivo (ad esempio, acquista a S1, target P).
* **Edge:** Questi sono i livelli che si autoavverano a cui tengono conto molti trader; funziona bene su 1h/4h.
### Alligatore Williams (alligatore)
La classica strategia di tendenza di Bill Williams.
* **Tipo:** Segui tendenza.
* **Logica:** Tre medie mobili livellate spostate in avanti (Mascelle, Denti, Labbra). Imitano il comportamento di un alligatore.
* **Nota:** Quando le linee sono aggrovigliate: "l'alligatore dorme" (raggio d'azione, non scambiare). Quando si aprono nell'ordine giusto (Labbra > Denti > Mascelle) — tendenza iniziata — Lungo.
* **Uscita:** Le linee si aggrovigliano di nuovo o il prezzo chiude sotto i “Denti”.
* **Edge:** Aiuta a negoziare solo movimenti forti e a ignorare range rumorosi.
### Modello inghiottente (engulfing_candle)
Trading sul pattern “Engulfing” a candela pura.
* **Tipo:** Azione/Inversione del prezzo.
* **Logica:** Due candele. La seconda candela (rialzista) inghiotte completamente il corpo della candela precedente (ribassista), mostrando un netto cambiamento del sentiment dalla vendita all'acquisto.
* **Voce:** Un Engulfing rialzista appare dopo una serie di candele al ribasso.
* **Uscita:** Obiettivo di profitto fisso o modello opposto.
* **Bordo:** Nessun ritardo; il segnale è disponibile proprio alla chiusura della candela.
### McGinley Dinamica (mcginley)
Trading con una media mobile “ideale”.
* **Tipo:** Tendenza avanzata.
* **Logica:** John McGinley ha creato un indicatore che assomiglia ad un EMA ma accelera automaticamente nei mercati veloci e rallenta nei mercati lenti, evitando i colpi di frusta meglio delle MA standard.
* **Entrata:** Il prezzo supera la linea McGinley.
* **Esci:** Il prezzo supera la linea.
* **Edge:** Risolve l'eterna domanda: "Quale periodo MA dovrei usare?" McGinley si adatta automaticamente.
### Doppia spinta (dual_thrust)
Un famoso sistema di breakout, spesso utilizzato nei futures.
* **Tipo:** Breakout dell'intervallo.
* **Logica:** Prendi l'intervallo sulle ultime N candele (Alto - Chiusura o Alto - Basso) e moltiplicalo per K.
* **Inserimento:** Se il prezzo supera `Open + (Range * K)` — Lungo. Se si rompe sotto: corto.
* **Uscita:** Chiusura di fine giornata o stop-and-reverse.
* **Edge:** Cattura forti impulsi fuori dal consolidamento; popolare nel trading algoritmico.
### Oscillatore Chande Momentum (cmo_strat)
Un indicatore di momentum puro, diverso dall'RSI.
* **Tipo:** Slancio.
* **Logica:** Il CMO è la differenza tra la somma dei movimenti verso l'alto e verso il basso divisa per il movimento totale. Intervallo: da -100 a +100.
* **Entrata:** Il CMO supera +50 dal basso verso l'alto (forte impulso rialzista) o risale dall'ipervenduto (< -50).
* **Esci:** il CMO scende sotto +50.
* **Edge:** A differenza del livellamento RSI, CMO reagisce direttamente a ogni movimento, mostrando la velocità pura.
### Facilità di movimento (eom_trend)
Una strategia che combina prezzo e volume per trovare il “percorso di minor resistenza”.
* **Tipo:** Volume + Prezzo.
* **Logica:** L'EVM di Richard Arms mostra la facilità con cui i prezzi si muovono. Un forte aumento dei prezzi su piccoli volumi è “facile”; un volume enorme con poco movimento è “difficile” (un combattimento).
* **Voce:** EVM supera lo 0.
* **Esci:** EVM scende sotto 0.
* **Edge:** Aiuta a individuare trend "sani" ed evitare mercati in cui si svolge una dura battaglia (grandi volumi, nessun movimento).
### Conosci la cosa certa (KST) (kst_momentum)
“Conosci una cosa certa”: un indicatore di momentum composito.
* **Tipo:** Momento ciclico (a lungo termine).
* **Logica:** Una somma di quattro componenti ROC con livellamento diverso; effettivamente un “MACD per cicli”.
* **Inserimento:** KST attraversa sopra la sua linea di segnale.
* **Esce:** La croce opposta.
* **Edge:** Progettato per cogliere i principali cicli di mercato ignorando piccole correzioni. Funziona bene su 4h e 1d.
### Ciclo di tendenza di Schaff (stc_cycle)
Una variante MACD migliorata che si muove più velocemente e con maggiore precisione.
* **Tipo:** Ciclo/Momentum.
* **Logica:** Doug Schaff ha combinato MACD e stocastico in un oscillatore da 0 a 100 che, a differenza dello stocastico, è meno nervoso nel taglio e mantiene meglio le posizioni.
* **Entrata:** STC sale sopra 25 (esce ipervenduto).
* **Uscita:** STC scende sotto 75 (esce in ipercomprato).
* **Nota:** Trova le tendenze prima del MACD e fornisce meno falsi segnali negli intervalli.
### Filtro indice di discontinuità + EMA (chop_ema)
Una strategia con un filtro “qualità del mercato”.
* **Tipo:** Tendenza con filtro.
* **Logica:** L'indice Choppiness (CHOP) indica se il mercato è in trend o in range. CHOP > 61,8 significa range (non scambiare). CHOP < 38,2 significa tendenza forte.
* **Entrata:** Il prezzo supera un EMA (ad es. 50) **e** CHOP < 50 (conferma del trend).
* **Uscita:** Il prezzo torna sotto l'EMA.
* **Nota:** L'obiettivo principale è evitare scambi in mercati morti e risparmiare commissioni e nervi.
### Media mobile adattiva frattale (frama_trend)
Utilizzare la geometria frattale per adattarsi al mercato.
* **Tipo:** Tendenza adattiva.
* **Logica:** FRAMA utilizza la “dimensione frattale”. Nel caos (intervallo), FRAMA rallenta e si appiattisce. Nel movimento direzionale, accelera.
* **Inserimento:** Il prezzo supera FRAMA.
* **Uscita:** Il prezzo supera FRAMA.
* **Nota:** A differenza di una EMA regolare, FRAMA può rimanere quasi piatto durante le correzioni, prevenendo falsi stop-out.
### Andamento dei prezzi in volume (vpt_cross)
Un indicatore simile a OBV più avanzato.
* **Tipo:** Volume.
* **Logica:** Il VPT tiene conto non solo della direzione (come l'OBV), ma anche della variazione di prezzo *percentuale*. Un grande volume con una piccola variazione di prezzo ha un impatto limitato; un grande volume con una grande mossa ha un grande impatto.
* **Entrata:** Il VPT supera la sua media mobile (MA).
* **Uscita:** Il VPT scende al di sotto della sua MA.
* **Nota:** Molto sensibile all'accumulo di “denaro intelligente”.
### Laguerre RSI (laguerre_rsi)
“RSI dal futuro” – utilizzando il filtro Laguerre.
* **Tipo:** Oscillatore di trend.
* **Logica:** John Ehlers ha applicato il filtro time-warp per creare un RSI con ritardo minimo con solo 4 componenti di livellamento.
* **Entrata:** Laguerre RSI supera lo 0,2 (20%).
* **Uscita:** Cross sotto 0,8 (80%).
* **Nota:** Reagisce molto più velocemente del classico RSI, catturando più movimenti.
### Pinbar (Martello/Stella cadente) (pinbar_reversal)
Azione pura dei prezzi: candele di inversione.
* **Tipo:** Pattern a candela (inversione).
* **Logica:** Una “barra a spillo” (martello o stella cadente) ha uno stoppino molto lungo e un corpo piccolo. Lo stoppino mostra che il prezzo si è mosso in una direzione ed è stato nettamente rifiutato.
* **Voce:** Una barra pin rialzista (stoppino lungo inferiore) appare al minimo locale.
* **Uscita:** Rischio/rendimento fisso (ad es. 1:3) o uscita su un segnale opposto.
* **Nota:** Funziona meglio ai livelli di supporto; spesso segna la capitolazione del venditore.
### Oscillatore del prezzo con trend (dpo_cycle)
Negoziare cicli a breve termine senza la distorsione della tendenza globale.
* **Tipologia:** Ciclico a breve termine.
* **Logica:** Il DPO rimuove il trend a lungo termine, lasciando solo oscillazioni a breve termine (“microonde”).
* **Voce:** DPO incrocia sopra 0.
* **Esci:** il DPO scende sotto lo 0.
* **Nota:** Aiuta a negoziare oscillazioni intraday anche quando il mercato globale è in un forte regime rialzista/orso.
### Breakout del range di apertura (orb_strat)
Classica strategia day-trader adattata ad un mercato 24 ore su 24, 7 giorni su 7.
* **Tipo:** Breakout basato sul tempo.
* **Logica:** La prima ora (o 4 ore) di un nuovo giorno/settimana dà il tono; il mercato “sceglie” la direzione.
* **Voce:** Definisci il massimo e il minimo della prima candela giornaliera (00:00 UTC). Se il prezzo rompe il massimo – Long.
* **Uscita:** Fine della giornata (23:59) o stop loss fisso al punto medio dell'intervallo.
* **Edge:** Utilizza l'impulso della sessione di apertura. Molto semplice, ma statisticamente efficace sugli asset ad alta volatilità.
### Indice di facilitazione del mercato (bw_mfi)
Strategia di Bill Williams (non Money Flow Index). Misura l’efficienza del movimento dei prezzi rispetto al volume.
* **Tipo:** Volume + Prezzo Efficienza.
* **Logica:** Confronta l'intervallo con il volume.
    * *Barra verde:* Volume su + movimento forte = trend reale.
    * *Squat Bar:* Volume su + prezzo piatto = lotta rialzista/orso (possibile inversione).
* **Inserimento:** 2–3 “barre verdi” consecutive.
* **Esci:** Appare una barra "Squat": la mossa sta finendo il carburante.
* **Edge:** Aiuta a distinguere un pump debole (volume basso) da un movimento reale.
### Linea psicologica (psy_line)
Indicatore del sentimento della folla.
* **Tipologia:** Sentiment / Controtendenza.
* **Logica:** Rapporto tra le candele up e il totale delle candele in un periodo (ad esempio, 12). Se PSY > 75%, 9 candele su 12 erano verdi: euforia (ipercomprato).
* **Inserimento:** PSY scende sotto il 25% (panico) e sale.
* **Uscita:** PSY sale sopra il 75%.
* **Edge:** Un termometro di mercato che ignora i prezzi assoluti e si concentra sulle “vittorie” rialzista/orso.
### Tasca dorata di Fibonacci (fib_golden)
Trading automatizzato dei pullback di Fibonacci.
* **Tipo:** Acquisto al ribasso.
* **Logica:** Trova l'ultimo swing significativo Alto/Basso e disegna il ritracciamento di Fibonacci. La zona tra 0,618 e 0,65 è la “tasca d'oro”, dove spesso si verificano rimbalzi.
* **Entrata:** Il prezzo tocca il livello di ritracciamento di 0,618.
* **Uscita:** Nuovo massimo (livello 0) o stop sotto 0,786.
* **Edge:** Una delle strategie discrezionali più popolari; il bot automatizza la ricerca di questi livelli.
### Tre soldati bianchi / Tre corvi neri (candle_patterns)
Trading di forti formazioni di candele che spesso continuano la tendenza.
* **Tipo:** Riconoscimento di pattern.
* **Logica:** “Three White Soldiers” sono tre candele verdi consecutive, ciascuna con chiusura più alta della precedente, preferibilmente con stoppini corti. Indica la posizione dominante dell'acquirente.
* **Inserimento:** Chiusura della 3a candela.
* **Uscita:** Appare la prima candela ribassista, o trailing stop ai minimi della candela.
* **Edge:** Se tre candele potenti vengono stampate di seguito, la probabilità di continuazione è spesso alta.
### Indice di camminata casuale (rwi_trend)
Un test statistico: “È una tendenza o una casualità?”
* **Tipo:** Filtro statistico.
* **Logica:** RWI confronta il movimento dei prezzi con quello che ti aspetteresti da una passeggiata casuale (lanci di monete).
* **Voce:** RWI Alto > 1 (il movimento verso l'alto è statisticamente significativo).
* **Uscita:** RWI High scende sotto 1.
* **Edge:** Ti evita di fare trading su mercati rumorosi e caotici.
### Strategia sull'indice dell'ulcera (ulcer_strat)
Una strategia che minimizza lo stress (e i drawdown).
* **Tipologia:** Compensato per il rischio/Gestione del rischio.
* **Logica:** L'indice dell'ulcera misura la profondità e la durata dei prelievi. A differenza della deviazione standard, tiene conto solo dei *movimenti al ribasso* (cattiva volatilità).
* **Entrata:** Il prezzo è in aumento mentre l'indice dell'ulcera è estremamente basso (trend rialzista regolare e calmo).
* **Uscita:** Un forte picco nell'indice dell'ulcera (inizia la turbolenza).
* **Edge:** Ottimo per una crescita conservativa del conto; esce presto in caso di instabilità senza attendere un incidente.
### Corrispondenza pattern k-Vicini più vicini (kNN) (knn_ml)
Apprendimento automatico semplice senza reti neurali pesanti.
* **Tipo:** Corrispondenza modello.
* **Logica:** L'algoritmo memorizza la forma delle ultime N candele (ad esempio 5), quindi ricerca nel grafico storico le forme più simili.
* **Inserimento:** Se nel 70% delle corrispondenze storiche trovate il prezzo è salito in seguito, acquista.
* **Uscita:** Periodo di detenzione fisso (ad esempio 3 candele) o quando la previsione cambia.
* **Edge:** Il bot non utilizza indicatori; “guarda” alla storia: “Questo è successo prima – ecco cosa è successo dopo”.
### Teoria della scatola di Darvas (darvas_box)
La leggendaria strategia di Nicholas Darvas che gli fece guadagnare 2 milioni di dollari negli anni ’50.
* **Tipo:** Breakout/Seguimento del trend.
* **Logica:** Quando il prezzo varia, costruisce una “scatola” con un soffitto (Alto) e un pavimento (Basso) chiari.
* **Inserimento:** Il prezzo supera il limite massimo della scatola. È un segnale che la risorsa si è spostata su un "nuovo piano". Fissare immediatamente una sosta sotto il nuovo pavimento del box.
* **Uscita:** Il prezzo scende al di sotto del box floor.
* **Edge:** Eccellente per andamenti parabolici ignorando piccoli spostamenti all'interno dei box.
### Indice Elder-Ray (elder_ray)
La strategia del “mercato ai raggi X” di Alexander Elder.
* **Tipo:** Segui tendenza + Momentum.
* **Logica:** Utilizza EMA(13) come valore consenso e due componenti: `Bull Power` (Alto - EMA) e `Bear Power` (Basso - EMA).
* **Entrata:** Trend rialzista (inclinazione EMA verso l'alto) **e** `Bear Power` è inferiore allo zero ma in aumento (indebolimento degli orsi). Acquista il ritiro.
* **Esci:** `Bull Power` raggiunge un massimo storico e inizia a scendere.
* **Bordo:** Separa la forza interna del toro e dell'orso.
### Centro di gravità (cog_ehlers)
Oscillatore a ritardo zero di John Ehlers.
* **Tipo:** Inversione.
* **Logica:** Ehlers usò la formula fisica del centro di gravità per trovare i punti di svolta. L'indicatore appare come un'onda sinusoidale liscia e può "prevedere" le inversioni con un ritardo minimo.
* **Inserimento:** il COG attraversa sopra la sua linea di segnale (Lag 1).
* **Esce:** La croce opposta.
* **Edge:** Uno degli strumenti più precisi per i mercati laterali. Nelle tendenze può uscire presto, quindi si consiglia un filtro tendenza.
### Entropia di Shannon (entropy_chaos)
Usare la teoria dell'informazione per misurare il caos del mercato.
* **Tipologia:** Filtro regime di mercato.
* **Logica:** L'entropia di Shannon misura l'incertezza.
    * Alta entropia = caos; il prezzo è imprevedibile (portata/rumore).
    * Bassa entropia = ordine; forte tendenza direzionale.
* **Entrata:** L'entropia scende al di sotto di una soglia (il mercato è diventato ordinato) + il prezzo è al di sopra della media mobile.
* **Esci:** Picchi di entropia (inizia il caos).
* **Edge:** Un modo matematicamente fondato per dire: "Non faccio trading perché il mercato è ubriaco in questo momento".
### Indice di vigore relativo (rvi_trend)
Energia del movimento dei prezzi.
* **Tipo:** Slancio.
* **Logica:** Basata sull'idea che nei mercati in rialzo le chiusure tendono ad essere al di sopra delle aperture. L’RVI attenua questi valori e assomiglia allo stocastico, ma si basa sull’”energia” delle candele piuttosto che sull’intervallo.
* **Inserimento:** RVI attraversa sopra la sua linea di segnale.
* **Esci:** Croce in basso.
* **Edge:** Conferma la sostenibilità del trend. Se il prezzo sale ma l’RVI scende (divergenza), il trend potrebbe essere debole.
### VSTOP (arresto della volatilità) (vstop_trend)
Strategia di trailing basata sulla volatilità.
* **Tipo:** Finale (Tendenza).
* **Logica:** Calcola una linea di stop in `N * ATR` lontano dai prezzi estremi. La linea si muove solo nella direzione del trend, mai indietro.
* **Entrata:** Chiusura sopra la linea VSTOP (si ribalta sotto il prezzo e diventa supporto).
* **Uscita:** Il prezzo tocca o chiude sotto VSTOP.
* **Edge:** Un approccio puramente di gestione dell'uscita che ti mantiene in trend finché la volatilità non interrompe la protezione. Simile a SuperTrend, ma con una matematica dei massimi diversa.
### Cosa scegliere dopo?
Per la fase successiva di implementazione (per completare il tuo portafoglio), ti consiglio:
1. **k-Nearest Neighbours (knn_ml)**: aggiunge una semplice **logica AI** al tuo bot senza librerie pesanti. Un approccio molto moderno.
2. **Darvas Box**: un **classico di successo** che funziona bene con le monete "hype" durante forti movimenti al rialzo.
3. **Centro di gravità**: un'arma potente per i **mercati range**, dove le strategie di tendenza tendono a perdere denaro.
### Indicatore Squeeze Momentum (lazybear_squeeze)
La leggendaria strategia TradingView (di LazyBear) basata sulle idee di John Carter.
* **Tipo:** Breakout di volatilità + Momentum.
* **Logica:** Combina le bande di Bollinger e i canali di Keltner.
    * **Fase “Squeeze”:** Le Bande di Bollinger sono all'interno del Canale Keltner (punti neri). Il mercato immagazzina energia.
    * **Fase di “rilascio”:** Le bande si spostano all'esterno del canale.
* **Inserimento:** lo squeeze termina (uscita dall'intervallo) **e** l'istogramma del momentum è sopra lo zero e in aumento.
* **Esci:** L'istogramma del momento cambia colore (inizia a diminuire) o scende sotto lo zero.
* **Edge:** Un sistema visivamente semplice che cattura i movimenti post-compressione più forti.
### Strategia con esponente di Hurst (hurst_exponent)
Una strategia matematica che determina la “memoria” del mercato.
* **Tipo:** Adattivo (commutatore di regime).
* **Logica:** L'esponente di Hurst (H) identifica la natura del mercato:
    * H > 0,5: Tendenza (persistente).
    * H < 0,5: range (ritorno alla media).
* **Inserimento:**
    * Se H > 0,6: utilizzare la logica di breakout (ad esempio, rompere il massimo degli ultimi N giorni).
    * Se H < 0,4: utilizzare la logica di controtendenza (acquistare ai minimi, vendere ai massimi).
* **Uscita:** Il regime di Hurst cambia.
* **Edge:** Una “strategia di strategie”: non indovina la direzione, determina *come* fare trading in questo momento.
### Tendenza Renko sintetica (renko_synthetic)
Usare i “mattoni” Renko invece delle candele per rimuovere il rumore del tempo.
* **Tipo:** Azione del prezzo (indipendente dal tempo).
* **Logica:** Costruisci virtualmente mattoncini di dimensioni fisse (ad esempio, 1% del prezzo). Un nuovo mattone appare solo se il prezzo percorre quella distanza; le piccole fluttuazioni vengono ignorate.
* **Nota:** Due mattoni verdi in fila dopo una serie di mattoni rossi (inversione di tendenza verso l'alto).
* **Esci:** Appare un mattone rosso (inversione verso il basso).
* **Edge:** Consente al bot di mantenere i trend per settimane, ignorando il taglio laterale che sembra spaventoso sulle candele ma è una linea piatta su Renko.
### Attivatore Gann Hi-Lo (gann_hilo)
Strategia trend-following semplice ma efficace ispirata a Gann.
* **Tipo:** Trend/Trailing Stop.
* **Logica:** Una semplice SMA(3) costruita sui massimi nei trend al ribasso e sui minimi nei trend rialzisti.
* **Entrata:** Chiudi sopra la linea dell'Attivatore Gann (si ribalta sotto il prezzo).
* **Esci:** Chiude sotto la linea.
* **Edge:** Un trailing stop meccanico rigoroso. Ottimo per altcoin con pompe affilate.
### Rifiuto POC del profilo volume (vpvr_poc)
Trading da livelli di volume orizzontali.
* **Tipo:** Livelli di supporto/resistenza.
* **Logica:** Calcola il profilo del volume negli ultimi N giorni. Trova il POC (punto di controllo) – il prezzo con il volume più scambiato – il “prezzo equo”.
* **Inserimento:**
    1. Il prezzo si avvicina al POC dall'alto.
    2. Il prezzo tocca il POC e rimbalza (la candela chiude in rialzo).
    3. È un test di supporto: vai lungo.
* **Uscita:** Profitto a percentuale fissa o raggiungimento del successivo Nodo a Basso Volume.
* **Vantaggio:** Fai trading al fianco di grandi giocatori che difendono le posizioni accumulate su POC.
### Rimbalzo DCA (media del costo in dollari) (dca_martingale)
Strategia di gestione del capitale popolare nelle piattaforme bot (3Commas, ecc.).
* **Tipo:** Media/Griglia.
* **Logica:** Utilizza i rebuy invece dello stop loss.
* **Entrata:** RSI < 30 (prima entrata con il 20% del capitale).
* **Gestione:** Se il prezzo scende del 2%, acquista un altro 30%. Se scende di un altro 3%, acquista il 50% (martingala/media).
* **Uscita:** Quando viene raggiunto il prezzo medio di entrata + 1% di profitto (sul rimbalzo).
* **Edge:** Può chiudere le operazioni in profitto anche in un mercato al ribasso (tramite rimbalzi), ma il rischio di liquidazione è elevato se il prezzo scende senza pullback (è necessario uno stop loss per l'intera "borsa").
### Trading su triplo schermo (triple_screen)
Il sistema classico di Alexander Elder.
* **Tipo:** Multi-timeframe (Trend + Correzione).
* **Logica:** Utilizza tre "schermate" (o moltiplicatori di intervalli temporali su un grafico).
    1. **Marea (a lungo termine):** Il MACD su un intervallo di tempo x5 mostra il trend rialzista.
    2. **Onda (medio termine):** Lo StochRSI nel periodo di tempo attuale è ipercomprato (un pullback al ribasso rispetto al trend).
    3. **Ripple (Entrata):** Breakout del massimo della candela precedente (quando termina il pullback).
* **Inserimento:** Quando la "marea" è alta e l'"onda" smette di cadere.
* **Esci:** Basato su segnali di timeframe inferiore.
* **Edge:** Uno dei filtri commerciali più affidabili: fai trading con la tendenza a lungo termine, ma acquista in caso di cali temporanei.
## Strategie combinate
Ottima idea. Le **strategie combinate** rappresentano il livello di evoluzione successivo per un bot di trading. I singoli indicatori spesso producono falsi segnali: le strategie che seguono il trend si perdono nei range e gli oscillatori (RSI) escono troppo presto dai trend.
La combinazione dei segnali ti consente di filtrare le voci utilizzando un semplice principio: **"Filtro (tendenza globale) + Trigger (tempi di ingresso)"**.
### Metodo a triplo schermo (triple_screen_custom)
Un adattamento in stile Elder che combina Trend, Wave e Momentum.
* **Componenti:** EMA (200) + RSI (14) + MACD.
* **Logica:**
    1. **Filtro:** Il prezzo deve essere **sopra** EMA 200 (trend rialzista globale).
    2. **Pullback:** l'RSI deve scendere al di sotto di 50 (correzione locale, “sconto”).
    3. **Trigger:** l'istogramma MACD inizia a salire (inversione di slancio verso l'alto).
* **Perché è bello:** Compri con il trend, non al top, e solo dopo che il pullback è confermato essere finito.
### Bollinger Breakout + MFI (bb_mfi_breakout)
Breakout della volatilità confermato dal flusso di denaro.
* **Componenti:** Bande di Bollinger + Indice del flusso di denaro.
* **Logica:** I breakout BB possono simulare; il volume aiuta.
    1. **Trigger:** Chiusura sopra la banda di Bollinger superiore.
    2. **Filtro:** IFM > 60 in aumento (afflusso di denaro). Se il prezzo rompe il BB ma l’MFI crolla, è probabile che si tratti di un falso.
* **Uscita:** Il prezzo ritorna all'interno del canale Bollinger.
* **Perché è bello:** Filtra le pompe "vuote" senza un volume reale dell'acquirente.
### Ichimoku Nuvola + MACD (ichimoku_macd)
Classico giapponese con conferme occidentali.
* **Componenti:** Ichimoku Kinko Hyo + MACD.
* **Logica:**
    1. **Filtro (breakout Kumo):** Chiudi **sopra** la nuvola di Ichimoku.
    2. **Trigger:** le linee MACD si incrociano (croce dorata).
* **Esci:** Il prezzo entra nuovamente nel cloud.
* **Perché è bello:** I breakout nuvolosi spesso significano un cambiamento di tendenza a lungo termine; Il MACD aiuta ad entrare presto.
### ADX + SAR parabolico (adx_psar)
A caccia di trend forti: “Non commerciare se non c’è forza”.
* **Componenti:** ADX + SAR parabolico.
* **Logica:** Il SAR parabolico si attiva costantemente (anche nei range). ADX risolve questo problema.
    1. **Filtro:** ADX > 25 (fase attiva; nessun intervallo).
    2. **Trigger:** i punti SAR si ribaltano **sotto** il prezzo.
* **Esci:** I punti SAR si spostano sopra il prezzo.
* **Perché è bello:** Ignori i mercati deboli e ti impegni solo quando il "razzo" inizia.
### Pullback SMA 50/200 (golden_cross_pullback)
Trading “Croce d’Oro” più intelligente.
* **Componenti:** SMA 50 + SMA 200.
* **Logica:** L'acquisto del cross è spesso seguito da un pullback che ti impedisce di uscire. Invece:
    1. **Condizione:** SMA 50 è superiore a SMA 200 (l'incrocio è già avvenuto).
    2. **Trigger:** Il prezzo tocca la SMA 50 dall'alto e si chiude di nuovo sopra (rimbalzo del supporto).
* **Uscita:** Chiusura sotto SMA 200.
* **Perché è interessante:** Ingresso a basso rischio con stop più ristretto: acquista la correzione, non l'hype.
### Regressione lineare + punteggio Z (stats_arbitrage)
Una combinazione matematica (inversione della media con gli steroidi).
* **Componenti:** Pendenza di regressione lineare + punteggio Z.
* **Logica:**
    1. **Filtro:** Pendenza di regressione > 0 (aspettativa positiva).
    2. **Trigger:** Z-Score < -2 (deviazione al ribasso di 2-sigma dalla linea di regressione).
* **Esci:** Il punteggio Z ritorna a 0.
* **Perché è interessante:** Un approccio scientifico: acquistare un asset che cresce *a livello globale* ma che è *localmente* ingiustamente economico.
### Metodo a triplo schermo (triple_screen_ema)
Un adattamento algoritmico del metodo “Triplo schermo” di Elder.
* **Logica:** Utilizza tre tipi di indicatori:
    1. **Marea (a lungo termine):** Il prezzo deve essere **sopra** EMA 200 (o EMA 100). Tendenza globale al rialzo.
    2. **Onda (Pullback):** L'RSI (14) deve scendere al di sotto di 50 (o 45). Correzione temporanea.
    3. **Ripple (Inserimento):** L'istogramma MACD inizia a salire (o le linee MACD si incrociano). Il ritiro termina; il movimento verso l'alto riprende.
* **Uscita:** RSI > 70 o MACD attraversa al ribasso.
* **Perché è bello:** Conservatore e robusto. Filtra le operazioni in controtendenza più pericolose.
### SMA Croce d'Oro Pullback (sma_pullback)
Trading crossover MA più intelligente: non sul cross, ma sul nuovo test.
* **Logica:**
    1. **Condizione:** SMA 50 è superiore a SMA 200 (la Croce d'Oro è già avvenuta).
    2. **Trigger:** Il prezzo tocca la SMA 50 dall'alto e rimbalza (prossima candela verde).
* **Uscita:** Chiusura sotto SMA 200 (rottura del trend) o take profit fisso.
* **Perché è bello:** Acquistare proprio all'incrocio spesso perde perché il mercato è già surriscaldato. Il nuovo test offre un rischio più ristretto e probabilità migliori.
### SuperTrend + StochRSI (super_stoch)
Combina un indicatore di tendenza superiore con un oscillatore veloce per voci "da cecchino".
* **Logica:**
    1. **Filtro (Trend):** il SuperTrend (basato su ATR) deve essere verde (prezzo sopra la linea). Niente pantaloncini.
    2. **Trigger (Entrata):** Lo StochRSI scende in ipervenduto (< 20) e incrocia verso l'alto (K incrocia D).
* **Uscita:** Lo StochRSI entra in ipercomprato (> 80) o il SuperTrend diventa rosso.
* **Perché è interessante:** Opera con il trend ma entra nei pullback locali, migliorando il rapporto rischio/rendimento.
### Breakout di Bollinger + MFI (bb_mfi)
Breakout della volatilità con conferma del volume (“smart money”).
* **Logica:**
    1. **Trigger:** Chiusura sopra la **Superiore** Banda di Bollinger (espansione della volatilità).
    2. **Filtro (Volume):** MFI > 60 in aumento. Conferma che il breakout è supportato da afflussi reali.
* **Uscita:** Richiudersi all'interno del canale (sotto la banda superiore) altrimenti l'MFI cade.
* **Perché è interessante:** Aiuta a distinguere una vera pompa da una trappola del market maker (falsa).
### Regressione lineare + punteggio Z (linreg_zscore)
Reversione media 2.0 (statistiche pure).
* **Logica:**
    1. **Filtro (direzione):** La pendenza di regressione (oltre 50–100 candele) è positiva.
    2. **Trigger (Deviazione):** Il punteggio Z scende sotto -2 (statisticamente basso rispetto al suo stesso trend).
* **Esci:** Il punteggio Z ritorna a 0 (linea mediana).
* **Perché è bello:** Non indovinare le candele: pura statistica. Acquista un asset in crescita a livello globale che è scontato a livello locale.
### Il sistema di trend "Fortezza" (trend_momentum_volatility_volume)
Il sistema “Fortezza”: quattro livelli di protezione dai traffici stupidi.
* **Componenti:** EMA 200 + MACD + Bande di Bollinger + OBV.
* **Logica:**
    1. **Filtro globale:** Prezzo > EMA 200 (trada solo sul trend rialzista).
    2. **Volatilità:** Il prezzo tocca o rompe la linea mediana del BB (ritiro al prezzo equo).
    3. **Volume:** l'OBV è superiore alla sua MA (il denaro non esce durante il pullback).
    4. **Trigger:** l'istogramma MACD cambia da rosso a verde (ritorna lo slancio).
* **Esci:** Tocca il BB superiore o le croci MACD verso il basso.
* **Perché è bello:** acquisti solo pullback confermati dal volume all'interno di un trend rialzista rafforzato.
### Il "cuoio capelluto perfetto" (heikin_ashi_ema_stochrsi_atr)
Scalping con filtro del rumore.
* **Componenti:** Heikin Ashi (virtuale) + EMA 50 + EMA 100 + StochRSI + ATR.
* **Logica:**
    1. **Tunnel:** EMA 50 è superiore a EMA 100 e la distanza è in aumento (forte tendenza).
    2. **Schema:** La candela Heikin Ashi passa dal rosso al verde.
    3. **Trigger:** lo StochRSI supera i 40.
    4. **Stop loss:** Fisso a 2xATR dall'ingresso.
* **Esci:** Heikin Ashi diventa rosso.
* **Perché è bello:** Heikin Ashi rimuove il rumore; il doppio EMA previene lo scalping contro un treno.
### Divergence Hunter Pro (rsi_cci_mfi_ema)
Inversioni di caccia con tripla conferma (convergenza dell'oscillatore).
* **Componenti:** EMA 200 + RSI (14) + CCI (20) + MFI (14).
* **Logica:**
    1. **Contesto:** Prezzo superiore all'EMA 200 (alla ricerca di un fondo di correzione locale).
    2. **Sincronizzazione:**
        *RSI < 30 (prezzo ipervenduto).
        * CCI < -100 (deviazione anomala).
        *MFI < 20 (volume ipervenduto/panico).
    3. **Inserimento:** Tutti e tre gli indicatori vengono visualizzati insieme.
* **Uscita:** Uno qualsiasi dei tre raggiunge l'ipercomprato.
* **Perché è interessante:** La possibilità che tre diversi oscillatori matematici (prezzo, deviazione, volume) falliscano tutti contemporaneamente è bassa.
### Compressione avanzata (bollinger_keltner_momentum_adx)
Una variante avanzata di TTM Squeeze per mosse esplosive.
* **Componenti:** Bande di Bollinger + Canali Keltner + Momentum + ADX.
* **Logica:**
    1. **Squeeze:** Bande di Bollinger completamente all'interno del Canale di Keltner: volatilità a un minimo critico.
    2. **Accumulazione:** ADX < 20 (il mercato è “dormiente”).
    3. **Trigger:** Le Bande di Bollinger escono dal Canale Keltner + ADX inizia a salire bruscamente.
    4. **Direzione:** Momento > 0.
* **Esci:** Lo slancio inizia a diminuire.
* **Perché è bello:** Si fanno grandi soldi quando il mercato passa dal sonno all'esplosione; questa combinazione prende di mira quella transizione.
### Ichimoku "Tutto esaurito" (tenkan_kijun_cloud_chikou_rsi)
Utilizzando l'intero set di segnali Ichimoku più un filtro ipercomprato.
* **Componenti:** Ichimoku Cloud (tutte le linee) + RSI.
* **Logica:**
    1. **Breakout:** Chiusura sopra la nuvola (breakout di Kumo).
    2. **Cross:** Tenkan incrocia Kijun dal basso verso l'alto (TK Cross).
    3. **Conferma ritardata:** Chikou Span è al di sopra del prezzo 26 periodi fa (conferma del trend).
    4. **Filtro:** RSI < 70 (mercato non surriscaldato).
* **Uscita:** Tenkan passa sotto Kijun o il prezzo entra nella nuvola.
* **Perché è bello:** Uno dei sistemi giapponesi più antichi e rispettati. L'utilizzo di tutte le parti rende le voci più rare ma più forti.
### Strategia istituzionale VWAP (vwap_ema_volume_profile_rsi)
Fare trading “come una balena” utilizzando il prezzo ponderato in base al volume.
* **Componenti:** VWAP + EMA 50 + Profilo a volume fisso (POC) + RSI.
* **Logica:**
    1. **Trend:** Prezzo > EMA 50.
    2. **Valore:** Il prezzo si ritira verso il VWAP (ritorno al prezzo “equo” del giorno).
    3. **Livello:** Il prezzo è in una zona ad alto volume (protezione POC del profilo volume).
    4. **Trigger:** l'RSI rimbalza da 40–50.
* **Uscita:** Il prezzo si allontana troppo dal VWAP (movimento della deviazione standard).
* **Perché è interessante:** VWAP è utilizzato da algoritmi istituzionali. Fare trading con VWAP significa fare trading con loro, non contro di loro.
### Il "cecchino delle tendenze" (parabolic_sar_adx_ema_macd)
Catturare tendenze incontrollate (percorsi parabolici).
* **Componenti:** SAR parabolico + ADX + EMA 100 + MACD.
* **Logica:**
    1. **Globale:** Prezzo > EMA 100.
    2. **Forza:** ADX > 30 e in aumento (trend molto forte).
    3. **Trigger:** i punti SAR sono inferiori al prezzo.
    4. **Filtro:** MACD > 0 e istogramma in aumento.
* **Regola speciale:** Mentre l'ADX è in aumento, ignora i piccoli segnali di vendita.
* **Uscita:** L'ADX inizia a scendere (il trend si indebolisce) OPPURE il SAR si ribalta.
* **Perché è bello:** Sfrutta al massimo i rally parabolici (ad esempio, BTC 20k→30k) senza uscire alla prima candela rossa.
### Il sistema "Sentiero delle balene" (volume_trend_value)
Seguendo il grande giocatore (“balena”).
* **Componenti:** VWAP + Chaikin Money Flow (CMF) + EMA 200 + Punti Pivot.
* **Logica:**
    1. **Tendenza globale:** Prezzo > EMA 200.
    2. **Prezzo equo:** Il prezzo è superiore (o ripetuto da sopra) VWAP: gli acquirenti controllano l'asta intraday.
    3. **Flusso di denaro:** CMF > 0 e in aumento (accumulazione).
    4. **Trigger:** Breakout della resistenza Pivot più vicina (R1/R2).
* **Uscita:** Il CMF scende sotto lo zero o il prezzo chiude sotto il VWAP.
* **Perché è bello:** Non si scambiano "modelli"; fai trading di flussi di denaro istituzionali reali.
### L'inversione della "banda elastica" (mean_reversion_trend_filter)
Catturare profondi pullback in un forte trend rialzista (la “fionda”).
* **Componenti:** Canali Keltner + RSI (2) + SMA 100 + Modello Engulfing.
* **Logica:**
    1. **Filtro:** Pendenza della SMA 100 rigorosamente in rialzo (forte tendenza al rialzo).
    2. **Allungamento:** Il prezzo scende al di sotto della linea Keltner inferiore (deviazione estrema).
    3. **Ipervenduto:** l'RSI(2) scende sotto 5.
    4. **Trigger:** La candela si chiude all'interno del canale + si forma un Engulfing rialzista.
* **Uscita:** Il prezzo tocca la linea Keltner media o superiore.
* **Perché è fantastico:** Tasso di vincita molto alto. Compri paura (dump) in un contesto di avidità (trend rialzista).
### Lo "tsunami Guppy" (gmma_adx)
Una strategia di tendenza visiva che utilizza medie mobili multiple (GMMA).
* **Componenti:** GMMA (12 MA: 6 veloci, 6 lenti) + ADX.
* **Logica:**
    1. **Compressione:** i gruppi MA veloci e lenti convergono (la volatilità diminuisce; il mercato si comprime).
    2. **Tsunami (espansione):** le MA veloci si separano bruscamente verso l'alto dalle MA lente.
    3. **Conferma:** Anche le MA lente iniziano ad espandersi (il trend diventa sostenibile).
    4. **Filtro:** ADX > 20 e in aumento.
* **Esci:** Le MA veloci iniziano ad attraversare le MA lente (compressione).
* **Perché è interessante:** Cattura fasi di trend esplosive e ignora piccoli pullback mentre la "scuola" MA punta verso l'alto.
### Il canale "Regressione quantistica" (linear_reg_pearson_r_atr)
Channel trading basato sulla matematica.
* **Componenti:** Canale di regressione lineare (100) + coefficiente di correlazione di Pearson (r) + Trailing Stop ATR.
* **Logica:**
    1. **Qualità del trend:** Pearson r > 0,7 (il prezzo si comporta come una linea ascendente: crescita stabile senza caos).
    2. **Acquista a buon mercato:** Il prezzo tocca il limite inferiore del canale di regressione (2 deviazioni standard).
    3. **Trigger:** Il prezzo rimbalza dal limite inferiore.
* **Uscita:** Il prezzo tocca il limite superiore o si attiva lo stop ATR.
* **Perché è bello:** Scambia solo trend “belli” e stabili e filtra i grafici disordinati con la matematica.
### Il "Caos d'Oro" (ichimoku_bill_williams_fractals_ao)
Una combinazione di saggezza orientale e teoria del caos.
* **Componenti:** Ichimoku Cloud + Frattali + Awesome Oscillator (AO).
* **Logica:**
    1. **Zona di sicurezza:** Prezzo > Ichimoku Cloud.
    2. **Energia:** AO è verde e superiore allo zero.
    3. **Trigger:** Il prezzo rompe l'ultimo frattale verso l'alto (massimo locale).
* **Esci:** Chiudi sotto Ichimoku Tenkan o AO diventa rosso (in sequenza).
* **Perché è bello:** I frattali forniscono un prezzo di entrata preciso (ordine in sospeso) e Ichimoku ti assicura di non contrastare la tendenza globale.
### Il sistema "Velocity" (hull_ma_laguerre_rsi_volatility_stop)
Un sistema di scalping ultraveloce per coppie volatili (ETH, SOL).
* **Componenti:** Media mobile dello scafo (HMA) + Laguerre RSI + Volatility Stop (VSTOP).
* **Logica:**
    1. **Velocità:** HMA diventa verde (reazione istantanea al rialzo).
    2. **Momentum:** Laguerre RSI supera 0,2 (uscita dal fondo).
    3. **Protezione:** Il prezzo è superiore a VSTOP.
* **Esci:** HMA diventa rosso o VSTOP si interrompe.
* **Perché è bello:** Gli indicatori classici sono in ritardo. Questa combinazione utilizza strumenti con ritardo minimo per essere il primo a muoversi.
### La "Confluenza di Fibonacci" (auto_fibs_ema_50_stochastic)
Trading pullback automatizzato nel “rapporto aureo”.
* **Componenti:** Ritracciamento automatico di Fibonacci + EMA 50 + Stocastico.
* **Logica:**
    1. **Contesto:** Prezzo > EMA 50.
    2. **Livello:** Il prezzo si corregge a Fib 0,5 o 0,618 (“Golden Pocket”) dell'ultimo impulso.
    3. **Trigger:** Lo stocastico è ipervenduto e incrocia verso l'alto.
* **Uscita:** Obiettivo a 0 (massimo precedente) o -0,27 (estensione Fib).
* **Perché è interessante:** Una delle configurazioni discrezionali più popolari: il bot automatizza la ricerca delle voci ideali.
## Consigli
**Raccomandazione generale:**
Concentrati su 3-5 strategie che coprono diversi regimi di mercato (trend, range, momentum, volume). Dare priorità ai sistemi multifattoriali, quindi a forti filtri combinati e solo successivamente a singoli indicatori e modelli.
## Attuazione della strategia
- [X] **RSI + Bande di Bollinger** (rsi_bb)
- [X] **MACD** (macd)
- [X] **RSI Base** (rsi_basic)
- [X] **SMA Crossover** (sma_cross)
- [X] **Il sistema di trend "Fortezza"** (trend_momentum_volatility_volume)
- [X] **Divergence Hunter Pro** (rsi_cci_mfi_ema)
- [X] **Il sistema "Sentiero delle balene"** (volume_trend_value)
- [X] **L'inversione della "banda elastica"** (mean_reversion_trend_filter)
- [X] **Lo "Tsunami Guppy"** (gmma_adx)
- [X] **Triplo schermo (EMA+RSI+MACD)** (triplo_schermo_ema)
- [X] **SuperTrend + StochRSI** (super_stoch)
- [X] **ADX + SAR parabolico** (adx_psar)
- [X] **Indice di discontinuità + EMA** (chop_ema)
- [X] **EMA + StochRSI** (ema_stoch)
- [X] **Ciclo di tendenza di Schaff** (stc_cycle)
- [X] **Tendenza VWAP** (vwap_cross)
- [ ] **Flusso di denaro Chaikin (CMF)** (cmf_trend)
- [ ] **Pendenza di regressione lineare** (lin_reg)
- [ ] **Z-Score** (z_score)
- [ ] **SuperTrend** (supertrend)
- [ ] **Separazione dal canale Donchian** (donchian)
- [ ] **SAR parabolico** (psar)
- [ ] **Dual Thrust** (dual_thrust)
- [ ] **Breakout del range di apertura** (orb_strat)
- [ ] **Fibonacci Tasca dorata** (fib_golden)
- [ ] **Squeeze Momentum** (lazybear_squeeze)
- [ ] **Rimbalzo DCA** (dca_martingala)
- [ ] **Gann Ciao-Lo** (gann_hilo)
- [ ] **McGinley Dinamico** (mcginley)
- [ ] **MA adattiva di Kaufman** (kama_trend)
- [ ] **Vortice** (vortice)
- [ ] **Indice dei flussi di denaro (MFI)** (mfi_div)
- [ ] **Stoch RSI** (stoch_rsi)
- [ ] **TEMA Croce** (tema_cross)
- [ ] **Scafo MA** (hma_trend)
- [ ] **Connors RSI 2** (rsi_2)
- [ ] **Divergenza RSI** (rsi_div)
- [ ] **Barra interna** (inside_bar)
- [ ] **Barra Pin** (pinbar_inversione)
- [ ] **Modello Engulfing** (engulfing_candle)
- [ ] **Tre soldati bianchi / Tre corvi neri** (candle_patterns)
- [ ] **Tendenza Heikin Ashi** (ha_trend)
- [ ] **Spremitura delle bande di Bollinger** (bb_squeeze)
- [ ] **Ichimoku Cloud Breakout** (ichimoku)
- [ ] **ADX + DMI** (adx_dmi)
- [ ] **Tendenza OBV** (obv_trend)
- [ ] **Pullback del canale Keltner** (keltner_pullback)
- [ ] **Oscillatore fantastico** (ao_saucer)
- [ ] **Correzione CCI** (cci_correction)
- [ ] **Indice della Forza dell'Elder** (elder_force)
- [ ] **Williams %R** (williams_r)
- [ ] **Tasso di variazione** (roc)
- [ ] **Breakout canale ATR** (volty_channel)
- [ ] **Strategia Aroon** (aroon)
- [ ] **TRIX (Tripla media esponenziale)** (trix_strat)
- [ ] **Curva Coppock** (coppock)
- [ ] **Commodity Channel Index** (cci_trend)
- [ ] **VWMA vs SMA** (vwma_cross)
- [ ] **Williams Frattali** (fractal_breakout)
- [ ] **Bande di Bollinger di Fibonacci** (fib_bands)
- [ ] **Strategia di uscita da Chandelier** (chandelier_trend)
- [ ] **TD sequenziale (semplificato)** (td_seq)
- [ ] **Trasformazione Ehlers Fisher** (fisher_trans)
- [ ] **Canale deviazione standard** (std_channel)
- [ ] **Inversione punti pivot** (pivot_rev)
- [ ] **Williams Alligator** (alligatore)
- [ ] **Oscillatore Chande Momentum** (cmo_strat)
- [ ] **Facilità di movimento (EOM)** (eom_trend)
- [ ] **Conosci le cose sicure (KST)** (kst_momentum)
- [ ] **Media mobile adattiva frattale (FRAMA)** (frama_trend)
- [ ] **Andamento dei prezzi in volume (VPT)** (vpt_cross)
- [ ] **Laguerre RSI** (laguerre_rsi)
- [ ] **Oscillatore del prezzo di tendenza (DPO)** (dpo_cycle)
- [ ] **Indice di facilitazione del mercato** (bw_mfi)
- [ ] **Linea psicologica** (psy_line)

- [ ] **Indice camminata casuale** (rwi_trend)
- [ ] **Strategia sull'indice Ulcer** (ulcer_strat)
- [ ] **Corrispondenza modello k-Vicini più vicini (kNN)** (knn_ml)
- [ ] **Teoria della scatola di Darvas** (darvas_box)
- [ ] **Indice Elder-Ray** (elder_ray)
- [ ] **Centro di gravità** (cog_ehlers)
- [ ] **Entropia di Shannon** (entropia_caos)
- [ ] **Indice di vigore relativo** (rvi_trend)
- [ ] **VSTOP (Stop volatilità)** (vstop_trend)
- [ ] **Strategia con esponente di Hurst** (hurst_exponent)
- [ ] **Tendenza Renko sintetico** (renko_sintetico)
- [ ] **Rifiuto POC profilo volume** (vpvr_poc)
- [ ] **Trading a triplo schermo** (triple_screen)
- [ ] **Metodo triplo schermo** (triple_screen_custom)
- [ ] **Breakout di Bollinger + MFI** (bb_mfi_breakout)
- [ ] **Ichimoku Cloud + MACD** (ichimoku_macd)
- [ ] **Ritiro SMA 50/200** (golden_cross_pullback)
- [ ] **Regressione lineare + punteggio Z** (stats_arbitrage)
- [ ] **SMA Golden Cross Pullback** (sma_pullback)
- [ ] **Breakout di Bollinger + MFI** (bb_mfi)
- [ ] **Regressione lineare + punteggio Z** (linreg_zscore)
- [ ] **Il "cuoio capelluto perfetto"** (heikin_ashi_ema_stochrsi_atr)
- [ ] **Spremitura avanzata** (bollinger_keltner_momentum_adx)
- [ ] **Ichimoku "Tutto esaurito"** (tenkan_kijun_cloud_chikou_rsi)
- [ ] **Strategia istituzionale VWAP** (vwap_ema_volume_profile_rsi)
- [ ] **Il "Cecchino delle Tendenze"** (parabolic_sar_adx_ema_macd)
- [ ] **Il canale "Regressione quantistica"** (linear_reg_pearson_r_atr)
- [ ] **Il "Caos d'Oro"** (ichimoku_bill_williams_fractals_ao)
- [ ] **Il sistema "Velocity"** (hull_ma_laguerre_rsi_volatility_stop)
- [ ] **La "Confluenza di Fibonacci"** (auto_fibs_ema_50_stochastic)
