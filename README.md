# An Interpretable Machine Learning Approach to Predict Student Dropout

Project Overview:
Student dropout is a major challenge in higher education, impacting academic outcomes and institutional planning. This project builds a machine learning–based classification system to predict whether a student is likely to drop out, remain enrolled, or graduate, using historical academic and enrollment data.
The project goes beyond prediction accuracy by integrating explainable AI techniques (SHAP and LIME) to interpret model decisions, making the results actionable and trustworthy for academic stakeholders.

Dataset:
Name: Students Dropout and Academic Success
Source: Kaggle
Time Span: Academic years 2008/2009 – 2018/2019
Description:
The dataset contains anonymized student records including: Demographic attributes
                                                           Enrollment and admission details
                                                           Financial information (e.g., tuition payment status)
                                                           Academic performance indicators from multiple semesters

Objective:
To develop a machine learning model that:
Predicts student dropout risk with high reliability
Identifies the most influential factors affecting dropout
Provides clear, interpretable explanations for each prediction

Methodology:
1. Data Preprocessing- Data cleaning and transformation
                       Encoding categorical features
                       Feature selection and normalization
2.Exploratory Data Analysis- Analysis of dropout, enrollment, and graduation patterns
                             Visualization of academic and financial trends
3.Model Training- Multiple classification models evaluated
                  Emphasis on tree-based and ensemble methods
                  Performance assessed using accuracy and ROC-AUC
4.Model Explainability- SHAP used for global and local feature importance analysis
                        SHAP summary, dependence, and waterfall plots
                        LIME applied for instance-level prediction explanations

Key Findings:
Explainability analysis revealed that student dropout risk is strongly influenced by: Age at enrollment
                                                                                      Course and academic program type
                                                                                      Tuition fee payment status
                                                                                      First- and second-semester academic performance
                                                                                      Application and admission mode
Ensemble-based classifiers demonstrated strong predictive performance, while SHAP and LIME confirmed that predictions were driven by meaningful academic and financial features.

Tech Stack:
Programming Language: Python
Data Processing: Pandas, NumPy
Visualization: Matplotlib, Plotly
Machine Learning: Scikit-learn, XGBoost, CatBoost
Explainability: SHAP, LIME

Repository Contents:
Jupyter Notebook(s) containing:
Data preprocessing and EDA
Model training and evaluation
SHAP and LIME explainability analysis
Dataset file (students_dropout_academic_success.csv)

Use Case:
This project can assist educational institutions in:
Early identification of at-risk students
Designing targeted intervention strategies
Supporting data-driven academic decision-making with transparent explanations
