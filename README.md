## Bank Churners Machine Learning Analysis
#### This project applies machine learning model to predict if a bank customer will stay or leave the credit card service. 
#### This project explores the use of machine learning models to predict customer churn in banking. By identifying at-risk customers, the analysis aims to help banks improve profitability, maintain customer relationships, and gain valuable insights for personalized service development.

### Purpose
Customers are the cornerstone of every industry, and in banking, they are at the heart of customer-dependent organizations. Long-term customers are directly tied to revenue generation, making it essential for banks to retain them. According to the Harvard Business Review, reducing customer churn by just 5% can result in a 25% to 85% increase in profits. Customers are the most important assets on profit of a bank. 

Customer churn, the process of losing customers to competitors, poses a fundamental challenge to banks, leading to revenue loss. Managing churn requires identifying customers who are likely to switch to other banks. As Risselada et al. (2010) demonstrated, effective churn management is crucial for building long-term relationships that maximize the value of the customer base.

Predicting customer churn using big data has become a focal point in machine learning research. Various models, including logistic regression, k-nearest neighbors, random forests, decision tree, gradient boost, and ada boost, have been employed to classify customers as churners or non-churners. The reasons for predicting churn are clear:

1. Profitability Improvement:   
   Retaining customers ensures continued revenue generation.

2. Customer Relationship Maintenance:   
   Preventing churn helps sustain long-term relationships, fostering loyalty and opening opportunities to offer additional financial products and services.

3. Data and Insight Accumulation:   
   Retaining high-risk customers allows for the accumulation of valuable data, providing critical insights for future risk management and the development of personalized services.
This report will explore the application of machine learning techniques in predicting customer churn, highlighting its importance in modern banking.

### Conclusion

Gradient Boosting has the highest balanced accuracy (0.969) and F1-score (0.982), making it the best-performing model in this study.

The ROC curve measures the performance of classification models. AUC (Area Under the Curve) = 0.93 means that the model is 93% effective at distinguishing between churners and non-churners. The closer AUC is to 1, the better the model performs.

![download](https://github.com/user-attachments/assets/e8fe388a-1033-4c05-bf6d-53ec5507cd8b)



### Next Action

For future research, I would recommend exploring hyperparameter tuning to further optimize the performance of the models. Techniques like Grid Search or Random Search can help identify the best combination of parameters to enhance model accuracy. Additionally, incorporating more advanced models such as XGBoost or CatBoost could potentially improve predictive power. It would also be valuable to perform a feature importance analysis to better understand which customer attributes contribute most to churn, leading to actionable insights for retention strategies.

### References
https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers

Risselada, H.; Verhoef, P.C.; Bijmolt, T.H. Staying power of churn prediction models. J. Interact. Mark. 2010, 24, 198–208.


