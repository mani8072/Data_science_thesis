**Predictive Maintenance using Machine Learning and Explainable AI (XAI)**

**📘 Project Overview**

This project focuses on developing an end-to-end predictive maintenance framework for industrial equipment within the context of Industry 4.0. 
The main goal is to predict potential equipment failures before they occur, thereby reducing downtime, improving productivity, and optimizing maintenance strategies.

By leveraging Machine Learning (ML) models and Explainable Artificial Intelligence (XAI) methods, this project bridges the gap between data science and industrial operations, 
providing both accurate predictions and interpretable insights to support data-driven decision-making.

**⚙️ Methodology**

**Data Collection & Preprocessing**

Utilized a synthetic dataset representing the operation of a milling machine.

Features included: torque, rotational speed, tool wear, temperature, and mechanical force measurements.

Data was cleaned, normalized, and prepared for model training and evaluation.

**Model Development**

Two ML models were implemented and compared:

Random Forest Classifier

Logistic Regression

Models were evaluated using metrics such as Accuracy, Precision, Recall, and F1-Score.

A Gradient Boosting Regressor was also used for continuous condition prediction.

**Explainability (XAI) Integration**

Applied SHAP (SHapley Additive exPlanations) to interpret model outputs.

Global and local SHAP plots were generated to visualize feature importance and explain model predictions.

Identified that peripheral workpiece force and horizontal spindle force are key predictors of failure.

**Model Evaluation Results
**
Random Forest: 94.6% accuracy, 93.8% precision, 92.5% recall, 93.1% F1-score.

Logistic Regression: 88.3% accuracy.

Gradient Boosting Regressor: R² = 0.92, RMSE = 0.18, MAE = 0.12.


**🧰 Tools & Technologies**

Programming Language: Python

Libraries & Frameworks:

pandas, numpy, scikit-learn, matplotlib, seaborn, shap

Modeling Techniques:

Random Forest, Logistic Regression, Gradient Boosting

Visualization:

Power BI, SHAP plots, Matplotlib

Version Control: GitHub

Environment: Jupyter Notebook / Google Colab


**🧩 Results Summary**

Random Forest achieved superior predictive performance compared to Logistic Regression.

XAI techniques (SHAP) provided clear interpretability, identifying critical operational parameters affecting failure.

Demonstrated how AI-driven maintenance can enhance industrial reliability, transparency, and efficiency.

**🧑‍💻 Author**

Manikandan Dhandayuthabani
Master’s in Data Science, University of Europe for Applied Sciences
📍 Based in Germany
📫 manikandand4466@gmail.com
