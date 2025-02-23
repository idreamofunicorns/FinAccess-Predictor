# Predicting Bank Account Ownership in East Africa
*Using Machine Learning to Enhance Financial Inclusion
## Project Overview
Financial inclusion is critical for economic development, yet many individuals in East Africa remain unbanked. This project leverages machine learning to predict bank account ownership using demographic and socio-economic data. Insights from this model can help financial institutions, policymakers, and international organizations identify key factors influencing financial inclusion.

## Business Understanding
Financial inclusion promotes economic growth and poverty reduction.
The World Bank recognizes it as a key driver for achieving 7 out of 17 Sustainable Development Goals (SDGs).
This project aims to develop a predictive model to classify individuals as either banked (1) or unbanked (0).

### Business Objective
**Goal**: Predict whether an individual owns a bank account.
**Use Case**: Assist financial institutions and policymakers in targeting the unbanked population.

### Key Business Questions
1.Who does not have a bank account?
2.What factors influence bank account ownership?
3.How can the model best support financial inclusion initiatives?

### Success Criteria
1.Model Accuracy: Ensure high predictive performance.
2.Actionable Insights: Identify key features influencing bank account ownership.
3.Business Impact: Support financial institutions in targeting unbanked individuals.

### Dataset Overview
Total Records: 23,524 individuals from Kenya, Uganda, Tanzania, and Rwanda.
Target Variable: Bank account ownership (1 = Yes, 0 = No).
Features:
Categorical: Country, location type, relationship with head, marital status, education level, job type.
Numerical: Age, household size, year.
Binary: Gender, cellphone access.

### Data Preprocessing
Handled class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).
Feature selection to retain the most relevant predictors.
Applied data cleaning & encoding for categorical variables.

### Modeling Approach
Models Considered: Decision Tree, Random Forest, XGBoost.
Feature Selection: Top 10 features based on importance.
Hyperparameter Tuning: Grid Search applied for optimization.
Resampling Technique: SMOTE used to balance the dataset.

### Model Evaluation Metrics
Accuracy: Overall correctness of predictions.
Precision: How well the model predicts bank account holders.
Recall: Model's ability to identify unbanked individuals.
F1 Score: Balance between precision and recall.

### Results - Model Performance
Metric	Before Tuning	After Tuning
Accuracy	82%	85%
F1 Score (Unbanked - Class 1)	39%	47%
Feature Importance

### Recommendations
Targeted Financial Programs: Prioritize outreach to those without cellphone access and rural populations.
Education Campaigns: Improve financial literacy among individuals with lower education levels.
Alternative Banking Solutions: Promote mobile banking and digital wallets for the unbanked.

## Next Steps
Validate the model with additional real-world data.
Improve performance with ensemble methods.
Collaborate with financial institutions to implement insights.

Contact & Contribution
Full analysis http://localhost:8888/notebooks/OneDrive/Desktop/FinAccess/FinAccess%20Predictor.ipynb
Github link https://github.com/idreamofunicorns/FinAccess-Predictor.git
For questions, feedback, or contributions, feel free to reach out!


