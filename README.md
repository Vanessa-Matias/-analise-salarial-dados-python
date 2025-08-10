# Projeto: Dashboard de Análise de Salários na Área de Dados

## 💻 Visão Geral do Projeto

Este projeto é um estudo de caso completo, desenvolvido como parte da Imersão de Dados com Python da Alura, com o objetivo de realizar uma análise exploratória de dados de salários de profissionais da área de dados. O projeto evolui desde a análise inicial no Google Colab até a criação de um dashboard interativo utilizando Streamlit, que permite a visualização e a exploração de insights de forma dinâmica.

O projeto é dividido em dois principais entregáveis:
* **Notebook de Análise Exploratória:** Onde a metodologia e os tratamentos de dados foram aplicados.
* **Dashboard Interativo:** Uma aplicação web que transforma os resultados da análise em uma ferramenta visual para a tomada de decisão.

---

## 🛠️ Tecnologias e Ferramentas

O desenvolvimento deste projeto envolveu as seguintes bibliotecas e ferramentas:

* **Python:** Linguagem principal para análise e desenvolvimento.
* **pandas:** Utilizada para carregar, manipular e tratar o conjunto de dados.
* **Streamlit:** Biblioteca utilizada para criar a interface do dashboard interativo, permitindo filtros dinâmicos e visualização em tempo real.
* **Plotly Express:** Biblioteca utilizada para a criação de gráficos estatísticos e visualizações de dados interativas.
* **Google Colab:** Ambiente de desenvolvimento para a fase de análise exploratória.
* **VS Code:** Ambiente para a construção e execução do dashboard interativo.
* **Git & GitHub:** Utilizados para controle de versão e hospedagem do projeto.

---

## 📊 Metodologia e Análise de Dados

A análise foi conduzida seguindo um fluxo de trabalho padrão em ciência de dados:

### 1. Carregamento e Exploração Inicial
* O conjunto de dados, contendo **133.349 registros e 11 colunas**, foi carregado diretamente de um arquivo CSV.
* Foi realizada uma exploração inicial para entender a estrutura dos dados, incluindo a visualização das primeiras linhas e das estatísticas descritivas básicas.

### 2. Tratamento e Pré-processamento
* **Limpeza de Dados:** Foi identificada e tratada a presença de valores nulos, especialmente na coluna `ano`, que continha 10 valores ausentes.
* **Padronização:** As colunas foram renomeadas de inglês para português para facilitar a compreensão e o manuseio dos dados.

### 3. Análise Exploratória e Geração de Insights
* **Estatísticas Descritivas:** Geradas estatísticas como média, desvio padrão e quartis para as variáveis numéricas do conjunto de dados.
* **Análise Categórica:** Explorada a frequência de variáveis categóricas, como nível de senioridade e tipo de contrato, utilizando contagens e gráficos de barras.

---

## 📈 Dashboard Interativo

O dashboard interativo permite que o usuário explore os dados de salários de forma autônoma. Ele apresenta as seguintes funcionalidades:

* **Filtros Dinâmicos:** Permite a seleção de dados por `Ano`, `Senioridade`, `Tipo de Contrato` e `Tamanho da Empresa`.
* **Métricas Chave:** Exibe métricas importantes em tempo real, como `Salário médio`, `Salário máximo`, `Total de registros` e `Cargo mais frequente`.
* **Visualizações Interativas:** Apresenta gráficos como "Top 10 cargos por salário médio" e a "Distribuição de salários anuais" para uma visualização completa.

---

### Links do Projeto
* **Versão online do Dashboard:** [Acesse aqui](https://dados-python-alura.streamlit.app/)
* **Notebook de Análise:** [dados_com_python.py](https://github.com/Vanessa-Matias/-analise-salarial-dados-python/blob/main/dados_com_python.py)

![Dashboard de Análise de Salários](https://github.com/user-attachments/assets/4d6457c1-ff21-4b6f-9da5-2207d0f4f05e)
