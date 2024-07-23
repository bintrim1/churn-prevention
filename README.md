# Churn Prevention
Final Project at TripleTen. Using a dataset of customer contracts and service agreements from a telecom, this project aims to identify early churn risk in customers, and provides the top features contributing to churn for further action.

## Problem Solved:
This project aims to solve the problem of customers churning at the surprise to the business. The model created successfully classifies customers as likely to churn, based on a large number of features gathered by the company.\
At the end, the top factors contributing to churn were provided, for further action by the company.

## Skills demonstrated:
In this project, I used the following skills:
* Exploratory Data Analysis
* SKLearn Logistic Regression
* SKLearn Random Forest
* SKLearn GridSearchCV for hyperparameter tuning and cross-validation
* LightGBM for a gradient boosting model
* CatBoost for another gradient boosting model

## Project Description

The telecom operator Interconnect aims to forecast client churn. By predicting which users are planning to leave, the company can offer promotional codes and special plan options to retain them. Interconnect's marketing team has collected various personal data from their clientele, including information about their plans and contracts.

### Interconnect's Services

Interconnect primarily provides two types of services:
1. **Landline Communication**: The telephone can be connected to several lines simultaneously.
2. **Internet**: The network can be set up via a telephone line (DSL) or through a fiber optic cable.

Additional services offered by the company include:
* **Internet Security**: Antivirus software (DeviceProtection) and a malicious website blocker (OnlineSecurity)
* **Technical Support**: A dedicated technical support line (TechSupport)
* **Cloud Services**: Cloud file storage and data backup (OnlineBackup)
* **Streaming Services**: TV streaming (StreamingTV) and a movie directory (StreamingMovies)

Clients can choose either a monthly payment or sign a 1- or 2-year contract. Various payment methods are available, and clients receive an electronic invoice after a transaction.

## Dataset Information

The dataset contains the following features:
- CustomerID
- Gender
- SeniorCitizen
- Partner
- Dependents
- Tenure
- PhoneService
- MultipleLines
- InternetService
- OnlineSecurity
- OnlineBackup
- DeviceProtection
- TechSupport
- StreamingTV
- StreamingMovies
- Contract
- PaperlessBilling
- PaymentMethod
- MonthlyCharges
- TotalCharges
- Churn

## Project Steps

1. **Data Exploration and Preprocessing**
    - Load and explore the dataset
    - Clean data
    - Encode categorical variables
2. **Exploratory Data Analysis (EDA)**
    - Visualize the distribution of various features
    - Analyze correlations between features
    - Perform feature engineering
3. **Model Building**
    - Split the data into training and testing sets
    - Train various machine learning models
    - Evaluate model performance
4. **Model Evaluation and Selection**
    - Compare model performance using the AUC-ROC metric
    - Select the best-performing model
5. **Deployment**
    - Save the model for future predictions

## Results

The final model achieved the following performance metric:
* AUC-ROC: **0.93**

The top 5 features that contributed most to churn are:
