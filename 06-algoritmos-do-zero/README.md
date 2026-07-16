# Algoritmos do Zero — sem bibliotecas de ML

Três implementações construídas **sem scikit-learn, sem scipy de atalho**: só NumPy, estruturas de dados e a matemática por trás de cada método. O restante do portfólio mostra que sei usar as ferramentas; esta seção mostra que sei o que existe dentro delas.

## O que está aqui

| Notebook | O que implementa | Núcleo técnico |
|---|---|---|
| [`busca-ucs-bfs-dfs-romenia`](./busca-ucs-bfs-dfs-romenia/) | Três estratégias de busca em grafos no mapa clássico da Romênia (Russell & Norvig) | UCS com `heapq`, BFS com `deque`, DFS com pilha — custo ótimo vs. completude vs. memória |
| [`regressao-linear-populacao-pouso-alegre`](./regressao-linear-populacao-pouso-alegre/) | Mínimos quadrados calculado na mão (Sx, Sy, Sxy, Sxx) sobre a população da minha cidade | Regressão linear sem `sklearn.linear_model` · previsão 2025 |
| [KNN Nativo + Validação Cruzada →](../01-machine-learning/knn-do-zero-validacao-cruzada/) | KNN completo em NumPy puro, com validação cruzada 3-fold e matriz de confusão nativas | Distância euclidiana vetorizada, votação por `bincount` · **99,12% no EMNIST** |

## Por que isso importa

Chamar `.fit()` é fácil. Saber **por que** o UCS garante o caminho ótimo e o DFS não, **como** a validação cruzada evita o overfitting do K, e **de onde** saem os coeficientes de uma regressão — é o que separa usar ferramenta de entender método. Cada notebook aqui aguenta a pergunta "explica esse código linha por linha".

## Tecnologias

`Python` · `NumPy` · `heapq` · `collections` · `Matplotlib`

---

*Parte do portfólio de Data Science de [Kamilla Evelyn](https://kmillaevelyn.github.io).*
