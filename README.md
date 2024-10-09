# criando-relatorio-vendas-lucros-data-analytics-com-PBI-DesafioBootcampDIO

# Relatório Gerencial de Vendas e Lucros - Power BI

Este projeto contém um relatório gerencial de vendas e lucros de diferentes produtos e regiões, utilizando o Power BI para criar visualizações interativas. O relatório facilita a tomada de decisões estratégicas com base em insights detalhados sobre unidades vendidas, receita, lucros e custos, organizados por país, segmento e produto.

## Sumário
- [Descrição do Projeto](#descrição-do-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Base de Dados](#base-de-dados)
- [Cálculos e Medidas](#cálculos-e-medidas)
- [Principais Insights](#principais-insights)
- [Conclusões](#conclusões)
- [Autor](#autor)

## Descrição do Projeto

Este relatório foi desenvolvido com o objetivo de fornecer uma visão clara e detalhada sobre as vendas e lucros de produtos em diferentes regiões e segmentos de mercado. Através do Power BI, criamos dashboards interativos que permitem aos usuários explorar os dados por diferentes filtros, como ano, país, produto e segmento.

O dashboard também apresenta os **Top 3** em diferentes categorias (países, produtos, segmentos), utilizando funções DAX como `CALCULATE`, `TOPN`, e `RANKX`, para destacar os principais contribuintes para as vendas e lucros.

## Tecnologias Utilizadas

- **Excel** para armazenar dados.
- **Power BI Desktop** para manipulação de dados, criação dos dashboards e visualizações.

## Base de Dados

A base de dados utilizada inclui as seguintes informações:

- **Produtos**: Nome dos produtos vendidos e suas características.
- **Segmentos**: Tipos de mercado, como Governo, Pequenas Empresas, Enterprise, etc.
- **Países**: Localização geográfica das vendas.
- **Unidades Vendidas**: Quantidade total de produtos vendidos por período.
- **Receita Bruta e Lucro**: Informações sobre o faturamento total e o lucro líquido.
- **COGS (Custo das Mercadorias Vendidas)**: Valor gasto na fabricação dos produtos.
- **Datas**: Período de realização das transações, com granularidade por ano, trimestre, mês e dia.

## Cálculos e Medidas

Diversas medidas calculadas foram aplicadas para gerar os insights no Power BI, utilizando funções DAX como:

- **Total Sales**: `SUM(FactSales[Gross Sales])` – Soma total das vendas brutas.
- **Total Profit**: `SUM(FactSales[Profit])` – Soma do lucro líquido.
- **Total COGS**: `SUM(FactSales[COGS])` – Soma dos custos das mercadorias vendidas.
- **Top 3 Produtos/Países/Segmentos**: Usando funções `CALCULATE`, `TOPN`, e `RANKX` para calcular os três maiores contribuintes de vendas e lucro.
  
## Principais Insights

1. **Top 3 Vendas por País**:
   - **Estados Unidos**: $25 milhões
   - **Canadá**: $25 milhões
   - **França**: $24 milhões

2. **Top 3 Vendas por Produto**:
   - **Paseo**: $33 milhões
   - **VTT**: $21 milhões
   - **Velo**: $18 milhões

3. **Top 3 Vendas por Segmento**:
   - **Governo**: $53 milhões
   - **Pequenas Empresas**: $42 milhões
   - **Enterprise**: $20 milhões

4. **Lucro por País**:
   - **França**: $3,78 milhões
   - **Alemanha**: $3,68 milhões
   - **Canadá**: $3,53 milhões

5. **Lucro por Produto**:
   - **Paseo**: $5 milhões
   - **VTT**: $3 milhões
   - **Amarilla**: $3 milhões

6. **Lucro por Segmento**:
   - **Governo**: $11 milhões
   - **Pequenas Empresas**: $4 milhões
   - **Channel Partners**: $1 milhão

## Conclusões

Este relatório gerencial destaca a forte performance de produtos como **Paseo** e segmentos governamentais em termos de vendas e lucros. A análise Top 3 permite identificar rapidamente os principais contribuintes em diferentes categorias, ajudando na tomada de decisões estratégicas de mercado e de produto.

## Autor

Este projeto foi desenvolvido por Samuel Batista, baseado nas orientações da tutora Juliana Mascarenhas (@julianazanelatto). Sinta-se à vontade para entrar em contato ou contribuir com melhorias!
