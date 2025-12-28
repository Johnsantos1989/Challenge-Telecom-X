📊 Projeto de Análise Exploratória de Dados (EDA) – Telecom X

💡 Identificação dos principais fatores de evasão de clientes (Churn) para decisão estratégica de retenção.

📧 E-mail: johnlenon8919@gmail.com

🔗 LinkedIn: linkedin.com/in/analistafinanceiro-powerbi
🐙 GitHub: github.com/Johnsantos1989

Python | Pandas | Matplotlib | Jupyter | Licença

🧠 Objetivo do Projeto

A Telecom X enfrenta um alto índice de cancelamentos e deseja identificar os fatores que levam os clientes a encerrar seus serviços.
O objetivo da análise é entender quais características impactam o churn, considerando:

💰 Cobrança mensal e total
⭐ Tipo de contrato e fidelização
🛠 Serviços de suporte contratados
📈 Relação entre cobrança, serviços e evasão
📊 Visualizações estratégicas para tomada de decisão

🧩 Etapas da Análise

🔹 1. Coleta e Consolidação dos Dados
Dados importados de uma API JSON e convertidos em DataFrame do Pandas.

🔹 2. Limpeza e Transformação

Remoção de registros vazios

Conversão de colunas para tipos numéricos

Mapeamento de respostas Yes/No para 1/0

Criação de métricas derivadas, como cobrança diária

🔹 3. Análise Exploratória (EDA)

Proporção geral de churn

Taxa média de churn por tipo de contrato

Churn por serviços de suporte

Relação entre cobrança mensal e churn

🔹 4. Visualizações Estratégicas

Gráficos de barras, rosca e boxplots para insights claros

Destaque para clientes com maior risco de cancelamento

🔹 5. Relatórios Automáticos

Resumo de métricas e insights principais gerado em Markdown

Identificação de pontos críticos para retenção de clientes

📊 Principais Resultados
Indicador	Descrição
💰 Cobrança Mensal	Clientes que cancelaram pagam, em média, mais que os que permaneceram
⭐ Tipo de Contrato	Contratos de curto prazo apresentam maior taxa de churn
🛠 Serviços de Suporte	Serviço {servico_maior_risco} apresenta maior impacto na evasão
📈 Proporção Geral	Taxa de churn geral: ~{churn_pct_cancelados:.2f}%
⚠️ Recomendação	Focar em retenção de contratos de curto prazo e serviços críticos
🎯 Conclusão

A análise permite decisões estratégicas para reduzir churn, garantindo:
✅ Maior retenção de clientes
✅ Identificação de serviços críticos
✅ Ajustes de cobrança e contratos estratégicos

📉 Recomendação final: priorizar clientes e serviços com maior risco de churn.
💹 Foco em contratos de longo prazo e melhoria de serviços de suporte.

🧰 Tecnologias Utilizadas
Ferramenta	Função
🐍 Python 3	Linguagem principal
📦 Pandas	Manipulação e análise de dados
📈 Matplotlib	Criação de gráficos e visualizações
🧮 Jupyter Notebook	Ambiente interativo de desenvolvimento
🧾 IPython.display	Geração automática do relatório final
📂 Estrutura do Projeto
/notebooks       - Notebooks com análise exploratória
/data            - Dados coletados via API
/figures         - Gráficos e visualizações
README.md        - Este arquivo
