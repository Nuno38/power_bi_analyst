# power_bi_analyst


- Relatório de Vendas - Power BI

Este projeto apresenta um conjunto de análises desenvolvidas no Power BI Desktop, com foco em **vendas, produtos, países e segmentos de clientes**.
<br>
---------------------------------------------------------------------------------------------------------------------------------------
<br>
1. Vendas por Produto
   - Soma de Sales por produto.
   - Média do Sale Price por produto.
   - Evolução das vendas por produto e ano.

2. Vendas por País
   - Soma de `Sales` por país.
   - Unidades vendidas (`Units Sold`) por país.
   - Lucro (`Profit`) por país.
   - Lucro médio por ano e mês.
   - Distribuição de vendas entre **Estados Unidos, Canadá, França, Alemanha e México**.

3. Segmentação de Clientes
   - Lucro e mediana por `Segment`.
   - Segmentos analisados: **Government, Small Business, Channel Partners, Midmarket**.
   - Distribuição de lucro, vendas e unidades vendidas por país e segmento.

4. Visuais Utilizados
   - Gráficos de colunas.
   - Gráficos de linha.
   - Gráficos de mapa e mapa preenchido (dependem da habilitação de Bing Maps / OpenStreetMap na organização).

- Objetivo
O relatório foi construído com o intuito de **demonstrar a aplicação de relatórios de Business Intelligence** utilizando o Power BI, permitindo:
- Comparar vendas entre produtos.
- Analisar o desempenho por país e segmento.
- Explorar tendências de lucro ao longo do tempo.
--------------------------------------------------------------------------------------------------------------------------------------
<br>
<h1>Módulo três</h1>

1. Transformação dos dados
   - realizado tratamento dos dados: realizado mesclação das informações firstname + lastename em todas as tabelas.
   - verificão de relação de projetos, localizações, horas trabalhada, sexo do empregado, tipo de projeto.
   - Tansformação de dados de número inteiros para horas trabalhadas.
   - Transformação de dados nullos: departamento, localicação para 'Sem registro'.
   - Retirada de dados Não factível, os quais não seriam apropriados para mensural no graficos tais como código do emprega, pois foi válidado para não ter necessidade de tratamento.
   - registros null para datas não foi possível realizar subistituição de valores.
   - verificação de dados inválidos para realizar mensuração.
     
<br>

2. Consulta extra com Queries
   - Foi realizado consulta utilizando algumas queries
   - Obs: Tive que realizar a criação de uma instância do SQL Server, pois o MySQL não estava deixando criar a instância dava erro então tive que reaprender a sixtas.

<img src='https://github.com/Nuno38/power_bi_analyst/blob/main/Imagens_M%C3%B3dulo03/queries.png' > </img>
<img src ='https://github.com/Nuno38/power_bi_analyst/blob/main/Imagens_M%C3%B3dulo03/Screenshot_15.png'></img>
<img src ='https://github.com/Nuno38/power_bi_analyst/blob/main/Imagens_M%C3%B3dulo03/Screenshot_16.png'></img> 

   - Verificação de média salárial poe genero, horas trabalhadas por projetos, quantidade de gerentes, média de trabalhadores, média dependetes. 
