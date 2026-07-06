# Previsão de Doença Cardíaca com Machine Learning

Prova de conceito (end-to-end) de um projeto de **classificação binária** em machine learning: dado um conjunto de parâmetros clínicos de um paciente, o modelo prevê se ele tem ou não doença cardíaca.

O objetivo principal é didático — servir como exemplo completo do fluxo de trabalho de um projeto de data science/ML, do problema aos dados, passando por modelagem, avaliação e otimização.

O projeto também tem como objetivo praticar técnicas de análise exploratória de dados estruturados (Structured Data), utilizando dados tabulares para identificar padrões, compreender as variáveis e orientar as etapas de pré-processamento e modelagem.

## Fonte dos dados

Os dados originais vêm do [Cleveland Database](https://archive.ics.uci.edu/dataset/45/heart+disease), do UCI Machine Learning Repository, e foram obtidos já formatados a partir do [Kaggle](https://www.kaggle.com/datasets/sumaiyatasmeem/heart-disease-classification-dataset).

O dataset original possui 76 atributos, dos quais apenas 14 são utilizados neste projeto (idade, sexo, tipo de dor no peito, pressão arterial, colesterol, entre outros). Não há informação pessoal identificável (PII) no dataset.

## Ideia do projeto

O problema é resumido pela pergunta:

> Dados os parâmetros clínicos de um paciente, conseguimos prever se ele tem ou não doença cardíaca?

> Todos os detalhes de raciocínio, decisões de modelagem e explicações estão comentados diretamente no notebook.

## Estrutura do projeto

```text
.
├── heart-disease.csv
└── heart-disease-classification.ipynb
```

- **heart-disease.csv:** conjunto de dados utilizado no projeto.
- **heart-disease-classification.ipynb:** notebook contendo todo o pipeline, incluindo EDA, pré-processamento, treinamento, comparação e avaliação dos modelos.
