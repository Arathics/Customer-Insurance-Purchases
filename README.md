 **Social Network Ads Purchase Prediction**
 
This project analyzes a dataset of social network users to predict whether a user will purchase a product based on their Age and Estimated Salary using various supervised machine learning models.

**Dataset**
File: Social_Network_Ads.csv

Features Used:

Age

EstimatedSalary

Target: Purchased (0 = No, 1 = Yes)

**Objective**
To build and evaluate different classification models to accurately predict user purchase behavior on a social networking platform using supervised machine learning algorithms.

**Data Preprocessing**
Removed irrelevant columns like User ID

Applied LabelEncoder to Gender

Feature Scaling using StandardScaler

Train-test split with 75% training and 25% testing data

**Models Used & Performance**
Model	Accuracy	Precision (0/1)	Recall (0/1)	F1-Score (0/1)
Logistic Regression	0.89	0.89 / 0.89	0.96 / 0.75	0.92 / 0.81
K-Nearest Neighbors	0.93	0.96 / 0.88	0.94 / 0.91	0.95 / 0.89
Support Vector Machine	0.93	0.96 / 0.88	0.94 / 0.91	0.95 / 0.89
Decision Tree	0.91	0.95 / 0.83	0.91 / 0.91	0.93 / 0.87
Random Forest	0.92	0.94 / 0.88	0.94 / 0.88	0.94 / 0.88

**Visualization**
bar chart

**Libraries Used**
pandas, numpy

matplotlib, seaborn

scikit-learn

**Observations**
KNN, SVM, and Random Forest performed best with ~93% accuracy

Logistic Regression had a slightly lower recall on class 1 (buyers), making it less ideal in a business-critical use case

Decision Trees are interpretable but prone to slight overfitting

**Future Enhancements (Optional)**
These are not mandatory, but will make your project more impressive:

**Area	Suggestion**
- Cross-Validation	Add K-Fold CV for better generalization
- Visualization	Add confusion matrix heatmaps, ROC-AUC curves
- Neural Network	Try a simple MLP using Keras
- Deployment	Deploy as a Streamlit or Flask web app for live predictions
- AUC-ROC Score	Include ROC-AUC metrics for deeper evaluation of models

**Author**
Arathi Pradeep
B.Tech CSE
Intern Project - Supervised Machine Learning using Python
2025
