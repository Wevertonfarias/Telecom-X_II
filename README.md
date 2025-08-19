# 📊 TelecomX II – Análise de Cancelamento de Clientes

Este repositório contém um projeto completo de análise de dados voltado para compreender as causas do alto índice de cancelamento de clientes da empresa fictícia Telecom X, uma operadora de telecomunicações.

## 🎯 Objetivo

O principal desafio foi aplicar conceitos de **ETL (Extração, Transformação e Carga)** e **EDA (Análise Exploratória de Dados)** para identificar padrões e características que influenciam a saída dos clientes, ajudando na criação de estratégias para aumentar a retenção.

## 📋 Sobre os Dados

O conjunto de dados utilizado contém informações de 7.032 clientes com 21 variáveis, incluindo:
- Informações demográficas (gênero, idade)
- Serviços contratados (internet, telefone, streaming)
- Informações financeiras (valor mensal, valor total)
- Status de cancelamento (variável alvo)

## 🛠️ Etapas do Projeto

### 1️⃣ Extração
- Carregamento dos dados do arquivo `dados_tratados.csv`
- Visualização inicial dos dados com `df.head()`
- Verificação da estrutura dos dados com `df.info()`

### 2️⃣ Transformação e Limpeza
- Remoção da coluna `ID_cliente` (irrelevante para análise)
- Eliminação de valores nulos na coluna `Cancelamento` e `Valor_total`
- Conversão da coluna `Valor_total` para tipo numérico
- Substituição de "No internet service" por "No" em várias colunas de serviços
- Codificação de variáveis categóricas usando **One-Hot Encoding**
- Normalização de dados numéricos com `MinMaxScaler`

### 3️Análise Exploratória (EDA)
- Análise da distribuição de cancelamentos (73,4% ativos vs 26,6% cancelados)
- Cálculo de matriz de correlação entre variáveis
- Heatmap interativo mostrando correlações relevantes (limiar ≥ 0.2)
- Identificação de variáveis mais correlacionadas com cancelamento

## 🔍 Principais Análises Realizadas

- **Distribuição de Cancelamento**: 73,4% clientes ativos vs 26,6% cancelados
- **Tempo de Serviço**: Análise do impacto dos `Meses_com_empresa` no cancelamento
- **Serviços Contratados**: Relação entre cancelamento e serviços como internet, telefone, segurança online
- **Formas de Pagamento**: Análise do impacto dos métodos de pagamento na retenção
- **Perfil Demográfico**: Influência de gênero, idade e dependentes no cancelamento

## 💡 Insights Iniciais

- **Contratos Month-to-month** apresentam maior taxa de cancelamento
- Maioria dos cancelamentos ocorre nos **primeiros meses** de serviço
- Serviços como **Suporte Técnico** e **Proteção de Aparelho** estão associados à maior retenção
- **Métodos de pagamento automáticos** mostram menor taxa de cancelamento
- **Tipo de Internet** (Fibra ótica vs DSL) influencia na decisão de cancelamento

## 🖥️ Tecnologias Utilizadas
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-%233776AB.svg?style=for-the-badge&logo=seaborn&logoColor=white)
![Jupyter](https://img.shields.io/badge/jupyter-%23FA6F1E.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
--- 
## 📂 Estrutura do Projeto
- **[📓 Notebook da Análise](https://colab.research.google.com/drive/1UaDE8LNumtN4WRtfGOnMg_8l7RljuL94?usp=sharing)** → contém todo o processo de ETL, análise exploratória e geração de gráficos.
- **`dados/`** → pasta com a base de dados utilizada.
- **`dados/TelecomX_II_dicionario.md`** → Dicionário de dados

---

##  Autor
**Nome:** Weverton Farias  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wevertonfarias/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Wevertonfarias)
