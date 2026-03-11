# Challenge-TelecomX_Parte2

# 📊 Telecom X — Predição de Evasão de Clientes (Churn)

## 📌 Descrição do Projeto

Este projeto tem como objetivo desenvolver modelos de Machine Learning capazes de prever a evasão de clientes (Churn) da empresa fictícia Telecom X.

A evasão de clientes é um problema relevante para empresas de telecomunicações, pois identificar clientes com maior probabilidade de cancelamento permite criar estratégias de retenção mais eficazes.

Neste projeto foram utilizados dados previamente tratados na etapa de ETL (Extração, Transformação e Carga) para treinar e avaliar modelos preditivos.

---

# 📂 Estrutura do Projeto

telecomx-churn-prediction

├── telecomx_modelos.ipynb  
├── dados_tratados.csv  
└── README.md  

Arquivos:

- telecomx_modelos.ipynb → Notebook com análise exploratória e construção dos modelos preditivos  
- dados_tratados.csv → Dataset tratado na etapa anterior do projeto  
- README.md → Documentação do projeto  

---

# 📊 Etapas do Projeto

## 1️⃣ Carregamento dos dados

Os dados tratados foram carregados a partir do arquivo:

dados_tratados.csv

Esse dataset contém informações sobre clientes da Telecom X, incluindo:

- tempo de permanência
- tipo de contrato
- método de pagamento
- valor mensal
- churn (evasão)

---

# 🔎 Análise Exploratória

Foram realizadas análises para entender o comportamento dos clientes.

Principais análises realizadas:

- distribuição de churn
- correlação entre variáveis
- análise de permanência do cliente
- análise de gastos mensais

Essas análises ajudam a identificar padrões associados à evasão.

---

# 🤖 Modelos de Machine Learning

Foram treinados dois modelos de classificação:

### Regressão Logística

Modelo estatístico utilizado para prever probabilidades de ocorrência de um evento binário.

### Random Forest

Modelo baseado em árvores de decisão, capaz de capturar relações mais complexas entre as variáveis.

---

# 📈 Avaliação dos Modelos

Os modelos foram avaliados utilizando as seguintes métricas:

- Accuracy
- Precision
- Recall
- F1-score
- Matriz de Confusão

Essas métricas permitem avaliar a capacidade dos modelos em prever corretamente a evasão de clientes.

---

# 📊 Importância das Variáveis

Foi realizada uma análise de importância das variáveis utilizando o modelo Random Forest.

As variáveis mais relevantes para prever churn incluem:

- tipo de contrato
- tempo de permanência do cliente
- valor mensal do serviço
- método de pagamento

Esses fatores ajudam a entender o comportamento dos clientes que tendem a cancelar o serviço.

---

# 📌 Conclusão

Os resultados indicam que clientes com contratos mensais, menor tempo de permanência e determinados métodos de pagamento apresentam maior probabilidade de evasão.

Entre os modelos avaliados, o Random Forest apresentou melhor desempenho, demonstrando maior capacidade de identificar padrões nos dados.

As informações obtidas neste projeto podem auxiliar a empresa Telecom X a desenvolver estratégias de retenção de clientes e reduzir o churn.

---

# 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# 👨‍💻 Autor

Projeto desenvolvido como parte de um desafio de Ciência de Dados com foco em análise de dados e modelos preditivos de churn.
