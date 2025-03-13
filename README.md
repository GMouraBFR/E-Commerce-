# 🛒 Análise de Dados de E-commerce: Insights e Segmentação RFM

Bem-vindo ao repositório! Este projeto apresenta uma análise completa de um dataset de e-commerce, cobrindo desde a limpeza e tratamento de dados até a segmentação de clientes por meio do método RFM, além de uma avaliação estatística do impacto de uma campanha de marketing.

---

## 📌 Descrição do Projeto

O objetivo deste projeto é explorar e entender o comportamento dos clientes e o desempenho das vendas de uma loja virtual. Para isso, realizamos:

- Tratamento e visualização dos dados de vendas.
- Análise de anomalias e inconsistências nos dados.
- Segmentação de clientes com base em métricas de **Recency, Frequency e Monetary** (RFM).
- Avaliação estatística do impacto de uma campanha de marketing com teste T.

Essas etapas resultam em insights relevantes para decisões estratégicas.

---

## 🛠️ Ferramentas e Tecnologias Utilizadas

- **Python**: Linguagem principal para manipulação e análise de dados.
- **Bibliotecas**:
  - `Pandas`: Limpeza e transformação dos dados.
  - `Matplotlib` e `Seaborn`: Criação de visualizações para identificação de padrões e insights.
  - `SciPy`: Teste T para análises estatísticas.
- **Segmentação RFM**: Método para identificar segmentos de clientes baseados em recência, frequência e valor monetário.

---

## 📂 Estrutura do Projeto

### 1. **Pré-processamento de Dados**
   - Conversão de colunas de datas para formato `datetime` e tratamento de valores ausentes.
   - Remoção de inconsistências, como valores negativos em `Quantity` e `UnitPrice`.
   - Identificação e remoção de duplicatas no conjunto de dados.

### 2. **Análises Exploratórias**
   - Análise de padrões de compras ao longo do tempo.
   - Identificação de relação entre variáveis como `Quantity` e `UnitPrice`.
   - Detecção de outliers com gráficos de **boxplot**.

### 3. **Segmentação RFM**
   - Cálculo de **Recency**, **Frequency** e **Monetary** para cada cliente.
   - Criação de uma pontuação RFM com base nos quartis.
   - Visualização da distribuição de recência, frequência e valor monetário por segmento.

### 4. **Impacto da Campanha de Marketing**
   - Divisão dos dados em dois períodos: **antes** e **depois da campanha**.
   - Cálculo das médias de vendas nos dois períodos.
   - Realização de teste T para avaliar a significância das mudanças.

---

## 📊 Exemplos de Visualizações

1. **Compras ao Longo do Tempo**  
   Um gráfico de linha destacando a frequência de compras por dia, revelando padrões sazonais.  

2. **Boxplot de Variáveis Numéricas**  
   Gráficos que ajudam a identificar outliers em `Quantity` e `UnitPrice`.

3. **Distribuições de Variáveis RFM**  
   Histogramas mostrando a distribuição de **Recency**, **Frequency** e **Monetary**, base para a segmentação de clientes.

4. **Segmentação RFM**  
   Tabela que classifica os clientes em segmentos com base nas pontuações RFM. Por exemplo:  

   | **RFM Score** | **Segmento**               | **Descrição**                                   |
   |---------------|----------------------------|------------------------------------------------|
   | 111           | Clientes Inativos          | Precisam ser reativados com campanhas.         |
   | 444           | Clientes Leais e Valiosos  | Merecem foco em programas de fidelidade.       |

5. **Impacto da Campanha de Marketing**  
   Gráficos comparando as médias de vendas antes e depois da campanha, complementados pelo resultado do teste T:  

   - Estatística T: **X**  
   - Valor P: **Y**  
   - Conclusão: **Significativa** ou **Não Significativa**.


