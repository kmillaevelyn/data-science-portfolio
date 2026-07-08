# KNN do Zero com Validação Cruzada

Implementação do algoritmo **K-Nearest Neighbors do zero** (sem scikit-learn no núcleo do modelo), com validação cruzada para seleção do hiperparâmetro k, aplicada ao dataset EMNIST.

## Objetivo

Demonstrar a compreensão dos mecanismos internos do KNN — cálculo de distâncias, votação por vizinhança e o trade-off viés-variância na escolha de k — em vez de apenas consumir a API pronta.

## Resultado

- **99,12% de acurácia no EMNIST filtrado**
- Implementação 100% NumPy: função de distância, votação e predição escritas à mão
- Validação cruzada k-fold para selecionar o melhor k e avaliar a estabilidade do modelo
- Matriz de confusão construída do zero

## Tecnologias

`Python` · `NumPy` · `pandas` · `Matplotlib`

## Notebook

📓 [`knn-do-zero-validacao-cruzada.ipynb`](./knn-do-zero-validacao-cruzada.ipynb) — com badge para abrir direto no Colab.

---

*Parte do portfólio de Data Science de [Kamilla Evelyn](https://kmillaevelyn.github.io).*
