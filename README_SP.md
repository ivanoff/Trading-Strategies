# Estrategias comerciales
- [Estrategias](#strategies)
  - [RSI + Bandas de Bollinger (rsi_bb)](#rsi--bollinger-bands-rsi_bb)
  - [MACD (macd)](#macd-macd)
  - [RSI Básico (rsi_basic)](#rsi-basic-rsi_basic)
  - [Cruce SMA (sma_cross)](#sma-crossover-sma_cross)
  - [Apretón de la banda de Bollinger (bb_squeeze)](#bollinger-band-squeeze-bb_squeeze)
  - [Ruptura del canal Donchian / Comercio de tortugas (donchian)](#donchian-channel-breakout--turtle-trading-donchian)
  - [Ruptura de la nube de Ichimoku (ichimoku)](#ichimoku-cloud-breakout-ichimoku)
  - [ADX + DMI (adx_dmi)](#adx--dmi-adx_dmi)
  - [Tendencia OBV (obv_trend)](#obv-trend-obv_trend)
  - [Estrategia SuperTrend (supertendencia)](#supertrend-strategy-supertrend)
  - [Tendencia EMA + RSI estocástico (ema_stoch)](#ema-trend--stochastic-rsi-ema_stoch)
  - [Estrategia SAR Parabólico (psar)](#parabolic-sar-strategy-psar)
  - [Índice de flujo monetario (IMF) (mfi_div)](#money-flow-index-mfi-mfi_div)
  - [Cruce de TEMA (tema_cross)](#tema-crossover-tema_cross)
  - [Retroceso del canal Keltner (keltner_pullback)](#keltner-channel-pullback-keltner_pullback)
  - [Oscilador impresionante (ao_saucer)](#awesome-oscillator-ao_saucer)
  - [Corrección CCI (cci_correction)](#cci-correction-cci_correction)
  - [Tendencia VWAP (vwap_cross)](#vwap-trend-vwap_cross)
  - [RSI estocástico (stoch_rsi)](#stochastic-rsi-stoch_rsi)
  - [Índice de fuerza del anciano (elder_force)](#elders-force-index-elder_force)
  - [Williams %R (williams_r)](#williams-r-williams_r)
  - [MA adaptativo de Kaufman (kama_trend)](#kaufmans-adaptive-ma-kama_trend)
  - [Tasa de cambio (roc)](#rate-of-change-roc)
  - [Desglose del canal ATR (volty_channel)](#atr-channel-breakout-volty_channel)
  - [Pendiente de regresión lineal (lin_reg)](#linear-regression-slope-lin_reg)
  - [Flujo de dinero de Chaikin (cmf_trend)](#chaikin-money-flow-cmf_trend)
  - [Indicador de vórtice (vórtice)](#vortex-indicator-vortex)
  - [Estrategia Aroon (aroon)](#aroon-strategy-aroon)
  - [TRIX (Promedio exponencial triple) (trix_strat)](#trix-triple-exponential-average-trix_strat)
  - [Curva de Coppock (coppock)](#coppock-curve-coppock)
  - [Índice de canales de productos básicos (cci_trend)](#commodity-channel-index-cci_trend)
  - [Tendencia de media móvil del casco (hma_trend)](#hull-moving-average-trend-hma_trend)
  - [Estrategia de puntuación Z (z_score)](#z-score-strategy-z_score)
  - [VWMA frente a SMA (vwma_cross)](#vwma-vs-sma-vwma_cross)
  - [Connors RSI 2 (rsi_2)] (#connors-rsi-2-rsi_2)
  - [Fractales de Williams (fractal_breakout)](#williams-fractals-fractal_breakout)
  - [Bandas de Fibonacci Bollinger (fib_bands)](#fibonacci-bollinger-bands-fib_bands)
  - [Estrategia de salida de la lámpara de araña (chandelier_trend)](#chandelier-exit-strategy-chandelier_trend)
  - [Ruptura de la barra interior (inside_bar)](#inside-bar-breakout-inside_bar)
  - [TD Secuencial (simplificado) (td_seq)](#td-sequential-simplified-td_seq)
  - [Transformación de Ehlers Fisher (fisher_trans)](#ehlers-fisher-transform-fisher_trans)
  - [Divergencia RSI (rsi_div)] (#rsi-divergence-rsi_div)
  - [Tendencia Heikin Ashi (ha_trend)](#heikin-ashi-trend-ha_trend)
  - [Canal de desviación estándar (std_channel)](#standard-deviation-channel-std_channel)
  - [Inversión de puntos de pivote (pivot_rev)](#pivot-points-reversal-pivot_rev)
  - [Cocodrilo Williams (cocodrilo)](#williams-alligator-alligator)
  - [Patrón envolvente (engulfing_candle)](#engulfing-pattern-engulfing_candle)
  - [McGinley dinámica (mcginley)](#mcginley-dynamic-mcginley)
  - [Empuje dual (dual_thrust)](#dual-thrust-dual_thrust)
  - [Oscilador de impulso Chande (cmo_strat)](#chande-momentum-oscillator-cmo_strat)
  - [Facilidad de movimiento (eom_trend)](#ease-of-movement-eom_trend)
  - [Saber algo seguro (KST) (kst_momentum)](#know-sure-thing-kst-kst_momentum)
  - [Ciclo de tendencia Schaff (stc_cycle)](#schaff-trend-cycle-stc_cycle)
  - [Filtro de índice de agitación + EMA (chop_ema)](#choppiness-index-filter--ema-chop_ema)
  - [Promedio móvil adaptativo fractal (frama_trend)](#fractal-adaptive-moving-average-frama_trend)
  - [Tendencia de precios por volumen (vpt_cross)](#volume-price-trend-vpt_cross)
  - [Laguerre RSI (laguerre_rsi)](#laguerre-rsi-laguerre_rsi)
  - [Pinbar (Martillo/Estrella fugaz) (pinbar_reversal)](#pinbar-hammershooting-star-pinbar_reversal)
  - [Oscilador de precios sin tendencia (dpo_cycle)](#detrended-price-oscillator-dpo_cycle)
  - [Ruptura del rango de apertura (orb_strat)](#opening-range-breakout-orb_strat)
  - [Índice de facilitación del mercado (bw_mfi)](#market-facilitation-index-bw_mfi)

- [Línea psicológica (psy_line)] (#psychological-line-psy_line)
  - [Bolsillo dorado de Fibonacci (fib_golden)](#fibonacci-golden-pocket-fib_golden)
  - [Tres soldados blancos / Tres cuervos negros (candle_patterns)](#three-white-soldiers--three-black-crows-candle_patterns)
  - [Índice de caminata aleatoria (rwi_trend)](#random-walk-index-rwi_trend)
  - [Estrategia del índice de úlceras (ulcer_strat)](#ulcer-index-strategy-ulcer_strat)
  - [k-Coincidencia de patrones de vecinos más cercanos (kNN) (knn_ml)](#k-nearest-neighbors-knn-pattern-matching-knn_ml)
  - [Teoría de la caja de Darvas (darvas_box)](#darvas-box-theory-darvas_box)
  - [Índice Elder-Ray (elder_ray)](#elder-ray-index-elder_ray)
  - [Centro de gravedad (cog_ehlers)](#center-of-gravity-cog_ehlers)
  - [Shannon Entropía (entropy_chaos)](#shannon-entropy-entropy_chaos)
  - [Índice de vigor relativo (rvi_trend)](#relative-vigor-index-rvi_trend)
  - [VSTOP (parada de volatilidad) (vstop_trend)](#vstop-volatility-stop-vstop_trend)
  - [¿Qué elegir a continuación?](#what-to-pick-next)
  - [Indicador de impulso de compresión (lazybear_squeeze)](#squeeze-momentum-indicator-lazybear_squeeze)
  - [Estrategia del exponente de Hurst (hurst_exponent)](#hurst-exponent-strategy-hurst_exponent)
  - [Tendencia Renko sintética (renko_synthetic)](#synthetic-renko-trend-renko_synthetic)
  - [Activador Gann Hi-Lo (gann_hilo)](#gann-hi-lo-activator-gann_hilo)
  - [Rechazo de POC del perfil de volumen (vpvr_poc)](#volume-profile-poc-rejection-vpvr_poc)
  - [Rebote del DCA (promedio del costo en dólares) (dca_martingale)](#dca-rebound-dollar-cost-averaging-dca_martingale)
  - [Comercio de pantalla triple (triple_screen)](#triple-screen-trading-triple_screen)
- [Estrategias combinadas](#combined-strategies)
  - [Método de pantalla triple (triple_screen_custom)](#triple-screen-method-triple_screen_custom)
  - [Ruptura de Bollinger + IMF (bb_mfi_breakout)](#bollinger-breakout--mfi-bb_mfi_breakout)
  - [Nube Ichimoku + MACD (ichimoku_macd)](#ichimoku-cloud--macd-ichimoku_macd)
  - [ADX + SAR parabólico (adx_psar)](#adx--parabolic-sar-adx_psar)
  - [Retroceso SMA 50/200 (golden_cross_pullback)](#sma-50200-pullback-golden_cross_pullback)
  - [Regresión lineal + puntuación Z (stats_arbitrage)](#linear-regression--z-score-stats_arbitrage)
  - [Método de pantalla triple (triple_screen_ema)](#triple-screen-method-triple_screen_ema)
  - [SMA Golden Cross Pullback (sma_pullback)](#sma-golden-cross-pullback-sma_pullback)
  - [SuperTrend + StochRSI (super_stoch)](#supertrend--stochrsi-super_stoch)
  - [Ruptura de Bollinger + IMF (bb_mfi)](#bollinger-breakout--mfi-bb_mfi)
  - [Regresión lineal + puntuación Z (linreg_zscore)](#linear-regression--z-score-linreg_zscore)
  - [El sistema de tendencias "Fortaleza" (trend_momentum_volatility_volume)](#the-fortress-trend-system-trend_momentum_volatility_volume)
  - [El "Cuero Cabelludo Perfecto" (heikin_ashi_ema_stochrsi_atr)](#the-perfect-scalp-heikin_ashi_ema_stochrsi_atr)
  - [Cazador de divergencias Pro (rsi_cci_mfi_ema)](#divergence-hunter-pro-rsi_cci_mfi_ema)
  - [Squeeze avanzado (bollinger_keltner_momentum_adx)](#advanced-squeeze-bollinger_keltner_momentum_adx)
  - [Ichimoku "Tres" (tenkan_kijun_cloud_chikou_rsi)](#ichimoku-full-house-tenkan_kijun_cloud_chikou_rsi)
  - [Estrategia institucional VWAP (vwap_ema_volume_profile_rsi)](#vwap-institutional-strategy-vwap_ema_volume_profile_rsi)
  - [El "Francotirador de tendencias" (parabolic_sar_adx_ema_macd)](#the-trend-sniper-parabolic_sar_adx_ema_macd)
  - [El sistema "Ruta de las Ballenas" (volume_trend_value)](#the-whale-trail-system-volume_trend_value)
  - [La inversión de la "banda elástica" (mean_reversion_trend_filter)](#the-elastic-band-reversal-mean_reversion_trend_filter)
  - [El "Tsunami Guppy" (gmma_adx)](#the-guppy-tsunami-gmma_adx)
  - [El canal "Regresión cuántica" (linear_reg_pearson_r_atr)](#the-quant-regression-channel-linear_reg_pearson_r_atr)
  - [El "Caos Dorado" (ichimoku_bill_williams_fractals_ao)](#the-golden-chaos-ichimoku_bill_williams_fractals_ao)
  - [El sistema "Velocidad" (hull_ma_laguerre_rsi_volatility_stop)](#the-velocity-system-hull_ma_laguerre_rsi_volatility_stop)
  - [La "Confluencia de Fibonacci" (auto_fibs_ema_50_stochastic)](#the-fibonacci-confluence-auto_fibs_ema_50_stochastic)
- [Recomendaciones](#recommendations)
- [Implementación de la estrategia](#strategy-implementation)
## Estrategias
### RSI + Bandas de Bollinger (rsi_bb)
Una estrategia híbrida que tiene como objetivo captar un punto de reversión ideal mientras filtra señales falsas.
* **Tipo:** Reversión media.
* **Lógica:** Combina volatilidad (Bandas de Bollinger) e impulso (RSI). Las Bandas de Bollinger nos dicen que el precio es estadísticamente "demasiado bajo" (desviado de la norma) y el RSI confirma que los vendedores están agotados.
* **Entrada:** El cierre rompe la banda BB **inferior** y, al mismo tiempo, el RSI está en sobreventa (< 30).
* **Salida:** El precio vuelve a la línea BB **Medio** (SMA 20). No esperamos a la banda superior, porque en un mercado a la baja el objetivo de reversión a la media más seguro es el medio.
* **Borde:** Resuelve el clásico problema de “atrapar cuchillos que caen”. No compras sólo porque es barato; se compra cuando la desviación es extrema y hay confirmación de la debilidad del vendedor.
### MACD (macd)
La estrategia de indicadores más clásica del mundo.
* **Tipo:** Seguimiento de tendencia/Impulso.
* **Lógica:** MACD mide el diferencial entre las EMA rápidas (12) y lentas (26). El histograma muestra la tasa de cambio de ese diferencial.
* **Entrada:** El MACD cruza la línea de señal de abajo hacia arriba (o el histograma pasa de negativo a positivo), lo que significa que el impulso a corto plazo ha superado al de largo plazo.
* **Salida:** La cruz opuesta (de arriba hacia abajo).
* **Borde:** Captura la “parte central” de la tendencia (la mitad del movimiento). Funciona mal en cortes, pero en movimientos fuertes de BTC/ETH puede generar señales confiables.
### RSI Básico (rsi_basic)
Una estrategia básica contra la tendencia.
* **Tipo:** Contratendencia.
* **Lógica:** El mercado se balancea como un péndulo. Si va demasiado lejos en una dirección, tiende a retroceder.
* **Entrada:** El RSI cae por debajo de 30 (sobreventa). Apuestas por un rebote.
* **Salida:** El RSI sube por encima de 70 (sobrecompra).
* **Edge:** El más sencillo de entender; Funciona bien en una amplia gama (mercado lateral).
* **Desventaja:** Peligroso en tendencias fuertes. En caso de caída, el RSI puede permanecer en 20 durante una semana mientras el precio cae otro 50%. Requiere un stop loss obligatorio.
### Cruce SMA (sma_cross)
La estrategia de la “Cruz de Oro”.
* **Tipo:** Seguimiento de tendencias.
* **Lógica:** Utiliza dos medias móviles simples. El Fast SMA reacciona más rápido al precio; la SMA lenta refleja la dirección más amplia.
* **Entrada:** La SMA rápida cruza por encima de la SMA lenta. Una confirmación matemática de que la tendencia se ha vuelto alcista.
* **Salida:** SMA rápido cruza por debajo de SMA lento (“Cruce de la Muerte”).
* **Edge:** Te mantiene en el lado correcto de las principales tendencias. No se perderá un movimiento “a la luna”, a costa de entradas y salidas retrasadas.
### Apretón de la banda de Bollinger (bb_squeeze)
Una estrategia de ruptura después de la calma. Utiliza bandas de Bollinger de forma diferente a `rsi_bb`.
* **Tipo:** Ruptura de volatilidad.
* **Lógica:** Los mercados son cíclicos: a una baja volatilidad le sigue una alta volatilidad. Busque una “compresión” en la que las Bandas de Bollinger se contraigan al mínimo y el Canal Keltner se encuentre dentro de las Bandas de Bollinger.
* **Entrada:** A medida que las bandas comienzan a expandirse y el precio supera el límite superior, vaya en largo.
* **Salir:** El precio vuelve a la línea media o las bandas se contraen nuevamente.
* **Por qué es genial:** Te permite entrar al inicio de un impulso poderoso antes de que sea obvio para todos.
### Fuga del canal Donchian / Comercio de tortugas (donchian)
La clásica estrategia de las “Tortugas”. Sencillo, pero eficaz en plazos más largos (4h, 1d).
* **Tipo:** Fuga.
* **Lógica:** El canal Donchian es el máximo más alto y el mínimo más bajo de los últimos N períodos (por ejemplo, 20).
* **Entrada:** El precio rompe el canal superior (nuevo máximo de 20 velas): largo.
* **Salir:** El precio toca el canal inferior (o la línea media para una toma de ganancias más rápida).
* **Por qué es genial:** Capta todas las tendencias principales. Desventaja: muchas entradas falsas en rangos (las reducciones pueden ser grandes).
### Fuga de la nube de Ichimoku (ichimoku)
Un complejo sistema japonés que muestra soporte, resistencia y tendencia al mismo tiempo.
* **Tipo:** Seguimiento de tendencias.
* **Lógica:** El núcleo es la “Nube” (Kumo).
* **Entrada:** Cerca de la Nube + Tenkan cruza Kijun de abajo hacia arriba (cruz dorada) – señal larga fuerte.
* **Salir:** Cierra por debajo de Kijun o el precio ingresa a la nube.
* **Por qué es genial:** La nube filtra bien el ruido. Si el precio está dentro de la nube, no opere. Ahorra capital en situaciones de incertidumbre.
### ADX + DMI (adx_dmi)
Negocia sólo cuando el mercado tiene fuerza.
* **Tipo:** Filtro de intensidad de tendencia.
* **Lógica:** ADX mide la fuerza de la tendencia (sin dirección). DMI (+DI y -DI) proporciona dirección.
* **Entrada:** Si ADX > 25 (tendencia fuerte) **y** +DI cruza -DI de abajo hacia arriba — Largo. Si ADX < 20: ignore las señales (mercado muerto).
* **Salir:** Cuando +DI vuelve a cruzar por debajo de -DI.
* **Por qué es genial:** Ayuda a evitar el "corte" donde las tarifas y las sierras hacen más daño.
### Tendencia OBV (obv_trend)
Usar el volumen para confirmar el movimiento del precio.
* **Tipo:** Tendencia de volumen.
* **Lógica:** OBV (Volumen en equilibrio) acumula volúmenes de velas. Si el precio aumenta pero el OBV cae, eso es divergencia. Para un bot, es más fácil intercambiar la tendencia OBV en sí.
* **Entrada:** Calcular un MA de OBV. Si el OBV supera su MA (el dinero está entrando), largo.
* **Salir:** OBV cae por debajo de su MA.
* **Por qué es genial:** El precio puede mentir; el volumen (dinero) normalmente no puede. El OBV a menudo comienza a subir antes de que suban los precios.
### Estrategia SuperTrend (supertendencia)
Una de las estrategias criptográficas más populares gracias al mecanismo de trailing stop incorporado.
* **Tipo:** Seguimiento de tendencias.
* **Lógica:** SuperTrend se basa en ATR (volatilidad promedio). Traza una línea por debajo del precio en las tendencias alcistas y por encima del precio en las tendencias bajistas.
* **Entrada:** Cierre por encima de la línea SuperTrend — Largo. Cerrar abajo: Corto (o cerrar el Largo).
* **Salir:** El indicador cambia de color/dirección.
* **Por qué es genial:** Capta grandes movimientos y sigue automáticamente el stop loss con el precio. Funciona muy bien en fuertes tendencias BTC/ETH.
### Tendencia EMA + RSI estocástico (ema_stoch)
Una estrategia híbrida que soluciona el problema principal de `rsi_basic`: comprar “cuchillos que caen”.
* **Tipo:** Oscilador filtrado por tendencias.
* **Lógica:** Utiliza una media móvil “larga” (EMA 200) para definir la tendencia global.
* **Entrada:**
    * Compre SÓLO si el precio está **por encima** de la EMA 200 (tendencia alcista) **y** el RSI estocástico cruza hacia arriba fuera de sobreventa (por ejemplo, <20).
    * Ignore las señales de compra si el precio está por debajo de EMA 200.
* **Salida:** El RSI estocástico entra en sobrecompra (>80) o cruza a la baja.
* **Por qué es genial:** Filtra aproximadamente el 80 % de las señales falsas contra la tendencia.
### Estrategia SAR parabólica (psar)
La clásica estrategia “siempre en el mercado” (Stop and Reverse).
* **Tipo:** Seguimiento/reversión de tendencia.
* **Lógica:** El indicador traza puntos por debajo del precio (tendencia alcista) o por encima del precio (tendencia bajista). Los puntos se ajustan al precio a medida que la tendencia madura.
* **Entrada:** El precio cruza un punto SAR parabólico. Si los puntos se mueven **por debajo** del precio: largo.
* **Salir:** Puntos volteados **arriba** del precio: cerrar en Largo (y opcionalmente abrir en Corto).
* **Pros:** Ideal para tendencias fuertes; te obliga a esperar hasta que haya una pausa explícita.
* **Contras:** En los rangos, los cambios frecuentes pueden sangrar la cuenta.
### Índice de flujo de dinero (IMF) (mfi_div)
“RSI con volumen”. Intenta detectar dinero inteligente.
* **Tipo:** Momento de volumen.
* **Lógica:** El precio puede subir por inercia, pero si el volumen baja la tendencia es quedarse sin combustible. Las IMF representan tanto el precio como el volumen.
* **Entrada:** MFI cae por debajo de 20 (sobreventa) y aparece en posición larga. La divergencia (precio abajo, IMF arriba) funciona aún mejor.
* **Salida:** IMF por encima de 80 (sobrecompra).
* **Pros:** Filtra movimientos de precios "vacíos" que no están respaldados por volumen. A menudo lidera el RSI.
### Cruce de TEMA (tema_cross)
Utiliza Triple EMA (TEMA) para reducir el retraso.
* **Tipo:** Tendencia rápida.
* **Lógica:** Retraso regular de SMA/EMA. TEMA reacciona casi instantáneamente.
* **Entrada:** TEMA rápido (p. ej., 9) cruza por encima de TEMA lento (p. ej., 21).
* **Salida:** El cruce de enfrente.
* **Pros:** Entra antes que el cruce SMA y sale más rápido en las reversiones.
* **Contras:** Más señales falsas (“ruido”) en mercados tranquilos.
### Retroceso del canal Keltner (keltner_pullback)
Retrocesos comerciales en tendencias fuertes. Una alternativa al BB.
* **Tipo:** Tendencia de retroceso.
* **Lógica:** Keltner Channel se basa en ATR (volatilidad). Si el precio se mantiene por encima de la banda *superior* durante mucho tiempo, la tendencia es muy fuerte.
* **Entrada:**
    1. Confirme la tendencia alcista (Precio> EMA 20 o línea media del canal).
    2. Espere a que retroceda a la línea del canal **inferior** o **medio**.
    3. Vaya largo al toque/rebote.
* **Salir:** El precio alcanza la banda superior del canal.
* **Pros:** “Compre la caída” dentro de una tendencia alcista. Buen riesgo/recompensa.
### Oscilador impresionante (ao_saucer)
La estrategia del “platillo” de Bill Williams.
* **Tipo:** Impulso.
* **Lógica:** El histograma AO muestra la fuerza impulsora del mercado.
* **Entrada (el patrón “Platillo”):** Histograma por encima de cero. Busque 3 barras: Roja -> Roja (más baja que la primera) -> Verde (más alta que la segunda). La corrección terminó y se reanuda el aumento.
* **Salir:** El color cambia a rojo o el histograma cae por debajo de cero.
* **Pros:** Un “microscopio” para medir el tiempo de entrada dentro de las olas.
### Corrección CCI (cci_corrección)
Índice de canales de productos básicos, popular en Forex y criptomonedas.
* **Tipo:** Cíclico.
* **Lógica:** El CCI mide la desviación del precio de su media estadística.
* **Entrada:** Espere a que CCI caiga por debajo de -100 (fuerte sobreventa) y luego vuelva a cruzar por encima de -100.
* **Salir:** CCI sube por encima de +100 o cruza 0 de arriba hacia abajo.
* **Pros:** Niveles claros (-100/+100), lógica mecánica simple.
### Tendencia VWAP (vwap_cross)
Una estrategia utilizada por los traders institucionales. VWAP (Precio promedio ponderado por volumen) muestra el precio "justo" del activo teniendo en cuenta el volumen.
* **Tipo:** Seguimiento de tendencia/Volumen.
* **Lógica:** Si el precio está por encima del VWAP, los compradores controlan el mercado (alcista). Si está debajo, vendedores.
* **Entrada:** El precio cruza VWAP de abajo hacia arriba.
* **Salir:** El precio cruza VWAP de arriba hacia abajo.
* **Nota:** Intradiario muy eficaz (5m, 15m, 1h) porque las instituciones suelen anclarse al VWAP.
### RSI estocástico (stoch_rsi)
Una versión más sensible y rápida de RSI. Ayuda a capturar cambios a corto plazo dentro de una tendencia.
* **Tipo:** Scalping / Oscilador.
* **Lógica:** StochRSI aplica la fórmula estocástica a los valores RSI, no al precio, lo que lo hace muy reactivo.
* **Entrada:** Las líneas StochRSI se cruzan en sobreventa (< 20) y suben.
* **Salir:** Cruce sobrecompra (>80) y baje.
* **Nota:** Genera muchas señales. Necesita un filtro (por ejemplo, operar solo con la tendencia EMA); de lo contrario, oscilará en los rangos.
### Índice de fuerza del anciano (elder_force)
La estrategia de Alexander Elder. Combina precio y volumen para medir el poder "alcista" y "bajista".
* **Tipo:** Impulso.
* **Lógica:** Índice de fuerza = (Cerrar - PrevCerrar) * Volumen, luego suavizado (EMA).
* **Entrada:** Tendencia global alcista (por ejemplo, precio por encima de EMA 22) y el Índice de fuerza (período 2) cae por debajo de cero (retroceso a corto plazo). Compra el chapuzón.
* **Salir:** El índice de fuerza vuelve a ser positivo (el impulso regresa).
* **Nota:** Excelente para detectar entradas de retroceso en tendencias fuertes.
### Williams %R (williams_r)
El indicador de Larry Williams. Similar al estocástico, pero invertido. Genial en rangos.
* **Tipo:** Reversión media.
* **Lógica:** Mide qué tan cerca está el cierre de los máximos/mínimos del rango.
* **Entrada:** El valor cae por debajo de -80 (sobreventa) y comienza a subir.
* **Salir:** El valor sube por encima de -20 (sobrecompra).
* **Nota:** Bueno para resaltar el agotamiento del vendedor.
### MA adaptativo de Kaufman (kama_trend)
Una estrategia basada en la media móvil adaptativa de Kaufman.
* **Tipo:** Tendencia adaptativa.
* **Lógica:** A diferencia de una EMA normal, KAMA se ralentiza en rangos ruidosos (se aplana) y se acelera en tendencias. Esto reduce las entradas falsas.
* **Entrada:** El precio cruza KAMA de abajo hacia arriba.
* **Salir:** El precio cruza KAMA de arriba hacia abajo.
* **Nota:** Una media móvil “inteligente” que filtra el picado.
### Tasa de cambio (roc)
Negociar la velocidad del cambio de precios. Pura física de mercado.
* **Tipo:** Velocidad / Momento.
* **Lógica:** La República de China muestra el cambio porcentual en N períodos. El aumento de la República de China significa que la tendencia se está acelerando.
* **Entrada:** La República de China cruza por encima de cero (aceleración al alza).
* **Salida:** La República de China cruza bajo cero (desaceleración).
* **Nota:** Un indicador adelantado; a menudo señala reversiones antes de que se crucen las MA.
### Desglose del canal ATR (volty_channel)
Ruptura del canal de volatilidad.
* **Tipo:** Fuga.
* **Lógica:** Cree un canal en torno al precio: `Close + (N * ATR)` y `Close - (N * ATR)`.
* **Entrada:** Cerrar por encima del canal superior. Un movimiento anormalmente fuerte más allá de la volatilidad normal.
* **Salir:** El precio vuelve al medio.
* **Nota:** Captura las bombas/descargas más potentes ignorando los ruidos menores.
### Pendiente de regresión lineal (lin_reg)
Negociación basada en la pendiente matemática de una línea de tendencia.
* **Tipo:** Estadístico/Tendencia.
* **Lógica:** En lugar de promediar precios (como SMA), ajuste una línea de regresión lineal sobre las últimas N velas y use su pendiente.
* **Entrada:** La pendiente se vuelve positiva y excede un umbral (filtro de ruido). Estadísticamente, la tendencia ha aumentado.
* **Salida:** La pendiente se vuelve negativa.
* **Por qué es genial:** Reacciona más rápido que los MA porque intenta modelar la dirección, no solo promediar el pasado.
### Flujo de dinero de Chaikin (cmf_trend)
Estrategia de acumulación/distribución. Similar a MFI, pero utiliza un análisis más profundo de la ubicación de cierre dentro del rango de velas.
* **Tipo:** Flujo volumétrico.
* **Lógica:** CMF estima presión compradora/vendedora. CMF > 0 significa acumulación (el dinero fluye); CMF < 0 significa distribución (el dinero sale).
* **Entrada:** CMF cruza por encima de cero.
* **Salir:** CMF vuelve a cruzar por debajo de cero.
* **Por qué es genial:** Ayuda a separar una reversión real de un “rebote del gato muerto”: si el precio aumenta mientras CMF < 0, es probable que el movimiento sea débil.
### Indicador de vórtice (vórtice)
Un indicador inspirado en patrones de flujo naturales (vórtices).
* **Tipo:** Seguimiento de tendencias.
* **Lógica:** Dos líneas: VI+ y VI-. Miden el movimiento direccional en función de las distancias entre el máximo actual y el mínimo anterior (y viceversa).
* **Entrada:** VI+ cruza por encima de VI-.
* **Salida:** VI+ cruza por debajo de VI-.
* **Por qué es interesante:** Confiable para detectar el inicio de tendencias más largas, aunque puede retrasarse en rangos.
### Estrategia Aroon (aroon)
Una estrategia que mide el *tiempo* desde el último máximo/mínimo.
* **Tipo:** Fuerza de la tendencia.
* **Lógica:** Aroon Up muestra cuántos días han transcurrido desde un máximo; Aroon abajo desde un mínimo. Los valores oscilan entre 0 y 100.
* **Entrada:** Aroon Up cruza por encima de Aroon Down **y** Aroon Up > 50. Aparecen nuevos máximos con más frecuencia que mínimos.
* **Salida:** Aroon Up cae por debajo de 50 o cruza por debajo de Aroon Down.
* **Por qué es genial:** Un enfoque único basado en el tiempo en lugar de señales puramente basadas en el precio.
### TRIX (Promedio exponencial triple) (trix_strat)
Un oscilador de impulso muy suave.
* **Tipo:** Impulso.
* **Lógica:** EMA con triple suavizado (a menudo en el precio de registro), que elimina la mayor parte del ruido del mercado.
* **Entrada:** TRIX cruza por encima de cero.
* **Salir:** Cruzar hacia abajo por debajo de cero o cruzar la línea de señal.
* **Por qué es genial:** Pocas señales pero de alta calidad; funciona bien en períodos de tiempo más altos (4h, 1d).
### Curva de Coppock (coppock)
Un indicador diseñado para detectar mínimos del mercado a largo plazo (originalmente para el S&P 500), pero que también funciona en criptomonedas.
* **Tipo:** Swing / Inversión a largo plazo.
* **Lógica:** Suma de dos valores ROC con diferentes períodos, suavizada por una media móvil ponderada.
* **Entrada:** La curva de Coppock comienza a aparecer cuando está por debajo de cero.
* **Salir:** La curva baja (o cruza el 0).
* **Por qué es genial:** Psicológicamente cómodo: entradas raras, a menudo cerca del inicio de un mercado alcista más amplio.
### Índice de canales de productos básicos (cci_trend)
Uso de CCI para operaciones de tendencia (no de contratendencia como antes).
* **Tipo:** Tendencia.
* **Lógica:** CCI se usa a menudo para reversiones, pero aquí lo usamos como una señal de ruptura/impulso.
* **Entrada:** El CCI sube por encima de +100: un fuerte impulso alcista.
* **Salir:** CCI vuelve a caer por debajo de +100 (o por debajo de 0).
* **Por qué es genial:** Captura la parte "más importante" de un movimiento cuando un activo va "a la luna".
### Tendencia de media móvil del casco (hma_trend)
Una estrategia basada en la media móvil del casco (HMA).
* **Tipo:** Seguimiento de tendencia de bajo retraso.
* **Lógica:** Alan Hull creó una fórmula que reduce el retraso típico de SMA/EMA mientras mantiene una curva suave.
* **Entrada:** El precio cruza por encima de HMA (o la pendiente de HMA cambia de abajo a arriba).
* **Salida:** El cruce opuesto o giro de pendiente.
* **Borde:** Reacciona a las reversiones casi instantáneamente; excelente en pares volátiles donde los MA regulares son demasiado lentos.
### Estrategia de puntuación Z (z_score)
Estadística matemática pura sin “líneas mágicas”.
* **Tipo:** Reversión media.
* **Lógica:** Z-Score mide cuántas desviaciones estándar (sigmas) hay entre el precio y su media, como las bandas de Bollinger “digitales”.
* **Entrada:** Z-Score cae por debajo de -2 (desviación a la baja de 2 sigma). Compre esperando reversión.
* **Salir:** Z-Score vuelve a 0 (media) o sube por encima de +2.
* **Ventaja:** Funciona en cualquier activo porque normaliza la volatilidad.
### VWMA frente a SMA (vwma_cross)
Validar la fuerza de la tendencia a través del volumen.
* **Tipo:** Tendencia + Confirmación de volumen.
* **Lógica:** Compare SMA con VWMA (MA ponderada por volumen).
    * Si VWMA > SMA, el volumen es más fuerte en las velas alcistas (los jugadores más grandes compran).
    * Si VWMA < SMA mientras el precio sube, el movimiento se produce por un volumen débil (posible trampa).
* **Entrada:** VWMA cruza por encima de SMA.
* **Salida:** VWMA cruza por debajo de SMA.
* **Ventaja:** Filtra bombas "infladas" sin dinero real detrás.
### Connors RSI 2 (rsi_2)
La famosa estrategia de especulación de Larry Connors.
* **Tipo:** Reversión media agresiva de corto plazo.
* **Lógica:** El RSI(14) estándar es demasiado lento; Connors usa RSI con período 2.
* **Entrada:** El RSI(2) cae por debajo de 10 (o 5): sobreventa extrema. Vaya largo.
* **Salida:** Cierre por encima de la SMA de 5 días. No espere a que RSI > 90; salir en el primer rebote.
* **Ventaja:** Tasa de ganancia muy alta (a menudo > 80%), pero las operaciones son cortas y la ganancia por operación es pequeña.
### Fractales de Williams (fractal_breakout)
Rupturas comerciales de niveles locales (Price Action).
* **Tipo:** Fuga.
* **Lógica:** Un fractal Williams es una formación de 5 velas donde la vela del medio tiene el máximo más alto (fractal superior) o el mínimo más bajo (fractal inferior). Estos son picos/depresiones locales.
* **Entrada:** El precio rompe el nivel del último fractal alcista (el máximo de la vela fractal).
* **Salida:** El precio rompe el nivel del último fractal bajista (parada dinámica).
* **Ventaja:** Negocia niveles reales de soporte/resistencia que ve el mercado, no fórmulas derivadas.
### Bandas de Fibonacci Bollinger (fib_bands)
Un enfoque modificado de las Bandas de Bollinger para capturar rebotes más precisos.
* **Tipo:** Reversión/Tendencia media.
* **Lógica:** En lugar de multiplicadores de desviación estándar (x2, x3), se utilizan proporciones de Fibonacci (1,618, 2,618, 4,236) para los anchos de banda.
* **Entrada:** El precio toca una banda interior (Fib 1.618) o una banda exterior (Fib 2.618) y rebota.
* **Salir:** Regresar a la línea media.
* **Borde:** Las criptomonedas a menudo respetan los niveles de Fibonacci más que un modelo gaussiano perfecto.
### Estrategia de salida de la lámpara de araña (chandelier_trend)
Una estrategia construida desde la dirección opuesta: gestión de salida (stop loss).
* **Tipo:** Seguimiento de tendencias.
* **Lógica:** Candelabro Exit cuelga un stop loss a una distancia (ATR * 3) por debajo del máximo más alto en una mirada retrospectiva. Si el precio no alcanza el "candelabro", te quedas ahí.
* **Entrada:** Cierre por encima de la línea de salida del candelabro (tendencia invertida alcista).
* **Salir:** El precio toca la línea (toque dinámico).
* **Ventaja:** Diseñado para dejar correr las ganancias y evitar salir en pequeños retrocesos.
### Desglose de la barra interior (inside_bar)
Una estrategia clásica de Price Action sin indicadores.
* **Tipo:** Ruptura/Patrón de volatilidad.
* **Lógica:** Encuentre una barra interior: una vela cuyo máximo/mínimo esté completamente dentro de la vela "madre" anterior. El mercado se comprime antes de la expansión.
* **Entrada:** El precio rompe el máximo de la barra interior (para posiciones largas).
* **Salir:** Take Profit fijo o trailing stop. El stop loss se coloca detrás del mínimo de la barra interior.
* **Borde:** Stops muy ajustados con alto potencial de subida (riesgo/recompensa).
### TD secuencial (simplificado) (td_seq)
Una versión simplificada de la legendaria estrategia de Thomas DeMark.
* **Tipo:** Contratendencia/Reversión.
* **Lógica:** Los mercados se cansan de moverse en una dirección. DeMark cuenta cierres secuenciales.
* **Entrada (Configuración):** Si ve **9 velas consecutivas** donde cada cierre está por debajo del cierre 4 velas antes (Configuración bajista), los vendedores están agotados. Ingrese Long en la apertura de la vela 10.
* **Salir:** En la configuración opuesta o después de un número fijo de velas.
* **Borde:** Popular en criptografía para capturar fondos locales.
### Transformación de Ehlers Fisher (fisher_trans)
La estrategia de John Ehlers utilizando conceptos de procesamiento de señales digitales.
* **Tipo:** Reversión / Cíclico.
* **Lógica:** Transforma el movimiento de precios en una distribución (casi) normal, haciendo que los puntos de inflexión sean nítidos y claros al eliminar el ruido.
* **Entrada:** La línea Fisher cruza por encima de su línea de señal (a menudo al salir de una zona inferior).
* **Salida:** El cruce de enfrente.
* **Edge:** Un oscilador “turbo”, que reacciona más rápido y más limpiamente que el RSI o el MACD.
### Divergencia RSI (rsi_div)
Negociar divergencias RSI en lugar de niveles RSI.
* **Tipo:** Reversión.
* **Lógica:** Si el precio alcanza un mínimo más bajo, pero el RSI alcanza un mínimo más alto, eso es **divergencia alcista**. El impulso bajista se agota incluso si el precio sigue bajando.
* **Entrada:** Después de confirmar divergencia alcista.
* **Salida:** El RSI sube por encima de 70 o cruza 50.
* **Edge:** Una de las señales TA más confiables; le permite ingresar cerca del fondo (atrapar los “cuchillos que caen” de manera profesional).
### Tendencia Heikin Ashi (ha_trend)
Uso de velas Heikin Ashi modificadas para filtrar el ruido.
* **Tipo:** Tendencia visual.
* **Lógica:** Las velas Heikin Ashi se calculan a partir de precios promedio de apertura/cierre. Suavizan el gráfico y ocultan pequeños retrocesos.
* **Entrada:** Después de una serie de velas rojas, aparece una vela verde sin mecha inferior (fuerte impulso alcista).
* **Salida:** Aparece una vela que cambia de color (roja), o una vela con mechas largas en ambos lados (doji/incertidumbre).
* **Ventaja:** Psicológicamente cómoda; le ayuda a analizar tendencias largas sin reaccionar exageradamente ante pequeñas velas rojas en un gráfico normal.
### Canal de desviación estándar (std_channel)
Negociar dentro de un canal de regresión lineal.
* **Tipo:** Reversión media.
* **Lógica:** Una línea media de regresión lineal más dos líneas paralelas con 2 desviaciones estándar. ~95% de los movimientos ocurren en el interior.
* **Entrada:** El precio toca el canal inferior (sobreventa en relación con la tendencia).
* **Salir:** Regresar a la línea de regresión (línea media).
* **Borde:** A diferencia de las Bandas de Bollinger, este canal tiene pendiente, por lo que se revierte **en la dirección** de la tendencia.
### Inversión de puntos de pivote (pivot_rev)
Negociar desde niveles de soporte matemático.
* **Tipo:** Rebote.
* **Lógica:** Utilice el máximo/bajo/cierre de ayer para calcular el pivote (P), los soportes (S1, S2) y las resistencias (R1, R2).
* **Entrada:** El precio cae en S1 o S2, lo prueba y cierra por encima (rebote).
* **Salir:** Siguiente nivel de pivote (por ejemplo, comprar en S1, objetivo P).
* **Ventaja:** Estos son niveles autocumplidos que muchos traders observan; Funciona bien en 1h/4h.
### Caimán Williams (cocodrilo)
La clásica estrategia de tendencias de Bill Williams.
* **Tipo:** Seguimiento de tendencias.
* **Lógica:** Tres medias móviles suavizadas y desplazadas hacia adelante (mandíbulas, dientes y labios). Imitan el comportamiento de un caimán.
* **Entrada:** Cuando las líneas están enredadas: “el caimán está durmiendo” (alcance, no intercambie). Cuando se abren en el orden correcto (Labios > Dientes > Mandíbulas) – comienza la tendencia – Largo.
* **Salir:** Las líneas se enredan nuevamente o el precio cierra por debajo de los “Dientes”.
* **Ventaja:** Ayuda a negociar solo movimientos fuertes e ignorar rangos ruidosos.
### Patrón envolvente (engulfing_candle)
Operando con el patrón de velas puras “envolvente”.
* **Tipo:** Acción/Reversión del Precio.
* **Lógica:** Dos velas. La segunda vela (alcista) envuelve completamente el cuerpo de la vela anterior (bajista), mostrando un fuerte cambio en el sentimiento de venta a compra.
* **Entrada:** Aparece un envolvente alcista después de una serie de velas bajistas.
* **Salir:** Objetivo de beneficio fijo o patrón opuesto.
* **Borde:** Sin retraso; la señal está disponible justo al cierre de la vela.
### McGinley dinámico (mcginley)
Operar con una media móvil "ideal".
* **Tipo:** Tendencia avanzada.
* **Lógica:** John McGinley creó un indicador que parece una EMA pero que automáticamente se acelera en mercados rápidos y se desacelera en mercados lentos, evitando las sacudidas mejor que los MA estándar.
* **Entrada:** El precio cruza por encima de la línea McGinley.
* **Salida:** El precio cruza por debajo de la línea.
* **Edge:** Resuelve la eterna pregunta: “¿Qué período MA debo usar?” McGinley se adapta automáticamente.
### Doble empuje (dual_thrust)
Un famoso sistema de ruptura, que se utiliza a menudo en futuros.
* **Tipo:** Desglose de rango.
* **Lógica:** Tome el rango de las últimas N velas (Alto - Cierre o Alto - Bajo) y multiplíquelo por K.
* **Entrada:** Si el precio se rompe `Open + (Range * K)` — Largo. Si se rompe por debajo, corto.
* **Salir:** Cierre de fin de día o parada y reversión.
* **Borde:** Capta fuertes impulsos fuera de la consolidación; popular en el comercio de algoritmos.
### Oscilador de impulso Chande (cmo_strat)
Un indicador de impulso puro, diferente del RSI.
* **Tipo:** Impulso.
* **Lógica:** CMO es la diferencia entre las sumas de movimientos ascendentes y descendentes dividida por el movimiento total. Rango: -100 a +100.
* **Entrada:** CMO cruza +50 de abajo hacia arriba (fuerte impulso alcista) o sube desde sobreventa (< -50).
* **Salir:** CMO vuelve a caer por debajo de +50.
* **Ventaja:** A diferencia del suavizado RSI, CMO reacciona directamente a cada movimiento, mostrando velocidad bruta.
### Facilidad de movimiento (eom_trend)
Una estrategia que combina Precio y Volumen para encontrar el “camino de menor resistencia”.
* **Tipo:** Volumen + Precio.
* **Lógica:** El EVM de Richard Arms muestra con qué facilidad se mueven los precios. Un fuerte aumento de precios en volúmenes pequeños es “fácil”; Un volumen enorme con poco movimiento es “difícil” (una pelea).
* **Entrada:** EVM cruza por encima de 0.
* **Salir:** EVM cae por debajo de 0.
* **Ventaja:** Ayuda a detectar tendencias "saludables" y evitar mercados donde hay una fuerte batalla (gran volumen, sin movimiento).
### Sepa lo seguro (KST) (kst_momentum)
“Sea seguro”: un indicador de impulso compuesto.
* **Tipo:** Momento del ciclo (a largo plazo).
* **Lógica:** Una suma de cuatro componentes ROC con diferente suavizado; efectivamente un “MACD para ciclos”.
* **Entrada:** KST cruza por encima de su línea de señal.
* **Salida:** El cruce de enfrente.
* **Ventaja:** Diseñado para captar los principales ciclos del mercado ignorando pequeñas correcciones. Funciona bien en 4h y 1d.
### Ciclo de tendencia de Schaff (stc_cycle)
Una variante MACD mejorada que se mueve más rápido y con mayor precisión.
* **Tipo:** Ciclo / Momento.
* **Lógica:** Doug Schaff combinó MACD y estocástico en un oscilador de 0 a 100 que, a diferencia del estocástico, es menos nervioso en el movimiento y mantiene mejor las posiciones.
* **Entrada:** STC sube por encima de 25 (sale sobrevendido).
* **Salida:** El STC cae por debajo de 75 (sale sobrecomprado).
* **Nota:** Encuentra tendencias antes que el MACD y proporciona menos señales falsas en los rangos.
### Filtro de índice de agitación + EMA (chop_ema)
Una estrategia con filtro de “calidad de mercado”.
* **Tipo:** Tendencia con filtro.
* **Lógica:** El índice de agitación (CHOP) indica si el mercado está en tendencia o en rango. CHOP > 61,8 significa rango (no intercambiar). CHOP <38,2 significa una fuerte tendencia.
* **Entrada:** El precio cruza por encima de una EMA (p. ej., 50) **y** CHOP < 50 (confirmación de tendencia).
* **Salida:** El precio vuelve a cruzar por debajo de la EMA.
* **Nota:** El objetivo principal es evitar operaciones en mercados muertos y ahorrar tarifas y nervios.
### Media móvil adaptativa fractal (frama_trend)
Utilizar la geometría fractal para adaptarse al mercado.
* **Tipo:** Tendencia adaptativa.
* **Lógica:** FRAMA utiliza “dimensión fractal”. En el caos (rango), FRAMA se ralentiza y se aplana. En movimiento direccional, acelera.
* **Entrada:** El precio cruza por encima de FRAMA.
* **Salir:** El precio cruza por debajo de FRAMA.
* **Nota:** A diferencia de una EMA normal, FRAMA puede permanecer casi plana durante las correcciones, evitando paradas falsas.
### Tendencia del precio por volumen (vpt_cross)
Un indicador similar a OBV más avanzado.
* **Tipo:** Volumen.
* **Lógica:** VPT tiene en cuenta no sólo la dirección (como OBV), sino también el cambio de precio *porcentual*. Un gran volumen con pequeños cambios de precio tiene un impacto pequeño; Un gran volumen con un gran movimiento tiene un gran impacto.
* **Entrada:** VPT cruza por encima de su media móvil (MA).
* **Salir:** VPT cae por debajo de su MA.
* **Nota:** Muy sensible a la acumulación de “dinero inteligente”.
### Laguerre RSI (laguerre_rsi)
“RSI del futuro”: utilizando el filtro de Laguerre.
* **Tipo:** Oscilador de tendencia.
* **Lógica:** John Ehlers aplicó un filtrado de distorsión de tiempo para crear un RSI de retraso mínimo con solo 4 componentes de suavizado.
* **Entrada:** Laguerre RSI cruza por encima de 0,2 (20%).
* **Salida:** Cruza por debajo de 0,8 (80%).
* **Nota:** Reacciona mucho más rápido que el RSI clásico y captura una mayor parte del movimiento.
### Pinbar (martillo/estrella fugaz) (pinbar_reversal)
Acción pura del precio: velas de reversión.
* **Tipo:** Patrón de velas japonesas (inversión).
* **Lógica:** Una “barra de alfiler” (martillo o estrella fugaz) tiene una mecha muy larga y un cuerpo pequeño. La mecha muestra que el precio se movió en una dirección y fue rechazada tajantemente.
* **Entrada:** Aparece una barra pin alcista (mecha inferior larga) en un mínimo local.
* **Salida:** Riesgo/recompensa fijo (p. ej., 1:3) o salida en una señal opuesta.
* **Nota:** Funciona mejor en niveles de soporte; A menudo marca la capitulación del vendedor.
### Oscilador de precios sin tendencia (dpo_cycle)
Operar con ciclos de corto plazo sin el sesgo de tendencia global.
* **Tipo:** Cíclico de Corto Plazo.
* **Lógica:** DPO elimina la tendencia a largo plazo, dejando solo oscilaciones a corto plazo (“microondas”).
* **Entrada:** DPO cruza por encima de 0.
* **Salir:** DPO cruza por debajo de 0.
* **Nota:** Ayuda a negociar las oscilaciones intradía incluso cuando el mercado global se encuentra en un fuerte régimen alcista/bajista.
### Ruptura del rango de apertura (orb_strat)
Estrategia clásica de day-trader adaptada a un mercado 24 horas al día, 7 días a la semana.
* **Tipo:** Desglose basado en tiempo.
* **Lógica:** La primera hora (o 4 horas) de un nuevo día/semana marca la pauta; el mercado “elige” la dirección.
* **Entrada:** Defina el máximo y el mínimo de la primera vela diaria (00:00 UTC). Si el precio supera el máximo – largo.
* **Salida:** Fin del día (23:59) o un stop loss fijo en el punto medio del rango.
* **Borde:** Utiliza el impulso de la sesión de apertura. Muy simple, pero estadísticamente efectivo en activos de alta volatilidad.
### Índice de facilitación del mercado (bw_mfi)
La estrategia de Bill Williams (no el índice de flujo de dinero). Mide la eficiencia del movimiento de precios en relación con el volumen.
* **Tipo:** Volumen + Precio Eficiencia.
* **Lógica:** Compara el rango con el volumen.
    * *Barra verde:* Subir volumen + movimiento fuerte = tendencia verdadera.
    * *Barra de sentadillas:* Volumen arriba + precio fijo = pelea alcista/bajista (posible reversión).
* **Entrada:** 2–3 “barras verdes” consecutivas.
* **Salir:** Aparece una barra de "Sentadilla": el movimiento se está quedando sin combustible.
* **Borde:** Ayuda a distinguir un bombeo débil (volumen bajo) de un movimiento real.
### Línea psicológica (psy_line)
Indicador de sentimiento de la multitud.
* **Tipo:** Sentimiento / Contratendencia.
* **Lógica:** Relación entre velas ascendentes y velas totales durante un período (por ejemplo, 12). Si PSY > 75%, 9 de cada 12 velas eran verdes: euforia (sobrecompra).
* **Entrada:** PSY cae por debajo del 25% (pánico) y aparece.
* **Salir:** PSY sube por encima del 75%.
* **Borde:** Un termómetro de mercado que ignora los precios absolutos y se centra en las “victorias” alcistas frente a bajistas.
### Bolsillo dorado de Fibonacci (fib_golden)
Negociación automatizada de retrocesos de Fibonacci.
* **Tipo:** Compra por inmersión.
* **Lógica:** Encuentra el último swing significativo alto/bajo y dibuja el retroceso de Fibonacci. La zona entre 0,618 y 0,65 es el “Bolsillo Dorado”, donde suelen producirse rebotes.
* **Entrada:** El precio toca el nivel de retroceso de 0,618.
* **Salida:** Nuevo máximo (nivel 0) o parada por debajo de 0,786.
* **Ventaja:** Una de las estrategias discrecionales más populares; el bot automatiza la búsqueda de estos niveles.
### Tres soldados blancos / Tres cuervos negros (candle_patterns)
Operando con fuertes formaciones de velas que a menudo continúan la tendencia.
* **Tipo:** Reconocimiento de patrones.
* **Lógica:** “Tres Soldados Blancos” son tres velas verdes consecutivas, cada una de las cuales cierra más alto que la anterior, preferiblemente con mechas cortas. Indica dominio del comprador.
* **Entrada:** Cierre de la 3ra vela.
* **Salir:** Aparece la primera vela bajista, o stop dinámico por los mínimos de la vela.
* **Borde:** Si se imprimen tres velas poderosas seguidas, la probabilidad de continuación suele ser alta.
### Índice de caminata aleatoria (rwi_trend)
Una prueba estadística: "¿Es esto una tendencia o aleatoriedad?"
* **Tipo:** Filtro estadístico.
* **Lógica:** RWI compara el movimiento de precios con lo que se esperaría de un paseo aleatorio (lanzamiento de moneda).
* **Entrada:** RWI Alto > 1 (el movimiento ascendente es estadísticamente significativo).
* **Salir:** El máximo del RWI cae por debajo de 1.
* **Ventaja:** Le evita operar en mercados ruidosos y caóticos.
### Estrategia de índice de úlceras (ulcer_strat)
Una estrategia que minimiza el estrés (y las reducciones).
* **Tipo:** Riesgo Ajustado / Gestión de Riesgos.
* **Lógica:** El índice de úlceras mide la profundidad y duración de las reducciones. A diferencia de la desviación estándar, sólo tiene en cuenta los *movimientos hacia abajo* (mala volatilidad).
* **Entrada:** El precio está subiendo mientras que Ulcer Index está extremadamente bajo (tendencia alcista suave y tranquila).
* **Salir:** Un fuerte aumento en el índice de úlceras (comienza la turbulencia).
* **Ventaja:** Ideal para un crecimiento conservador de la cuenta; sale temprano de la inestabilidad sin esperar a que se produzca un choque.
### Coincidencia de patrones de k-vecinos más cercanos (kNN) (knn_ml)
Aprendizaje automático simple sin redes neuronales pesadas.
* **Tipo:** Coincidencia de patrones.
* **Lógica:** El algoritmo memoriza la forma de las últimas N velas (por ejemplo, 5) y luego busca en el gráfico histórico las formas más similares.
* **Entrada:** Si en el 70% de las coincidencias históricas encontradas el precio subió después, compre.
* **Salida:** Período de tenencia fijo (p. ej., 3 velas) o cuando cambia el pronóstico.
* **Borde:** El bot no utiliza indicadores; "mira" la historia: "Esto sucedió antes; esto es lo que vino después".
### Teoría de la caja de Darvas (darvas_box)
La legendaria estrategia de Nicholas Darvas que le hizo ganar 2 millones de dólares en la década de 1950.
* **Tipo:** Ruptura/Seguimiento de tendencia.
* **Lógica:** Cuando el precio varía, construye una “Caja” con un techo (Alto) y un piso (Bajo) despejados.
* **Entrada:** El precio supera el techo de la caja. Es una señal de que el activo se movió a un "nuevo piso". Inmediatamente coloque un tope debajo del nuevo piso de la caja.
* **Salir:** El precio cae por debajo del piso de la caja.
* **Borde:** Excelente para tendencias parabólicas ignorando sacudidas menores dentro de las cajas.
### Índice Elder-Ray (elder_ray)
La estrategia de “rayos X del mercado” de Alexander Elder.
* **Tipo:** Seguimiento de tendencia + Impulso.
* **Lógica:** Utiliza EMA(13) como consenso de valor y dos componentes: `Bull Power` (Alto - EMA) y `Bear Power` (Bajo - EMA).
* **Entrada:** Tendencia alcista (pendiente ascendente de la EMA) **y** `Bear Power` está por debajo de cero pero está subiendo (los bajistas se debilitan). Compra el retroceso.
* **Salir:** `Bull Power` alcanza un máximo histórico y comienza a caer.
* **Borde:** Separa la fuerza interna alcista y bajista.
### Centro de gravedad (cog_ehlers)
Oscilador de retraso cero de John Ehlers.
* **Tipo:** Reversión.
* **Lógica:** Ehlers utilizó una fórmula física del centro de gravedad para encontrar puntos de inflexión. El indicador parece una onda sinusoidal suave y puede "predecir" reversiones con un retraso mínimo.
* **Entrada:** COG cruza por encima de su línea de señal (Retraso 1).
* **Salida:** El cruce de enfrente.
* **Edge:** Una de las herramientas más precisas para mercados laterales. En las tendencias puede salir temprano, por lo que se recomienda un filtro de tendencias.
### Entropía de Shannon (entropía_caos)
Utilizar la teoría de la información para medir el caos del mercado.
* **Tipo:** Filtro de régimen de mercado.
* **Lógica:** La entropía de Shannon mide la incertidumbre.
    * Alta entropía = caos; El precio es impredecible (alcance/ruido).
    * Baja entropía = orden; fuerte tendencia direccional.
* **Entrada:** La entropía cae por debajo de un umbral (el mercado se ordenó) + el precio está por encima de una media móvil.
* **Salida:** Picos de entropía (comienza el caos).
* **Edge:** Una forma matemáticamente fundamentada de decir: "No hago negocios porque el mercado está borracho en este momento".
### Índice de vigor relativo (rvi_trend)
Energía del movimiento de precios.
* **Tipo:** Impulso.
* **Lógica:** Basado en la idea de que en los mercados alcistas los cierres tienden a ser superiores a las aperturas. El RVI suaviza estos valores y se parece al estocástico, pero se basa en la “energía” de la vela en lugar del rango.
* **Entrada:** RVI cruza por encima de su línea de señal.
* **Salir:** Cruzar abajo.
* **Borde:** Confirma la sostenibilidad de la tendencia. Si el precio aumenta pero el RVI cae (divergencia), la tendencia puede ser débil.
### VSTOP (Parada de volatilidad) (vstop_trend)
Estrategia de seguimiento basada en la volatilidad.
* **Tipo:** Trailing (Tendencia).
* **Lógica:** Calcule una línea de parada en `N * ATR` lejos de los precios extremos. La línea sólo se mueve en la dirección de la tendencia, nunca hacia atrás.
* **Entrada:** Cierre por encima de la línea VSTOP (baja por debajo del precio y se convierte en soporte).
* **Salir:** El precio toca o cierra por debajo de VSTOP.
* **Ventaja:** Un enfoque puro de gestión de salidas que le mantiene en tendencia hasta que la volatilidad rompe la protección. Similar a SuperTrend, pero con una matemática de máximos diferente.
### ¿Qué elegir a continuación?
Para la siguiente fase de implementación (para completar su cartera), recomiendo:
1. **k-Vecinos más cercanos (knn_ml)**: agrega **lógica de IA** simple a su bot sin bibliotecas pesadas. Un enfoque muy moderno.
2. **Darvas Box**: un **clásico revolucionario** que funciona bien con monedas “exageradas” durante fuertes movimientos alcistas.
3. **Centro de gravedad**: un arma poderosa para los **mercados de rango**, donde las estrategias de tendencia tienden a perder dinero.
### Indicador de impulso de compresión (lazybear_squeeze)
La legendaria estrategia TradingView (de LazyBear) basada en las ideas de John Carter.
* **Tipo:** Ruptura de volatilidad + impulso.
* **Lógica:** Combina bandas de Bollinger y canales de Keltner.
    * **Fase de “compresión”:** Las Bandas de Bollinger están dentro del Canal Keltner (puntos negros). El mercado almacena energía.
    * **Fase de “liberación”:** Las bandas se mueven fuera del canal.
* **Entrada:** El apretón termina (salida del rango) **y** el histograma de impulso está por encima de cero y aumenta.
* **Salir:** El histograma de impulso cambia de color (comienza a caer) o cae por debajo de cero.
* **Edge:** Un sistema visualmente simple que captura los movimientos posteriores a la compresión más fuertes.
### Estrategia del exponente de Hurst (hurst_exponent)
Una estrategia matemática que determina la “memoria” del mercado.
* **Tipo:** Adaptativo (cambiador de régimen).
* **Lógica:** El exponente de Hurst (H) identifica la naturaleza del mercado:
    * H > 0,5: Tendencia (persistente).
    * H < 0,5: Rango (reversión media).
* **Entrada:**
    * Si H > 0,6: utilice la lógica de ruptura (por ejemplo, ruptura del máximo de los últimos N días).
    * Si H < 0,4: Utilice la lógica contratendencia (comprar mínimos, vender máximos).
* **Salida:** Cambios de régimen de Hurst.
* **Ventaja:** Una “estrategia de estrategias”: no adivina la dirección, determina *cómo* operar en este momento.
### Tendencia Renko sintética (renko_synthetic)
Usar “ladrillos” Renko en lugar de velas para eliminar el ruido del tiempo.
* **Tipo:** Acción del precio (independiente del tiempo).
* **Lógica:** Construir virtualmente ladrillos de tamaño fijo (por ejemplo, 1% del precio). Un nuevo ladrillo aparece sólo si el precio recorre esa distancia; Se ignoran las pequeñas fluctuaciones.
* **Entrada:** Dos ladrillos verdes seguidos después de una serie de ladrillos rojos (inversión de tendencia al alza).
* **Salida:** Aparece un ladrillo rojo (inversión hacia abajo).
* **Borde:** Permite que el robot mantenga las tendencias durante semanas, ignorando el corte lateral que parece aterrador en las velas pero que es una línea plana en Renko.
### Activador Gann Hi-Lo (gann_hilo)
Estrategia de seguimiento de tendencias simple pero efectiva inspirada en Gann.
* **Tipo:** Tendencia / Trailing Stop.
* **Lógica:** Una SMA(3) simple basada en máximos en tendencias bajistas y mínimos en tendencias alcistas.
* **Entrada:** Cierra por encima de la línea del Activador Gann (cambia por debajo del precio).
* **Salir:** Cerrar debajo de la línea.
* **Borde:** Un tope mecánico estricto. Ideal para altcoins con bombas agudas.
### Rechazo de POC del perfil de volumen (vpvr_poc)
Negociar desde niveles de volumen horizontales.
* **Tipo:** Niveles de soporte/resistencia.
* **Lógica:** Calcular el perfil de volumen durante los últimos N días. Encuentre el POC (Punto de Control), el precio con el mayor volumen negociado, el "precio justo".
* **Entrada:**
    1. El precio se acerca a POC desde arriba.
    2. El precio toca POC y rebota (la vela cierra al alza).
    3. Es una prueba de soporte: vaya en largo.
* **Salir:** Porcentaje de ganancia fija o llegar al siguiente Nodo de Bajo Volumen.
* **Ventaja:** Comercia junto a grandes jugadores que defienden posiciones acumuladas en POC.
### Rebote de DCA (promedio de costos en dólares) (dca_martingale)
Estrategia de gestión de capital popular en plataformas bot (3Commas, etc.).
* **Tipo:** Promedio / Cuadrícula.
* **Lógica:** Utiliza recompras en lugar de un stop loss.
* **Entrada:** RSI < 30 (primera entrada con 20% del capital).
* **Gestión:** Si el precio baja un 2%, compre otro 30%. Si cae otro 3%, compre el 50% (martingala/promedio).
* **Salida:** Cuando se alcanza el precio medio de entrada + 1% de beneficio (en el rebote).
* **Ventaja:** Puede cerrar operaciones con ganancias incluso en un mercado a la baja (a través de rebotes), pero el riesgo de liquidación es alto si el precio cae sin retrocesos (se necesita un límite de pérdidas para toda la “bolsa”).
### Comercio de pantalla triple (triple_screen)
El sistema clásico de Alexander Elder.
* **Tipo:** Multi-timeframe (Tendencia + Corrección).
* **Lógica:** Utiliza tres “pantallas” (o multiplicadores de períodos de tiempo en un gráfico).
    1. **Marea (largo plazo):** MACD en el marco temporal x5 muestra la tendencia alcista.
    2. **Ola (mediano plazo):** StochRSI en el período actual está sobrecomprado (un retroceso contra la tendencia).
    3. **Ripple (entrada):** Ruptura del máximo de la vela anterior (cuando finaliza el retroceso).
* **Entrada:** Cuando la “Marea” sube y la “Ola” deja de caer.
* **Salir:** Basado en señales de períodos de tiempo más bajos.
* **Ventaja:** Uno de los filtros comerciales más confiables: opere con la tendencia a largo plazo, pero compre caídas temporales.
## Estrategias combinadas
Gran idea. **Las estrategias combinadas** son el siguiente nivel de evolución para un robot comercial. Los indicadores individuales a menudo producen señales falsas: las estrategias de seguimiento de tendencias sangran en rangos y los osciladores (RSI) salen demasiado pronto de las tendencias.
La combinación de señales le permite filtrar entradas utilizando un principio simple: **“Filtro (tendencia global) + Activador (momento de entrada)”**.
### Método de pantalla triple (triple_screen_custom)
Una adaptación al estilo Elder que combina Trend, Wave y Momentum.
* **Componentes:** EMA (200) + RSI (14) + MACD.
* **Lógica:**
    1. **Filtro:** El precio debe estar **por encima** de EMA 200 (tendencia alcista global).
    2. **Retroceso:** El RSI debe caer por debajo de 50 (corrección local, “descuento”).
    3. **Activador:** El histograma MACD comienza a aumentar (inversión del impulso hacia arriba).
* **Por qué es genial:** Compras con la tendencia, no en la parte superior, y solo después de que se confirme que el retroceso ha terminado.
### Fuga de Bollinger + IMF (bb_mfi_breakout)
Ruptura de volatilidad confirmada por el flujo de dinero.
* **Componentes:** Bandas de Bollinger + Índice de flujo de dinero.
* **Lógica:** Los brotes de BB pueden fingir; El volumen ayuda.
    1. **Activador:** Cierre por encima de la Banda de Bollinger Superior.
    2. **Filtro:** IMF > 60 y en aumento (entrada de dinero). Si el precio supera a BB pero MFI cae, es probable que se trate de una falsificación.
* **Salir:** El precio regresa dentro del canal de Bollinger.
* **Por qué es genial:** Filtra bombas "vacías" sin volumen real de compradores.
### Nube Ichimoku + MACD (ichimoku_macd)
Clásico japonés con confirmación occidental.
* **Componentes:** Ichimoku Kinko Hyo + MACD.
* **Lógica:**
    1. **Filtro (ruptura de Kumo):** Cierra **arriba** de la Nube Ichimoku.
    2. **Activador:** Las líneas MACD se cruzan hacia arriba (cruz dorada).
* **Salir:** El precio vuelve a entrar a la nube.
* **Por qué es genial:** Los brotes de nubes a menudo significan un cambio de tendencia a largo plazo; MACD ayuda a entrar temprano.
### ADX + SAR parabólico (adx_psar)
Busca tendencias fuertes: "No negocies si no tienes fuerzas".
* **Componentes:** ADX + SAR Parabólico.
* **Lógica:** El SAR parabólico dispara constantemente (incluso en rangos). ADX soluciona eso.
    1. **Filtro:** ADX > 25 (fase activa; sin rango).
    2. **Activador:** Los puntos SAR se mueven **por debajo** del precio.
* **Salir:** Los puntos SAR están por encima del precio.
* **Por qué es genial:** Ignoras los mercados débiles y participas sólo cuando arranca el “cohete”.
### Retroceso SMA 50/200 (golden_cross_pullback)
Comercio más inteligente de "Cruz Dorada".
* **Componentes:** SMA 50 + SMA 200.
* **Lógica:** La compra del cruce a menudo va seguida de un retroceso que le impide salir. En lugar de eso:
    1. **Condición:** SMA 50 está por encima de SMA 200 (el cruce ya ocurrió).
    2. **Activador:** El precio toca SMA 50 desde arriba y cierra nuevamente por encima (rebote de soporte).
* **Salir:** Cerrar por debajo de SMA 200.
* **Por qué es genial:** Entrada de menor riesgo con un stop más ajustado: compre la corrección, no las exageraciones.
### Regresión lineal + puntuación Z (stats_arbitrage)
Una combinación matemática (reversión media con esteroides).
* **Componentes:** Pendiente de regresión lineal + Puntuación Z.
* **Lógica:**
    1. **Filtro:** Pendiente de regresión > 0 (expectativa positiva).
    2. **Desencadenante:** Puntuación Z < -2 (desviación a la baja de 2 sigma con respecto a la línea de regresión).
* **Salir:** Z-Score vuelve a 0.
* **Por qué es genial:** Un enfoque científico: comprar un activo que crece *globalmente* pero que es *localmente* injustamente barato.
### Método de pantalla triple (triple_screen_ema)
Una adaptación algorítmica del método de “triple pantalla” de Elder.
* **Lógica:** Utiliza tres tipos de indicadores:
    1. **Marea (largo plazo):** El precio debe estar **por encima** de EMA 200 (o EMA 100). Tendencia mundial alcista.
    2. **Ola (retroceso):** El RSI (14) debe caer por debajo de 50 (o 45). Corrección temporal.
    3. **Ripple (Entrada):** El histograma MACD comienza a subir (o las líneas MACD se cruzan). Extremos de retroceso; Se reanuda el movimiento hacia arriba.
* **Salida:** RSI > 70 o MACD cruza hacia abajo.
* **Por qué es genial:** Conservador y robusto. Filtra las operaciones contratendencia más peligrosas.
### Retroceso de la cruz dorada de SMA (sma_pullback)
Comercio cruzado MA más inteligente: no en el cruce, sino en la nueva prueba.
* **Lógica:**
    1. **Condición:** SMA 50 está por encima de SMA 200 (Golden Cross ya sucedió).
    2. **Activador:** El precio toca SMA 50 desde arriba y rebota (siguiente vela verde).
* **Salir:** Cierre por debajo de SMA 200 (ruptura de tendencia) o una toma de ganancias fija.
* **Por qué es genial:** Comprar justo en el cruce a menudo pierde porque el mercado ya está sobrecalentado. La repetición de la prueba ofrece un riesgo mayor y mejores probabilidades.
### SuperTrend + StochRSI (super_stoch)
Combina un indicador de tendencia superior con un oscilador rápido para entradas de "francotirador".
* **Lógica:**
    1. **Filtro (Tendencia):** SuperTrend (basado en ATR) debe estar en verde (precio por encima de la línea). Sin pantalones cortos.
    2. **Activador (entrada):** StochRSI cae a sobreventa (< 20) y cruza hacia arriba (K cruza D).
* **Salir:** StochRSI entra en sobrecompra (> 80) o SuperTrend cambia a rojo.
* **Por qué es genial:** Opera con la tendencia pero ingresa en retrocesos locales, lo que mejora el riesgo/recompensa.
### Fuga de Bollinger + IMF (bb_mfi)
Ruptura de volatilidad con confirmación de volumen (“dinero inteligente”).
* **Lógica:**
    1. **Activador:** Cierre por encima de la **Banda de Bollinger superior** (expansión de la volatilidad).
    2. **Filtro (Volumen):** MFI > 60 y en aumento. Confirma que la ruptura está respaldada por entradas reales.
* **Salir:** Cerrar nuevamente dentro del canal (por debajo de la banda superior) o MFI cae.
* **Por qué es genial:** Ayuda a distinguir una bomba real de una trampa de creador de mercado (falsa).
### Regresión lineal + puntuación Z (linreg_zscore)
Reversión media 2.0 (estadísticas puras).
* **Lógica:**
    1. **Filtro (Dirección):** La pendiente de regresión (más de 50 a 100 velas) es positiva.
    2. **Disparador (desviación):** Z-Score cae por debajo de -2 (estadísticamente barato frente a su propia tendencia).
* **Salir:** Z-Score vuelve a 0 (línea media).
* **Por qué es genial:** No es adivinar velas, es pura estadística. Compre un activo en alza a nivel mundial que tenga un descuento local.
### El sistema de tendencias "Fortaleza" (trend_momentum_volatility_volume)
El sistema “Fortaleza”: cuatro capas de protección contra oficios tontos.
* **Componentes:** EMA 200 + MACD + Bandas de Bollinger + OBV.
* **Lógica:**
    1. **Filtro global:** Precio > EMA 200 (negocie solo la tendencia alcista).
    2. **Volatilidad:** El precio toca o rompe la línea media de BB (retroceso al precio justo).
    3. **Volumen:** OBV está por encima de su MA (el dinero no sale durante el retroceso).
    4. **Activador:** El histograma MACD cambia de rojo a verde (el impulso regresa).
* **Salir:** Toque el BB superior o el MACD cruza hacia abajo.
* **Por qué es genial:** Solo compras retrocesos confirmados por volumen dentro de una tendencia alcista reforzada.
### El "cuero cabelludo perfecto" (heikin_ashi_ema_stochrsi_atr)
Reventa con filtro de ruido.
* **Componentes:** Heikin Ashi (virtual) + EMA 50 + EMA 100 + StochRSI + ATR.
* **Lógica:**
    1. **Túnel:** EMA 50 está por encima de EMA 100 y la distancia está aumentando (tendencia fuerte).
    2. **Patrón:** La vela Heikin Ashi cambia de rojo a verde.
    3. **Desencadenante:** StochRSI cruza por debajo de 40.
    4. **Stop loss:** Fijado en 2xATR desde la entrada.
* **Salir:** Heikin Ashi se pone rojo.
* **Por qué es genial:** Heikin Ashi elimina el ruido; La EMA dual evita la especulación contra un tren.
### Cazador de divergencias Pro (rsi_cci_mfi_ema)
Caza de reversiones con triple confirmación (convergencia del oscilador).
* **Componentes:** EMA 200 + RSI (14) + CCI (20) + MFI (14).
* **Lógica:**
    1. **Contexto:** Precio por encima de EMA 200 (buscando un fondo de corrección local).
    2. **Sincronización:**
        * RSI < 30 (precio sobrevendido).
        * CCI < -100 (desviación anormal).
        * MFI < 20 (sobreventa de volumen/pánico).
    3. **Entrada:** Los tres indicadores aparecen juntos.
* **Salir:** Cualquiera de los tres alcanza sobrecompra.
* **Por qué es genial:** La probabilidad de que tres osciladores matemáticos diferentes (precio, desviación, volumen) fallen a la vez es baja.
### Apretón avanzado (bollinger_keltner_momentum_adx)
Una variante avanzada de TTM Squeeze para movimientos explosivos.
* **Componentes:** Bandas de Bollinger + Canales de Keltner + Momentum + ADX.
* **Lógica:**
    1. **Apretar:** Bandas de Bollinger completamente dentro del canal Keltner: volatilidad en un mínimo crítico.
    2. **Acumulación:** ADX < 20 (el mercado está “durmiendo”).
    3. **Desencadenante:** Las Bandas de Bollinger salen del Canal Keltner + ADX comienza a subir bruscamente.
    4. **Dirección:** Momento > 0.
* **Salir:** El impulso comienza a caer.
* **Por qué es genial:** Se gana mucho dinero cuando el mercado pasa del sueño a la explosión; este combo apunta a esa transición.
### Ichimoku "Tres por tres" (tenkan_kijun_cloud_chikou_rsi)
Usando el conjunto completo de señales Ichimoku más un filtro de sobrecompra.
* **Componentes:** Ichimoku Cloud (todas las líneas) + RSI.
* **Lógica:**
    1. **Ruptura:** Cerrar por encima de la Nube (rrupción de Kumo).
    2. **Cruz:** Tenkan cruza a Kijun de abajo hacia arriba (TK Cross).
    3. **Confirmación rezagada:** Chikou Span está por encima del precio hace 26 períodos (confirmación de tendencia).
    4. **Filtro:** RSI < 70 (mercado no sobrecalentado).
* **Salida:** Tenkan cruza por debajo de Kijun o el precio ingresa a la nube.
* **Por qué es genial:** Uno de los sistemas japoneses más antiguos y respetados. El uso de todas las piezas hace que las entradas sean más raras pero más fuertes.
### Estrategia institucional VWAP (vwap_ema_volume_profile_rsi)
Negociar “como una ballena” utilizando precios ponderados por volumen.
* **Componentes:** VWAP + EMA 50 + Perfil de volumen fijo (POC) + RSI.
* **Lógica:**
    1. **Tendencia:** Precio > EMA 50.
    2. **Valor:** El precio retrocede hacia VWAP (regreso al precio “justo” del día).
    3. **Nivel:** El precio está en una zona de alto volumen (protección POC del perfil de volumen).
    4. **Desencadenante:** El RSI sube de 40 a 50.
* **Salir:** El precio se aleja demasiado del VWAP (movimiento de desviación estándar).
* **Por qué es genial:** VWAP lo utilizan algos institucionales. Operar con VWAP significa comerciar con ellos, no contra ellos.
### El "Francotirador de tendencias" (parabolic_sar_adx_ema_macd)
Capturando tendencias desbocadas (carreras parabólicas).
* **Componentes:** SAR Parabólico + ADX + EMA 100 + MACD.
* **Lógica:**
    1. **Global:** Precio > EMA 100.
    2. **Fuerza:** ADX > 30 y en aumento (tendencia muy fuerte).
    3. **Activador:** Los puntos SAR están por debajo del precio.
    4. **Filtro:** MACD > 0 e histograma ascendente.
* **Regla especial:** Mientras el ADX esté subiendo, ignore las pequeñas señales de venta.
* **Salir:** El ADX comienza a caer (la tendencia se debilita) O el SAR cambia.
* **Por qué es genial:** Exprime al máximo los repuntes parabólicos (por ejemplo, BTC 20k→30k) sin salir en la primera vela roja.
### El sistema "Ruta de las Ballenas" (volume_trend_value)
Siguiendo al gran jugador (“ballena”).
* **Componentes:** VWAP + Chaikin Money Flow (CMF) + EMA 200 + Pivot Points.
* **Lógica:**
    1. **Tendencia global:** Precio > EMA 200.
    2. **Precio justo:** El precio está por encima (o se vuelve a probar desde arriba) VWAP: los compradores controlan la subasta intradiaria.
    3. **Flujo de dinero:** CMF > 0 y creciente (acumulación).
    4. **Activador:** Ruptura de la resistencia del Pivote más cercana (R1/R2).
* **Salida:** CMF cae por debajo de cero o el precio cierra por debajo de VWAP.
* **Por qué es genial:** No intercambias “patrones”; usted comercia con flujo de dinero institucional real.
### La reversión de la "banda elástica" (mean_reversion_trend_filter)
Captar retrocesos profundos en una fuerte tendencia alcista (el “tirachinas”).
* **Componentes:** Canales Keltner + RSI (2) + SMA 100 + Patrón envolvente.
* **Lógica:**
    1. **Filtro:** SMA 100 con pendiente estrictamente alcista (fuerte tendencia alcista).
    2. **Estiramiento:** El precio cae por debajo de la línea inferior de Keltner (desviación extrema).
    3. **Sobreventa:** El RSI(2) cae por debajo de 5.
    4. **Activador:** La vela se cierra nuevamente dentro del canal + se forma una envolvente alcista.
* **Salida:** El precio toca la línea de Keltner media o superior.
* **Por qué es genial:** Tasa de ganancias muy alta. Compras miedo (dumping) en un contexto de codicia (tendencia alcista).
### El "Tsunami Guppy" (gmma_adx)
Una estrategia de tendencia visual que utiliza múltiples promedios móviles (GMMA).
* **Componentes:** GMMA (12 MA: 6 rápidos, 6 lentos) + ADX.
* **Lógica:**
    1. **Compresión:** Los grupos MA rápidos y lentos convergen (la volatilidad cae; el mercado se comprime).
    2. **Tsunami (Expansión):** Los MA rápidos se separan marcadamente hacia arriba de los MA lentos.
    3. **Confirmación:** Las AM lentas también comienzan a expandirse (la tendencia se vuelve sostenible).
    4. **Filtro:** ADX > 20 y en aumento.
* **Salir:** Los MA rápidos comienzan a cruzar hacia abajo a través de MA lentos (compresión).
* **Por qué es genial:** Capta fases de tendencias explosivas e ignora retrocesos menores mientras la “escuela” de MA apunta hacia arriba.
### El canal "Regresión cuántica" (linear_reg_pearson_r_atr)
Comercio de canales con base matemática.
* **Componentes:** Canal de regresión lineal (100) + Coeficiente de correlación de Pearson (r) + Trailing Stop ATR.
* **Lógica:**
    1. **Calidad de la tendencia:** Pearson r > 0,7 (el precio se comporta como una línea ascendente: crecimiento estable sin caos).
    2. **Compre barato:** El precio toca el límite inferior del canal de regresión (2 desviaciones estándar).
    3. **Desencadenante:** El precio rebota desde el límite inferior.
* **Salir:** El precio toca el límite superior o los activadores de parada ATR.
* **Por qué es genial:** Opera solo con tendencias estables y "hermosas" y filtra gráficos desordenados con matemáticas.
### El "Caos Dorado" (ichimoku_bill_williams_fractals_ao)
Una combinación de sabiduría oriental y teoría del caos.
* **Componentes:** Nube Ichimoku + Fractales + Oscilador impresionante (AO).
* **Lógica:**
    1. **Zona de seguridad:** Precio > Nube Ichimoku.
    2. **Energía:** AO es verde y está por encima de cero.
    3. **Desencadenante:** El precio rompe el último fractal alcista (máximo local).
* **Salir:** Cerrar debajo de Ichimoku Tenkan o AO se vuelve rojo (en secuencia).
* **Por qué es genial:** Los fractales brindan un precio de entrada preciso (orden pendiente) e Ichimoku garantiza que no lucharás contra la tendencia global.
### El sistema "Velocidad" (hull_ma_laguerre_rsi_volatility_stop)
Un sistema de especulación ultrarrápido para pares volátiles (ETH, SOL).
* **Componentes:** Media móvil del casco (HMA) + Laguerre RSI + Volatility Stop (VSTOP).
* **Lógica:**
    1. **Velocidad:** HMA se vuelve verde (reacción instantánea al alza).
    2. **Impulso:** Laguerre RSI cruza por encima de 0,2 (salga por debajo).
    3. **Protección:** El precio está por encima de VSTOP.
* **Salir:** HMA se vuelve rojo o VSTOP se rompe.
* **Por qué es genial:** Los indicadores clásicos se retrasan. Esta combinación utiliza herramientas de retraso mínimo para ser el primero en moverse.
### La "Confluencia de Fibonacci" (auto_fibs_ema_50_stochastic)
Negociación de retroceso automatizada hacia la “proporción áurea”.
* **Componentes:** Retroceso automático de Fibonacci + EMA 50 + Estocástico.
* **Lógica:**
    1. **Contexto:** Precio > EMA 50.
    2. **Nivel:** El precio se corrige a Fib 0,5 o 0,618 (“Golden Pocket”) del último impulso.
    3. **Desencadenante:** El estocástico está sobrevendido y cruza hacia arriba.
* **Salida:** Objetivo en 0 (máximo anterior) o -0,27 (extensión de Fib).
* **Por qué es genial:** Una de las configuraciones discrecionales más populares: el bot automatiza la búsqueda de entradas ideales.
## Recomendaciones
**Recomendación general:**
Concéntrese en entre 3 y 5 estrategias que cubran diferentes regímenes de mercado (tendencia, rango, impulso, volumen). Priorice los sistemas multifactoriales, luego los filtros combinados fuertes y solo después los indicadores y patrones únicos.
## Implementación de la estrategia
- [X] **RSI + Bandas de Bollinger** (rsi_bb)
- [X] **MACD** (macd)
- [X] **RSI Básico** (rsi_basic)
- [X] **Cruce SMA** (sma_cross)
- [X] **El sistema de tendencias "Fortaleza"** (trend_momentum_volatility_volume)
- [X] **Cazador de divergencias Pro** (rsi_cci_mfi_ema)
- [X] **El sistema "Sendero de ballenas"** (volume_trend_value)
- [X] **La inversión de la "banda elástica"** (mean_reversion_trend_filter)
- [X] **El "Tsunami Guppy"** (gmma_adx)
- [X] **Pantalla triple (EMA+RSI+MACD)** (triple_screen_ema)
- [X] **SuperTrend + StochRSI** (super_stoch)
- [X] **ADX + SAR parabólico** (adx_psar)
- [X] **Índice de agitación + EMA** (chop_ema)
- [X] **EMA + StochRSI** (ema_stoch)
- [X] **Ciclo de tendencia Schaff** (stc_cycle)
- [X] **Tendencia VWAP** (vwap_cross)
- [] **Flujo de dinero de Chaikin (CMF)** (cmf_trend)
- [ ] **Pendiente de regresión lineal** (lin_reg)
- [ ] **Puntuación Z** (puntuación_z)
- [ ] **SuperTrend** (supertendencia)
- [] **Fuga del canal Donchian** (donchian)
- [ ] **SAR parabólico** (psar)
- [] **Empuje dual** (empuje_dual)
- [] **Ruptura del rango de apertura** (orb_strat)
- [] **Bolsillo dorado de Fibonacci** (fib_golden)
- [] **Aprieta el impulso** (lazybear_squeeze)
- [] **Rebote DCA** (dca_martingale)
- [] **Gann Hola-Bajo** (gann_hilo)
- [] **McGinley Dinámico** (mcginley)
- [] **MA adaptativo de Kaufman** (kama_trend)
- [ ] **Vórtice** (vórtice)
- [ ] **Índice de flujo monetario (IMF)** (mfi_div)
- [ ] **Stoch RSI** (stoch_rsi)
- [ ] **TEMA Cruz** (tema_cross)
- [ ] **MA del casco** (hma_trend)
- [] **Connors RSI 2** (rsi_2)
- [] **Divergencia RSI** (rsi_div)
- [] **Barra interior** (barra_interior)
- [ ] **Pinbar** (pinbar_reversal)
- [] **Patrón envolvente** (engulfing_candle)
- [ ] **Tres soldados blancos / Tres cuervos negros** (candle_patterns)
- [] **Tendencia Heikin Ashi** (ha_trend)
- [] **Apretón de la banda de Bollinger** (bb_squeeze)
- [] **Ichimoku Cloud Breakout** (ichimoku)
- [ ] **ADX + DMI** (adx_dmi)
- [ ] **Tendencia OBV** (obv_trend)
- [] **Retroceso del canal Keltner** (keltner_pullback)
- [] **Oscilador impresionante** (ao_saucer)
- [] **Corrección CCI** (cci_corrección)
- [] **Índice de fuerza del anciano** (elder_force)
- [ ] **Williams %R** (williams_r)
- [ ] **Tasa de cambio** (roc)
- [] **Desglose del canal ATR** (volty_channel)
- [] **Estrategia Aroon** (aroon)
- [ ] **TRIX (Promedio exponencial triple)** (trix_strat)
- [ ] **Curva de Coppock** (coppock)
- [ ] **Índice de canales de productos básicos** (cci_trend)
- [] **VWMA frente a SMA** (vwma_cross)
- [] **Fractales de Williams** (fractal_breakout)
- [] **Bandas de Fibonacci Bollinger** (fib_bands)
- [] **Estrategia de salida de candelabro** (chandelier_trend)
- [ ] **TD Secuencial (Simplificado)** (td_seq)
- [] **Transformación de Ehlers Fisher** (fisher_trans)
- [ ] **Canal de desviación estándar** (std_channel)
- [] **Inversión de puntos de pivote** (pivot_rev)
- [ ] **Williams Alligator** (cocodrilo)
- [] **Oscilador de impulso Chande** (cmo_strat)
- [ ] **Facilidad de movimiento (EOM)** (eom_trend)
- [] **Saber algo seguro (KST)** (kst_momentum)
- [] **Promedio móvil adaptativo fractal (FRAMA)** (frama_trend)
- [] **Tendencia de precios por volumen (VPT)** (vpt_cross)
- [ ] **Laguerre RSI** (laguerre_rsi)
- [ ] **Oscilador de precios sin tendencia (DPO)** (dpo_cycle)
- [ ] **Índice de facilitación del mercado** (bw_mfi)
- [ ] **Línea Psicológica** (psy_line)

- [] **Índice de caminata aleatoria** (rwi_trend)
- [ ] **Estrategia de índice de úlceras** (ulcer_strat)
- [] **k-Coincidencia de patrones de vecinos más cercanos (kNN)** (knn_ml)
- [] **Teoría de la caja de Darvas** (darvas_box)
- [] **Índice Elder-Ray** (elder_ray)
- [ ] **Centro de gravedad** (cog_ehlers)
- [] **Entropía de Shannon** (entropía_caos)
- [ ] **Índice de vigor relativo** (rvi_trend)
- [ ] **VSTOP (Parada de volatilidad)** (vstop_trend)
- [] **Estrategia del exponente de Hurst** (hurst_exponent)
- [] **Tendencia Renko sintética** (renko_synthetic)
- [] **Rechazo de POC del perfil de volumen** (vpvr_poc)
- [] **Comercio de pantalla triple** (triple_screen)
- [] **Método de pantalla triple** (triple_screen_custom)
- [] **Ruptura de Bollinger + IMF** (bb_mfi_breakout)
- [] **Nube Ichimoku + MACD** (ichimoku_macd)
- [] **SMA 50/200 Retroceso** (golden_cross_pullback)
- [] **Regresión lineal + puntuación Z** (stats_arbitrage)
- [] **SMA Golden Cross Pullback** (sma_pullback)
- [] **Ruptura de Bollinger + IMF** (bb_mfi)
- [] **Regresión lineal + puntuación Z** (linreg_zscore)
- [ ] **El "cuero cabelludo perfecto"** (heikin_ashi_ema_stochrsi_atr)
- [] **Squeeze avanzado** (bollinger_keltner_momentum_adx)
- [] **Ichimoku "Tres"** (tenkan_kijun_cloud_chikou_rsi)
- [ ] **Estrategia Institucional VWAP** (vwap_ema_volume_profile_rsi)
- [ ] **El "Francotirador de tendencias"** (parabolic_sar_adx_ema_macd)
- [] **El canal "Regresión cuántica"** (linear_reg_pearson_r_atr)
- [ ] **El "Caos Dorado"** (ichimoku_bill_williams_fractals_ao)
- [ ] **El sistema "Velocidad"** (hull_ma_laguerre_rsi_volatility_stop)
- [ ] **La "Confluencia de Fibonacci"** (auto_fibs_ema_50_stochastic)
