# Stratégies de trading
- [Stratégies](#strategies)
  - [RSI + Bandes de Bollinger (rsi_bb)](#rsi--bollinger-bands-rsi_bb)
  - [MACD (macd)](#macd-macd)
  - [RSI Basique (rsi_basic)](#rsi-basic-rsi_basic)
  - [SMA Crossover (sma_cross)](#sma-crossover-sma_cross)
  - [Bollinger Band Squeeze (bb_squeeze)](#bollinger-band-squeeze-bb_squeeze)
  - [Donchian Channel Breakout / Turtle Trading (donchian)](#donchian-channel-breakout--turtle-trading-donchian)
  - [Évasion du nuage Ichimoku (ichimoku)](#ichimoku-cloud-breakout-ichimoku)
  - [ADX + DMI (adx_dmi)](#adx--dmi-adx_dmi)
  - [Tendance OBV (obv_trend)](#obv-trend-obv_trend)
  - [Stratégie SuperTrend (supertrend)](#supertrend-strategy-supertrend)
  - [Tendance EMA + RSI stochastique (ema_stoch)](#ema-trend--stochastic-rsi-ema_stoch)
  - [Stratégie SAR parabolique (psar)](#parabolic-sar-strategy-psar)
  - [Indice de flux monétaire (IMF) (mfi_div)](#money-flow-index-mfi-mfi_div)
  - [TEMA Crossover (tema_cross)](#tema-crossover-tema_cross)
  - [Retrait de la chaîne Keltner (keltner_pullback)](#keltner-channel-pullback-keltner_pullback)
  - [Oscillateur génial (ao_saucer)](#awesome-oscillator-ao_saucer)
  - [Correction CCI (cci_correction)](#cci-correction-cci_correction)
  - [Tendance VWAP (vwap_cross)](#vwap-trend-vwap_cross)
  - [RSI stochastique (stoch_rsi)](#stochastic-rsi-stoch_rsi)
  - [Indice de force des aînés (elder_force)](#elders-force-index-elder_force)
  - [Williams %R (williams_r)](#williams-r-williams_r)
  - [MA adaptative de Kaufman (kama_trend)](#kaufmans-adaptive-ma-kama_trend)
  - [Taux de changement (roc)](#rate-of-change-roc)
  - [Répartition du canal ATR (volty_channel)](#atr-channel-breakout-volty_channel)
  - [Pente de régression linéaire (lin_reg)](#linear-regression-slope-lin_reg)
  - [Flux d'argent Chaikin (cmf_trend)](#chaikin-money-flow-cmf_trend)
  - [Indicateur de vortex (vortex)](#vortex-indicator-vortex)
  - [Stratégie Aroon (aroon)](#aroon-strategy-aroon)
  - [TRIX (Triple Exponential Average) (trix_strat)](#trix-triple-exponential-average-trix_strat)
  - [Courbe Coppock (coppock)](#coppock-curve-coppock)
  - [Indice des canaux de matières premières (cci_trend)](#commodity-channel-index-cci_trend)
  - [Tendance moyenne mobile de coque (hma_trend)](#hull-moving-average-trend-hma_trend)
  - [Stratégie Z-Score (z_score)](#z-score-strategy-z_score)
  - [VWMA contre SMA (vwma_cross)](#vwma-vs-sma-vwma_cross)
  - [Connors RSI 2 (rsi_2)](#connors-rsi-2-rsi_2)
  - [Fractales de Williams (fractal_breakout)](#williams-fractals-fractal_breakout)
  - [Bandes de Bollinger de Fibonacci (fib_bands)](#fibonacci-bollinger-bands-fib_bands)
  - [Stratégie de sortie de lustre (chandelier_trend)](#chandelier-exit-strategy-chandelier_trend)
  - [Inside Bar Breakout (inside_bar)](#inside-bar-breakout-inside_bar)
  - [TD séquentiel (simplifié) (td_seq)](#td-sequential-simplified-td_seq)
  - [Ehlers Fisher Transform (fisher_trans)](#ehlers-fisher-transform-fisher_trans)
  - [Divergence RSI (rsi_div)](#rsi-divergence-rsi_div)
  - [Tendance Heikin Ashi (ha_trend)](#heikin-ashi-trend-ha_trend)
  - [Canal d'écart type (std_channel)](#standard-deviation-channel-std_channel)
  - [Inversion des points pivots (pivot_rev)](#pivot-points-reversal-pivot_rev)
  - [Williams Alligator (alligator)](#williams-alligator-alligator)
  - [Motif engloutissant (engulfing_candle)](#engulfing-pattern-engulfing_candle)
  - [McGinley Dynamique (mcginley)](#mcginley-dynamic-mcginley)
  - [Double poussée (dual_thrust)](#dual-thrust-dual_thrust)
  - [Oscillateur Chande Momentum (cmo_strat)](#chande-momentum-oscillator-cmo_strat)
  - [Facilité de mouvement (eom_trend)](#ease-of-movement-eom_trend)
  - [Know Sure Thing (KST) (kst_momentum)](#know-sure-thing-kst-kst_momentum)
  - [Cycle de tendance Schaff (stc_cycle)](#schaff-trend-cycle-stc_cycle)
  - [Filtre d'indice de saccade + EMA (chop_ema)](#choppiness-index-filter--ema-chop_ema)
  - [Moyenne mobile adaptative fractale (frama_trend)](#fractal-adaptive-moving-average-frama_trend)
  - [Tendance des prix en volume (vpt_cross)](#volume-price-trend-vpt_cross)
  - [Laguerre RSI (laguerre_rsi)](#laguerre-rsi-laguerre_rsi)
  - [Pinbar (Marteau/Étoile filante) (pinbar_reversal)](#pinbar-hammershooting-star-pinbar_reversal)
  - [Oscillateur de prix sans tendance (dpo_cycle)](#detrended-price-oscillator-dpo_cycle)
  - [Répartition de la plage d'ouverture (orb_strat)](#opening-range-breakout-orb_strat)
  - [Indice de facilitation du marché (bw_mfi)](#market-facilitation-index-bw_mfi)

- [Ligne psychologique (psy_line)](#psychological-line-psy_line)
  - [Fibonacci Golden Pocket (fib_golden)](#fibonacci-golden-pocket-fib_golden)
  - [Trois soldats blancs / Trois corbeaux noirs (candle_patterns)](#three-white-soldiers--three-black-crows-candle_patterns)
  - [Indice de marche aléatoire (rwi_trend)](#random-walk-index-rwi_trend)
  - [Stratégie d'indice d'ulcère (ulcer_strat)](#ulcer-index-strategy-ulcer_strat)
  - [Correspondance de modèles k-voisins les plus proches (kNN) (knn_ml)](#k-nearest-neighbors-knn-pattern-matching-knn_ml)
  - [Théorie des boîtes de Darvas (darvas_box)](#darvas-box-theory-darvas_box)
  - [Index Elder-Ray (elder_ray)](#elder-ray-index-elder_ray)
  - [Centre de gravité (cog_ehlers)](#center-of-gravity-cog_ehlers)
  - [Shannon Entropie (entropy_chaos)](#shannon-entropy-entropy_chaos)
  - [Indice de vigueur relative (rvi_trend)](#relative-vigor-index-rvi_trend)
  - [VSTOP (Volatility Stop) (vstop_trend)](#vstop-volatility-stop-vstop_trend)
  - [Que choisir ensuite ?](#what-to-pick-next)
  - [Indicateur d'élan de compression (lazybear_squeeze)](#squeeze-momentum-indicator-lazybear_squeeze)
  - [Stratégie des exposants Hurst (hurst_exponent)](#hurst-exponent-strategy-hurst_exponent)
  - [Tendance Renko synthétique (renko_synthetic)](#synthetic-renko-trend-renko_synthetic)
  - [Activateur Gann Hi-Lo (gann_hilo)](#gann-hi-lo-activator-gann_hilo)
  - [Rejet du POC du profil de volume (vpvr_poc)](#volume-profile-poc-rejection-vpvr_poc)
  - [DCA Rebound (Dollar Cost Averaging) (dca_martingale)](#dca-rebound-dollar-cost-averaging-dca_martingale)
  - [Trading triple écran (triple_screen)](#triple-screen-trading-triple_screen)
- [Stratégies combinées](#combined-strategies)
  - [Méthode triple écran (triple_screen_custom)](#triple-screen-method-triple_screen_custom)
  - [Bollinger Breakout + MFI (bb_mfi_breakout)](#bollinger-breakout--mfi-bb_mfi_breakout)
  - [Cloud Ichimoku + MACD (ichimoku_macd)](#ichimoku-cloud--macd-ichimoku_macd)
  - [ADX + SAR parabolique (adx_psar)](#adx--parabolic-sar-adx_psar)
  - [SMA 50/200 Pullback (golden_cross_pullback)](#sma-50200-pullback-golden_cross_pullback)
  - [Régression linéaire + Z-Score (stats_arbitrage)](#linear-regression--z-score-stats_arbitrage)
  - [Méthode triple écran (triple_screen_ema)](#triple-screen-method-triple_screen_ema)
  - [SMA Golden Cross Pullback (sma_pullback)](#sma-golden-cross-pullback-sma_pullback)
  - [SuperTrend + StochRSI (super_stoch)](#supertrend--stochrsi-super_stoch)
  - [Bollinger Breakout + MFI (bb_mfi)](#bollinger-breakout--mfi-bb_mfi)
  - [Régression linéaire + Z-Score (linreg_zscore)](#linear-regression--z-score-linreg_zscore)
  - [Le système de tendances "Forteresse" (trend_momentum_volatility_volume)](#the-fortress-trend-system-trend_momentum_volatility_volume)
  - [Le « cuir chevelu parfait » (heikin_ashi_ema_stochrsi_atr)](#the-perfect-scalp-heikin_ashi_ema_stochrsi_atr)
  - [Divergence Hunter Pro (rsi_cci_mfi_ema)](#divergence-hunter-pro-rsi_cci_mfi_ema)
  - [Pression avancée (bollinger_keltner_momentum_adx)](#advanced-squeeze-bollinger_keltner_momentum_adx)
  - [Ichimoku "Full House" (tenkan_kijun_cloud_chikou_rsi)](#ichimoku-full-house-tenkan_kijun_cloud_chikou_rsi)
  - [Stratégie institutionnelle VWAP (vwap_ema_volume_profile_rsi)](#vwap-institutional-strategy-vwap_ema_volume_profile_rsi)
  - [Le "Trend Sniper" (parabolic_sar_adx_ema_macd)](#the-trend-sniper-parabolic_sar_adx_ema_macd)
  - [Le système "Whale Trail" (volume_trend_value)](#the-whale-trail-system-volume_trend_value)
  - [L'inversion de la « bande élastique » (mean_reversion_trend_filter)](#the-elastic-band-reversal-mean_reversion_trend_filter)
  - [Le "Tsunami Guppy" (gmma_adx)](#the-guppy-tsunami-gmma_adx)
  - [Le canal "Régression Quantique" (linear_reg_pearson_r_atr)](#the-quant-regression-channel-linear_reg_pearson_r_atr)
  - [Le "Chaos doré" (ichimoku_bill_williams_fractals_ao)](#the-golden-chaos-ichimoku_bill_williams_fractals_ao)
  - [Le Système "Vitesse" (hull_ma_laguerre_rsi_volatility_stop)](#the-velocity-system-hull_ma_laguerre_rsi_volatility_stop)
  - [La "Confluence de Fibonacci" (auto_fibs_ema_50_stochastic)](#the-fibonacci-confluence-auto_fibs_ema_50_stochastic)
- [Recommandations](#recommendations)
- [Mise en œuvre de la stratégie](#strategy-implementation)
## Stratégies
### RSI + Bandes de Bollinger (rsi_bb)
Une stratégie hybride qui vise à capter un point de retournement idéal tout en filtrant les faux signaux.
* **Type :** Réversion moyenne.
* **Logique :** Combine la volatilité (bandes de Bollinger) et le momentum (RSI). Les bandes de Bollinger nous indiquent que le prix est statistiquement « trop bas » (dévié de la norme), et RSI confirme que les vendeurs sont épuisés.
* **Entrée :** La clôture brise la bande **Lower** BB, et en même temps le RSI est en survente (< 30).
* **Sortie :** Le prix revient à la ligne **Milieu** BB (SMA 20). Nous n’attendons pas la bande supérieure, car dans un marché baissier, l’objectif de retour à la moyenne le plus sûr est la bande médiane.
* **Edge :** Résout le problème classique de « attraper les couteaux qui tombent ». Vous n’achetez pas simplement parce que c’est bon marché ; vous achetez lorsque l’écart est extrême et que la faiblesse du vendeur est confirmée.
### MACD (macd)
La stratégie d’indicateurs la plus classique au monde.
* **Type :** Suivi de tendance / Momentum.
* **Logique :** MACD mesure l'écart entre les EMA rapides (12) et lentes (26). L'histogramme montre le taux de variation de cet écart.
* **Entrée :** Le MACD traverse la ligne de signal de bas en haut (ou l'histogramme passe du négatif au positif), ce qui signifie que l'élan à court terme a dépassé celui à long terme.
* **Sortie :** La croix opposée (de haut en bas).
* **Edge :** Capture la « viande » de la tendance (le milieu du mouvement). Fonctionne mal en Chop, mais sur des mouvements BTC/ETH forts, il peut générer des signaux fiables.
### RSI de base (rsi_basic)
Une stratégie de base contre-tendance.
* **Type :** Contre-tendance.
* **Logique :** Le marché oscille comme un pendule. Si cela va trop loin dans un sens, cela a tendance à revenir en arrière.
* **Entrée :** Le RSI tombe en dessous de 30 (survente). Vous pariez sur un rebond.
* **Sortie :** Le RSI dépasse 70 (surachat).
* **Edge :** Le plus simple à comprendre ; fonctionne bien dans une large gamme (marché latéral).
* **Inconvénient :** Dangereux dans les tendances fortes. En cas de crash, le RSI peut rester à 20 pendant une semaine tandis que le prix baisse encore de 50 %. Nécessite un stop loss obligatoire.
### Croisement SMA (sma_cross)
La stratégie de la « Croix d'Or ».
* **Type :** Suivi de tendance.
* **Logique :** Utilise deux moyennes mobiles simples. Le Fast SMA réagit plus rapidement au prix ; le Slow SMA reflète la direction plus large.
* **Entrée :** Le SMA rapide passe au-dessus du SMA lent. Une confirmation mathématique que la tendance est devenue haussière.
* **Sortie :** Le SMA rapide passe en dessous du SMA lent (« Death Cross »).
* **Edge :** vous tient au courant des principales tendances. Vous ne manquerez aucun déplacement « vers la lune », au prix d’entrées et de sorties lentes.
### Bande de Bollinger Squeeze (bb_squeeze)
Une stratégie d’évasion après le calme. Utilise les bandes de Bollinger différemment de `rsi_bb`.
* **Type :** Évasion de volatilité.
* **Logique :** Les marchés sont cycliques : une faible volatilité est suivie d'une forte volatilité. Recherchez une « compression » où les bandes de Bollinger se contractent au minimum et où le canal Keltner se trouve à l’intérieur des bandes de Bollinger.
* **Entrée :** À mesure que les bandes commencent à s'élargir et que le prix dépasse la limite supérieure, optez pour une position longue.
* **Sortie :** Le prix revient à la ligne médiane ou les bandes se contractent à nouveau.
* **Pourquoi c'est cool :** Vous permet d'entrer au début d'une impulsion puissante avant qu'elle ne devienne évidente pour tout le monde.
### Évasion du canal Donchian / Trading de tortues (donchian)
La stratégie classique des « Tortues ». Simple, mais efficace sur des délais plus longs (4h, 1j).
* **Type :** Répartition.
* **Logique :** Le canal Donchian est le plus haut et le plus bas des N dernières périodes (par exemple, 20).
* **Entrée :** Le prix franchit le canal supérieur (nouveau sommet de 20 bougies) – Long.
* **Sortie :** Le prix touche le canal inférieur (ou la ligne médiane pour une prise de profit plus rapide).
* **Pourquoi c'est cool :** Capture toutes les principales tendances. Inconvénient : nombreuses fausses entrées dans les ranges (les drawdowns peuvent être importants).
### Évasion du nuage Ichimoku (ichimoku)
Un système japonais complexe montrant à la fois support, résistance et tendance.
* **Type :** Suivi de tendance.
* **Logique :** Le noyau est le « Cloud » (Kumo).
* **Entrée :** Fermez au-dessus du nuage + Tenkan croise Kijun de bas en haut (croix dorée) – signal long fort.
* **Sortie :** Fermez en dessous de Kijun ou le prix entre dans le cloud.
* **Pourquoi c'est cool :** Le cloud filtre bien le bruit. Si le prix est à l’intérieur du cloud, n’échangez pas. Économise du capital dans l’incertitude.
### ADX + DMI (adx_dmi)
Négocie uniquement lorsque le marché est fort.
* **Type :** Filtre de force de tendance.
* **Logique :** ADX mesure la force de la tendance (pas de direction). DMI (+DI et -DI) fournit la direction.
* **Entrée :** Si ADX > 25 (tendance forte) **et** +DI croise -DI bottom-up — Long. Si ADX < 20 – ignorez les signaux (marché mort).
* **Sortie :** Lorsque +DI repasse en dessous de -DI.
* **Pourquoi c'est cool :** Aide à éviter les « coups » là où les frais et les scies à fouet font le plus de dégâts.
### Tendance OBV (obv_trend)
Utiliser le volume pour confirmer le mouvement des prix.
* **Type :** Tendance du volume.
* **Logique :** OBV (On-Balance Volume) accumule des volumes de bougies. Si le prix augmente mais que l’OBV baisse, c’est une divergence. Pour un bot, il est plus facile de trader la tendance OBV elle-même.
* **Entrée :** Calculez une MA d'OBV. Si l'OBV dépasse sa MA - l'argent afflue - Long.
* **Sortie :** L'OBV tombe en dessous de sa MA.
* **Pourquoi c'est cool :** Le prix peut mentir ; le volume (l’argent) ne le peut généralement pas. L’OBV commence souvent à augmenter avant la hausse des prix.
### Stratégie SuperTrend (supertrend)
L'une des stratégies de cryptographie les plus populaires grâce au mécanisme d'arrêt suiveur intégré.
* **Type :** Suivi de tendance.
* **Logique :** SuperTrend est basé sur l'ATR (volatilité moyenne). Il trace une ligne en dessous du prix dans les tendances haussières et au-dessus du prix dans les tendances à la baisse.
* **Entrée :** Fermez au-dessus de la ligne SuperTrend – Long. Fermer ci-dessous – Short (ou fermez le Long).
* **Sortie :** L'indicateur change de couleur/direction.
* **Pourquoi c'est cool :** Capture les mouvements importants et suit automatiquement le stop loss en fonction du prix. Fonctionne très bien dans les fortes tendances BTC/ETH.
### Tendance EMA + RSI stochastique (ema_stoch)
Une stratégie hybride qui résout le problème principal de `rsi_basic` : acheter des « couteaux qui tombent ».
* **Type :** Oscillateur filtré par tendance.
* **Logique :** Utilise une moyenne mobile « longue » (EMA 200) pour définir la tendance mondiale.
* **Entrée :**
    * Achetez UNIQUEMENT si le prix est **au-dessus** de l'EMA 200 (tendance haussière) **et** le RSI stochastique dépasse la survente (par exemple, < 20).
    * Ignorez les signaux d'achat si le prix est inférieur à l'EMA 200.
* **Sortie :** Le RSI stochastique entre en surachat (> 80) ou se croise à la baisse.
* **Pourquoi c'est cool :** Filtre environ 80 % des faux signaux contraires à la tendance.
### Stratégie SAR parabolique (psar)
La stratégie classique « toujours sur le marché » (Stop and Reverse).
* **Type :** Suivi/Inversion de tendance.
* **Logique :** L'indicateur trace les points en dessous du prix (tendance haussière) ou au-dessus du prix (tendance baissière). Les points se resserrent sur les prix à mesure que la tendance mûrit.
* **Entrée :** Le prix traverse un point SAR parabolique. Si les points basculent **en dessous** du prix – Long.
* **Sortie :** Les points s'inversent **au-dessus** du prix – fermez Long (et éventuellement ouvrez Short).
* **Avantages :** Idéal pour les tendances fortes ; cela vous oblige à tenir jusqu'à ce qu'il y ait une pause explicite.
* **Inconvénients :** Dans les plages, des retournements fréquents peuvent saigner le compte.
### Indice de flux monétaire (IMF) (mfi_div)
"RSI avec volume". Essaie de détecter l'argent intelligent.
* **Type :** Momentum du volume.
* **Logique :** Le prix peut augmenter par inertie, mais si le volume baisse, la tendance est à court de carburant. L’IMF tient compte à la fois du prix et du volume.
* **Entrée :** L'IMF tombe en dessous de 20 (survente) et apparaît — Long. La divergence (prix en baisse, IMF en hausse) fonctionne encore mieux.
* **Sortie :** IMF supérieure à 80 (surachat).
* **Avantages :** Filtre les mouvements de prix « vides » non pris en charge par le volume. Mène souvent RSI.
### TEMA Crossover (tema_cross)
Utilise Triple EMA (TEMA) pour réduire le décalage.
* **Type :** Tendance rapide.
* **Logique :** Décalage SMA/EMA régulier. TEMA réagit presque instantanément.
* **Entrée :** Le TEMA rapide (par exemple, 9) passe au-dessus du TEMA lent (par exemple, 21).
* **Sortie :** La croix opposée.
* **Avantages :** Entre plus tôt que le croisement SMA et sort plus rapidement en cas d'inversion.
* **Inconvénients :** Plus de faux signaux (« bruit ») sur des marchés calmes.
### Retrait du canal Keltner (keltner_pullback)
Retraits commerciaux dans des tendances fortes. Une alternative au BB.
* **Type :** Tendance de retrait.
* **Logique :** Keltner Channel est construit sur l'ATR (volatilité). Si le prix reste longtemps au-dessus de la bande *supérieure*, la tendance est très forte.
* **Entrée :**
    1. Confirmez la tendance haussière (Prix > EMA 20 ou ligne médiane du canal).
    2. Attendez le retrait vers la ligne de canal **inférieure** ou **milieu**.
    3. Allez longtemps au toucher/rebond.
* **Sortie :** Le prix atteint la bande supérieure du canal.
* **Avantages :** « Achetez la baisse » dans une tendance haussière. Bon rapport risque/récompense.
### Oscillateur génial (ao_saucer)
La stratégie « Soucoupe » de Bill Williams.
* **Type :** Élan.
* **Logique :** L'histogramme AO montre la force motrice du marché.
* **Entrée (le motif « Soucoupe ») :** Histogramme au-dessus de zéro. Recherchez 3 barres : Rouge -> Rouge (inférieur à la première) -> Vert (supérieur à la seconde). La correction est terminée et la hausse reprend.
* **Quitter :** La couleur devient rouge ou l'histogramme descend en dessous de zéro.
* **Avantages :** Un « microscope » pour le timing d'entrée à l'intérieur des vagues.
### Correction CCI (cci_correction)
Commodity Channel Index, populaire sur le forex et la crypto.
* **Type :** cyclique.
* **Logique :** CCI mesure l'écart du prix par rapport à sa moyenne statistique.
* **Entrée :** Attendez que le CCI descende en dessous de -100 (forte survente), puis repasse au-dessus de -100.
* **Sortie :** Le CCI dépasse +100 ou franchit 0 de haut en bas.
* **Avantages :** Niveaux clairs (-100/+100), logique mécanique simple.
### Tendance VWAP (vwap_cross)
Une stratégie utilisée par les traders institutionnels. Le VWAP (Volume Weighted Average Price) indique le prix « juste » de l’actif en tenant compte du volume.
* **Type :** Suivi de tendance / Volume.
* **Logique :** Si le prix est supérieur au VWAP, les acheteurs contrôlent le marché (haussier). Si ci-dessous — vendeurs.
* **Entrée :** Le prix croise le VWAP ascendant.
* **Sortie :** Le prix croise le VWAP de haut en bas.
* **Remarque :** Très efficace en intrajournalier (5 min, 15 min, 1 h) car les institutions s'ancrent souvent au VWAP.
### RSI stochastique (stoch_rsi)
Une version plus sensible et plus rapide de RSI. Aide à capturer les fluctuations à court terme au sein d’une tendance.
* **Type :** Scalping / Oscillateur.
* **Logique :** StochRSI applique la formule stochastique aux valeurs RSI, et non au prix, ce qui la rend très réactive.
* **Entrée :** Les lignes StochRSI se croisent en survente (< 20) et montent.
* **Sortie :** Traversez le surachat (> 80) et descendez.
* **Remarque :** Génère de nombreux signaux. Nécessite un filtre (par exemple, négociez uniquement avec la tendance EMA), sinon il se divisera en fourchettes.
### Indice de force des aînés (elder_force)
La stratégie d’Alexander Elder. Combine le prix et le volume pour mesurer la puissance « haussière » et « baissière ».
* **Type :** Élan.
* **Logique :** Force Index = (Close - PrevClose) * Volume, puis lissé (EMA).
* **Entrée :** Tendance mondiale à la hausse (par exemple, prix supérieur à l'EMA 22) et l'indice de force (période 2) tombe en dessous de zéro (retrait à court terme). Achetez la trempette.
* **Sortie :** L'indice de force redevient positif (l'élan revient).
* **Remarque :** Idéal pour détecter les entrées de retrait dans les tendances fortes.
### Williams %R (williams_r)
L’indicateur de Larry Williams. Semblable au stochastique, mais inversé. Idéal dans les gammes.
* **Type :** Réversion moyenne.
* **Logique :** Mesure la proximité de la clôture par rapport aux hauts/bas de la fourchette.
* **Entrée :** La valeur tombe en dessous de -80 (survente) et commence à augmenter.
* **Sortie :** La valeur dépasse -20 (surachat).
* **Remarque :** Excellent pour mettre en évidence l'épuisement du vendeur.
### MA adaptative de Kaufman (kama_trend)
Une stratégie basée sur la moyenne mobile adaptative de Kaufman.
* **Type :** Tendance adaptative.
* **Logique :** Contrairement à un EMA classique, KAMA ralentit dans les plages bruyantes (aplatit) et accélère dans les tendances. Cela réduit les fausses entrées.
* **Entrée :** Le prix croise KAMA de bas en haut.
* **Sortie :** Le prix croise KAMA de haut en bas.
* **Remarque :** Une moyenne mobile « intelligente » qui filtre les coupures.
### Taux de changement (roc)
Négocier la vitesse de changement des prix. Physique pure du marché.
* **Type :** Vitesse / Momentum.
* **Logique :** ROC affiche le pourcentage de changement sur N périodes. La hausse du ROC signifie que la tendance s’accélère.
* **Entrée :** Le ROC passe au-dessus de zéro (accélération à la hausse).
* **Sortie :** Le ROC passe en dessous de zéro (décélération).
* **Remarque :** Un indicateur avancé ; signale souvent des renversements avant le croisement des MA.
### Répartition du canal ATR (volty_channel)
Rupture du canal de volatilité.
* **Type :** Répartition.
* **Logique :** Créez un canal autour du prix : `Close + (N * ATR)` et `Close - (N * ATR)`.
* **Entrée :** Fermez au-dessus du canal supérieur. Un mouvement anormalement fort au-delà de la volatilité normale.
* **Sortie :** Le prix revient au milieu.
* **Remarque :** Capture les pompes/vidages les plus puissantes tout en ignorant les bruits mineurs.
### Pente de régression linéaire (lin_reg)
Trading basé sur la pente mathématique d'une ligne de tendance.
* **Type :** Statistique/Tendance.
* **Logique :** Au lieu de faire la moyenne des prix (comme SMA), tracez une ligne de régression linéaire sur les N dernières bougies et utilisez sa pente.
* **Entrée :** La pente devient positive et dépasse un seuil (filtre de bruit). Statistiquement, la tendance s’est inversée.
* **Sortie :** La pente devient négative.
* **Pourquoi c'est cool :** Réagit plus rapidement que les MA car il essaie de modéliser la direction, pas seulement de faire la moyenne du passé.
### Flux monétaire Chaikin (cmf_trend)
Stratégie d'accumulation/distribution. Semblable à MFI, mais utilise une analyse plus approfondie de l’emplacement proche dans la plage des bougies.
* **Type :** Débit volumique.
* **Logique :** CMF estime la pression d'achat/vente. CMF > 0 signifie accumulation (l’argent entre) ; CMF < 0 signifie distribution (l’argent sort).
* **Entrée :** CMF passe au-dessus de zéro.
* **Sortie :** Le CMF repasse en dessous de zéro.
* **Pourquoi c'est cool :** Aide à distinguer un véritable renversement d'un « rebond de chat mort » – si le prix augmente alors que le CMF < 0, le mouvement est probablement faible.
### Indicateur de vortex (vortex)
Un indicateur inspiré des modèles d'écoulement naturels (vortex).
* **Type :** Suivi de tendance.
* **Logique :** Deux lignes : VI+ et VI-. Ils mesurent le mouvement directionnel en fonction des distances entre le haut actuel et le bas précédent (et vice versa).
* **Entrée :** VI+ passe au-dessus de VI-.
* **Sortie :** VI+ passe en dessous de VI-.
* **Pourquoi c'est cool :** Fiable pour détecter le début de tendances plus longues, même s'il peut être en retard dans les plages.
### Stratégie Aroon (aroon)
Une stratégie qui mesure le *temps* depuis le dernier haut/bas.
* **Type :** Force de tendance.
* **Logique :** Aroon Up indique le nombre de jours écoulés depuis un High ; Aroon en baisse depuis un minimum. Les valeurs vont de 0 à 100.
* **Entrée :** Aroon Up passe au-dessus d'Aroon Down **et** Aroon Up > 50. De nouveaux hauts apparaissent plus souvent que des bas.
* **Sortie :** Aroon Up descend en dessous de 50 ou passe en dessous d'Aroon Down.
* **Pourquoi c'est cool :** Une approche unique basée sur le temps au lieu de signaux purement basés sur les prix.
### TRIX (Triple Exponentielle Moyenne) (trix_strat)
Un oscillateur de quantité de mouvement très fluide.
* **Type :** Élan.
* **Logique :** EMA triple lissage (souvent sur le prix du journal), qui supprime la plupart des bruits du marché.
* **Entrée :** TRIX passe au-dessus de zéro.
* **Sortie :** Repassez en dessous de zéro ou franchissez la ligne de signal.
* **Pourquoi c'est cool :** Peu de signaux mais de haute qualité ; fonctionne bien sur des délais plus longs (4h, 1j).
### Courbe de Coppock (coppock)
Un indicateur conçu pour détecter les creux du marché à long terme (à l’origine pour le S&P 500), mais qui fonctionne également en cryptographie.
* **Type :** Swing/Investissement à long terme.
* **Logique :** Somme de deux valeurs ROC avec des périodes différentes, lissées par une moyenne mobile pondérée.
* **Entrée :** La courbe de Coppock commence à augmenter lorsqu'elle est en dessous de zéro.
* **Sortie :** La courbe descend (ou franchit 0).
* **Pourquoi c'est cool :** Psychologiquement confortable : entrées rares, souvent proches du début d'un marché haussier plus large.
### Indice des canaux de matières premières (cci_trend)
Utiliser CCI pour le trading de tendance (et non contre-tendance comme précédemment).
* **Type :** Tendance.
* **Logique :** Le CCI est souvent utilisé pour les inversions, mais ici nous l'utilisons comme signal de cassure/d'élan.
* **Entrée :** Le CCI dépasse +100 – une forte impulsion à la hausse.
* **Sortie :** CCI retombe en dessous de +100 (ou en dessous de 0).
* **Pourquoi c'est cool :** Capture la partie « la plus importante » d'un mouvement lorsqu'un actif va « sur la lune ».
### Tendance de la moyenne mobile de Hull (hma_trend)
Une stratégie basée sur la Hull Moving Average (HMA).
* **Type :** Suivi de tendance à faible décalage.
* **Logique :** Alan Hull a créé une formule qui réduit le décalage typique du SMA/EMA tout en conservant une courbe lisse.
* **Entrée :** Le prix dépasse le HMA (ou la pente du HMA s'inverse de bas en haut).
* **Sortie :** Le retournement croisé ou incliné opposé.
* **Edge :** Réagit aux inversions presque instantanément ; idéal sur les paires volatiles où les MA régulières sont trop lentes.
### Stratégie Z-Score (z_score)
Statistiques mathématiques pures sans « lignes magiques ».
* **Type :** Réversion moyenne.
* **Logique :** Le Z-Score mesure le nombre d'écarts types (sigmas) du prix par rapport à sa moyenne, comme les bandes de Bollinger « numériques ».
* **Entrée :** Le score Z tombe en dessous de -2 (écart à la baisse de 2 sigma). Achetez en attendant le retour.
* **Sortie :** Le Z-Score revient à 0 (moyenne) ou dépasse +2.
* **Edge :** Fonctionne sur n'importe quel actif car il normalise la volatilité.
### VWMA contre SMA (vwma_cross)
Valider la force de la tendance via le volume.
* **Type :** Tendance + Confirmation du volume.
* **Logique :** Comparez SMA à VWMA (MA pondérée en volume).
    * Si VWMA > SMA, le volume est plus fort sur les bougies ascendantes (les plus gros joueurs achètent).
    * Si VWMA < SMA alors que le prix augmente, le mouvement se fait sur un volume faible (piège possible).
* **Entrée :** VWMA passe au-dessus de SMA.
* **Sortie :** VWMA passe en dessous de SMA.
* **Edge :** Filtre les pompes « gonflées » sans argent réel derrière elles.
### Connors RSI 2 (rsi_2)
La célèbre stratégie de scalping de Larry Connors.
* **Type :** Réversion moyenne agressive à court terme.
* **Logique :** Le RSI(14) standard est trop lent ; Connors utilise RSI avec la période 2.
* **Entrée :** Le RSI(2) tombe en dessous de 10 (ou 5) – survente extrême. Allez-y longtemps.
* **Sortie :** Clôture au-dessus du SMA de 5 jours. N'attendez pas un RSI > 90 ; sortie au premier rebond.
* **Edge :** Taux de réussite très élevé (souvent > 80 %), mais les transactions sont courtes et le profit par transaction est faible.
### Fractales de Williams (fractal_breakout)
Négociation des cassures des niveaux locaux (Price Action).
* **Type :** Répartition.
* **Logique :** Une fractale de Williams est une formation de 5 bougies où la bougie du milieu a le plus haut (fractale vers le haut) ou le plus bas (fractale vers le bas). Ce sont des pics/creux locaux.
* **Entrée :** Le prix dépasse le niveau de la dernière fractale ascendante (la bougie fractale High).
* **Sortie :** Le prix dépasse le niveau de la dernière fractale baissière (trailing stop).
* **Edge :** Négocie les niveaux de support/résistance réels que le marché voit, et non des formules dérivées.
### Bandes de Bollinger de Fibonacci (fib_bands)
Une approche modifiée des bandes de Bollinger pour capturer des rebonds plus précis.
* **Type :** Réversion / Tendance moyenne.
* **Logique :** Au lieu de multiplicateurs d'écart type (x2, x3), des rapports de Fibonacci (1,618, 2,618, 4,236) sont utilisés pour les largeurs de bande.
* **Entrée :** Le prix touche une bande intérieure (Fib 1.618) ou une bande externe (Fib 2.618) et rebondit.
* **Sortie :** Revenez à la ligne médiane.
* **Edge :** Crypto respecte souvent les niveaux de Fibonacci plus qu'un modèle gaussien parfait.
### Stratégie de sortie du lustre (chandelier_trend)
Une stratégie construite à contre-courant : la gestion des sorties (stop loss).
* **Type :** Suivi de tendance.
* **Logique :** Chandelier Exit suspend un stop loss à une distance (ATR * 3) en dessous du plus haut niveau sur une analyse rétrospective. Si le prix n’atteint pas le « lustre », vous restez.
* **Entrée :** Clôture au-dessus de la ligne de sortie Chandelier (tendance inversée haussière).
* **Sortie :** Le prix touche la ligne (coup de stop suiveur).
* **Edge :** Conçu pour laisser courir les bénéfices et éviter de sortir en cas de légers replis.
### Répartition de la barre intérieure (inside_bar)
Une stratégie classique d'action sur les prix sans indicateurs.
* **Type :** Répartition/modèle de volatilité.
* **Logique :** Trouvez une barre intérieure – une bougie dont le haut/bas est entièrement à l'intérieur de la bougie « mère » précédente. Le marché se comprime avant l’expansion.
* **Entrée :** Le prix dépasse le sommet de la barre intérieure (pour les positions longues).
* **Sortie :** Take profit fixe ou stop suiveur. Le stop loss est placé derrière le bas de la barre intérieure.
* **Edge :** Stops très serrés avec un potentiel de hausse élevé (risque/récompense).
### TD Séquentiel (simplifié) (td_seq)
Une version simplifiée de la stratégie légendaire de Thomas DeMark.
* **Type :** Contre-tendance / Inversion.
* **Logique :** Les marchés en ont assez d'évoluer dans une seule direction. DeMark compte les clôtures séquentielles.
* **Entrée (configuration) :** Si vous voyez **9 bougies consécutives** où chaque clôture est inférieure à la clôture 4 bougies plus tôt (configuration baissière) – les vendeurs sont épuisés. Entrez Long à l’ouverture de la bougie 10.
* **Sortie :** Sur la configuration inverse ou après un nombre fixe de bougies.
* **Edge :** Populaire en crypto pour attraper les fonds locaux.
### Transformation d'Ehlers Fisher (fisher_trans)
La stratégie de John Ehlers utilisant les concepts de traitement numérique du signal.
* **Type :** Inversion / Cyclique.
* **Logique :** Transforme le mouvement des prix en une distribution (presque) normale, rendant les points tournants nets et clairs en supprimant le bruit.
* **Entrée :** La ligne Fisher passe au-dessus de sa ligne de signal (souvent à la sortie d'une zone inférieure).
* **Sortie :** La croix opposée.
* **Edge :** Un oscillateur « turbo », réagissant plus rapidement et plus proprement que RSI ou MACD.
### Divergence RSI (rsi_div)
Négociez les divergences RSI au lieu des niveaux RSI.
* **Type :** Inversion.
* **Logique :** Si le prix atteint un plus bas inférieur, mais que le RSI atteint un plus bas plus élevé, c'est une **divergence haussière**. La dynamique baissière est épuisée même si le prix continue de baisser.
* **Entrée :** Après confirmation de la divergence haussière.
* **Sortie :** Le RSI dépasse 70 ou dépasse 50.
* **Edge :** L'un des signaux TA les plus fiables ; vous permet d'entrer près du bas (attraper les « couteaux qui tombent » de manière professionnelle).
### Tendance Heikin Ashi (ha_trend)
Utilisation de bougies Heikin Ashi modifiées pour filtrer le bruit.
* **Type :** Tendance visuelle.
* **Logique :** Les bougies Heikin Ashi sont calculées à partir des prix moyens d'ouverture et de clôture. Ils lissent le graphique et masquent les petits retraits.
* **Entrée :** Après une série de bougies rouges, une bougie verte apparaît sans mèche inférieure (forte impulsion haussière).
* **Sortie :** Une bougie à changement de couleur (rouge) apparaît, ou une bougie avec de longues mèches des deux côtés (doji/incertitude).
* **Bord :** Psychologiquement confortable ; vous aide à suivre les tendances longues sans réagir de manière excessive aux petites bougies rouges sur un graphique normal.
### Canal d'écart type (std_channel)
Trading dans un canal de régression linéaire.
* **Type :** Réversion moyenne.
* **Logique :** Une ligne médiane de régression linéaire plus deux lignes parallèles à 2 écarts types. Environ 95 % des mouvements ont lieu à l’intérieur.
* **Entrée :** Le prix touche le canal inférieur (survendu par rapport à la tendance).
* **Sortie :** Retour à la ligne de régression (ligne médiane).
* **Bord :** Contrairement aux bandes de Bollinger, ce canal a une pente, vous voulez donc revenir **dans la direction** de la tendance.
### Inversion des points pivots (pivot_rev)
Trading à partir de niveaux de support mathématiques.
* **Type :** Rebond.
* **Logique :** Utilisez le haut/bas/fermeture d'hier pour calculer le pivot (P), les supports (S1, S2) et les résistances (R1, R2).
* **Entrée :** Le prix tombe en S1 ou S2, le teste et clôture au-dessus (rebond).
* **Sortie :** Niveau pivot suivant (par exemple, acheter à S1, cible P).
* **Edge :** Il s'agit de niveaux auto-réalisateurs que de nombreux traders surveillent ; fonctionne bien sur 1h/4h.
### Alligator Williams (alligator)
La stratégie de tendance classique de Bill Williams.
* **Type :** Suivi de tendance.
* **Logique :** Trois moyennes mobiles lissées décalées vers l'avant (mâchoires, dents, lèvres). Ils imitent le comportement d’un alligator.
* **Entrée :** Lorsque les lignes sont emmêlées – « l'alligator dort » (portée, n'échangez pas). Lorsqu'elles s'ouvrent dans le bon ordre (Lèvres > Dents > Mâchoires) — tendance lancée — Longues.
* **Sortie :** Les lignes s'emmêlent à nouveau ou le prix clôture en dessous des « dents ».
* **Edge :** Permet d'échanger uniquement des mouvements forts et d'ignorer les ranges bruyantes.
### Modèle engloutissant (engulfing_candle)
Négocier le modèle de chandelier pur « Engloutissant ».
* **Type :** Action/Inversion des prix.
* **Logique :** Deux bougies. La deuxième bougie (haussière) engloutit entièrement le corps de la bougie précédente (baissière), montrant un brusque changement de sentiment de la vente à l'achat.
* **Entrée :** Un engloutissement haussier apparaît après une série de bougies descendantes.
* **Sortie :** Objectif de profit fixe ou modèle inverse.
* **Edge :** Pas de décalage ; le signal est disponible dès la fermeture de la bougie.
### McGinley Dynamique (mcginley)
Trader avec une moyenne mobile « idéale ».
* **Type :** Tendance avancée.
* **Logique :** John McGinley a créé un indicateur qui ressemble à une EMA mais qui accélère automatiquement sur les marchés rapides et ralentit sur les marchés lents, évitant ainsi mieux les scies à fouet que les MA standard.
* **Entrée :** Price passe au-dessus de la ligne McGinley.
* **Sortie :** Le prix passe en dessous de la ligne.
* **Edge :** Résout l'éternelle question : "Quelle période de MA dois-je utiliser ?" McGinley s'adapte automatiquement.
### Double poussée (dual_thrust)
Un système de cassure célèbre, souvent utilisé dans les contrats à terme.
* **Type :** Répartition de la plage.
* **Logique :** Prenez la fourchette des N dernières bougies (Haut - Clôture ou Haut - Bas) et multipliez par K.
* **Entrée :** Si le prix casse `Open + (Range * K)` — Long. S'il casse en dessous - Court.
* **Sortie :** Clôture de fin de journée ou stop-and-reverse.
* **Edge :** Capte les fortes impulsions issues de la consolidation ; populaire dans le trading d’algorithmes.
### Oscillateur d'impulsion Chande (cmo_strat)
Un indicateur de momentum pur, différent du RSI.
* **Type :** Élan.
* **Logique :** Le CMO est la différence entre les sommes des mouvements ascendants et descendants divisée par le mouvement total. Plage : -100 à +100.
* **Entrée :** Le CMO franchit +50 bottom-up (forte impulsion haussière) ou passe d'une survente (< -50).
* **Sortie :** Le CMO repasse en dessous de +50.
* **Edge :** Contrairement au lissage RSI, CMO réagit directement à chaque mouvement, affichant la vitesse brute.
### Facilité de mouvement (eom_trend)
Une stratégie combinant Prix et Volume pour trouver le « chemin de moindre résistance ».
* **Type :** Volume + Prix.
* **Logique :** L'EVM de Richard Arms montre avec quelle facilité les prix évoluent. Une forte hausse des prix sur de petits volumes est « facile » ; un volume énorme avec peu de mouvement est « dur » (un combat).
* **Entrée :** EVM passe au-dessus de 0.
* **Quitter :** L'EVM tombe en dessous de 0.
* **Edge :** Aide à repérer les tendances « saines » et à éviter les marchés où il y a de fortes batailles (gros volume, aucun mouvement).
### Savoir une chose sûre (KST) (kst_momentum)
« Sachez-le avec certitude » – un indicateur composite de dynamique.
* **Type :** Cycle Momentum (à plus long terme).
* **Logique :** Une somme de quatre composants ROC avec un lissage différent ; effectivement un « MACD pour les cycles ».
* **Entrée :** KST passe au-dessus de sa ligne de signal.
* **Sortie :** La croix opposée.
* **Edge :** Conçu pour capter les principaux cycles du marché tout en ignorant les petites corrections. Fonctionne bien sur 4h et 1j.
### Cycle de tendance de Schaff (stc_cycle)
Une variante MACD améliorée qui se déplace plus rapidement et plus précisément.
* **Type :** Cycle / Momentum.
* **Logique :** Doug Schaff a combiné MACD et Stochastic dans un oscillateur de 0 à 100 qui, contrairement au Stochastic, est moins instable et maintient mieux les positions.
* **Entrée :** Le STC dépasse 25 (sorties survendues).
* **Sortie :** Le STC descend en dessous de 75 (sortie surachetée).
* **Remarque :** Trouve les tendances antérieures au MACD et donne moins de faux signaux dans les plages.
### Filtre d'index de saccades + EMA (chop_ema)
Une stratégie avec un filtre « qualité marché ».
* **Type :** Tendance avec filtre.
* **Logique :** L'indice de saccades (CHOP) indique si le marché est en tendance ou en fourchette. CHOP > 61,8 signifie range (ne pas échanger). CHOP < 38,2 signifie une forte tendance.
* **Entrée :** Le prix dépasse une EMA (par exemple, 50) **et** CHOP < 50 (confirmation de tendance).
* **Sortie :** Le prix repasse en dessous de l'EMA.
* **Remarque :** L'objectif principal est d'éviter les transactions sur des marchés morts et d'économiser des frais et des nerfs.
### Moyenne mobile adaptative fractale (frama_trend)
Utiliser la géométrie fractale pour s'adapter au marché.
* **Type :** Tendance adaptative.
* **Logique :** FRAMA utilise la « dimension fractale ». Dans le chaos (portée), FRAMA ralentit et s'aplatit. En mouvement directionnel, il accélère.
* **Entrée :** Le prix dépasse FRAMA.
* **Sortie :** Le prix passe en dessous de FRAMA.
* **Remarque :** Contrairement à un EMA classique, FRAMA peut rester presque plat pendant les corrections, évitant ainsi les faux arrêts.
### Tendance des prix en volume (vpt_cross)
Un indicateur de type OBV plus avancé.
* **Tapez :** Volume.
* **Logique :** VPT ne tient pas seulement compte de la direction (comme OBV), mais aussi du *pourcentage* de changement de prix. Un volume important avec un faible changement de prix a un faible impact ; un gros volume avec un grand mouvement a un grand impact.
* **Entrée :** VPT dépasse sa moyenne mobile (MA).
* **Sortie :** VPT tombe en dessous de sa MA.
* **Remarque :** Très sensible à l’accumulation de « monnaie intelligente ».
### Laguerre RSI (laguerre_rsi)
« RSI du futur » — en utilisant le filtre Laguerre.
* **Type :** Oscillateur de tendance.
* **Logique :** John Ehlers a appliqué un filtrage de déformation temporelle pour créer un RSI à décalage minimal avec seulement 4 composants de lissage.
* **Entrée :** Laguerre RSI passe au-dessus de 0,2 (20%).
* **Sortie :** Traverse en dessous de 0,8 (80%).
* **Remarque :** Réagit beaucoup plus rapidement que le RSI classique, capturant davantage le mouvement.
### Pinbar (Marteau/Étoile filante) (pinbar_reversal)
Pure Price Action – bougies d’inversion.
* **Type :** Modèle de chandelier (inversion).
* **Logique :** Un « pin bar » (marteau ou étoile filante) a une très longue mèche et un petit corps. La mèche montre que le prix a évolué dans un sens et a été fortement rejeté.
* **Entrée :** Un pin bar haussier (longue mèche inférieure) apparaît à un plus bas local.
* **Sortie :** Risque/récompense fixe (par exemple, 1:3) ou sortie sur un signal opposé.
* **Remarque :** Fonctionne mieux aux niveaux de support ; marque souvent la capitulation du vendeur.
### Oscillateur de prix sans tendance (dpo_cycle)
Négocier des cycles à court terme sans le biais de tendance mondiale.
* **Type :** cyclique à court terme.
* **Logique :** Le DPO supprime la tendance à long terme, ne laissant que les oscillations à court terme (« micro-ondes »).
* **Entrée :** Le DPO passe au-dessus de 0.
* **Sortie :** Le DPO passe en dessous de 0.
* **Remarque :** Aide à négocier les fluctuations intrajournalières même lorsque le marché mondial se trouve dans un régime haussier/baissier fort.
### Ouverture de la plage d'ouverture (orb_strat)
Stratégie de day-trader classique adaptée à un marché 24h/24 et 7j/7.
* **Type :** Répartition basée sur le temps.
* **Logique :** La première heure (ou 4 heures) d'un nouveau jour/semaine donne le ton ; le marché « choisit » la direction.
* **Entrée :** Définissez le haut et le bas de la première bougie quotidienne (00:00 UTC). Si le prix dépasse le High – Long.
* **Sortie :** Fin de journée (23h59) ou un stop loss fixe au point médian du range.
* **Edge :** Utilise l'impulsion de la session d'ouverture. Très simple, mais statistiquement efficace sur les actifs à forte volatilité.
### Indice de facilitation du marché (bw_mfi)
La stratégie de Bill Williams (pas le Money Flow Index). Mesure l’efficacité du mouvement des prix par rapport au volume.
* **Type :** Volume + Efficacité des prix.
* **Logique :** Compare la plage au volume.
    * *Barre verte :* Augmentation du volume + mouvement fort = vraie tendance.
    * *Squat Bar :* Augmentation du volume + prix fixe = combat taureau/ours (inversion possible).
* **Entrée :** 2 à 3 « barres vertes » consécutives.
* **Quitter :** Une barre « Squat » apparaît : le mouvement est à court de carburant.
* **Edge :** Aide à distinguer une pompe faible (faible volume) d'un mouvement réel.
### Ligne psychologique (psy_line)
Indicateur du sentiment de la foule.
* **Type :** Sentiment / Contre-tendance.
* **Logique :** Rapport entre les bougies montantes et le nombre total de bougies sur une période (par exemple, 12). Si PSY > 75 %, 9 bougies sur 12 étaient vertes – euphorie (surachat).
* **Entrée :** PSY tombe en dessous de 25 % (panique) et apparaît.
* **Sortie :** PSY dépasse les 75 %.
* **Edge :** Un thermomètre de marché qui ignore les prix absolus et se concentre sur les « gains » haussiers et baissiers.
### Poche dorée de Fibonacci (fib_golden)
Trading automatisé des retraits de Fibonacci.
* **Type :** Achat par trempette.
* **Logique :** Trouve le dernier swing significatif Haut/Bas et dessine le retracement de Fibonacci. La zone comprise entre 0,618 et 0,65 est la « Golden Pocket », où des rebonds se produisent souvent.
* **Entrée :** Le prix touche le niveau de retracement de 0,618.
* **Sortie :** Nouveau plus haut (niveau 0) ou stop en dessous de 0,786.
* **Edge :** L'une des stratégies discrétionnaires les plus populaires ; le bot automatise la recherche de ces niveaux.
### Trois soldats blancs / Trois corbeaux noirs (candle_patterns)
Négociez des formations de bougies fortes qui poursuivent souvent la tendance.
* **Type :** Reconnaissance de formes.
* **Logique :** « Trois soldats blancs » sont trois bougies vertes consécutives, chacune fermant plus haut que la précédente, de préférence avec des mèches courtes. Indique la domination de l'acheteur.
* **Entrée :** Clôture de la 3ème bougie.
* **Sortie :** La première bougie baissière apparaît, ou le stop suiveur au plus bas de la bougie.
* **Edge :** Si trois bougies puissantes s'impriment d'affilée, la probabilité de continuation est souvent élevée.
### Indice de marche aléatoire (rwi_trend)
Un test statistique : « Est-ce une tendance ou un hasard ?
* **Type :** Filtre statistique.
* **Logique :** RWI compare l'évolution des prix à ce que vous attendez d'une marche aléatoire (lancements de pièces).
* **Entrée :** RWI High > 1 (le mouvement vers le haut est statistiquement significatif).
* **Quitter :** RWI High tombe en dessous de 1.
* **Edge :** vous évite de négocier sur des marchés bruyants et chaotiques.
### Stratégie d'indice d'ulcère (ulcer_strat)
Une stratégie qui minimise le stress (et les retraits).
* **Type :** Ajusté au risque / Gestion des risques.
* **Logique :** L'indice d'ulcère mesure la profondeur et la durée des retraits. Contrairement à l’écart type, il ne prend en compte que les *mouvements à la baisse* (mauvaise volatilité).
* **Entrée :** Le prix augmente alors que l'indice Ulcer est extrêmement bas (tendance haussière douce et calme).
* **Sortie :** Une forte hausse de l'indice d'ulcère (les turbulences commencent).
* **Edge :** Idéal pour une croissance de compte prudente ; sort tôt de l'instabilité sans attendre un crash.
### Correspondance de modèle des k-voisins les plus proches (kNN) (knn_ml)
Apprentissage automatique simple sans réseaux neuronaux lourds.
* **Type :** Correspondance de motifs.
* **Logique :** L'algorithme mémorise la forme des N dernières bougies (par exemple 5), puis recherche dans le graphique historique les formes les plus similaires.
* **Entrée :** Si dans 70 % des correspondances historiques trouvées, le prix a augmenté par la suite, achetez.
* **Sortie :** Période de détention fixe (par exemple, 3 bougies) ou lorsque les prévisions changent.
* **Edge :** Le bot n'utilise pas d'indicateurs ; il « regarde » l’histoire : « Cela s’est produit avant – voici ce qui s’est passé ensuite. »
### Théorie des boîtes de Darvas (darvas_box)
La stratégie légendaire de Nicholas Darvas qui lui a rapporté 2 millions de dollars dans les années 1950.
* **Type :** Breakout / Suivi de tendance.
* **Logique :** Lorsque les prix varient, il construit une « boîte » avec un plafond (haut) et un plancher (bas) clairs.
* **Entrée :** Le prix dépasse le plafond de la boîte. C’est un signal que l’actif a été déplacé vers un « nouvel étage ». Placez immédiatement un arrêt sous le nouveau plancher du caisson.
* **Sortie :** Le prix est divisé en dessous du plancher de la boîte.
* **Edge :** Excellent pour les tendances paraboliques tout en ignorant les secousses mineures à l'intérieur des boîtes.
### Indice Elder-Ray (elder_ray)
La stratégie des « rayons X du marché » d’Alexander Elder.
* **Type :** Suivi de tendance + Momentum.
* **Logique :** Utilise EMA(13) comme consensus de valeur et deux composants : `Bull Power` (Élevé - EMA) et `Bear Power` (Faible - EMA).
* **Entrée :** Tendance haussière (pente ascendante de l'EMA) **et** `Bear Power` est en dessous de zéro mais en hausse (affaiblissement des ours). Achetez le retrait.
* **Sortie :** `Bull Power` atteint un sommet historique et commence à baisser.
* **Bord :** Sépare la force interne du taureau et de l'ours.
### Centre de gravité (cog_ehlers)
L'oscillateur à décalage zéro de John Ehlers.
* **Type :** Inversion.
* **Logique :** Ehlers a utilisé une formule physique du centre de gravité pour trouver les points tournants. L'indicateur ressemble à une onde sinusoïdale lisse et peut « prédire » les inversions avec un décalage minimal.
* **Entrée :** COG passe au-dessus de sa ligne de signal (Lag 1).
* **Sortie :** La croix opposée.
* **Edge :** L'un des outils les plus précis pour les marchés latéraux. Dans les tendances, il peut se terminer plus tôt, c'est pourquoi un filtre de tendance est recommandé.
### Entropie de Shannon (entropy_chaos)
Utiliser la théorie de l’information pour mesurer le chaos du marché.
* **Type :** Filtre de régime de marché.
* **Logique :** L'entropie de Shannon mesure l'incertitude.
    * Entropie élevée = chaos ; le prix est imprévisible (gamme/bruit).
    * Faible entropie = ordre ; forte tendance directionnelle.
* **Entrée :** L'entropie tombe en dessous d'un seuil (le marché est devenu ordonné) + le prix est supérieur à une moyenne mobile.
* **Sortie :** Pics d'entropie (le chaos commence).
* **Edge :** Une façon mathématiquement fondée de dire : "Je ne négocie pas parce que le marché est ivre en ce moment."
### Indice de vigueur relative (rvi_trend)
Énergie du mouvement des prix.
* **Type :** Élan.
* **Logique :** Basée sur l'idée que sur les marchés haussiers, les clôtures ont tendance à être supérieures aux ouvertures. RVI adoucit ces valeurs et ressemble au stochastique, mais est basé sur « l'énergie » des bougies plutôt que sur la plage.
* **Entrée :** RVI passe au-dessus de sa ligne de signal.
* **Sortie :** Traversez en bas.
* **Edge :** Confirme la durabilité de la tendance. Si le prix augmente mais que le RVI diminue (divergence), la tendance peut être faible.
### VSTOP (arrêt de volatilité) (vstop_trend)
Stratégie de suivi basée sur la volatilité.
* **Type :** Fin (Tendance).
* **Logique :** Calculez une ligne d'arrêt à `N * ATR` loin des prix extrêmes. La ligne se déplace uniquement dans le sens de la tendance, jamais en arrière.
* **Entrée :** Clôture au-dessus de la ligne VSTOP (elle bascule sous le prix et devient support).
* **Sortie :** Le prix touche ou clôture en dessous de VSTOP.
* **Edge :** Une approche pure de gestion des sorties qui vous maintient dans la tendance jusqu'à ce que la volatilité brise la protection. Semblable à SuperTrend, mais avec un calcul de maxima différent.
### Que choisir ensuite ?
Pour la prochaine phase de mise en œuvre (pour compléter votre portefeuille), je recommande :
1. **k-Nearest Neighbours (knn_ml)** — ajoute une **logique IA** simple à votre bot sans bibliothèques lourdes. Une approche très moderne.
2. **Darvas Box** — un **classique** qui fonctionne bien sur les pièces « à la mode » lors de forts mouvements haussiers.
3. **Centre de gravité** — une arme puissante pour les **marchés de gamme**, où les stratégies de tendance ont tendance à perdre de l'argent.
### Indicateur d'élan de compression (lazybear_squeeze)
La légendaire stratégie TradingView (par LazyBear) basée sur les idées de John Carter.
* **Type :** Cassation de la volatilité + Momentum.
* **Logique :** Combine les bandes de Bollinger et les canaux Keltner.
    * **Phase « Squeeze » :** Les bandes de Bollinger se trouvent à l'intérieur du canal Keltner (points noirs). Le marché stocke de l’énergie.
    * **Phase « Release » :** Les bandes se déplacent en dehors du canal.
* **Entrée :** Fin de la compression (sortie de la plage) **et** l'histogramme de l'élan est au-dessus de zéro et en hausse.
* **Quitter :** L'histogramme Momentum change de couleur (commence à baisser) ou descend en dessous de zéro.
* **Edge :** Un système visuellement simple qui capture les mouvements post-compression les plus forts.
### Stratégie d'exposant Hurst (hurst_exponent)
Une stratégie mathématique qui détermine la « mémoire » du marché.
* **Type :** Adaptatif (changeur de régime).
* **Logique :** L'exposant de Hurst (H) identifie la nature du marché :
    * H > 0,5 : tendance (persistante).
    * H < 0,5 : Télémétrie (retour à la moyenne).
* **Entrée :**
    * Si H > 0,6 : utilisez une logique de cassure (par exemple, franchissez le plus haut des N derniers jours).
    * Si H < 0,4 : utilisez une logique de contre-tendance (acheter les plus bas, vendre les plus hauts).
* **Sortie :** Changements de régime Hurst.
* **Edge :** Une « stratégie de stratégies » : elle ne devine pas la direction, elle détermine *comment* trader en ce moment.
### Tendance Renko synthétique (renko_synthetic)
Utiliser des « briques » Renko au lieu de bougies pour supprimer le bruit du temps.
* **Type :** Action sur les prix (indépendant du temps).
* **Logique :** Construisez virtuellement des briques de taille fixe (par exemple, 1 % du prix). Une nouvelle brique n'apparaît que si le prix parcourt cette distance ; les petites fluctuations sont ignorées.
* **Entrée :** Deux briques vertes d'affilée après une série de briques rouges (inversion de tendance à la hausse).
* **Sortie :** Une brique rouge apparaît (inversion vers le bas).
* **Edge :** Permet au bot de conserver les tendances pendant des semaines, en ignorant les côtelettes latérales qui semblent effrayantes sur les bougies mais qui constituent une ligne plate sur Renko.
### Gann Hi-Lo Activateur (gann_hilo)
Stratégie de suivi des tendances simple mais efficace inspirée de Gann.
* **Type :** Tendance / Trailing Stop.
* **Logique :** Un simple SMA(3) construit sur les hauts dans les tendances baissières et sur les bas dans les tendances haussières.
* **Entrée :** Clôture au-dessus de la ligne Gann Activator (elle retourne sous le prix).
* **Sortie :** Fermez en dessous de la ligne.
* **Edge :** Un stop suiveur mécanique strict. Idéal pour les altcoins avec des pompes pointues.
### Rejet du POC du profil de volume (vpvr_poc)
Négocier à partir de niveaux de volume horizontaux.
* **Type :** Niveaux de support/résistance.
* **Logique :** Calculer le profil de volume au cours des N derniers jours. Trouvez le POC (Point of Control) — le prix avec le volume le plus échangé — le « juste prix ».
* **Entrée :**
    1. Le prix s’approche du POC par le haut.
    2. Le prix touche le POC et rebondit (la bougie clôture plus haut).
    3. C'est un test de support – allez-y longtemps.
* **Quitter :** Pourcentage de profit fixe ou atteinte du prochain nœud à faible volume.
* **Edge :** Échangez aux côtés de grands acteurs défendant les positions accumulées au POC.
### Rebond DCA (Dollar Cost Averaging) (dca_martingale)
Stratégie de gestion du capital populaire dans les plateformes de bots (3Commas, etc.).
* **Type :** Moyenne / Grille.
* **Logique :** Utilise des rachats au lieu d'un stop loss.
* **Entrée :** RSI < 30 (première entrée avec 20% du capital).
* **Gestion :** Si le prix baisse de 2 %, achetez 30 % supplémentaires. S'il baisse encore de 3 %, achetez 50 % (martingale/moyenne).
* **Sortie :** Lorsque le prix d'entrée moyen + 1 % de profit est atteint (au rebond).
* **Edge :** Peut clôturer des transactions avec profit même dans un marché baissier (via des rebonds), mais le risque de liquidation est élevé si le prix baisse sans recul (vous avez besoin d'un stop loss pour l'ensemble du « sac »).
### Trading sur triple écran (triple_screen)
Le système classique d’Alexander Elder.
* **Type :** Multi-périodes (Tendance + Correction).
* **Logique :** Utilise trois « écrans » (ou multiplicateurs de délais sur un graphique).
    1. **Marée (long terme) :** Le MACD sur la période x5 montre la tendance haussière.
    2. **Vague (mi-terme) :** Le StochRSI sur la période actuelle est suracheté (un recul par rapport à la tendance).
    3. **Ondulation (entrée) :** Rupture du plus haut de la bougie précédente (lorsque le retrait se termine).
* **Entrée :** Lorsque la « Marée » est montante et que la « Vague » cesse de descendre.
* **Sortie :** Basé sur des signaux de délais inférieurs.
* **Edge :** L'un des filtres commerciaux les plus fiables : négociez avec la tendance à long terme, mais achetez des baisses temporaires.
## Stratégies combinées
Excellente idée. Les **Stratégies combinées** constituent le prochain niveau d'évolution pour un robot de trading. Les indicateurs uniques produisent souvent de faux signaux : les stratégies de suivi de tendance s'étendent dans les fourchettes et les oscillateurs (RSI) sortent trop tôt des tendances.
La combinaison de signaux vous permet de filtrer les entrées selon un principe simple : **« Filtre (tendance globale) + Déclencheur (synchronisation des entrées) »**.
### Méthode triple écran (triple_screen_custom)
Une adaptation de style Elder combinant Trend, Wave et Momentum.
* **Composants :** EMA (200) + RSI (14) + MACD.
* **Logique :**
    1. **Filtre :** Le prix doit être **supérieur** à l'EMA 200 (tendance haussière mondiale).
    2. **Pullback :** Le RSI doit tomber en dessous de 50 (correction locale, « remise »).
    3. **Déclencheur :** L'histogramme MACD commence à augmenter (inversion de l'élan vers le haut).
* **Pourquoi c'est cool :** Vous achetez avec la tendance, pas au sommet, et seulement après que le recul soit confirmé.
### Bollinger Breakout + IMF (bb_mfi_breakout)
Casse de volatilité confirmée par le flux monétaire.
* **Composants :** Bandes de Bollinger + Indice de flux monétaire.
* **Logique :** Les éruptions BB peuvent simuler ; le volume aide.
    1. **Déclencheur :** Fermez au-dessus de la bande de Bollinger supérieure.
    2. **Filtre :** IMF > 60 et en hausse (argent entrant). Si le prix dépasse BB mais que l’IMF chute, il s’agit probablement d’une contrefaçon.
* **Sortie :** Le prix revient à l'intérieur du canal Bollinger.
* **Pourquoi c'est cool :** Filtre les pompes « vides » sans volume réel d'acheteur.
### Nuage Ichimoku + MACD (ichimoku_macd)
Classique japonais avec confirmation occidentale.
* **Composants :** Ichimoku Kinko Hyo + MACD.
* **Logique :**
    1. **Filtre (Kumo breakout) :** Fermez **au-dessus** le nuage Ichimoku.
    2. **Déclencheur :** Les lignes MACD se croisent (croix dorée).
* **Quitter :** Price entre à nouveau dans le cloud.
* **Pourquoi c'est cool :** Les éruptions nuageuses signifient souvent un changement de tendance à long terme ; MACD aide à entrer tôt.
### ADX + SAR parabolique (adx_psar)
Chasse les tendances fortes : « Ne négociez pas s’il n’y a pas de force. »
* **Composants :** ADX + SAR parabolique.
* **Logique :** Le SAR parabolique tire constamment (y compris à distance). ADX corrige cela.
    1. **Filtre :** ADX > 25 (phase active ; pas de plage).
    2. **Déclencheur :** les points SAR basculent **en dessous** du prix.
* **Sortie :** Les points SAR se retournent au-dessus du prix.
* **Pourquoi c'est cool :** Vous ignorez les marchés faibles et vous vous engagez uniquement lorsque la « fusée » démarre.
### SMA 50/200 Pullback (golden_cross_pullback)
Trading « Croix d'Or » plus intelligent.
* **Composants :** SMA 50 + SMA 200.
* **Logique :** L'achat du cross est souvent suivi d'un retrait qui vous empêche de sortir. Au lieu de cela :
    1. **Condition :** SMA 50 est supérieur à SMA 200 (un croisement s'est déjà produit).
    2. **Déclencheur :** Le prix touche le SMA 50 par le haut et referme au-dessus (rebond du support).
* **Sortie :** Clôture en dessous de SMA 200.
* **Pourquoi c'est cool :** Entrée à moindre risque avec un stop plus serré : achetez la correction, pas le battage médiatique.
### Régression linéaire + Z-Score (stats_arbitrage)
Une combinaison mathématique (réversion moyenne sous stéroïdes).
* **Composants :** Pente de régression linéaire + Z-Score.
* **Logique :**
    1. **Filtre :** Pente de régression > 0 (espérance positive).
    2. **Déclencheur :** Z-Score < -2 (écart à la baisse de 2 sigma par rapport à la ligne de régression).
* **Quitter :** Le Z-Score revient à 0.
* **Pourquoi c'est cool :** Une approche scientifique : achetez un actif qui croît *à l'échelle mondiale* mais qui est *localement* injustement bon marché.
### Méthode triple écran (triple_screen_ema)
Une adaptation algo de la méthode « Triple Screen » de Elder.
* **Logique :** Utilise trois types d'indicateurs :
    1. **Marée (long terme) :** Le prix doit être **supérieur** à EMA 200 (ou EMA 100). Tendance haussière mondiale.
    2. **Vague (Pullback) :** Le RSI (14) doit descendre en dessous de 50 (ou 45). Correction temporaire.
    3. **Ondulation (entrée) :** L'histogramme MACD commence à augmenter (ou les lignes MACD se croisent). Le retrait se termine ; le mouvement vers le haut reprend.
* **Sortie :** RSI > 70 ou MACD croise vers le bas.
* **Pourquoi c'est cool :** Conservateur et robuste. Filtre les transactions à contre-tendance les plus dangereuses.
### SMA Golden Cross Pullback (sma_pullback)
Trading croisé MA plus intelligent : pas sur le croisement, mais sur le retest.
* **Logique :**
    1. **Condition :** SMA 50 est supérieur à SMA 200 (Golden Cross est déjà arrivé).
    2. **Déclencheur :** Le prix touche le SMA 50 par le haut et rebondit (prochaine bougie verte).
* **Sortie :** Clôture en dessous de SMA 200 (casse de tendance) ou d'un take profit fixe.
* **Pourquoi c'est cool :** Acheter directement à la croix est souvent perdant parce que le marché est déjà surchauffé. Le nouveau test donne un risque plus serré et de meilleures chances.
### SuperTrend + StochRSI (super_stoch)
Combine un indicateur de tendance supérieur avec un oscillateur rapide pour les entrées « sniper ».
* **Logique :**
    1. **Filtre (Trend) :** SuperTrend (basé sur ATR) doit être vert (prix au-dessus de la ligne). Pas de short.
    2. **Déclencheur (entrée) :** StochRSI tombe en survente (< 20) et croise (K croise D).
* **Sortie :** StochRSI entre en surachat (> 80) ou SuperTrend devient rouge.
* **Pourquoi c'est cool :** Négocie avec la tendance mais entre dans des replis locaux, améliorant ainsi le rapport risque/récompense.
### Bollinger Breakout + MFI (bb_mfi)
Cassation de la volatilité avec confirmation du volume (« argent intelligent »).
* **Logique :**
    1. **Déclencheur :** Clôture au-dessus de la bande de Bollinger **supérieure** (expansion de la volatilité).
    2. **Filtre (Volume) :** MFI > 60 et en hausse. Confirme que la cassure est soutenue par des entrées réelles.
* **Sortie :** Refermez à l'intérieur du canal (sous la bande supérieure) ou le MFI tombe.
* **Pourquoi c'est cool :** Aide à distinguer une vraie pompe d'un piège de teneur de marché (faux).
### Régression linéaire + Z-Score (linreg_zscore)
Réversion moyenne 2.0 (statistiques pures).
* **Logique :**
    1. **Filtre (direction) :** La pente de régression (plus de 50 à 100 bougies) est positive.
    2. **Déclencheur (déviation) :** Le score Z tombe en dessous de -2 (statistiquement bon marché par rapport à sa propre tendance).
* **Quitter :** Le Z-Score revient à 0 (ligne médiane).
* **Pourquoi c'est cool :** Pas de suppositions sur les bougies : de pures statistiques. Achetez un actif en hausse à l’échelle mondiale et bénéficiant d’une réduction locale.
### Le système de tendances "Forteresse" (trend_momentum_volatility_volume)
Le système « Forteresse » : quatre niveaux de protection contre les transactions stupides.
* **Composants :** EMA 200 + MACD + Bandes de Bollinger + OBV.
* **Logique :**
    1. **Filtre global :** Prix > EMA 200 (négociez uniquement la tendance haussière).
    2. **Volatilité :** Le prix touche ou casse la ligne médiane du BB (retrait au juste prix).
    3. **Volume :** L'OBV est supérieur à sa MA (l'argent ne part pas pendant le retrait).
    4. **Déclencheur :** L'histogramme MACD passe du rouge au vert (l'élan revient).
* **Quitter :** Touchez la croix supérieure BB ou MACD vers le bas.
* **Pourquoi c'est cool :** Vous achetez uniquement des retraits confirmés en volume dans une tendance haussière renforcée.
### Le "cuir chevelu parfait" (heikin_ashi_ema_stochrsi_atr)
Scalping filtré par le bruit.
* **Composants :** Heikin Ashi (virtuel) + EMA 50 + EMA 100 + StochRSI + ATR.
* **Logique :**
    1. **Tunnel :** L'EMA 50 est supérieure à l'EMA 100 et la distance augmente (forte tendance).
    2. **Motif :** La bougie Heikin Ashi passe du rouge au vert.
    3. **Déclencheur :** StochRSI passe en dessous de 40.
    4. **Stop loss :** Fixé à 2xATR dès l'entrée.
* **Sortie :** Heikin Ashi passe au rouge.
* **Pourquoi c'est cool :** Heikin Ashi supprime le bruit ; le double EMA empêche le scalping contre un train.
### Divergence Hunter Pro (rsi_cci_mfi_ema)
Chasse aux inversions avec triple confirmation (convergence des oscillateurs).
* **Composants :** EMA 200 + RSI (14) + CCI (20) + MFI (14).
* **Logique :**
    1. **Contexte :** Prix supérieur à EMA 200 (à la recherche d'un fond de correction local).
    2. **Synchronisation :**
        * RSI < 30 (prix survendu).
        * CCI < -100 (écart anormal).
        * MFI < 20 (volume survendu / panique).
    3. **Entrée :** Les trois indicateurs apparaissent ensemble.
* **Sortie :** L'un des trois atteint le surachat.
* **Pourquoi c'est cool :** Le risque que trois oscillateurs mathématiques différents (prix, écart, volume) échouent tous en même temps est faible.
### Compression avancée (bollinger_keltner_momentum_adx)
Une variante avancée de TTM Squeeze pour des mouvements explosifs.
* **Composants :** Bandes de Bollinger + Canaux Keltner + Momentum + ADX.
* **Logique :**
    1. **Squeeze :** Bandes de Bollinger entièrement à l’intérieur du canal Keltner – volatilité à un niveau critique.
    2. **Accumulation :** ADX < 20 (le marché « dort »).
    3. **Déclencheur :** Les bandes de Bollinger quittent le canal Keltner + ADX commence à augmenter fortement.
    4. **Direction :** Momentum > 0.
* **Sortie :** L'élan commence à baisser.
* **Pourquoi c'est cool :** On gagne beaucoup d'argent lorsque le marché passe du sommeil à l'explosion ; ce combo cible cette transition.
### Ichimoku "Full House" (tenkan_kijun_cloud_chikou_rsi)
Utilisation de l'ensemble complet de signaux Ichimoku plus un filtre de surachat.
* **Composants :** Ichimoku Cloud (toutes les lignes) + RSI.
* **Logique :**
    1. ** Breakout : ** Fermez au-dessus du Cloud (breakout Kumo).
    2. **Cross :** Tenkan croise Kijun de bas en haut (TK Cross).
    3. **Confirmation en retard :** Chikou Span est au-dessus du prix il y a 26 périodes (confirmation de la tendance).
    4. **Filtre :** RSI < 70 (marché non surchauffé).
* **Sortie :** Tenkan passe en dessous de Kijun ou le prix entre dans le cloud.
* **Pourquoi c'est cool :** L'un des systèmes japonais les plus anciens et les plus respectés. L'utilisation de toutes les pièces rend les entrées plus rares mais plus fortes.
### Stratégie institutionnelle VWAP (vwap_ema_volume_profile_rsi)
Négociez « comme une baleine » en utilisant un prix pondéré en fonction du volume.
* **Composants :** VWAP + EMA 50 + Profil de volume fixe (POC) + RSI.
* **Logique :**
    1. **Tendance :** Prix > EMA 50.
    2. **Valeur :** Le prix recule vers le VWAP (retour au prix « juste » du jour).
    3. **Niveau :** Le prix se situe dans une zone à volume élevé (protection POC Volume Profile).
    4. **Déclencheur :** Le RSI passe de 40 à 50.
* **Sortie :** Le prix s'éloigne trop du VWAP (mouvement de l'écart type).
* **Pourquoi c'est cool :** VWAP est utilisé par des algorithmes institutionnels. Trader du VWAP signifie négocier avec eux, pas contre eux.
### Le "Trend Sniper" (parabolic_sar_adx_ema_macd)
Capturer les tendances incontrôlables (exécutions paraboliques).
* **Composants :** SAR parabolique + ADX + EMA 100 + MACD.
* **Logique :**
    1. **Global :** Prix > EMA 100.
    2. **Force :** ADX > 30 et en hausse (tendance très forte).
    3. **Déclencheur :** Les points SAR sont inférieurs au prix.
    4. **Filtre :** MACD > 0 et histogramme croissant.
* **Règle spéciale :** Pendant que l'ADX est en hausse, ignorez les petits signaux de vente.
* **Sortie :** L'ADX commence à baisser (la tendance s'affaiblit) OU le SAR s'inverse.
* **Pourquoi c'est cool :** Tire le maximum des rallyes paraboliques (par exemple, BTC 20k → 30k) sans sortir à la première bougie rouge.
### Le système "Whale Trail" (volume_trend_value)
À la suite du grand joueur (« baleine »).
* **Composants :** VWAP + Chaikin Money Flow (CMF) + EMA 200 + Points pivots.
* **Logique :**
    1. **Tendance mondiale :** Prix > EMA 200.
    2. **Prix équitable :** Le prix est supérieur (ou nouveau test à partir d'en haut) au VWAP — les acheteurs contrôlent l'enchère intrajournalière.
    3. **Flux d'argent :** CMF > 0 et en hausse (accumulation).
    4. **Déclencheur :** Rupture de la résistance pivot la plus proche (R1/R2).
* **Sortie :** Le CMF tombe en dessous de zéro ou le prix clôture en dessous du VWAP.
* **Pourquoi c'est cool :** Vous n'échangez pas de « modèles » ; vous négociez des flux monétaires institutionnels réels.
### L'inversion de la « bande élastique » (mean_reversion_trend_filter)
Attraper de profonds replis dans une forte tendance haussière (la « fronde »).
* **Composants :** Canaux Keltner + RSI (2) + SMA 100 + Modèle engloutissant.
* **Logique :**
    1. **Filtre :** Pente du SMA 100 strictement ascendante (forte tendance haussière).
    2. **Étendue :** Le prix dépasse la ligne inférieure de Keltner (écart extrême).
    3. **Survente :** Le RSI(2) tombe en dessous de 5.
    4. **Déclencheur :** La bougie se referme à l'intérieur du canal + un engloutissement haussier se forme.
* **Sortie :** Le prix touche la ligne Keltner médiane ou supérieure.
* **Pourquoi c'est cool :** Taux de victoire très élevé. Vous achetez de la peur (dump) sur fond de cupidité (tendance haussière).
### Le "Tsunami Guppy" (gmma_adx)
Une stratégie de tendance visuelle utilisant plusieurs moyennes mobiles (GMMA).
* **Composants :** GMMA (12 MA : 6 rapides, 6 lentes) + ADX.
* **Logique :**
    1. **Compression :** Les groupes MA rapides et lents convergent (baisse de la volatilité ; compression du marché).
    2. **Tsunami (expansion) :** Les MA rapides se séparent brusquement vers le haut des MA lentes.
    3. **Confirmation :** Les MA lentes commencent également à se développer (la tendance devient durable).
    4. **Filtre :** ADX > 20 et croissant.
* **Sortie :** Les MA rapides commencent à traverser les MA lentes (compression).
* **Pourquoi c'est cool :** Capture les phases de tendance explosives et ignore les reculs mineurs pendant que « l'école » MA pointe vers le haut.
### Le canal "Régression Quantique" (linear_reg_pearson_r_atr)
Trading de canaux mathématiquement fondé.
* **Composants :** Canal de régression linéaire (100) + Coefficient de corrélation de Pearson (r) + Stop suiveur ATR.
* **Logique :**
    1. **Qualité de la tendance :** Pearson r > 0,7 (le prix se comporte comme une ligne ascendante – croissance stable sans chaos).
    2. **Achetez pas cher :** Le prix touche la limite inférieure du canal de régression (2 écarts types).
    3. **Déclencheur :** Le prix rebondit à partir de la limite inférieure.
* **Sortie :** Le prix touche la limite supérieure ou les déclencheurs d'arrêt ATR.
* **Pourquoi c'est cool :** Négocie uniquement les « belles tendances stables » et filtre les graphiques désordonnés grâce aux mathématiques.
### Le "Chaos doré" (ichimoku_bill_williams_fractals_ao)
Une combinaison de sagesse orientale et de théorie du chaos.
* **Composants :** Ichimoku Cloud + Fractales + Awesome Oscillator (AO).
* **Logique :**
    1. **Zone de sécurité :** Prix > Ichimoku Cloud.
    2. **Énergie :** AO est vert et supérieur à zéro.
    3. **Déclencheur :** Le prix brise la dernière fractale ascendante (plus haut local).
* **Sortie :** Fermez en dessous d'Ichimoku Tenkan ou AO devient rouge (dans l'ordre).
* **Pourquoi c'est cool :** Les fractales donnent un prix d'entrée précis (ordre en attente), et Ichimoku garantit que vous ne combattez pas la tendance mondiale.
### Le système "Velocity" (hull_ma_laguerre_rsi_volatility_stop)
Un système de scalping ultra-rapide pour les paires volatiles (ETH, SOL).
* **Composants :** Moyenne mobile de coque (HMA) + Laguerre RSI + Volatility Stop (VSTOP).
* **Logique :**
    1. **Vitesse :** Le HMA passe au vert (réaction instantanée à la hausse).
    2. **Momentum :** Laguerre RSI passe au-dessus de 0,2 (sortie par le bas).
    3. **Protection :** Le prix est supérieur à VSTOP.
* **Sortie :** Le HMA bascule en rouge ou les pauses VSTOP.
* **Pourquoi c'est cool :** Les indicateurs classiques sont en retard. Ce combo utilise des outils à décalage minimal pour être le premier à se lancer.
### La "Confluence de Fibonacci" (auto_fibs_ema_50_stochastic)
Trading de retrait automatisé vers le « nombre d’or ».
* **Composants :** Retracement automatique de Fibonacci + EMA 50 + Stochastique.
* **Logique :**
    1. **Contexte :** Prix > EMA 50.
    2. **Niveau :** Le prix se corrige à Fib 0,5 ou 0,618 (« Golden Pocket ») de la dernière impulsion.
    3. **Déclencheur :** Le stochastique est survendu et se croise.
* **Sortie :** Cible à 0 (plus haut précédent) ou -0,27 (extension Fib).
* **Pourquoi c'est cool :** L'une des configurations discrétionnaires les plus populaires : le bot automatise la recherche des entrées idéales.
## Recommandations
**Recommandation générale :**
Concentrez-vous sur 3 à 5 stratégies qui couvrent différents régimes de marché (tendance, range, momentum, volume). Donnez la priorité aux systèmes multifactoriels, puis aux filtres combinés puissants, et ensuite seulement aux indicateurs et modèles uniques.
