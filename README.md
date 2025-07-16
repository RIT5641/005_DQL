# Deep Q-Learning para Trading Algorítmico en Bitcoin
Este proyecto implementa un agente de Deep Q-Learning (DQN) para operar de forma automática sobre Bitcoin utilizando aprendizaje por refuerzo. El objetivo principal es comparar el desempeño de un agente RL entrenado con una estrategia tradicional de Buy & Hold, analizando sus resultados y limitaciones en un entorno financiero realista.
## Descripción

Se utiliza un notebook en Python (Jupyter) que incluye:
Descarga y procesamiento de datos históricos del ETF (QQQ) usando `yfinance`.
Definición del entorno de trading personalizado.
Implementación del agente DQN desde cero con PyTorch.
Entrenamiento, backtesting y análisis de métricas (retorno, Sharpe, drawdown, etc.).
Comparación con Buy & Hold y visualizaciones detalladas.

## Estructura del proyecto

/005_DQL_INT_Final_Project/

│

├── 005_DQL_INT_Final_Project.ipynb  

├── README.md

├── .gitignore

└── requirements.txt         

## Requisitos

Python 3.8+
Jupyter Notebook
numpy, pandas, matplotlib, yfinance
torch (PyTorch)
Dependencias recomendadas con:
```bash
pip install numpy pandas matplotlib yfinance torch
