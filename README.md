# 📊 Projeto de Análise Exploratória de Dados (EDA) – Telecom X

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellowgreen)
![Requests](https://img.shields.io/badge/Requests-API%20Access-blueviolet)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![License](https://img.shields.io/badge/License-MIT-green)

💡 Identificação dos principais fatores de evasão de clientes (Churn) para decisão estratégica de retenção.
---

## 🧠 Objetivo do Projeto

A Telecom X enfrenta um alto índice de cancelamentos e deseja identificar os fatores que levam os clientes a encerrar seus serviços.  
O objetivo da análise é entender quais características impactam o churn, considerando:

- 💰 Cobrança mensal e total  
- ⭐ Tipo de contrato e fidelização  
- 🛠 Serviços de suporte contratados  
- 📈 Relação entre cobrança, serviços e evasão  
- 📊 Visualizações estratégicas para tomada de decisão  

---

## 🧩 Etapas da Análise

### 🔹 1. Coleta e Consolidação dos Dados
- Dados importados de uma API JSON e convertidos em DataFrame do Pandas.

### 🔹 2. Limpeza e Transformação
- Remoção de registros vazios  
- Conversão de colunas para tipos numéricos  
- Mapeamento de respostas Yes/No para 1/0  
- Criação de métricas derivadas, como cobrança diária

### 🔹 3. Análise Exploratória (EDA)
- Proporção geral de churn  
- Taxa média de churn por tipo de contrato  
- Churn por serviços de suporte  
- Relação entre cobrança mensal e churn

### 🔹 4. Visualizações Estratégicas
- Gráficos de barras, rosca e boxplots para insights claros  
- Destaque para clientes com maior risco de cancelamento

### 🔹 5. Relatórios Automáticos
- Resumo de métricas e insights principais gerado em Markdown  
- Identificação de pontos críticos para retenção de clientes

---

## 📊 Principais Visualizações e Resultados

### 1️⃣ Proporção Geral de Churn
**Taxa de churn geral:** ~26.54%  
**Insight:** A evasão representa um problema relevante, impactando receita e retenção.

### 2️⃣ Churn por Tipo de Contrato
**Contrato com maior churn:** Mensal (45.32%)  
**Insight:** Contratos de curto prazo apresentam maior risco de cancelamento.

### 3️⃣ Churn vs Serviços de Suporte
**Serviço com maior impacto:** TechSupport (diferença de 18.70% entre cancelados e ativos)  
**Insight:** A ausência ou percepção de baixo valor desse serviço aumenta a probabilidade de churn.

### 4️⃣ Churn vs Cobrança Mensal
- Clientes que cancelaram: R$ 85.40  
- Clientes que permaneceram: R$ 65.20  
**Insight:** Cobranças mais altas podem contribuir para a evasão.

---

## 🎯 Conclusão

A análise permite decisões estratégicas para reduzir churn, garantindo:  
✅ Maior retenção de clientes  
✅ Identificação de serviços críticos  
✅ Ajustes de cobrança e contratos estratégicos  

📉 **Recomendação final:** priorizar clientes e serviços com maior risco de churn.  
💹 Foco em contratos de longo prazo e melhoria de serviços de suporte.

---

## 🧰 Tecnologias Utilizadas

| Ferramenta         | Função                           |
|--------------------|----------------------------------|
| 🐍 Python 3         | Linguagem principal              |
| 📦 Pandas           | Manipulação e análise de dados   |
| 🌐 `Requests`       | Acesso a dados via API           |
| 📈 Matplotlib       | `Criação de gráficos`              |
| ☁️ Google Colab     | Ambiente interativo de análise   |
| 🧾 IPython.display  | Geração automática de relatórios |

---

## 📂 Estrutura do Projeto

```bash
Projeto_EDA_TelecomX/
│
├── data/              # Dados brutos e tratados
├── notebooks/         # Jupyter Notebooks com as análises
├── src/               # Scripts Python para limpeza, transformação e visualização
├── reports/           # Relatórios gerados em Markdown/HTML
├── README.md          # Documentação principal do projeto
└── requirements.txt   # Dependências do projeto
