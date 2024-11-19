# 1. Objetivo do Projeto
Este projeto tem como objetivo analisar os dados de clientes de uma imobiliária para melhorar suas estratégias de marketing e compreender melhor o perfil de seus clientes. As análises incluem:

* Distribuição de renda por estado.
* Segmentação de clientes por estado civil e gênero.
* Distribuição geográfica dos clientes.
* Análise de outliers de renda.
* Correlação entre renda e estado civil.

# 2. Estrutura do Relatório

## 2.1 Importação das Bibliotecas Necessárias
As bibliotecas utilizadas incluem:

* pandas: para manipulação e análise de dados.
* matplotlib.pyplot: para criação de gráficos e visualizações.
* seaborn: para visualizações estatísticas.
* numpy: para operações numéricas eficientes.

## 2.2 Carregamento do Dataset
Os dados foram carregados a partir de um arquivo CSV contendo informações de clientes.

## 2.3 Visualização Inicial do Dataset
Foi realizada uma análise inicial para observar a quantidade de registros e verificar se há valores nulos.

## 2.4 Análise Preliminar
Os dados foram agrupados por diferentes categorias, como estado, cidade, gênero e estado civil, para obter uma visão geral do perfil dos clientes.

## 2.5 Limpeza e Tratamento de Dados
As transformações realizadas foram:

* Remoção de caracteres indesejados em colunas numéricas.
* Divisão de ranges de renda em valores mínimo e máximo.
* Cálculo de uma nova coluna com a média dos valores de renda.
Observação: Alguns valores ausentes foram preenchidos, o que pode comprometer a precisão de algumas análises.

## 2.6. Análises Propostas

### 2.6.1 Distribuição de Renda por Estado (UF)
A média e a mediana de renda por estado foram calculadas e ordenadas para identificar concentrações de clientes com maior poder aquisitivo.

### 2.6.2 Segmentação de Clientes por Estado Civil e Gênero
A proporção de clientes foi analisada com base no estado civil e no gênero, gerando insights para segmentação de campanhas.

### 2.6.3 Distribuição Geográfica dos Clientes
A distribuição de clientes por estado foi visualizada em um mapa de calor, destacando as regiões de maior concentração.

### 2.6.4 Análise de Outliers de Renda
Foram identificados clientes com renda muito superior ou inferior à média para detectar padrões atípicos. As contagens de outliers foram detalhadas por estado, gênero, escolaridade e estado civil.

### 2.6.5 Correlação entre Renda e Estado Civil
A relação entre o estado civil dos clientes e sua renda foi analisada para compreender melhor possíveis correlações.

# Conclusão
Este projeto forneceu uma visão detalhada sobre o perfil dos clientes, ajudando a imobiliária a direcionar suas estratégias de marketing de forma mais eficaz. As análises realizadas oferecem subsídios para identificar oportunidades de mercado e ajustar campanhas conforme as características dos clientes.
