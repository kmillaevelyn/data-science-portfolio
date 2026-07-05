# Análise de Sentimento — Reviews B2W/Americanas

Classificação de sentimento em avaliações reais de e-commerce (dataset público B2W), comparando duas abordagens: **léxico de sentimento** vs. **machine learning supervisionado**.

## Resultado central

| Abordagem | Acurácia |
|---|---|
| Baseline léxica | 72,07% |
| **ML supervisionado (CountVectorizer + Regressão Logística)** | **89,90%** |

O ponto metodológico mais importante: a abordagem léxica ficou **abaixo do baseline de classe majoritária**, o que demonstra na prática por que regras fixas de vocabulário não capturam contexto, negação e ironia em português — e por que o modelo treinado nos próprios dados supera com folga.

## O que o notebook cobre

- Pré-processamento de texto em PT-BR com spaCy
- - Construção da baseline léxica e análise crítica de suas falhas
  - - Vetorização com CountVectorizer e treino de Regressão Logística
    - - Avaliação com matriz de confusão e análise de erros
     
      - ## Tecnologias
     
      - `Python` · `spaCy` · `scikit-learn` · `pandas`
     
      - ## Equipe
     
      - Projeto em grupo — Kamilla Evelyn, João Vitor Fidanza e Dimas de Barros Cobra.
     
      - ## Status
     
      - 📓 Notebook em publicação — o arquivo `.ipynb` será adicionado a esta pasta em seguida.
     
      - ---

      *Parte do portfólio de Data Science de [Kamilla Evelyn](https://kmillaevelyn.github.io).*
