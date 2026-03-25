# Exercício referente ao módulo 32 do curso de ciência de dados da EBAC
**Neste módulo é feita a prática do algoritimo de aprendizado supervisionado random forest(floresta aleatória) utilizando uma base de dados de vinhos**

## As Colunas da base são as seguintes:
* fixed acidity -  mede a acides fixa do vinho
* volatile acidity -  mede a acides volatil do vinho
* citric acid -  mede a quantidade de acido citrico presente no vinho
* residual sugar -  mede a quantidade de açucar residual presente no vinho
* chlorides -  mede os cloretos do vinho
* free sulfur dioxide - A quantidade de dioxido de enxofre livre no vinho
* total sulfur dioxide - Quantidade de dioxido de enxofre total no vinho
* density - A densidade total do vinho
* pH - O ph do vinho se é mais acido ou mais base
* sulphates - O nivel de sulfatos no vinho
* alchohol - O teor alcoolico do vinho
* qualitiy - A qualidade do vinho

## O que foi feito:
* Realização da primeira etapa do pré-processamento de dados
* Realização da segunda e terceira etapas do pré-processamento de dados
  * Utilização da função describe
  * Gráficos para identificar os outliers
  * Substituição dos outliers utilizando IQR
  * Verificação do balanceamento da variável target
  * Criação de uma tabela para indicar as variável com maior correlação
* Criado um novo datagrame somente com as variáveis melhor correlacionadas
* Separação dos dados em X(features) e Y(target)
* Separação em base de treino e teste
* Iniciado o treinamento do modelo de Random Forest
* Aplicação do modelo a base de testes
* Avaliação de métricas e interpretação dos valores
* Hyperparametrização e análise das novas métricas

## Como Rodar o projeto
* Clone o repositório para o sua máquina
* Abra o projeto em um ambiente python
* Execute o código

## Tecnologias utilizadas
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![Imbalanced-learn](https://img.shields.io/badge/Imbalanced--learn-SMOTE%20%26%20Resampling-green)
