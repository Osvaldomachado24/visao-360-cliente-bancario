Projeto – Visão 360° do Cliente Bancário
📌 Descrição

Este projeto consiste na construção de uma solução analítica completa para análise de clientes bancários, risco de crédito e churn.

A arquitetura segue boas práticas de modelagem dimensional (Star Schema) e construção de KPIs estratégicos em Power BI.

🎯 Objetivos

Monitorar churn de clientes

Analisar perfil de risco

Avaliar comportamento transacional

Analisar concessão de crédito

Criar visão executiva consolidada

## 🐍 Etapa Python (Pandas)
Na pasta `/jupyter_ipynb`, encontras o processo de:
- Limpeza de dados corrompidos.
- Engenharia de Atributos (Feature Engineering) para calcular o risco inicial.
- Exportação dos dados limpos para consumo em SQL/Power BI.

  ## 🚀 Tecnologias Utilizadas
- **Python (Pandas)**: Manipulação e limpeza.
- **Power BI**: Visualização e DAX.
- **SQL**: Criação de tabelas e views de negócio.

🏗 Arquitetura
🔄 Pipeline de Dados

Python (Pandas) → SQL (Modelagem Dimensional) → Power BI (Dashboard + DAX)

📊 Modelo de Dados

Dimensões:

d_clientes_churn

d_calendario

d_agencias_atm

Fatos:

f_transacoes

f_credito_risco

Modelo estrela implementado na camada de banco de dados.

📈 KPIs Desenvolvidos

Total de Clientes

Clientes Churn

Taxa de Churn (%)

Crédito Concedido

Total de Transações

Ticket Médio

🛠 Tecnologias Utilizadas

Python (Pandas)

SQL

Power BI

DAX

📊 Principais Insights

Identificação de segmentos com maior churn

Relação entre risco e concessão de crédito

Análise temporal de transações

Distribuição de crédito por objetivo

🚀 Próximos Passos

Modelagem preditiva de churn

Segmentação por Machine Learning

Automatização de pipeline

