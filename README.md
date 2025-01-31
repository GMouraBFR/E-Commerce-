# E-Commerce-
 Identificar os perfis dos consumidores
Carregamento de Dados: Utilizamos Google Colab para carregar e ler um arquivo CSV de dados de e-commerce em chunks, garantindo a correta manipulação e visualização dos dados.

Tratamento de Dados: Realizamos a verificação da estrutura dos dados, tratamento de valores ausentes e conversão da coluna 'InvoiceDate' para o tipo datetime.

Análise Exploratória de Dados (EDA): Criamos visualizações iniciais para entender a distribuição das compras ao longo do tempo.

Cálculo de Métricas RFM: Calculamos as métricas Recency, Frequency e Monetary para cada cliente, segmentando-os em quartis para atribuir pontuações RFM.

Visualizações RFM: Geramos gráficos para visualizar a distribuição das métricas RFM, como recência, frequência e valor monetário.

Teste de Hipótese: Realizamos um teste de hipótese simples, comparando a média das compras entre clientes que fizeram mais de 10 compras e aqueles que fizeram 10 ou menos. Rejeitamos a hipótese nula ao encontrarmos uma diferença significativa nas médias das compras entre os dois grupos.
