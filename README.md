# Payment-Patterns-Brazil
To analyze the trends and patterns in using various payment methods in Brazil, and to understand their impact on the financial ecosystem. The key questions to be answered include:

1. How has the adoption of different payment methods evolved?
2. What are the most and least popular payment methods?
3. How do the total values of transactions compare across different payment methods?
4. Are there seasonal or monthly trends in using these payment methods?

From the data fetching process to the construction of the Data Lake, each step of this project was documented inside the .ipynb (Google Colab) file.

## Data Collection and Ingestion
### 1. Data Source: 
  - Clovis Vieira Kaggle [Database project](https://www.kaggle.com/datasets/clovisdalmolinvieira/brazilian-payment-methods).
#### 2. Data Ingestion: 
Used Databricks to create a pipeline to ingest data.
  - Utilized Databricks Community Edition for development.
  - Leveraged Spark for data ingestion and processing.
  
## Data Set Story:
The dataset was downloaded from Kaggle, an online platform for data scientists, machine learning enthusiasts, and related professionals. Its use is strictly didactic. For more information about the dataset, see the following link: [Brazilian Payment Methods](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers/data) and uploaded into a cloud environment Databricks.

- It consists of 101 observations and 13 variables.
- Independent variables contain information about payment methods.
- The dataset was uploaded into [Google Cloud Storage](https://cloud.google.com/?hl=pt-BR).


### Features:

- YearMonth: The reference month in YYYYMM format.
- quantityPix: Number of PIX transactions.
- valuePix: Total value of PIX transactions.
- quantityTED: The number of TED transactions.
- valueTED: The total value of TED transactions.
- quantityTEC: The number of TEC transactions.
- valueTEC: The total value of TEC transactions.
- quantityBankCheck: The number of check transactions.
- valueBankCheck: The total value of check transactions.
- quantityBrazilianBoletoPayment: Number of billing by transactions.
- valueBrazilianBoletoPayment: The total value of billing by transactions.
- quantityDOC: The number of DOC transactions.
- valueDOC: The total value of DOC transactions.

## Pre-requirements

Before running PaymentPatternsBrazil, make sure you have the following requirements:

- Python 3.9 or higher
  

## Run Environment

Everything was developed into a Google Colab Notebook for the project's current version. However, a local version (.py) will be deployed sooner.
