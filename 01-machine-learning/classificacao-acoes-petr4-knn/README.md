# Classificação de Tendências PETR4 (B3) com KNN

Modelo de K-Nearest Neighbors aplicado a **dados reais da PETR4** coletados via `yfinance`, com padronização de features (`StandardScaler`) e painel interativo em `ipywidgets` para classificar tendências do ativo.

- **Pipeline:** coleta de dados históricos → engenharia de features → padronização → treino/teste → classificação interativa
- **Stack:** yfinance, Pandas, scikit-learn, ipywidgets

📓 [`classificacao-petr4-knn.ipynb`](./classificacao-petr4-knn.ipynb) — notebook completo, com todos os gráficos e saídas.
