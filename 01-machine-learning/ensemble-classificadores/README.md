# Ensemble de Classificadores

Benchmark sistemático de **5 algoritmos de classificação** — KNN, Árvore de Decisão, Random Forest, SVM Linear e SVM Polinomial — com otimização de hiperparâmetros via **GridSearchCV** e combinação final por **voto majoritário**.

## Objetivo

Responder a uma pergunta prática de ML: quando vale a pena combinar modelos? O notebook compara cada classificador individualmente e mede se o ensemble por votação supera o melhor modelo isolado.

## O que o notebook cobre

- Pipeline de pré-processamento e padronização dos dados
- GridSearchCV para tuning de hiperparâmetros de cada algoritmo
- Comparação de métricas entre os 5 classificadores
- Ensemble por voto majoritário e análise do ganho (ou não) sobre os modelos individuais

## Tecnologias

`Python` · `scikit-learn` · `pandas` · `NumPy` · `Matplotlib`

## Status

📓 Notebook em publicação — o arquivo `.ipynb` será adicionado a esta pasta em seguida.

---

*Parte do portfólio de Data Science de [Kamilla Evelyn](https://kmillaevelyn.github.io).*
