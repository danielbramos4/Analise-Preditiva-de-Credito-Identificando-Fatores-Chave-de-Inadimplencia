# 📊 Análise Preditiva de Crédito: Identificando Fatores Chave de Inadimplência

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success)

## 📝 Descrição do Projeto
Este projeto de Ciência de Dados tem como objetivo realizar uma Análise Exploratória de Dados (EDA) e desenvolver um modelo de **Machine Learning** para prever a propensão à inadimplência (`default = 1`) de clientes de uma instituição financeira. 

Além da construção do modelo preditivo, o projeto foca em extrair **Business Insights** valiosos para apoiar a tomada de decisão estratégica, como políticas de renegociação de dívidas e retenção de clientes de alta renda.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Python
* **Manipulação e Limpeza de Dados:** Pandas, Numpy
* **Visualização de Dados:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest Classifier)

## ⚙️ Metodologia
O projeto foi estruturado nas seguintes etapas:
1. **Coleta e Compreensão dos Dados:** Leitura da base de clientes e entendimento das variáveis.
2. **Data Wrangling:** Correção de schema, tratamentos de dados faltantes (NA) e uso de funções lambda para transformação de strings em floats.
3. **Análise Exploratória (EDA):** Visualizações categóricas e numéricas para identificar padrões preliminares entre clientes adimplentes e inadimplentes.
4. **Modelagem Preditiva:** Padronização de dados (StandardScaler), One-Hot Encoding para variáveis categóricas e treinamento de um modelo **Random Forest Classifier** com pesos balanceados.
5. **Avaliação e Importância das Variáveis:** Extração matemática dos fatores que mais impactam a decisão de inadimplência.

## 💡 Principais Resultados e Business Insights
A partir da extração de *Feature Importance* do algoritmo, identificamos que a **queda no engajamento financeiro** (quantidade e valor de transações) aliado à **baixa faixa salarial** são os principais precursores do *default*.

Com base nisso, propomos as seguintes ações de negócio:
* **Prevenção de Inadimplência:** Ofertas de parcelamento de fatura com juros reduzidos para clientes com queda abrupta em transações, antes do vencimento.
* **Recuperação de Crédito:** Campanhas de quitação com descontos em multas para clientes inadimplentes com salário inferior a $40K.
* **Retenção de Adimplentes de Alta Renda:** Upgrades gratuitos de cartões (ex: Blue para Gold/Platinum) e cross-selling de produtos financeiros para clientes de alta performance e baixo risco.

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone [https://github.com/danielbramos4/Analise-Preditiva-de-Credito-Identificando-Fatores-Chave-de-Inadimplencia.git](https://github.com/danielbramos4/Analise-Preditiva-de-Credito-Identificando-Fatores-Chave-de-Inadimplencia.git)
