# Data Science Portfolio · Kamilla de Paula

Repositório central dos meus projetos de **Dados, Machine Learning e IA Aplicada**, desenvolvidos ao longo do Bacharelado em Ciência e Tecnologia (UNIFEI) e de estudos independentes — com base de domínio real em **Supply Chain e PCM** na indústria.

Cada projeto resolve um problema real: da classificação de imagens térmicas de motores industriais à análise de sentimento em reviews de e-commerce.

## Trajetória

| Período | Marco | Projeto |
|---|---|---|
| 2024 | Primeiros passos em Python | [`03-fundamentos`](./03-fundamentos) |
| 2025 | Dashboards interativos e análise de dados | [`dashboard-mercado-vagas-linkedin`](./02-dashboards-visualizacao/dashboard-mercado-vagas-linkedin) · [`dashboard-saude-academica`](./02-dashboards-visualizacao/dashboard-saude-academica) |
| 2026 | Machine Learning e NLP aplicados | [`classificacao-acoes-petr4-knn`](./01-machine-learning/classificacao-acoes-petr4-knn) · [`knn-do-zero-validacao-cruzada`](./01-machine-learning/knn-do-zero-validacao-cruzada) · [`classificacao-termica-motores-pi5`](./01-machine-learning/classificacao-termica-motores-pi5) · [`analise-sentimento-b2w`](./01-machine-learning/analise-sentimento-b2w) |

## Projetos em destaque

### 🧠 Machine Learning & NLP
- **[Análise de Sentimento B2W/Americanas](./01-machine-learning/analise-sentimento-b2w)**: NLP em PT-BR sobre reviews reais de e-commerce — ML supervisionado com **89,90% de acurácia** vs. 72,07% da baseline léxica.
- **[KNN do zero + Validação Cruzada](./01-machine-learning/knn-do-zero-validacao-cruzada)**: implementação 100% NumPy do KNN, validação cruzada 3-fold e matriz de confusão nativas. Acurácia de 99,12% no EMNIST filtrado.
- **[Ensemble de Classificadores](./01-machine-learning/ensemble-classificadores)**: benchmark de 5 algoritmos (KNN, Árvore, Random Forest, SVM Linear e Polinomial) com GridSearchCV e voto majoritário.
- **[Classificação de Tendências PETR4 (B3)](./01-machine-learning/classificacao-acoes-petr4-knn)**: KNN sobre dados reais via yfinance, com StandardScaler e painel ipywidgets.
- **[Classificação Térmica de Motores (PI5)](./01-machine-learning/classificacao-termica-motores-pi5)**: visão computacional aplicada à manutenção preditiva na Indústria 4.0.

### 📊 Dashboards & Visualização
- **[Impacto da IA em Estudantes](./02-dashboards-visualizacao/dashboard-impacto-ia-estudantes)**: Streamlit + Plotly com deploy via Cloudflare Tunnel.
- **[Mercado de Vagas de Tecnologia](./02-dashboards-visualizacao/dashboard-mercado-vagas-linkedin)**: mineração de texto sobre vagas do LinkedIn.
- **[Hábitos de Estudo e Saúde Acadêmica](./02-dashboards-visualizacao/dashboard-saude-academica)**: análise exploratória interativa de 31 variáveis.
- **[Análise de Grafos & Clustering](./02-dashboards-visualizacao/analise-grafos-clustering)**: NetworkX + clustering hierárquico (SciPy).

### 🏭 Engenharia de Produto
- **[Hidrotech](./04-engenharia-de-produto/hidrotech)**: desenvolvimento de produto IoT (ducha inteligente) com especificações de fabricação e **simulador de viabilidade econômica** (economia ~R$ 20/mês, payback ~44 meses).

### 🚚 Supply Chain & PCM
- **[Compras Estratégicas e Planejamento](./05-supply-chain-pcm)**: framework de compras hospitalares e industriais com resultados anonimizados — **25–30% de redução de custo em EPIs** e **12% em materiais de limpeza**.

## Stack

`Python` `NumPy` `Pandas` `scikit-learn` `spaCy` `Streamlit` `Plotly` `Matplotlib` `Seaborn` `ipywidgets` `NetworkX` `SciPy` `yfinance`

## Sobre mim

Assistente de Planejamento (PCM) na indústria e estudante de BCTec na UNIFEI, unindo Supply Chain, dados e IA aplicada.

- Portfólio: [kmillaevelyn.github.io](https://kmillaevelyn.github.io)
- LinkedIn: [linkedin.com/in/kmillaevelyn](https://www.linkedin.com/in/kmillaevelyn/)
