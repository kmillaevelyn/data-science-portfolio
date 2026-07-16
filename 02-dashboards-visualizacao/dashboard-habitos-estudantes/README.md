# Dashboard — Hábitos e Desempenho de Estudantes

Dashboard exploratório sobre o dataset `enhanced_student_habits_performance`, com detecção automática de coluna temporal e quatro visualizações configuráveis pelo usuário.

## O que o notebook cobre

- Carregamento com cache (`@st.cache_data`) e filtro por ano quando há coluna de data
- Gráficos de linha, barras, dispersão e pizza com seleção dinâmica de variáveis
- Deploy via ngrok com token no cofre do Colab (`userdata`) — sem credencial no código

## Tecnologias

`Python` · `pandas` · `Streamlit` · `Matplotlib` · `Seaborn`

## Notebook

📓 [`dashboard-habitos-estudantes.ipynb`](./dashboard-habitos-estudantes.ipynb)

---

*Parte do portfólio de Data Science de [Kamilla Evelyn](https://kmillaevelyn.github.io).*
