<<<<<<< HEAD
# 📊 Customer Churn Analysis Using Python
## 🧾 Executive Summary | Resumo Executivo

### 🇧🇷 Português (Brasil)

Este projeto apresenta uma **análise exploratória de dados (EDA)** voltada à compreensão do **cancelamento de clientes (Customer Churn)** em uma empresa com uma base superior a **800 mil clientes**.

A partir da análise de dados comportamentais, contratuais e financeiros, o estudo identifica **fatores críticos associados ao churn**, permitindo transformar informações operacionais em **insights estratégicos para o negócio**.

Foram utilizadas técnicas de **limpeza, exploração e visualização de dados**, com foco na identificação de padrões relevantes, como:
- Impacto da duração do contrato no cancelamento
- Relação entre atrasos de pagamento e churn
- Influência da frequência de uso e do nível de interação do cliente

Os resultados obtidos fornecem **subsídios objetivos para a tomada de decisão**, possibilitando a definição de **ações preventivas e estratégias de retenção**, com potencial de redução significativa da taxa de cancelamento e aumento do valor do cliente ao longo do tempo.

Este projeto demonstra competências em **análise de dados, pensamento analítico e comunicação de resultados**, alinhadas às demandas do mercado corporativo e de equipes de dados.

---

### 🇺🇸 English (US)

This project presents an **Exploratory Data Analysis (EDA)** focused on understanding **Customer Churn** within a company holding a customer base of over **800,000 clients**.

By analyzing behavioral, contractual, and financial data, the study identifies **key factors associated with churn**, transforming operational data into **strategic business insights**.

The analysis applies **data cleaning, exploration, and visualization techniques**, emphasizing the identification of relevant patterns, such as:
- The impact of contract duration on churn
- The relationship between payment delays and cancellations
- The influence of usage frequency and customer interaction levels

The findings provide **objective support for decision-making**, enabling the development of **preventive actions and customer retention strategies**, with the potential to significantly reduce churn rates and increase customer lifetime value.

This project demonstrates skills in **data analysis, analytical thinking, and results communication**, aligned with corporate environments and modern data-driven teams.

---


# 📊 Python Insights – Customer Churn Analysis  
*Data Analysis Project | Python, Pandas & Plotly*

---

## 🌍 Project Overview | Visão Geral do Projeto

### 🇧🇷 Português (Brasil)

Este projeto apresenta uma **análise exploratória de dados (EDA)** focada no **cancelamento de clientes (Customer Churn)** de uma empresa com mais de **800 mil clientes**.

O objetivo principal é **identificar padrões e comportamentos** associados ao cancelamento de serviços, transformando dados brutos em **insights acionáveis** que podem apoiar **decisões estratégicas de negócio**.

Este projeto foi desenvolvido com foco em **boas práticas de análise de dados**, clareza na comunicação dos resultados e visualizações interativas, sendo ideal para **portfólio profissional e apresentação a recrutadores**.

---

### 🇺🇸 English (US)

This project presents an **Exploratory Data Analysis (EDA)** focused on **Customer Churn** for a company with over **800,000 customers**.

The main goal is to **identify patterns and behaviors** related to service cancellations, transforming raw data into **actionable insights** that support **strategic business decisions**.

The project was developed following **data analysis best practices**, clear result communication, and interactive visualizations, making it suitable for **professional portfolios and recruiter evaluation**.

---

## 🎯 Business Problem | Problema de Negócio

### 🇧🇷
- Por que os clientes estão cancelando seus contratos?
- Quais fatores mais influenciam o churn?
- Quais ações podem reduzir o número de cancelamentos?

### 🇺🇸
- Why are customers canceling their contracts?
- Which factors most influence churn?
- What actions could help reduce customer cancellations?

---

## 🗂 Dataset Description | Descrição do Conjunto de Dados

### 🇧🇷
O conjunto de dados contém informações sobre perfil, comportamento, contratos, pagamentos e interações dos clientes com a empresa.

