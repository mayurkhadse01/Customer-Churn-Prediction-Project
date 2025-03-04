# Customer-Churn-Prediction
Customer attrition or churn, is when customers stop doing business with a company. It can have a significant impact on a company's revenue and it's crucial for businesses to find out the reasons why customers are leaving and take steps to reduce the number of customers leaving. One way to do this is by identifying customer segments that are at risk of leaving, and implementing retention strategies to keep them. Also, by using data and machine learning techniques, companies can predict which customers are likely to leave in the future and take actions to keep them before they decide to leave.
We are going to build a basic model for predicting customer churn using **Telco Customer Churn dataset** . We are using some classification algorithm to model customers who have left, using Python tools such as pandas for data manipulation and matplotlib for visualizations.

## Steps Involved to Predict Customer Churn
- Importing Libraries
- Loading Dataset
- Exploratory Data Analysis
- Outliers using IQR method
- Cleaning and Transforming Data
    - One-hot Encoding
    - Rearranging Columns
    - Feature Scaling
    - Feature Selection
- Prediction using Logistic Regression
- Prediction using Support Vector Classifier
- Prediction using Decision Tree Classifier
- Prediction using KNN Classifier
- 
**What is Customer Churning?**
![Image Alt](https://github.com/mayurkhadse01/Customer-Churn-Prediction-Using-Artificial-Neural-Network-ANN-/blob/41972cda548940e2206972a0a0bd76437cebcb50/Telco1.JPG)

  **What are the different Churn Scenarios?**
  ![Image Alt](https://github.com/mayurkhadse01/Customer-Churn-Prediction-Using-Artificial-Neural-Network-ANN-/blob/9382144834023d3872ad22c6b4b0f210340b70d4/Telco2.JPG)

  **Decision Cycle of a Subscriber?**
  ![Image Alt](https://github.com/mayurkhadse01/Customer-Churn-Prediction-Using-Artificial-Neural-Network-ANN-/blob/5dc013d557344eb8ad8255d74d0d0277c2d8c911/Telco3.JPG)


**Conclusion**

The customer churn prediction project successfully implemented multiple classification models, achieving accuracy between **72%-80%**. The models performed well in identifying non-churners but struggled with churn prediction due to class imbalance. Future improvements, such as advanced boosting techniques and hyperparameter tuning, can enhance performance. Addressing class imbalance using oversampling techniques like SMOTE can further improve churn detection.
