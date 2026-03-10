
# Análise Comparativa de Lojas de Varejo

---

## Descrição do Projeto

O objetivo é realizar uma análise comparativa do desempenho de quatro lojas de varejo, a fim de identificar qual unidade apresenta menor desempenho e poderia ser considerada para venda, permitindo a realocação estratégica de capital para novos investimentos.
Para isso, foram analisados indicadores como faturamento total, vendas por categoria de produto, média de avaliação dos clientes, custo médio de frete e desempenho geográfico das lojas.

---

## Dados

Os dados utilizados nesta análise foram extraídos de quatro arquivos no formato CSV, sendo que cada arquivo representa o histórico de vendas de uma loja específica.

*   **Loja 1:** [loja_1.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv)
*   **Loja 2:** [loja_2.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv)
*   **Loja 3:** [loja_3.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv)
*   **Loja 4:** [loja_4.csv](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv)

Cada arquivo reúne informações detalhadas sobre as transações, incluindo produtos, categorias, preços, custos de frete, datas de compra, vendedores, localização das vendas, avaliações dos clientes, métodos de pagamento, número de parcelas, além de dados geográficos (latitude e longitude) que permitem análises espaciais.

---

## Análises

As seguintes análises exploratórias foram conduzidas para avaliar o desempenho das lojas e identificar possíveis oportunidades de otimização:
* **1. Faturamento Total:**
Cálculo do faturamento total gerado por cada loja, permitindo comparar diretamente o desempenho financeiro entre as unidades.
* **2. Vendas por Categoria:**
Identificação das categorias de produtos mais e menos vendidas em cada loja, acompanhada de visualizações em gráficos de barras para facilitar a comparação.
* **3. Média de Avaliação dos Clientes:**
Cálculo da média das avaliações atribuídas pelos clientes a cada loja, fornecendo um indicador da percepção de qualidade do serviço.
* **4. Produtos Mais e Menos Vendidos:**
Identificação dos produtos com maior e menor volume de vendas, permitindo compreender padrões de demanda dentro do portfólio.
* **5. Frete Médio:**
Cálculo do custo médio de frete por loja, auxiliando na análise de possíveis diferenças logísticas entre as unidades.
* **6. Consolidação das Métricas:**
Construção de um DataFrame consolidado reunindo as principais métricas analisadas para cada loja, facilitando comparações e interpretação dos resultados.
* **7. Gráficos Comparativos:**
Desenvolvimento de visualizações para destacar diferenças de desempenho entre as lojas:
  * Faturamento total por loja (gráfico de barras)
  * Média de avaliação por loja (gráfico de barras horizontais)
  * Heatmap com as cinco categorias mais vendidas por loja
* **8. Visualização Geográfica:**
Representação espacial do desempenho das lojas utilizando coordenadas de latitude e longitude, onde o tamanho das bolhas indica o faturamento total e as cores distinguem cada loja.

---

## Conclusões

Com base nas análises exploratórias realizadas com a biblioteca Pandas, a Loja 4 se apresenta como a candidata mais indicada para venda. Os principais fatores que sustentam essa decisão são:
* **Menor faturamento total**: Entre as quatro lojas analisadas, a Loja 4 apresentou o menor volume de faturamento, o que indica que sua venda teria menor impacto na receita global do negócio.
* **Avaliação média intermediária**: A média de avaliações da Loja 4 não é a mais baixa, porém também não se destaca positivamente quando comparada às demais lojas.
* **Proximidade geográfica com outra unidade**: A Loja 4 está localizada muito próxima da Loja 1, o que sugere a possibilidade de absorção parcial da demanda por essa unidade caso a Loja 4 seja descontinuada, reduzindo potenciais perdas de receita.
Dessa forma, a decisão de venda da Loja 4 busca otimizar a alocação de recursos e liberar capital, minimizando impactos operacionais e concentrando esforços nas unidades com melhor desempenho.

---

## Como Executar a Análise

Para replicar e explorar esta análise:

1.  **Clone o Repositório:** `git clone [URL do seu repositório]`
2.  **Abra no Google Colab:** O notebook (`seu_notebook.ipynb`) pode ser aberto diretamente no Google Colab.
3.  **Execute as Células:** Execute todas as células do notebook sequencialmente. Certifique-se de que todas as bibliotecas necessárias (pandas, matplotlib, seaborn, folium) estão instaladas. O Google Colab geralmente já as possui pré-instaladas.

Os resultados, incluindo gráficos e relatórios, serão gerados dinamicamente no notebook.

---

**Desenvolvido por:** Mayara Martins.<br>
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MayaraMartins95)[![LinkedInd](https://img.shields.io/badge/LinkedIn-100000?style=for-the-badge&logo=github&logoColor=white)](https://www.linkedin.com/in/mayara-martins-rp/)
