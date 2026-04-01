# Classificação de Qualidade de Vinhos com Random Forest

Uma análise prática de aprendizado supervisionado utilizando o algoritmo Random Forest (Floresta Aleatória) em um conjunto de dados de propriedades físico-químicas de vinhos.

## Visão Geral do Projeto

Este projeto implementa um modelo de classificação baseado em Random Forest para prever a qualidade de vinhos a partir de suas características físico-químicas. O projeto faz parte do módulo 32 do curso de Ciência de Dados da EBAC.

## Dicionário de Dados

| Campo | Descrição |
|---------|-----------|
| **fixed acidity** | Acidez fixa do vinho (g/dm³) |
| **volatile acidity** | Acidez volátil do vinho (g/dm³) |
| **citric acid** | Quantidade de ácido cítrico presente (g/dm³) |
| **residual sugar** | Açúcar residual após fermentação (g/dm³) |
| **chlorides** | Teor de cloretos (g/dm³) |
| **free sulfur dioxide** | Dióxido de enxofre livre (mg/dm³) |
| **total sulfur dioxide** | Dióxido de enxofre total (mg/dm³) |
| **density** | Densidade do vinho (g/cm³) |
| **pH** | Potencial hidrogeniônico (acidez/basicidade) |
| **sulphates** | Nível de sulfatos (g/dm³) |
| **alcohol** | Teor alcoólico (%) |
| **quality** | Qualidade do vinho (variável-alvo) |

## Metodologia

### Pré-processamento de Dados
- ✓ Exploração e limpeza inicial dos dados
- ✓ Análise descritiva com função `describe()`
- ✓ Visualização e identificação de outliers
- ✓ Remoção de outliers utilizando método IQR
- ✓ Análise de balanceamento da variável-alvo
- ✓ Matriz de correlação de variáveis

### Engenharia de Features
- ✓ Seleção de variáveis com maior correlação
- ✓ Criação de novo dataset com features otimizadas
- ✓ Separação de features (X) e target (Y)

### Modelagem
- ✓ Divisão dos dados em treino/teste
- ✓ Treinamento do modelo Random Forest
- ✓ Avaliação de métricas de desempenho
- ✓ Hiperparametrização e otimização do modelo

##  Como Executar

### Pré-requisitos
- Python 3.7+
- Jupyter Notebook

### Instalação

# Clone o repositório
* git clone https://github.com/GrizzoHenrique/RandomForest.git
* cd RandomForest

# Instale as dependências (caso necessário)
* pip install -r requirements.txt

## Tecnologias utilizadas
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![Imbalanced-learn](https://img.shields.io/badge/Imbalanced--learn-SMOTE%20%26%20Resampling-green)
