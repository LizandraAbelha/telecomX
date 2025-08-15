# Telecom Customer Churn Analysis - TelecomX

[![GitHub repo size](https://img.shields.io/github/repo-size/LizandraAbelha/telecomX)](https://github.com/LizandraAbelha/telecomX)
[![Python](https://img.shields.io/badge/python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/LizandraAbelha/telecomX/blob/main/TelecomX_BR.ipynb)

---

## Descrição do Projeto
Análise de evasão de clientes (churn) em uma empresa de telecomunicações.  
O projeto realiza desde a exploração de dados, análise de correlação, visualização de variáveis até a construção de modelos de machine learning para prever clientes com maior risco de cancelamento.

---

## Conteúdo do Repositório
- `TelecomX_BR.ipynb` - Notebook com o pipeline completo.
- Base de dados fictícia de clientes com informações demográficas, serviços contratados, valores cobrados e status de churn.

---

## Objetivos do Projeto
1. **Análise Exploratória**
   - Distribuição de variáveis.
   - Correlação entre variáveis numéricas e churn.
   - Padrões de comportamento de clientes que cancelaram o serviço.

2. **Modelagem Preditiva**
   - Dois modelos principais:
     - **Regressão Logística** (com normalização)
     - **Random Forest** (sem normalização)
   - Avaliação com métricas: Acurácia, Precisão, Recall, F1-score e Matriz de Confusão.
   - Comparação de desempenho e análise de overfitting/underfitting.

3. **Interpretação e Conclusões**
   - Identificação das variáveis mais relevantes.
   - Estratégias de retenção de clientes baseadas nos resultados.

---

## Principais Resultados
- **Top Variáveis Impactantes (Logistic Regression):**
  - `tenure`, `Contract_Two year`, `Charges`, `Contract_Month-to-month`, `InternetService_DSL`  
- **Top Variáveis Impactantes (Random Forest):**
  - `Charges`, `tenure`, `Contract_Month-to-month`, `PaymentMethod_Electronic check`, `TechSupport_No`

- Clientes com menor tempo de contrato e gastos mais altos apresentam maior risco de churn.
- Random Forest apresentou melhor desempenho geral, enquanto Regressão Logística permite interpretação direta das variáveis.

---


## Como Rodar o Notebook
1. Clonar o repositório:

2. Abrir o notebook no Google Colab ou Jupyter Notebook.

3. Executar todas as células na ordem.

3. Certifique-se de que as bibliotecas abaixo estão instaladas: pandas, numpy, matplotlib, seaborn, scikit-learn


