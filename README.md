# Predict_model_employee_turnover_rate_Salifort_Motors_Project
Salifort Motors, a fiction company, has a high rate of turnover. Analyze the key factors driving employee turnover, build an effective model, and share recommendations.

The focusing feature: that predicts whether an employee will leave the company.
The factors: their job title, department, number of projects, average monthly hours, and any other relevant data points.

Through the PACE strategy, the final champion model will help the company increase retention and job satisfaction for current employees, and save money and time training new employees. 

Workflow:
1. Data Preprocessing
2. Model Training & Evaluation
3. Feature Importance Analysis
4. Execute Recommendation

Why Random Forest, XGBoost > Logistic Regression > decision tree:
Employee data usually includes mixed types (e.g., department = categorical, monthly hours = numerical). Random Forest can handle this naturally.
Built-in feature importance scores, helping us highlight the most influential variables.
Works well with non-linear relationships.

Now let's get started

![{675D19D6-479E-4652-801F-8B4F1EE6182F}](https://github.com/user-attachments/assets/86b0b3f9-9f71-40d1-a3bf-979ccab1fb69)

Summary of model results
Logistic Regression
The logistic regression model achieved precision of 80%, recall of 83%, f1-score of 80% (all weighted averages), and accuracy of 83%, on the test set.

Tree-based Machine Learning
After conducting feature engineering, the decision tree model achieved AUC of 93.8%, precision of 87.0%, recall of 90.4%, f1-score of 88.7%, and accuracy of 96.2%, on the test set. The random forest modestly outperformed the decision tree model.

![image](https://github.com/user-attachments/assets/26cb5348-17a4-4342-a582-b9aedc37b215)
![image](https://github.com/user-attachments/assets/01889e28-cc0a-4f23-95b9-3c6041a9658d)


- Cap the number of projects that employees can work on.
- Consider promoting employees who have been with the company for at least four years, or conduct further investigation about why four-year tenured employees are so dissatisfied.
- Either reward employees for working longer hours, or don't require them to do so.
- If employees aren't familiar with the company's overtime pay policies, inform them about this. If the expectations around workload and time off aren't explicit, make them clear.
- Hold company-wide and within-team discussions to understand and address the company work culture, across the board and in specific contexts.
- High evaluation scores should not be reserved for employees who work 200+ hours per month. Consider a proportionate scale for rewarding employees who contribute more/put in more effort.
