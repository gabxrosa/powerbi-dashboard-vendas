# 📊 Dashboard de Vendas -- Power BI

Este projeto foi desenvolvido como parte do **Curso de Power BI para
Business Intelligence e Data Science** da [Data Science
Academy](https://www.datascienceacademy.com.br/).

O objetivo foi aplicar conceitos fundamentais de **modelagem de dados**,
**relacionamentos e cardinalidade**, **Power Query**, **DAX (Data
Analysis Expressions)** e **criação de medidas e colunas calculadas**
para responder perguntas de negócio através de um dashboard interativo.

------------------------------------------------------------------------

## 🚀 Funcionalidades do Dashboard

O dashboard foi construído para responder às seguintes perguntas de
negócio:

1.  **Total de valor de venda por modo de envio**
    -   Visualização: Gráfico de cascata.
2.  **Mercados com maior custo médio de envio dos produtos vendidos**
    -   Visualização: Treemap.
3.  **Meta de valor médio de venda mensal (350)**
    -   Visualização: KPI (Key Performance Indicator).\
    -   Análise específica: O resultado de **abril/2014** ficou **acima
        ou abaixo da meta**?
4.  **Categoria de produto com maior lucro médio**
    -   Considerando:

        ``` dax
        Lucro = [Valor Venda] - [Custo Envio]
        ```
5.  **Comportamento da margem de lucro ao longo do tempo**
    -   Considerando:

        ``` dax
        Margem Lucro = DIVIDE([Lucro], [Valor Venda], 0)
        ```

------------------------------------------------------------------------

## 📂 Fontes de Dados

Foram utilizadas **4 tabelas** como fontes de dados:

-   `Clientes.csv` -- Informações sobre clientes.\
-   `Produtos.csv` -- Detalhes dos produtos.\
-   `Pedidos.csv` -- Dados sobre os pedidos realizados.\
-   `Vendas.csv` -- Registros de vendas, custos e valores.

Essas tabelas foram relacionadas no modelo de dados do Power BI,
aplicando **relacionamentos adequados e cardinalidades corretas**.

------------------------------------------------------------------------

## 🛠️ Tecnologias e Recursos Utilizados

-   **Power BI Desktop**\
-   **Power Query** para transformação e limpeza dos dados.\
-   **DAX** para criação de colunas calculadas e medidas.\
-   **Relacionamentos** entre tabelas fact e dimensionais.\
-   **Visualizações**: Gráfico de cascata, treemap, KPI, entre outros.


------------------------------------------------------------------------

## 🎯 Objetivo de Aprendizado

Este projeto foi desenvolvido como **exercício prático** para fixar
conceitos de:\
- Modelagem de dados no Power BI.\
- Relacionamentos entre tabelas.\
- Criação de medidas e indicadores com DAX.\
- Uso de diferentes tipos de visualizações para responder perguntas de
negócio.

------------------------------------------------------------------------

## 📌 Autor

👤 Desenvolvido por **Gabrielle Rosa**\
📧 Contato: \[gabriellerosaribeiro@outlook.com\]\
🔗 LinkedIn: \[https://www.linkedin.com/in/gabrielle-rosa-ribeiro/]\
