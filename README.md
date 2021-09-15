# Telecom_Churn
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, **customer retention** has now become even more important than customer acquisition.
<br>
To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

#### Business Objective

The business objective is to predict the churn in the last (i.e. the ninth) month using the data (features) from the first three months. To do this task well, understanding the typical customer behaviour during churn will be helpful.


# Steps:
1. Loading data
2. Data Preprocessing:
    - Derive new features  
    - Filter High-Value Customers (HVC)
    - Tag churners and remove attributes of the churn phase
3. Exploratory Data Analysis
    - No variance columns
    - Analye correlated features
4. Mssing value treatment
5. Feature engineering
6. Handle outliers
7. Train and test split
8. Scaling and encoding the features
    - Categorical columns (One hot multiclass encoding)
9. Model Building  <br/> (For evaluation metrics I used 'roc_auc')
    1. Models without PCA <br/>
        - Logistic Regression<br/>
        - Logistic Regression with RFE<br/>
        - Random Forest Classifier<br/>
        - AdaBoost Classifier<br/>
        - SVM<br/>
    2. Models with PCA <br/>
        - Logistic Regression<br/>
        - Random Forest Classifier<br/>
        - SVM<br/>
10. Feature Importance of best models <br/>
11. Recommendations to minimise the churn customers.
