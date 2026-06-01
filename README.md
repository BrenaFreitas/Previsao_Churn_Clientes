# Previsao_Churn_Clientes
### Objetivo
O objetivo é entender o perfil dos clientes que optam pelo cancelamento do plano com a empresa Y. Para isso, realiza-se a Análise Exploratória dos Dados para saber as variáveis relevantes e a correlação entre elas e a variável 'churn'. Ao final, realiza-se o treinamento de modelo para previsão de clientes de 'churn'.

### Descrição do projeto desenvolvido

- Tema : Previsão de churn em serviços de assinatura

- Modelos : Random Forest e XGBoost

- Avaliação : F1-Score, Matriz de confusão , curva ROC-AUC


### Variáveis

- Colunas : customerId, gender, SeniorCitizen, Partner,Depends,tenure, PhoneService, MultiplLines,InternetServive,OnlineSecurity,DeviceProtection , TechSupport, StreamingTV,StreamingMovies,
Contract,PaperlessBilling,PaymentMethod. MonthlyCharges,TotalCharges
- Alvo :  Churn

### Tecnologias utilizadas 

- Python
- Pandas (manipulação de dados)
- NumPy (operações numéricas)
- Scikit-learn (avaliação de modelo, normalização)
- Matplotlib & Seaborn (visualização)

### Resultados
O projeto foi avaliado a partir da perspectiva de dois modelos comuns para Classificação de dados.

Random Forest com utilização do RandomForestClassifier para ajuste de hiperparâmetros:
- Accuracy: 80%
- F1-Score: 85%
- ROC Curve indica um bom desempenho do modelo para classificação de churn entre clientes.

XGBoost com utilização do XGBClassifier para ajuste de hiperparâmetros:
- Accuracy: 78%
- F1-Score: 86%
- ROC Curve indica um bom desempenho do modelo para classificação de churn entre clientes.
