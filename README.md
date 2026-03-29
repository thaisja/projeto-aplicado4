Monitoramento Inteligente de Consumo Energético

Projeto desenvolvido na disciplina Projeto Aplicado IV da Universidade Presbiteriana Mackenzie.

Objetivo

Desenvolver uma solução analítica baseada em séries temporais para monitorar e prever o consumo de energia elétrica, com foco na redução de desperdícios e aumento da eficiência energética.

Estrutura do Projeto
projeto-aplicado/
│
├── data/
│   └── CARGA_ENERGIA_2025.csv
│
├── notebooks/
│   └── analise_exploratoria.ipynb
│
├── outputs/
│   ├── grafico_serie.png
│   ├── acf.png
│   ├── pacf.png
│   └── decomposicao.png
│
└── README.md

Base de Dados

A base utilizada contém dados reais de consumo de energia elétrica no Brasil, com granularidade horária, obtidos a partir de fontes oficiais como:

Operador Nacional do Sistema Elétrico (ONS)
Câmara de Comercialização de Energia Elétrica (CCEE)

Etapa 2 — Análise Exploratória

Nesta etapa foram realizadas as seguintes análises:

Preparação e tratamento dos dados

Análise exploratória da série temporal
Cálculo de estatísticas descritivas
Análise de autocorrelação (ACF e PACF)
Decomposição da série temporal

Tecnologias Utilizadas

Python
Pandas
Matplotlib
Statsmodels


Principais Insights

A série apresenta forte sazonalidade diária
Existe tendência não linear ao longo do tempo
O consumo energético possui alta variabilidade
A série não é estacionária

Integrantes

Felipe Graciano de Moura Ramos

João Pedro Rocha Abbade

Marcos Davi Duarte Abibe

Thais Jorge Azevedo
