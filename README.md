## MultipleLinearRegression_50_startups_prj3

## Prediction with Multiple Regression

### Objective
The project aims to predict the profit of a startup based on various factors like R&D spend, marketing spend, administration spend, and state.

### Solution
The model was built using multiple linear regression, and EDA was performed on the 50_Startups and toyota_corolla datasets to understand the relationships between variables.
1. **Data Preprocessing and EDA**: We cleaned the dataset, encoded categorical variables, and scaled the numerical features. Detailed EDA was performed using Seaborn to visualize relationships and correlations between features and `Profit`.

2. **Modeling and Results**: We trained a Multiple Linear Regression model and evaluated it using R² to assess its predictive performance. Polynomial Regression was also tested, and the best model was selected based on the highest R² value.

### Business Impact
This model can help businesses predict their profits based on spending in different departments, enabling them to make informed decisions on budgeting.

### Tools Used
- Python
- Pandas
- Seaborn
- Scikit-learn

### Insights
- The state variable showed a significant impact on profits after encoding.
- Marketing spend and R&D spend were found to be the most influential predictors of profit.

### Keywords
- Multiple Linear Regression
- Profit Prediction
- 50_Startups Dataset
- Data Analysis
- Polynomial Regression
- Model Comparison
- R² Evaluation
