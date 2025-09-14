
Linear Regression Trading Bot 2.0
This project is an automated trading bot and backtesting framework designed to analyze and trade in the stock market using a strategy that combines linear regression with key technical indicators. It is ideal for quantitative trading enthusiasts and developers looking to explore algorithmic strategies with Python.

Key Features
Complex Trading Strategy: The bot generates buy and sell signals based on a combination of three indicators:

Linear Regression: Identifies the underlying trend of an asset. Signals are triggered when the closing price crosses above or below the regression line with a configurable threshold.

Moving Averages (MA): Uses a 50- and 200-day Moving Average crossover to confirm short- and long-term trends.

Relative Strength Index (RSI): The bot uses the RSI to avoid trading in overbought or oversold conditions, filtering signals to reduce risk.

Integrated Risk Management: Includes a stop-loss function to limit potential losses on each trade.

Robust Backtesting Framework: The backtesting function evaluates the strategy's performance on historical data, calculating cumulative returns and the evolution of the portfolio value over time.

Parameter Optimization: The bot is designed to automatically optimize the threshold and stop_loss_percentage parameters to find the most profitable combination.

Clear Visualizations: Generates performance charts of the strategy against the "Buy and Hold" strategy and heatmaps of parameter optimization for easy understanding of the results.

Technologies and Libraries Used
Pandas: For data manipulation and analysis.

NumPy: For efficient numerical operations.

yfinance: To download historical price data for financial assets.

scikit-learn: The linear regression library for the bot's prediction component.

Matplotlib and Seaborn: For data visualization and backtesting.

Project Structure
generate_signals_with_ma_refined: A function that implements the trading logic and generates buy or sell signals based on the indicators and stop-loss.

run_backtest: A function that simulates the strategy's performance on past data and calculates profits or losses.

Parameter Optimization Section: A loop that iterates through different combinations of threshold and stop-loss to find the optimal parameters.

Final Backtesting Section: A final backtest of the strategy using the optimal parameters on a list of different assets.

This bot is not investment advice but an educational tool to explore the backtesting of quantitative trading strategies.
______________________________________________________________

Trading Bot de Regresión Lineal 2.0
Este proyecto es un bot de trading automatizado y un marco de backtesting diseñado para analizar y operar en el mercado de valores utilizando una estrategia que combina la regresión lineal con indicadores técnicos clave. Es ideal para entusiastas del trading cuantitativo y desarrolladores que buscan explorar estrategias algorítmicas con Python.

Características Principales
Estrategia de Trading Compleja: El bot genera señales de compra y venta basándose en una combinación de tres indicadores:

Regresión Lineal: Identifica la tendencia subyacente de un activo. Las señales se activan cuando el precio de cierre cruza por encima o por debajo de la línea de regresión con un umbral configurable.

Medias Móviles (MA): Utiliza un cruce de Medias Móviles de 50 y 200 días para confirmar la tendencia a corto y largo plazo.

Índice de Fuerza Relativa (RSI): El bot utiliza el RSI para evitar operar en condiciones de sobrecompra o sobreventa, filtrando así las señales para reducir el riesgo.

Gestión de Riesgos Integrada: Incluye una función de stop-loss para limitar las pérdidas potenciales en cada operación.

Marco de Backtesting Robusto: La función de backtesting evalúa el rendimiento de la estrategia en datos históricos, calculando el rendimiento acumulado y la evolución del valor de la cartera a lo largo del tiempo.

Optimización de Parámetros: El bot está diseñado para optimizar de forma automática los parámetros threshold (umbral) y stop_loss_percentage (porcentaje de stop-loss) para encontrar la combinación más rentable.

Visualizaciones Claras: Genera gráficos de rendimiento de la estrategia frente a la estrategia de "comprar y mantener" (Buy and Hold) y mapas de calor de la optimización de parámetros para una fácil comprensión de los resultados.

Tecnologías y Librerías Utilizadas
Pandas: Para la manipulación y análisis de datos.

NumPy: Para operaciones numéricas eficientes.

yfinance: Para descargar datos históricos de precios de activos financieros.

scikit-learn: La biblioteca de regresión lineal para el componente de predicción del bot.

Matplotlib y Seaborn: Para la visualización de datos y el backtesting.

Estructura del Proyecto
generate_signals_with_ma_refined: Una función que implementa la lógica de trading y genera señales de compra o venta en función de los indicadores y el stop-loss.

run_backtest: Una función que simula el rendimiento de la estrategia en datos pasados y calcula las ganancias o pérdidas.

Sección de Optimización de Parámetros: Un bucle que itera a través de diferentes combinaciones de umbral y stop-loss para encontrar los parámetros óptimos.

Sección de Backtesting Final: Un backtest final de la estrategia utilizando los parámetros óptimos en una lista de diferentes activos.

Este bot no es un consejo de inversión, sino una herramienta educativa para explorar el backtesting de estrategias de trading cuantitativo.
