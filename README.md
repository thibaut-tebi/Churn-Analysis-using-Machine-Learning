# Churn Prediction Project

This project aims to predict customer churn using machine learning techniques. The goal is to develop models that can accurately identify customers who are likely to cancel their subscriptions, allowing businesses to implement targeted retention strategies.

| Project Name   | Description                                                                                                                           | Technologies Used                                       | Published Article                                         |
|----------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|-----------------------------------------------------------|
| Churn Analysis | Analyzing customer churn in a telecom company to identify factors influencing customer attrition and develop predictive models. | Python, scikit-learn, pandas, matplotlib, Jupyter Notebook | [Link to Published Article](https://mavenanalytics.io/project/6839) |



#### Data Description

The dataset used for this analysis consists of customer information, including various features. The target variable is the churn status, indicating whether a customer has churned or not.

#### Project Structure

1. Data Preprocessing: The dataset is cleaned and preprocessed to handle missing values, duplicates, and format the data appropriately for machine learning algorithms.

2. Exploratory Data Analysis (EDA): EDA is performed to gain insights into the data, identify patterns, and understand the factors that contribute to churn.

3. Model Training: Different machine learning algorithms, including logistic regression, decision trees, random forests, and gradient boosting, are trained on the preprocessed data.

4. Model Evaluation: The trained models are evaluated using performance metrics such as accuracy, precision, recall, and F1-score. The goal is to select the best-performing model for churn prediction.

#### Results and Insights

Through the analysis, several key insights were obtained, including:

The amount spent per month has a significant impact on churn likelihood.
Customer tenure is an important predictor, with longer-tenured customers showing lower churn rates.
The availability of technical support influences customer retention.
Contract type, such as month-to-month or yearly contracts, is strongly correlated with churn.

#### Model Interpretation

To gain a deeper understanding of the predictions made by the best-performing model, Local Interpretable Model-agnostic Explanations (LIME) technique was used. This provided interpretable explanations for the model's decision-making process.

#### Future Enhancements

Potential areas for future improvement include:

Incorporating more advanced modeling techniques and exploring additional features or external data sources to improve prediction accuracy.
Also Developing real-time churn prediction models to enable proactive customer retention strategies.

#### Dependencies and Instructions

This project requires Python along with the following libraries: pandas, scikit-learn, matplotlib, and lime. To reproduce the analysis, run the provided code and follow the instructions mentioned in the code comments.


#### Author Information

This churn prediction project was developed by Thibaut Kwadzo Tebi . For any questions or inquiries, please contact thibauttebi@azubiafrica.org.

Feel free to contribute, provide feedback, or explore further improvements to enhance the churn prediction models and their applications.




