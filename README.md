# Análise Comparativa de Lojas de Varejo

## Descrição do Projeto

Este projeto é uma parceria com a Alura e Oracle no programa ONE, realiza uma análise comparativa do desempenho de quatro lojas de varejo, com o objetivo de identificar qual loja seria a melhor candidata para ser vendida, a fim de realocar capital para novos investimentos. A análise abrange faturamento, vendas por categoria de produto, média de avaliação de clientes, frete médio e desempenho geográfico.

## Dados

Os dados para esta análise foram obtidos de quatro arquivos CSV, cada um representando as vendas de uma loja específica:

*   **Loja 1:** [loja_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
*   **Loja 2:** [loja_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
*   **Loja 3:** [loja_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
*   **Loja 4:** [loja_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

Cada arquivo contém informações detalhadas sobre produtos, categorias, preços, frete, datas de compra, vendedores, locais de compra, avaliações, tipos de pagamento, quantidade de parcelas, latitude e longitude.

## Análises Realizadas

As seguintes análises foram conduzidas:

1.  **Faturamento Total:** Cálculo do faturamento total para cada loja.
2.  **Vendas por Categoria:** Identificação das categorias de produtos mais e menos vendidas em cada loja, com visualizações em barras.
3.  **Média de Avaliação:** Determinação da média de avaliação dos clientes para cada loja.
4.  **Produtos Mais e Menos Vendidos:** Listagem dos produtos com maior e menor volume de vendas.
5.  **Frete Médio:** Cálculo do custo médio de frete para cada loja.
6.  **Visualização Consolidada:** Geração de um DataFrame consolidado com as principais métricas de cada loja.
7.  **Gráficos Comparativos:**
    *   Faturamento total por loja (Gráfico de Barras).
    *   Média de avaliação por loja (Gráfico de Barras Horizontais).
    *   Heatmap das Top 5 categorias mais vendidas por loja.
8.  **Visualização Geográfica:** Mapeamento do desempenho das lojas utilizando as coordenadas de latitude e longitude, com bolhas representando o faturamento total e cores representando cada loja.

## Conclusões Principais

Com base em todas as análises realizadas, a **Loja 4** é a candidata mais indicada para ser vendida. Os principais motivos são:

*   **Menor Faturamento Total:** A Loja 4 apresentou o menor faturamento entre as quatro lojas, tornando-a a opção com menor impacto na receita geral ao ser desinvestida.
*   **Média de Avaliação Mediana:** Embora não seja a mais baixa, sua média de avaliação está em uma posição intermediária.
*   **Sobreposição Geográfica:** A Loja 4 possui uma localização geográfica muito próxima da Loja 1. Ao vender a Loja 4, há um potencial de que parte de seu faturamento seja absorvida pela Loja 1, minimizando perdas e concentrando esforços em uma loja mais rentável na mesma região.

Esta decisão visa liberar capital com o menor impacto possível na operação e com a perspectiva de otimização de recursos.

## Como Executar a Análise

Para replicar e explorar esta análise:

1.  **Clone o Repositório:** `git clone [URL do seu repositório]`
2.  **Abra no Google Colab:** O notebook (`seu_notebook.ipynb`) pode ser aberto diretamente no Google Colab.
3.  **Execute as Células:** Execute todas as células do notebook sequencialmente. Certifique-se de que todas as bibliotecas necessárias (pandas, matplotlib, seaborn, folium) estão instaladas. O Google Colab geralmente já as possui pré-instaladas.

Os resultados, incluindo gráficos e relatórios, serão gerados dinamicamente no notebook.
