## **CUSTOMER CHURN PREDICTOR FOR SYRIALTEL**
SyriaTel, a major telecom provider, is facing customer retention challenges. Losing customers (“churn”) is expensive, especially in highly saturated telecom markets. The goal of this project is to build a machine learning classifier that can accurately predict whether a customer is likely to stop using SyriaTel’s services soon, based on behavioral and demographic data.

Understanding churn allows the business to take proactive steps—such as offering discounts, personalized services, or re-engagement campaigns—to reduce the churn rate, boost customer lifetime value (CLV), and maintain market share

✅ Business question:
Can we use historical customer data to identify patterns that predict whether a customer is likely to churn?

✅ Machine Learning task:
Binary classification (Churn = Yes/No)

#### Project Objectives

•Identify the key drivers and patterns that contribute to customer churn

•Predict churn with a classification model .

•Provide actionable business insights and interventions.

•Reduce customer attrition and increase revenue stability.

#### Key Metrics for Evaluation

•Accuracy: General performance-How often was the model right?i.e Correct predictions/Total Predictions.

•Precision: Important if the cost of wrongly classifying a non-churner as churner is high, i.e of all customers we said will churn, how many actually did? Precision = True Positives/(True Positives + False Positives)

•Recall (Sensitivity): Crucial—SyriaTel would rather catch all potential churners, even with some false alarms.

•F1 Score: Balanced metric.

•ROC-AUC: Useful for understanding model performance at various thresholds. i.e How well does the model rank churn risk?

### Data Source
Syriatel Customer Chern(https://github.com/learn-co-curriculum/dsc-phase-3-choosing-a-dataset?tab=readme-ov-file#1-syriatel-customer-churn) The dataset contains records of  telecommunications customers, capturing details about their usage behavior, account features, and customer service interactions. 

###  Methodology: CRISP-DM

This project follows the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** framework, a proven approach for structuring data science projects. The process includes:

- **Business Understanding**: Defined the problem of customer churn and its business impact.
- **Data Understanding**: Explored historical customer data to uncover patterns and anomalies.
- **Data Preparation**: Cleaned, transformed, and encoded features for model readiness.
- **Modeling**: Built and tuned classification models (e.g., Gradient Boosting) to predict churn.
- **Evaluation**: Assessed model performance using metrics like ROC-AUC, precision, recall, and F1-score.
- **Deployment Planning**: Derived actionable business insights and proposed retention strategies based on model outputs.

This structured approach ensured both technical rigor and business relevance.

# Key Visualizations
Below are the critical visualizations that helped provide insights 
Customer Churn Distribution![Churn Distribution](../images/Customer_Churn_Distribution.png)
Numerical Features boxplots-![Boxplot of Numerical Features](Images/boxplot_numerical_columns.png)

Correlation Heatmap

This heatmap highlights linear relationships between features. Strong positive or negative correlations can inform feature selection and multicollinearity issues.

![Correlation Heatmap](Images/correlation_heatmap.png)
### Model Performance Comparison ![Model Performance Comparison](Images/model_performance_comparison.png)

#  Conclusion

This project used a Gradient Boosting model to uncover key churn drivers among SyriaTel customers. High total day minutes, frequent customer service calls, and unusual voicemail usage emerged as top predictors. By targeting these indicators with tailored retention strategies—such as proactive support, billing interventions, and usage-based plan adjustments—SyriaTel can reduce churn, improve customer satisfaction, and safeguard revenue.

