# Customer retention rate and RFM segmentaion analysis

![image](https://github.com/DooPhiLong/Customer-retention-rate-and-RFM-segmentaion-analysis/assets/120476961/f21ce8e5-74e2-46c3-8c41-515d3973eeb2) ![image](https://github.com/DooPhiLong/Customer-retention-rate-and-RFM-segmentaion-analysis/assets/120476961/af2efb72-1c21-480a-b30a-915149a2d779)


## 💼 Case study
- Based on a data set about the behaviors, characteristics, and services that customers have used of a telecommunications services sector and internet service providers. Build machine learning algorithm models to predict customer churn rates.
- From there, the service provider can determine which customers are most likely to stay in the store for the longest time to be able to offer them loyalty policies. But the main purpose is to be able to determine which customers are most likely to leave in the near future so that the service provider can offer policies to advise on needs, make modifications and take care of customers, increase communication and information sharing to retain them. The ultimate goal is to help service providers retain as many customers as possible
## 🔆 Target output
- **Customer churn prediction**: With the customer churn prediction model, service providers can pre-identify customers with a tendency to churn. This helps focus on maintaining and improving customer satisfaction and implementing more effective customer retention measures.

- **Customer retention strategies**:: Based on predicted results, service providers can build customer retention strategies to increase customer engagement and engagement. These strategies may include promotions, personalized consulting services, or improving the service experience to create customer satisfaction and loyalty.

- **Optimize marketing campaigns**:: Understanding the factors that influence customer churn, service providers can optimize marketing and advertising campaigns. By focusing on customers at higher risk of churn, service providers can promote personalized marketing campaigns, increase engagement, and create value for customer retention.

- **Enhance business performance**:: By reducing customer churn, service providers can maintain and expand their existing customer base. This helps increase revenue and profits, while reducing costs associated with finding, attracting and maintaining new customers.
## 📁 Data set
### I only have 1 data table 7043 rows and 21 features about customer behavioral information, below are 5 rows of sample data :

![image](https://github.com/DooPhiLong/Customer-Churn-Rate-Prediction/assets/120476961/a368b568-dca1-4484-81e9-69d9156e1eb8)

![image](https://github.com/DooPhiLong/Customer-Churn-Rate-Prediction/assets/120476961/f0016c47-62d0-498b-81d9-e16aa7b07859)

### Detail features
- **CustomerID**:: Customer ID, uniquely representing each customer in the data set.
- **Gender**: The customer's gender, can be "Male" (Male) or "Female" (Female).
- **SeniorCitizen**: Senior citizen status, value 0 or 1. 0 represents not a senior citizen, 1 represents a senior citizen.
- **Partner**: Marital or cohabitation status, with value "Yes" or "No". "Yes" corresponds to married or living together, "No" corresponds to not married or living together.
- **Dependents**: The state of having dependents, with value "Yes" or "No". "Yes" corresponds to having dependents, "No" corresponds to having no dependents.
- **Tenure**: Time (number of months) the customer has used the retail store's services.
- **PhoneService**: Phone service usage status, with value "Yes" or "No". "Yes" corresponds to using phone service, "No" corresponds to not using phone service.
- **MultipleLines**: Status of using multiple phone services, with values "Yes", "No" or "No phone service". "Yes" corresponds to using many phone services, "No" corresponds to not using many phone services, "No phone service" corresponds to no phone service.
- **InternetService**: Type of Internet service used, with value "DSL" (Digital Subscriber Line), "Fiber optic" (Optic fiber optic) or "No" (Do not use Internet service).
- **OnlineSecurity**: Status of using online security services, with value "Yes", "No" or "No internet service". "Yes" corresponds to using online security services, "No" corresponds to not using - Online security services, "No internet service" corresponds to no Internet service.
- **OnlineBackup**: Status of using online backup service, with value "Yes", "No" or "No internet service". "Yes" corresponds to using online backup service, "No" corresponds to not using online - Backup service, "No internet service" corresponds to no Internet service.
- **DeviceProtection**: Device protection service usage status, with value "Yes", "No" or "No internet service". "Yes" corresponds to using device protection service, "No" corresponds to not using device protection service, "No internet service" corresponds to no Internet service.
- **TechSupport**: Status of using technical support service, with value "Yes", "No" or "No internet service". "Yes" corresponds to using technical support service, "No" corresponds to not using - Technical support service, "No internet service" corresponds to no Internet service.
- **StreamingTV**: Status of using online TV viewing service, with value "Yes", "No" or "No internet service". "Yes" corresponds to using online TV viewing service, "No" corresponds to not using - Online TV viewing service, "No internet service" corresponds to not having Internet service.
- **StreamingMovies**: Status of using online movie watching service, with value "Yes", "No" or "No internet service". "Yes" corresponds to using online movie watching service, "No" corresponds to not using online movie watching service, "No internet service" corresponds to not having Internet service.
- **Contract**: Contract type, valid "Month-to-month", "One year" or "Two year".
- **PaperlessBilling**: Status of using electronic invoices, with value "Yes" or "No". "Yes" corresponds to using electronic invoices, "No" corresponds to not using electronic invoices.
- **PaymentMethod**: Payment method, including "Electronic check", "Mailed check", "Bank transfer (automatic)" and "Credit card (automatic)" (automatic credit card).
- **MonthlyCharges**: The customer's monthly payment amount.
- **TotalCharges**: Total amount of the customer's payment.
- **Return**: Customer status, with value "Yes" or "No". "Yes" corresponds to customers who have left the store, "No" corresponds to customers who have not left.
## 🔎 Analysis
[Click here and wait a few seconds](https://github.com/DooPhiLong/Customer-Churn-Rate-Prediction/blob/main/Project%20Customer%20churn%20classification.ipynb)
## Methods apply
- Data cleanning
- Data Preproccessing
- Data Mining
- Data modeling (K-NN, Logistic regression, Random forrest, Perceptron, Naive Bayes, Decision tree, Neraul network)
     

