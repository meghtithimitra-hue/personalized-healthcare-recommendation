# personalized-healthcare-recommendation
Machine learning project to predict donor return and generate personalized healthcare-style recommendations using classification models.
End-to-end machine learning project that predicts whether a person is likely to donate blood again and turns those predictions into personalized, actionable recommendations. Demonstrates data analysis, model comparison, evaluation on imbalanced data, and decision-focused model selection.

### What I Did:

Performed EDA and correlation analysis on donor behavior data

Handled class imbalance and evaluated models with proper metrics (Precision, Recall, F1, ROC–AUC)

Trained and compared:

Logistic Regression (baseline)

Random Forest (ensemble)

Gradient Boosting (improved model)

Selected Random Forest based on higher recall for the minority class (business/decision priority)

Analyzed feature importance for interpretability

Built a recommendation logic layer:

Likely to return → proactive reminders & engagement

Unlikely to return → awareness & long-term engagement

### Data:

Dataset: blood.csv (748 rows, 5 features)

Features: Recency, Frequency, Monetary, Time

Target: Class (1 = donated again, 0 = did not)

Note: Imbalanced target (~24% positive class)

### Key Results:

Logistic Regression: good accuracy, poor recall for returning donors

Random Forest: better balance between precision & recall for minority class

Gradient Boosting: improved overall discrimination (ROC–AUC)

Final choice: Random Forest (better for catching potential returning donors)

Most important features: Recency, Frequency, Monetary

### Tools:

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter/Colab

### How to Run:

Keep blood.csv in the same folder as the notebook/script

Open the notebook in Jupyter or Google Colab

Run all cells to reproduce the results

### Why This Matters:

Shows practical skills in:

Data analysis & visualization

Model evaluation on imbalanced classification problems

Comparing models and choosing based on business goals (not just accuracy)
Turning ML predictions into real-world decisions

sonalized Healthcare Recommendations.pdf – Detailed report (optional)
