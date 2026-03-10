# Alura-Store-Data-Science

## Sobre o projeto

Esse projeto faz parte do **Challenge de Data Science da Alura**. A ideia é analisar os dados de 4 lojas fictícias da Alura Store pra descobrir qual delas tem o pior desempenho e deveria ser vendida.

Pra isso, analisei coisas como faturamento, categorias mais vendidas, avaliações dos clientes, produtos mais/menos vendidos e custo de frete.

## O que tem no projeto
├── AluraStoreBr.ipynb <- notebook com toda a análise

└── README.md

Os dados vêm direto do GitHub da Alura (arquivos CSV), então não precisa baixar nada separado.

## O que foi analisado

### 1. Faturamento total de cada loja
Comparei a receita das 4 lojas pra ver qual fatura mais e qual fatura menos.

### 2. Vendas por categoria
Vi quais categorias de produto vendem mais em cada loja usando gráficos de pizza.

### 3. Média de avaliação dos clientes
Comparei a nota média de satisfação (de 1 a 5) entre as lojas.

### 4. Produtos mais e menos vendidos
Ranking dos 5 produtos que mais vendem e os 5 que menos vendem em cada loja.

### 5. Frete médio
Quanto cada loja gasta em média com frete.

## Alguns insights

- A **Loja 4** tem o menor faturamento entre todas
- As médias de avaliação são bem parecidas entre as lojas, ficam em torno de 3.0
- Cada loja tem um mix de categorias um pouco diferente
- O frete varia bastante dependendo da loja

## Como rodar

1. Abre o [Google Colab](https://colab.research.google.com/)
2. Faz upload do arquivo `AluraStoreBr.ipynb` (ou abre direto pelo GitHub)
3. Clica em **Runtime > Run all** (ou Ctrl+F9)
4. Pronto, os gráficos vão aparecer no próprio notebook

> Não precisa instalar nada, o Colab já tem pandas e matplotlib.

## Feito com

- Python
- Pandas
- Matplotlib
- Google Colab
