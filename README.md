# Brainwave_Matrix_Intern-
🕵️‍♂️ Credit Card Fraud Detection – Task 2 | Brainware Matrix Solution
This project is part of Task 2 from the Brainware Matrix Solution internship. The goal is to detect fraudulent credit card transactions using machine learning techniques.
📌 Objective
Build a machine learning model to detect fake (fraudulent) transactions in a credit card dataset. The model should be trained to classify transactions as either fraudulent or genuine, helping financial institutions reduce fraud risk.
📂 Dataset
The dataset used is a well-known anonymized credit card transactions dataset from Kaggle. It contains transactions made by European cardholders in September 2013.
Total records: 284,807
Fraudulent transactions: 492 (highly imbalanced)
Features: 30 (V1 to V28 - PCA components, Time, Amount, Class)
⚙️ Technologies Used
Python
Pandas, NumPy
Scikit-learn (Random Forest, SMOTE for balancing)
Matplotlib & Seaborn (Data Visualization)
📊 Workflow
Data Preprocessing
Checked for missing values
Normalized/standardized the Amount feature
Data Balancing
Applied SMOTE (Synthetic Minority Oversampling Technique) to handle class imbalance
Model Training
Trained a Random Forest Classifier
Model Evaluation
Evaluated using accuracy, precision, recall, F1-score, and confusion matrix
Prediction
Predicted and verified outputs for both fake and genuine transactions
✅ Results
The model successfully detects fraudulent transactions with high accuracy and recall, ensuring a strong ability to catch frauds with minimal false negatives.







