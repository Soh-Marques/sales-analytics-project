📊 Projeto de Análise de Vendas Superstore
📌 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de aplicar técnicas de ETL (Extract, Transform, Load) e Análise Exploratória de Dados utilizando Python e Pandas.

O dataset utilizado contém informações de vendas de uma empresa global, permitindo análises relacionadas a faturamento, lucro, segmentos de clientes, categorias de produtos e mercados de atuação.

O foco do projeto foi transformar dados brutos em um conjunto de dados limpo e estruturado para apoiar análises de negócio e futuras visualizações em Power BI.

🛠️ Tecnologias Utilizadas
Python
Pandas
Google Colab
GitHub
Power BI (próxima etapa)

📂 Estrutura do Projeto
superstore-sales-analysis
│
├── data
│   ├── raw
│   │   └── SuperStoreOrders.csv
│   │
│   └── processed
│       └── superstore_clean.csv
│
├── notebooks
│   └── superstore_etl_analysis.ipynb
│
└── README.md
🔄 Processo ETL

1. Extração
Importação do dataset original.
Verificação da estrutura dos dados.

3. Transformação

Foram realizadas as seguintes etapas:

Conversão de tipos de dados.
Conversão de colunas de data.
Verificação de valores nulos.
Verificação de registros duplicados.
Padronização de informações para análise.

3. Engenharia de Atributos

Foram criadas novas métricas para enriquecer as análises:

Profit Margin

Calcula a margem de lucro percentual de cada venda.

Delivery Days

Calcula o tempo de entrega em dias.

Month

Identifica o mês da venda.

Month Name

Identifica o nome do mês para análises temporais.

📈 Análises Realizadas

Durante a análise exploratória foram avaliados:

Distribuição de vendas por categoria.
Distribuição de clientes por segmento.
Distribuição de pedidos por mercado.
Identificação de vendas com lucro negativo.
Comparação de faturamento entre categorias.
Indicadores de desempenho comercial.

🎯 Principais Objetivos
Demonstrar conhecimentos em ETL com Python.
Aplicar boas práticas de tratamento de dados.
Criar métricas relevantes para análise de negócio.
Preparar os dados para consumo em ferramentas de BI.

🚀 Próximos Passos
Construção de dashboard interativo no Power BI.
Criação de KPIs estratégicos.
Desenvolvimento de visualizações gerenciais.


👩‍💻 Autora

Solange Marques

Em transição para a área de Data Analytics, desenvolvendo projetos práticos com Python, SQL, Power BI e análise de dados.
