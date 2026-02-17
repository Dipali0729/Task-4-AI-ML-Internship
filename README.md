# Task-4-AI-ML-Internship

📌 Task 4: Logistic Regression – Binary Classification
🎯 Objective

To build a binary classification model using Logistic Regression and evaluate its performance.

📂 Dataset

Custom dataset (data.csv)

Target column: diagnosis

Removed unnecessary columns (id, Unnamed: 32)

Converted categorical values to numeric

Handled missing values

🛠 Tools Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

🚀 Steps Performed

Loaded dataset using Pandas

Cleaned data (removed unwanted columns & handled missing values)

Converted target values into numeric format

Split data into training (80%) and testing (20%)

Standardized features using StandardScaler

Trained Logistic Regression model

Evaluated model using:

Confusion Matrix

Precision

Recall

ROC-AUC Score

Performed threshold tuning

📈 Sigmoid Function

Logistic Regression uses the Sigmoid Function:

σ(z) = 1 / (1 + e⁻ᶻ)

It converts model output into probability between 0 and 1.

✅ Conclusion

The Logistic Regression model successfully performed binary classification and was evaluated using multiple performance metrics.
