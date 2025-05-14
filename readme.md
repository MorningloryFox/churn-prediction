# 🔍 Churn Prediction – Detecção de Evasão de Clientes

Este projeto tem como objetivo prever o cancelamento de clientes de uma empresa de telecom utilizando técnicas de Machine Learning. Foi desenvolvido em Python, com foco em um processo completo de ciência de dados, desde a análise exploratória até a exportação do modelo e integração com Power BI.

---

## 🧠 Objetivos

- Identificar clientes com maior propensão ao churn
- Utilizar modelos preditivos para antecipar cancelamentos
- Gerar insights estratégicos para o negócio
- Integrar resultados com BI para visualização executiva

---

## 📁 Estrutura do Projeto

churn-prediction/
│
├── data/ → Dataset original
│ └── Telco-Customer-Churn.csv
│
├── notebooks/ → Análises e modelo
│ └── churn_model.ipynb
│
├── exports/ → Saídas do projeto
│ ├── model_churn_rf.joblib
│ └── predicoes_churn.csv
│
├── powerbi/ → Dashboard (arquivo .pbix, se aplicável)
│
├── requirements.txt → Dependências do projeto
└── README.md → Este documento


---

## 🛠️ Tecnologias Utilizadas

- Python 3.10
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- Joblib
- Power BI

---

## 🚶‍♂️ Etapas do Projeto

### 1. Carregamento e Limpeza de Dados
- Leitura do CSV com Pandas
- Conversão de colunas, remoção de dados inconsistentes
- Codificação de variáveis categóricas

### 2. Análise Exploratória (EDA)
- Distribuições de churn
- Gráficos de dispersão, histogramas e correlação
- Análise de variáveis com maior impacto

### 3. Preparação dos Dados
- Separação entre features e target
- Divisão em treino e teste (80/20)
- Normalização (padronização)

### 4. Treinamento do Modelo
- Random Forest Classifier
- Avaliação por acurácia, recall, precisão e F1
- Matriz de confusão e classificação

### 5. Explicabilidade
- Gráfico de importância das variáveis
- Interpretação de influências no churn

### 6. Exportação
- Modelo treinado salvo com Joblib
- CSV com predições gerado para BI

### 7. Integração com Power BI
- Visualização de predições
- Dashboards interativos com filtros por cliente, plano, contrato, etc.

---

## 📊 Exemplo de Uso no Power BI

Após importar `predicoes_churn.csv`, é possível:

- Visualizar clientes com risco de churn
- Comparar valores reais e preditos
- Explorar métricas por categoria
- Acompanhar a acurácia do modelo em tempo real

---

## 📎 Dataset

Dataset público: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## ✍️ Autor

**[Daniel Alfredo Silva dos Santos]**  
Analista de Dados com foco em Ciência de Dados e BI  
[(https://br.linkedin.com/in/das1)]

---

## 🧾 Licença

Este projeto é de uso educacional e demonstração. Sinta-se livre para adaptá-lo.
