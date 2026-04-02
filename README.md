# Análise de Vendas de uma Loja 📊
Este projeto consiste em uma análise de dados utilizando Python e a biblioteca Pandas para extrair insights estratégicos de uma base de dados de vendas (arquivo train.csv). O objetivo principal é compreender o desempenho comercial através de diferentes métricas de volume e lucro.

## 🎯 Objetivos da Análise
O notebook foi estruturado para responder às seguintes perguntas de negócio:

* Qual produto mais vende? (Análise por quantidade).

* Qual categoria dá mais lucro? (Análise por rentabilidade).

* Quais meses têm mais vendas? (Análise de sazonalidade).

* Qual região vende mais? (Análise geográfica de lucro).

## 🛠️ Tecnologias Utilizadas
* Python 3

* Pandas: Para manipulação e análise de dados.

* Google Colab: Ambiente de desenvolvimento.

* ExcelWriter: Para geração de relatórios multi-abas.

## 📂 Estrutura do Projeto
O código segue um fluxo lógico de processamento de dados:

* **Carregamento:** Importação dos dados e visualização inicial das colunas (Order ID, Order Date, Region, Category, Product, Sales, Quantity, Profit).

* **Exploração:** Uso de métodos como .info() e .describe() para entender a distribuição estatística.

* **Processamento:** Tratamento da coluna de data e criação de novas colunas temporais.

* **Agregação:** Agrupamento de dados (groupby) para somar vendas e lucros por categorias e regiões.

* **Exportação:** Geração de um arquivo final chamado relatorio.xlsx.

## 📈 Resultados Encontrados
Com base nos dados processados:

* **Top Produto:** O item Pen (Caneta) lidera com 15 unidades vendidas.

* **Lucro por Categoria:** A categoria de Electronics é a mais lucrativa, gerando 1.525 em lucro.

* **Sazonalidade:** O mês de Janeiro apresentou o maior volume de vendas (5.050).

* **Região:** A região East é a que apresenta o maior lucro acumulado (1.030).

## 🚀 Como Executar
* Certifique-se de ter o arquivo train.csv no mesmo diretório do script.

* Execute as células do notebook analise_vendas.ipynb.

* O script gerará automaticamente um arquivo relatorio.xlsx com abas separadas para cada análise realizada.
