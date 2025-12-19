# Sistema de Recomendação de Livros

## Visão Geral do Projeto

Este projeto tem como objetivo o desenvolvimento de um Sistema de Recomendação de Livros, utilizando técnicas de Análise de Dados, Exploração Visual e Machine Learning, com foco em K-Nearest Neighbors (KNN).

A solução simula um cenário real de negócio, no qual dados de usuários, livros e avaliações são integrados para gerar recomendações personalizadas, apoiando a tomada de decisão e a experiência do usuário.

### Objetivos

* Entender o comportamento dos usuários a partir de dados reais
* Integrar múltiplas bases de dados (usuários, livros e avaliações)
* Explorar padrões e tendências por meio de visualizações
* Construir um modelo de recomendação baseado em similaridade
* Simular recomendações de livros de forma prática e visual

### Entendimento do Negocio

O projeto segue uma abordagem orientada ao negócio:
  
  **1- Entendimento da necessidade do cliente**
  **2- Alinhamento com áreas de produto/comercial**
  **3- Conhecimento do domínio (livros, autores, usuários)**
   **4- Validação por meio de testes e simulações**

### Estrutura do Projeto

O notebook contempla as seguintes etapas: A importação de bibliotecas e dados, o tratamento e modelagem dos dados, o cruzamento das bases utilizando o metodo merge,
a análise exploratória e visualização de dados, a construção do modelo de recomendação, a simulação de recomendações e a visualização dos resultados

### Análise Exploratória de Dados (EDA)

Durante a análise exploratória, foram avaliados:

1- Distribuição de livros por ano de publicação

2- Ranking dos autores mais populares

3- Distribuição geográfica dos usuários

4- Análise da idade dos usuários

5- Frequência e padrões de avaliações

**Foram utilizadas bibliotecas como:**
matplotlib, seaborn e plotly

### Modelo de Recomendação
Técnica Utilizada: K-Nearest Neighbors (KNN) e Métrica de distância: Distância Euclidiana

**Funcionamento**
O modelo identifica usuários ou livros similares com base em características selecionadas a partir da similaridade, são recomendados livros com maior probabilidade de interesse

### Simulador de Recomendação

**O projeto inclui um simulador, que:**

* **Seleciona um livro de referência**

* **Gera uma lista de livros recomendados**

* **Recupera imagens (capas) dos livros via URL**

* **Apresenta visualmente as recomendações**

Essa etapa aproxima o projeto de um cenário real de aplicação.

### Tecnologias e Ferramentas

**Python - Pandas - NumPy - Matplotlib - Seaborn - Plotly - Scikit-learn - PIL / Requests (simulação visual)**

## Impactos

**Geração de recomendações personalizadas**

**Identificação de padrões relevantes de consumo**

**Aplicação prática de Machine Learning em dados reais**

**Projeto aplicável a contextos de e-commerce, educação e plataformas digitais**
