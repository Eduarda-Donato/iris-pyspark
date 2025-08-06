#  Classificação de Espécies de Íris com PySpark

Este projeto utiliza PySpark para classificar espécies de flores do conjunto de dados **Iris**. Ele inclui **análise exploratória de dados (EDA)**, **pré-processamento**, **codificação de rótulos**, e a aplicação de **modelos de classificação**.

## Tecnologias Utilizadas

- Python 3.10+

- PySpark

- Jupyter Notebook

- Docker 

- Spark MLlib

## Etapas do Projeto

### 1. EDA

- Contagem de valores nulos e tipos de dados

- Estatísticas descritivas 

- Análise de distribuição de classes

- Correlações


### 2. Pré-processamento

- Conversão do label usando `StringIndexer`

- Vetorização com `VectorAssembler`

- Normalização dos dados

### 3. Modelagem

- Treinamento com modelos como:
`LogisticRegression`
`NaiveBayes`
`RandomForestClassifier`

- Split de dados com `.randomSplit([0.8, 0.2])`

### 4. Avaliação

- Métricas como `accuracy`, `precision`, `recall` 

- Matriz de confusão

##  Resultados

- O modelo alcançou uma acurácia de aproximadamente **X%** na base de teste.

##  Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/iris-pyspark.git
   cd iris-pyspark
