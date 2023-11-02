# **SALES PREDICTION**

## **Project Overview**

The Sales Prediction project leverages data science and machine learning techniques in Python to predict the car purchase amount that customers are likely to spend. The prediction is based on various customer attributes, including age, annual salary, credit card debt, net worth, and other factors. Accurate predictions of car purchase amounts allow businesses to optimize their advertising strategies and maximize their sales potential.

This project is a regression problem, involving predicting a continuous numerical value (the car purchase amount) based on input features.

## **Business Understanding**

In businesses that offer products or services, understanding customer behavior and accurately predicting future sales is crucial. By leveraging data science and machine learning, businesses can make informed decisions regarding advertising costs, target audience segmentation, and advertising platform selection. This project aims to help businesses optimize their advertising strategies and improve their return on investment.

### **Business Problem**

The business problem is to predict the car purchase amount that customers are likely to spend based on their characteristics and attributes. This prediction enables businesses to allocate their advertising budget more effectively and tailor their marketing campaigns to target customers who are more likely to make high-value purchases.

### **Objectives**

The main objectives of this project are as follows:

- Build a machine learning model to predict car purchase amounts based on customer attributes.
- Evaluate the model's performance and accuracy.
- Provide insights to help businesses optimize their advertising strategies and maximize sales potential.

## **Data Understanding**

The dataset used in this project is obtained from Kaggle and contains information about 500 customers. It includes various features such as customer name, customer email, country, gender, age, annual salary, credit card debt, net worth, and car purchase amount. The dataset provides the necessary information to train and evaluate the predictive model.

## **Data Preparation**

The data preparation phase involves several important steps, including checking for missing values, handling duplicates, removing outliers, and encoding categorical data. The steps include:

- Checking for missing values and ensuring data integrity.
- Removing duplicates from the dataset.
- Identifying and handling outliers using Z-score-based methods.
- Dropping unnecessary columns like customer name and customer email.
- Scaling numerical features for consistent model performance.
- Encoding categorical data, such as the country, using one-hot encoding.

## **Exploratory Data Analysis**

The exploratory data analysis (EDA) phase involves gaining insights from the data. Some key findings from EDA include:

- Understanding the distribution of car purchase amounts.
- Analyzing the distribution of customer ages.
- Investigating the relationship between age and car purchase amounts.
- Identifying top countries with high car purchase amounts.
- Analyzing the influence of gender on mean car purchase amounts.
- Investigating the correlation between features through correlation matrices and data distribution plots.

## **Modeling**

The project involves training and evaluating several regression models, including:

1. Linear Regression
2. Ridge Regression
3. Random Forest Regression
4. XGBoost Regression

The models are assessed for their ability to predict car purchase amounts, and the best-performing model is selected for making predictions.

## **Conclusion**

The project's key findings and conclusions are as follows:

- The best-performing model for predicting car purchase amounts is the tuned XGBoost Regression model.
- Insights from exploratory analysis can inform marketing strategies, such as targeting specific age groups and gender-based marketing.
- The model can be deployed to make real-time predictions for new customers.

## **Recommendations**

Based on the project's findings, here are some recommendations:

- Utilize the tuned XGBoost Regression model for accurate predictions of car purchase amounts.
- Design marketing campaigns specifically targeting the age group with the highest purchase activity.
- Consider gender-based marketing strategies with tailored incentives.
- Focus on customer attributes other than credit card debt in marketing campaigns.

## **Next Steps**

To further enhance the project and its impact, consider the following steps:

- Deploy the trained XGBoost Regression model to make real-time predictions for new customers.
- Continuously collect data on customer attributes and car purchase amounts to retrain the model and keep it up to date.
- Explore additional features or external data sources to further enhance prediction accuracy.
- Conduct A/B testing to validate the effectiveness of marketing strategies tailored based on customer insights.

## **AUTHOR**
- Marwa Osman
- marwaosman9975@gmail.com
- [LinkedIn](https://www.linkedin.com/in/marwa-osman-00190b222/)
- [GitHub](https://github.com/marwa9975)