**Principais variáveis analisadas:**
- `idade` – Idade do cliente  
- `sexo` – Gênero  
- `tempo_como_cliente` – Tempo como cliente  
- `frequencia_de_uso` – Frequência de uso do serviço  
- `ligacoes_call_center` – Número de ligações ao call center  
- `dias_atraso` – Dias de atraso em pagamentos  
- `assinatura` – Tipo de assinatura  
- `duracao_contrato` – Duração do contrato  
- `total_gasto` – Total gasto pelo cliente  
- `meses_ultima_interacao` – Meses desde a última interação  
- `cancelou` – Indicador de cancelamento (1 = Cancelou, 0 = Ativo)

---

### 🇺🇸
The dataset includes customer profile, behavior, contract, payment, and interaction data.

**Main analyzed features:**
- `age`
- `gender`
- `time_as_customer`
- `frequency_of_use`
- `call_center_calls`
- `days_late_payment`
- `subscription`
- `contract_duration`
- `total_spent`
- `months_since_last_interaction`
- `cancelled` (1 = Yes, 0 = No)

---

## 🛠 Technologies & Tools | Tecnologias Utilizadas

- Python 3  
- Pandas  
- Plotly  
- IPython / Jupyter  
- PyCharm  

---

## 🔄 Data Cleaning & Preparation | Limpeza e Preparação dos Dados

### 🇧🇷
- Remoção de colunas irrelevantes
- Identificação de dados ausentes ou inconsistentes
- Exclusão de registros com valores nulos
- Padronização dos dados para análise

### 🇺🇸
- Removal of irrelevant columns
- Identification of missing or inconsistent data
- Removal of null records
- Data standardization for analysis

---

## 📈 Exploratory Data Analysis (EDA) | Análise Exploratória

### 🇧🇷
- Análise inicial da taxa de cancelamento
- Comparação entre clientes ativos e cancelados
- Análise da relação entre churn e:
  - Duração do contrato
  - Frequência de uso
  - Atrasos de pagamento
  - Interação com o call center

Visualizações interativas foram criadas com **Plotly**, facilitando a identificação de padrões e tendências.

---

### 🇺🇸
- Initial churn rate analysis
- Comparison between active and canceled customers
- Relationship analysis between churn and:
  - Contract duration
  - Usage frequency
  - Payment delays
  - Customer support interactions

Interactive visualizations were created using **Plotly** to highlight patterns and trends.

---

## 🔍 Key Insights | Principais Insights

### 🇧🇷
- Clientes com **contratos de curta duração** apresentam maior taxa de churn  
- **Atrasos em pagamentos** estão fortemente associados ao cancelamento  
- **Baixa frequência de uso** aumenta a probabilidade de churn  
- Menor interação recente indica maior risco de cancelamento  

---

### 🇺🇸
- Customers with **short-term contracts** show higher churn rates  
- **Payment delays** are strongly associated with churn  
- **Low usage frequency** increases churn probability  
- Lack of recent interaction indicates higher churn risk  

---

## 📊 Visualizations | Visualizações
### BR
- Histogramas comparativos
- Gráficos interativos com segmentação por churn
- Análises visuais focadas em tomada de decisão

---
### US
- Comparative histograms
- Interactive charts with churn segmentation
- Visual analyses focused on decision-making
- 
## ✅ Conclusion & Recommendations | Conclusão e Recomendações

### 🇧🇷
- Incentivar contratos de longo prazo  
- Melhorar políticas de cobrança e comunicação financeira  
- Aumentar o engajamento de clientes com baixo uso  
- Adotar estratégias proativas de retenção  

---

### 🇺🇸
- Encourage long-term contracts  
- Improve billing and financial communication  
- Increase engagement with low-usage customers  
- Adopt proactive customer retention strategies  

---

## ▶️ How to Run the Project | Como Executar o Projeto

```bash
pip install pandas plotly ipython
=======
# Customer-Churn-Analysis
Customer churn analysis using Python and Pandas | Análise de cancelamento de clientes com Python.
>>>>>>> f33ac689a4815cbb355dd8282a926fa27f05a105
