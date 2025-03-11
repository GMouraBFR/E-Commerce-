 Análise de Dados de E-commerce: Insights e Segmentação RFM 
 
Este repositório contém uma análise detalhada de um dataset de e-commerce, explorando desde a limpeza de dados até a segmentação de clientes utilizando o método RFM. Também realizamos uma análise estatística para avaliar o impacto de uma campanha de marketing.

 Descrição do Projeto
O objetivo deste projeto é fornecer insights sobre o comportamento de clientes e o desempenho de vendas por meio de:

Tratamento e visualização de dados de vendas.

Análise de anomalias, outliers e inconsistências.

Segmentação de clientes com base em métricas de Recency, Frequency e Monetary (RFM).

Comparação de desempenho antes e depois de uma campanha de marketing utilizando teste T.

 Ferramentas e Tecnologias Utilizadas
Python: Para manipulação e análise de dados.

Bibliotecas:

Pandas: Limpeza e transformação de dados.

Matplotlib e Seaborn: Visualização de padrões e insights.

SciPy: Teste estatístico (Teste T).

Segmentação RFM: Identificação de segmentos de clientes com base em recência, frequência e valor monetário.

Estrutura do Projeto
1. Pré-processamento de Dados
Conversão de colunas de datas para formato datetime e tratamento de valores ausentes.

Remoção de inconsistências, como valores negativos em Quantity e UnitPrice.

Análise de duplicatas no conjunto de dados.

2. Análises Explorativas
Identificação de padrões de compras ao longo do tempo.

Análise da relação entre variáveis (Quantity e UnitPrice).

Detecção de outliers com gráficos de boxplot.

3. Segmentação RFM
Cálculo de métricas de Recency, Frequency e Monetary para cada cliente.

Criação de pontuação RFM com base nos quartis.

Visualização da distribuição de recência, frequência e valor monetário em cada segmento.

4. Impacto da Campanha de Marketing
Divisão dos dados em dois períodos (antes e depois da campanha).

Cálculo das médias de vendas nos dois períodos.

Aplicação de teste T para verificar a significância estatística entre as médias.

📊 Exemplos de Visualizações
1. Compras ao Longo do Tempo
Gráfico de linha destacando a frequência de compras por dia, revelando padrões sazonais.


2. Boxplot de Variáveis Numéricas
Um gráfico que identifica outliers em Quantity e UnitPrice.


3. Distribuições de Variáveis RFM
Histogramas mostrando a distribuição das métricas de Recência, Frequência e Monetário, essenciais para a segmentação.


4. Segmentação RFM
Tabela destacando os segmentos de clientes com base na pontuação RFM. Exemplo:

RFM Score	Segmento	Descrição
111	Clientes Inativos	Precisam ser reativados com campanhas.
444	Clientes Leais e Valiosos	Merecem foco em programas de fidelidade.
5. Impacto da Campanha de Marketing
Gráfico comparando as médias de vendas antes e depois da campanha, complementado pelo resultado do teste T:

Estatística T: X

Valor P: Y

Conclusão: Significativa/Não Significativa
