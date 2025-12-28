🚀 Telecom X – Análise de Evasão de Clientes (Churn)
📌 Descrição do Projeto

Este projeto tem como objetivo analisar a evasão de clientes da Telecom X, identificando os principais fatores que levam ao churn (cancelamento de serviços).
A partir da Análise Exploratória de Dados (EDA), geramos insights estratégicos que podem apoiar a criação de modelos preditivos e o desenvolvimento de ações eficazes de retenção de clientes.

🎯 Objetivos da Análise

Coletar e tratar dados via API (requests) e pandas.

Aplicar técnicas de ETL para limpeza e transformação dos dados.

Mapear dados categóricos (Yes/No → 1/0) e tratar valores nulos.

Criar métricas derivadas (ex.: cobrança diária).

Realizar visualizações estratégicas com gráficos de barras, rosca e boxplots.

Gerar insights acionáveis para reduzir churn e aumentar a retenção.

📊 Principais Insights
1️⃣ Proporção Geral de Churn

Taxa de churn: ~{churn_pct_cancelados:.2f}%

Insight: A evasão representa um problema relevante para receita e retenção.

2️⃣ Churn por Tipo de Contrato

Contrato com maior churn: {contrato_maior_churn} ({valor_maior_churn:.2f}%)

Insight: Contratos de curto prazo têm menor fidelização e maior risco de cancelamento.

3️⃣ Churn vs Serviços de Suporte

Serviço com maior impacto: {servico_maior_risco} (diferença de {valor_maior_risco:.2f}% entre cancelados e ativos)

Insight: A ausência ou percepção de baixo valor desse serviço aumenta a probabilidade de churn.

4️⃣ Churn vs Cobrança Mensal

Clientes que cancelaram: R$ {media_cancel:.2f}

Clientes que permaneceram: R$ {media_perm:.2f}

Insight: Cobranças mais altas podem contribuir para a evasão.

🛠 Ferramentas e Bibliotecas

Python

pandas, numpy

matplotlib, seaborn

requests

IPython.display (para exibir relatórios e Markdown)

📂 Estrutura do Repositório
/notebooks       - Notebooks com análise exploratória
/data            - Dados coletados via API
/figures         - Gráficos e visualizações
README.md        - Este arquivo

💻 Como Usar

Clone o repositório:

git clone https://github.com/usuario/repositorio.git


Abra o notebook no Google Colab.

Execute as células para reproduzir a análise e visualizar os gráficos.

🚀 Próximos Passos

Criar modelos preditivos de churn com base nas variáveis identificadas.

Desenvolver estratégias de retenção focadas em contratos de curto prazo e serviços críticos.

Ajustar preços ou benefícios para reduzir churn associado a cobranças mais altas.

✅ Autor

John Lenon Nogueira
📅 Data: 2025
