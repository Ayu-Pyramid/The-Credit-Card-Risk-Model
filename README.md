Machine learning pipeline for detecting fraudulent credit card transactions on a highly imbalanced dataset (<0.2% fraud). Focused on recall optimization, class imbalance handling, and practical model evaluation.
Approach
Standardized transaction Amount and Time
Stratified train/test split
Balanced training data using SMOTE
Trained and compared:
Logistic Regression (recall-focused baseline)
Random Forest (nonlinear ensemble model)
Tuned probability threshold to increase fraud recall
Results
Random Forest: strong precision–recall balance
Tuned model: improved fraud recall with controlled false positives
Identified top fraud-related features using feature importance
Tech Stack
Python, Pandas, NumPy, Scikit-learn, SMOTE, Matplotlib, Seaborn
Skills Demonstrated
Imbalanced classification, ensemble learning, threshold tuning, model evaluation beyond accuracy, fraud detection systems
