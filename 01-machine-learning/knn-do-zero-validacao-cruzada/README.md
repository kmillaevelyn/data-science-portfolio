# KNN do Zero com Validação Cruzada

Implementação do algoritmo **K-Nearest Neighbors do zero** (sem scikit-learn no núcleo do modelo), com validação cruzada para seleção do hiperparâmetro k.

## Objetivo

Demonstrar a compreensão dos mecanismos internos do KNN — cálculo de distâncias, votação por vizinhança e o trade-off viés-variância na escolha de k — em vez de apenas consumir a API pronta.

## O que o notebook cobre

- Implementação manual da distância euclidiana e da lógica de classificação
- - Validação cruzada k-fold para avaliar a estabilidade do modelo
  - - Comparação de desempenho entre diferentes valores de k
    - - Comparação do resultado com a implementação de referência do scikit-learn
     
      - ## Tecnologias
     
      - `Python` · `NumPy` · `pandas` · `Matplotlib` · `scikit-learn (benchmark)`
     
      - ## Status
     
      - 📓 Notebook em publicação — o arquivo `.ipynb` será adicionado a esta pasta em seguida.
     
      - ---

      *Parte do portfólio de Data Science de [Kamilla Evelyn](https://kmillaevelyn.github.io).*
