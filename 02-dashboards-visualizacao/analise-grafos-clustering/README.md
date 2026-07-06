# Clustering de Notícias — TF-IDF + K-Means

Pipeline completo de **NLP não supervisionado** para agrupamento de notícias em português: do texto bruto aos tópicos descobertos, com validação estatística da escolha do número de clusters.

## O que o notebook cobre

- Limpeza de texto: remoção de pontuação e normalização
- Tokenização com NLTK e remoção de stopwords
- Lematização com spaCy (português)
- Vetorização Bag-of-Words e TF-IDF
- Agrupamento K-Means com k = 4
- **Método do Cotovelo + Silhouette Score** para validar o número de clusters — a escolha de k é defendida com métrica, não com intuição
- Identificação dos tópicos dominantes de cada cluster pelos termos de maior peso TF-IDF

## Tecnologias

`Python` · `NLTK` · `spaCy` · `scikit-learn` · `pandas` · `Matplotlib`

## Equipe

Projeto em grupo (Projeto Integrador 5) — Kamilla Evelyn, João Vitor Fidanza e Dimas de Barros Cobra.

## Notebook

📓 [`clustering-noticias-tfidf-kmeans.ipynb`](./clustering-noticias-tfidf-kmeans.ipynb) — com badge para abrir direto no Colab.

---

*Parte do portfólio de Data Science de [Kamilla Evelyn](https://kmillaevelyn.github.io).*
