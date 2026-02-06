Credit Card Fraud Detection Pipeline
📌 Project Overview
This project implements a machine learning pipeline to detect fraudulent credit card transactions on a highly imbalanced dataset (<0.2% fraud). The focus is on optimizing recall, handling class imbalance, and evaluating models using practical metrics beyond accuracy.
🚀 Key Features
Data Preprocessing & Balancing:
Standardized Amount and Time features
Stratified train/test split to preserve class distribution
Used SMOTE to balance training data
Model Training & Evaluation:
Logistic Regression (baseline, recall-focused)
Random Forest (nonlinear ensemble model)
Tuned probability thresholds to improve fraud recall
Evaluated models with precision–recall metrics
Insights & Feature Analysis:
Random Forest achieved strong precision–recall balance
Threshold tuning improved fraud recall while controlling false positives
Identified top fraud-related features via feature importance
🛠️ Tech Stack & Tools
Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Imbalanced-learn (SMOTE), Matplotlib, Seaborn
🎯 Skills Demonstrated
Handling highly imbalanced classification problems
Ensemble learning and model comparison
Probability threshold tuning for recall optimization
Practical model evaluation beyond simple accuracy
Fraud detection system design
