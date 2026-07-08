# Análise de Sentimento — B2W / Americanas

Classificação de sentimento em **10.000 avaliações reais de produtos** da B2W/Americanas, comparando a abordagem léxica com Machine Learning supervisionado — e mostrando por que o modelo treinado vence.

## Resultado

- **Regressão Logística + CountVectorizer: 89,9% de acurácia**
- Abordagem léxica (dicionário de palavras positivas/negativas): desempenho inferior ao baseline da classe majoritária — evidência de que contagem de palavras não captura contexto
- Avaliação com matriz de confusão e classification report (precision, recall, F1)

## Metodologia

1. **Rotulagem pela nota do cliente**: notas 3–5 = positivo · notas 1–2 = negativo — critério aplicado de forma consistente em treino e teste
2. **Vetorização** com CountVectorizer (bag-of-words)
3. **Treino/teste** com split estratificado e avaliação fora da amostra
4. **Análise de erros** pela matriz de confusão: onde o modelo confunde elogio irônico e crítica moderada

## Por que este projeto importa

Avaliações de clientes são o termômetro mais barato de um e-commerce: classificar sentimento em escala permite priorizar respostas, detectar crises de produto e alimentar KPIs de reputação sem leitura manual.

## Tecnologias

`Python` · `pandas` · `scikit-learn` · `CountVectorizer` · `Regressão Logística` · `Matplotlib`

## Notebook

📓 [`analise-sentimento-b2w.ipynb`](./analise-sentimento-b2w.ipynb) — com badge para abrir direto no Colab.

---

*Parte do portfólio de Data Science de [Kamilla Evelyn](https://kmillaevelyn.github.io).*
