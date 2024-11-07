# Projeto de Análise de Dados - Análise Exploratória e Preditiva

Este repositório contém o projeto de análise de dados, incluindo uma **Análise Exploratória de Dados (AED)** e uma **Análise Preditiva** para prever o status operacional de empresas cadastradas no Brasil. O projeto foi desenvolvido com foco em microempreendedores individuais (MEIs), com o objetivo de fornecer insights sobre o estado e o desenvolvimento de suas atividades empresariais.

## Objetivo do Projeto

O objetivo principal é entender melhor os dados empresariais, identificar padrões relevantes e construir modelos preditivos para estimar o status operacional de uma empresa com base em variáveis fornecidas. O projeto foi dividido em duas fases:
- **Análise Exploratória de Dados (AED)**: Exploramos e limpamos os dados para entender suas características, distribuição e qualidade.
- **Análise Preditiva (AD)**: Construímos e avaliamos modelos de machine learning para prever o status operacional das empresas, com classes de resposta "Ativa", "Encerrada" e "Irregular".

## Estrutura do Repositório

Este repositório está organizado da seguinte forma:

- **Data Cleaning AED/**: Scripts e bases de dados utilizados para limpeza e pré-processamento dos dados, garantindo a qualidade da análise.
- **Análises AD/**: Notebooks e scripts que implementam os modelos preditivos, incluindo treinamento, avaliação e ajuste de hiperparâmetros para a previsão do status operacional.
- **Bases de Dados**: Um arquivo ZIP com arquivos `.xlsx` das bases originais antes da preparação dos dados, disponível na raiz do repositório.

### Link de Referência da Base de Dados

Os dados foram obtidos a partir do portal [Dados.gov.br](https://dados.gov.br/dados/conjuntos-dados/cadastro-nacional-da-pessoa-juridica---cnpj).

## Descrição das Etapas

### 1. Análise Exploratória de Dados (AED)

A **Análise Exploratória de Dados** teve como objetivo investigar a estrutura e a qualidade dos dados. As principais atividades realizadas foram:
- **Limpeza dos Dados**: Tratamento de dados ausentes e inconsistentes.
- **Transformação de Variáveis**: Ajustes em variáveis categóricas e numéricas para facilitar a análise.
- **Visualização e Estatísticas**: Exploração visual e estatística para identificar padrões e correlações entre variáveis relevantes para a modelagem preditiva.

### 2. Análise Preditiva (AD)

A **Análise Preditiva** focou na construção e avaliação de modelos para prever o status operacional das empresas. As etapas desta fase incluíram:
- **Pré-processamento**: Seleção e transformação das variáveis de entrada, incluindo o balanceamento de classes.
- **Treinamento e Avaliação de Modelos**: Modelos como GaussianNB, K-Nearest Neighbors e Decision Trees foram testados. Ajustamos hiperparâmetros e avaliamos os modelos com métricas de acurácia, precisão, recall e F1-Score.
- **Seleção do Melhor Modelo**: Baseando-se nas métricas de avaliação, escolhemos o modelo mais adequado para prever o status operacional.

## Como Executar o Projeto

Para rodar as análises ou fazer testes com os modelos preditivos, siga os passos abaixo:

1. Clone este repositório em sua máquina local:
   ```bash
   git clone https://github.com/BiMODados/AED_AD.git

2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt

3. Execute os scripts nas pastas Análises AD e Data Cleaning AED para acessar as análises e resultados.
