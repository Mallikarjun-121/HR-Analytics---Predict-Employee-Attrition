HR-Analytics---Predict-Employee-Attrition
A comprehensive HR Analytics project to explore, model, and visualize employee attrition patterns using Python, SHAP, and Power BI.

📁 Repository Structure
data/ – HR dataset (CSV)

notebooks/ – Jupyter/Colab notebooks for EDA and modeling

visuals/ – Power BI dashboards and plots

reports/ – Final PDF reports and findings

shap_analysis/ – SHAP plots for interpretability

README.md – Project documentation

🧰 Tools & Technologies
Python: Pandas, Seaborn, Matplotlib, Scikit-learn

SHAP: Model interpretability & explainability

Power BI: Dashboard and stakeholder-facing visualizations

Google Colab: Analysis and model development

📊 Exploratory Data Analysis (EDA)
Key insights uncovered:

High attrition in Sales and R&D departments

Younger employees (age 25–35) and low salary bands showed higher attrition

Employees with frequent OverTime and BusinessTravel were more likely to resign

Attrition rate is highest among employees with 0–3 years at the company

Visuals used:

Correlation matrix

Boxplots

Bar charts for trend identification

🤖 Machine Learning Models
Two classification models were trained:

Logistic Regression (Baseline)

Decision Tree Classifier (max_depth=5)

Metric	Logistic Regression	Decision Tree
Accuracy	~87%	~84%
ROC AUC Score	~0.80	~0.66

🔍 SHAP Explainability
SHAP (SHapley Additive exPlanations) was used to explain feature contributions.

Top influencing features:

OverTime

MonthlyIncome

JobRole

Age

YearsAtCompany

📈 Power BI Dashboard
Includes bar chart visuals for:

Attrition by Department, Job Role, Age Group, Education, Gender

Salary Ranges, Business Travel, OverTime

Interactive Slicers:

Department

Gender

✅ Key Recommendations
Improve compensation in low-paying roles

Reduce overtime hours and travel frequency

Provide career growth programs for early-tenure employees

Monitor high-risk job roles such as Sales Executives

Conduct regular pulse surveys and exit interviews
