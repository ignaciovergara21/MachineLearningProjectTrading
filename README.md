# MachineLearningProjectTrading

Este proyecto utiliza Machine Learning (XGBoost) para predecir movimientos de precio a corto plazo en las acciones de Apple (AAPL) y ejecutar una estrategia de trading algorítmico automatizada.

🎯 Objetivo
Desarrollar un modelo de clasificación capaz de predecir si el retorno del siguiente día superará un umbral específico (0.3%), combinando indicadores técnicos de precio y volumen para superar la estrategia pasiva de Buy & Hold.

🛠️ Stack Tecnológico
Lenguaje: Python 3.x

Librerías principales: XGBoost, Pandas, Scikit-Learn, YFinance, Streamlit.

Visualización: Plotly y Matplotlib.

Optimización: Búsqueda de hiperparámetros (Optuna/GridSearch).

📊 Características del Modelo (Features)
El modelo se basa en 6 variables clave que capturan la estructura del mercado:

Momentum: Returns, ROC (Rate of Change).

Volatilidad: Daily Range (High-Low).

Volumen: Volumen Relativo, MFI (Money Flow Index), Volume Force.

🚀 Resultados Clave
Modelo Ganador: XGBoost (125 estimadores, LR 0.04).

Recall: 89% (Alta capacidad para detectar oportunidades de subida).

Estrategia: Combinación de predicción ML + Filtro de tendencia (EMA30).

Interfaz: Dashboard interactivo en Streamlit que permite realizar backtesting en tiempo real cambiando el ticker y el umbral de rentabilidad.

💻 Instalación y Uso
