# Previsão de Câncer com Aprendizado de Máquina

***Preditor do tipo de tumor***
*by [Yago Pacheco](https://www.linkedin.com/in/yago-pacheco-de-aquino-958881183/)*

---

## Introdução
Este projeto tem como objetivo desenvolver um modelo de aprendizado de máquina para prever a possibilidade de uma pessoa ter câncer, utilizando o conjunto de dados `Breast Cancer Wisconsin`. As etapas incluem análise exploratória e visualização dos dados, redução de dimensionalidade, padronização dos dados, criação de um baseline com `DummyClassifier()`, implementação do modelo de aprendizado de máquina usando `KBest`, avaliação do modelo com métricas e matriz de confusão, e uma compreensão gráfica dos dados utilizando o algoritmo `t-SNE`.

## Funcionalidades

### Análise Exploratória e Visualização de Dados
- Utilização do `Pandas` e `Seaborn` para análise exploratória e visualização dos dados.
- Identificação de padrões e relações entre variáveis para compreender o conjunto de dados.

### Redução de Dimensionalidade
- Remoção de colunas desnecessárias para melhorar o processamento dos dados e facilitar a visualização.

### Padronização dos Dados
- Utilização da biblioteca `scikit-learn` para padronizar os dados.

### Baseline com DummyClassifier
- Criação de um baseline para estabelecer uma base de comparação.

### Modelo de Aprendizado de Máquina com KBest
- Implementação de um modelo de aprendizado de máquina utilizando a técnica `KBest` para seleção de características.
- Avaliação do modelo com métricas como precisão, recall e F1-score.

### Matriz de Confusão
- Criação de uma matriz de confusão para analisar o desempenho do modelo em cada classe.

### Compreensão Gráfica dos Dados com t-SNE
- Utilização do algoritmo `t-SNE` para compreender visualmente a distribuição dos dados.
