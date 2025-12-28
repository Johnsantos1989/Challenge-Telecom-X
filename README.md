# Telecom X – Análise de Evasão de Clientes (Churn)
### Descrição do Projeto

Este projeto tem como objetivo analisar a evasão de clientes da Telecom X, identificando fatores que levam ao churn (cancelamento de serviços).
A partir da análise exploratória de dados (EDA), geramos insights estratégicos que podem ser utilizados para criar modelos preditivos e desenvolver ações de retenção de clientes.
O que foi feito

✅ Coleta de dados via API (requests) e transformação em DataFrame (pandas).

✅ Limpeza de dados, tratamento de valores nulos e conversão de tipos.

✅ Criação de métricas e colunas derivadas (ex.: cobrança diária).

✅ Mapeamento de colunas categóricas (Yes/No → 1/0).

✅ Análise exploratória (EDA) com estatísticas descritivas.

✅ Visualizações estratégicas (matplotlib, gráficos de barras, rosca, boxplots).

✅ Identificação de padrões e insights relacionados a churn.

Principais Insights
1️⃣ Proporção Geral de Churn

Taxa de churn: ~{churn_pct_cancelados:.2f}%

Insight: A evasão representa um problema relevante, impactando receita e retenção.

2️⃣ Churn por Tipo de Contrato

Contrato com maior churn: {contrato_maior_churn} ({valor_maior_churn:.2f}%)

Insight: Contratos de curto prazo apresentam menor fidelização e maior risco de cancelamento.

3️⃣ Churn vs Serviços de Suporte

Serviço com maior impacto: {servico_maior_risco} (diferença de {valor_maior_risco:.2f}% entre cancelados e ativos)

Insight: A ausência ou baixo valor percebido desse serviço aumenta a probabilidade de churn.

4️⃣ Churn vs Cobrança Mensal

Clientes que cancelaram pagam, em média: R$ {media_cancel:.2f}

Clientes que permaneceram: R$ {media_perm:.2f}

Insight: Valores mais altos de cobrança mensal podem contribuir para o churn.

Ferramentas e Bibliotecas Utilizadas

Python

Pandas, NumPy

Matplotlib, Seaborn

Requests

IPython.display (para exibir relatórios e markdown)

Estrutura do Repositório
/notebooks       - Notebooks com análise exploratória
/data            - Dados coletados via API
/figures         - Gráficos e visualizações
README.md        - Este arquivo

Como Usar

Clone o repositório:

git clone https://github.com/usuario/repositorio.git


Abra o notebook no Google Colab.

Execute as células para reproduzir a análise e visualizar os gráficos.

Próximos Passos

Desenvolver modelos preditivos de churn utilizando as variáveis identificadas.

Criar estratégias de retenção focadas em contratos de curto prazo e serviços críticos.

Ajustar preços ou benefícios para reduzir churn relacionado a cobranças mais altas.

✅ Autor: John Lenon Nogueira
📅 Data: 2025
