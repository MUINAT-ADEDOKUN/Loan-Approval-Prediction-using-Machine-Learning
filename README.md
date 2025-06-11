# Loan-Approval-Prediction-using-Machine-Learning
This project aims to predict whether a loan will be approved or not based on applicant details using various classification models like Random Forest, KNN, SVM, and Logistic Regression.
Dataset

Dataset: `LoanApprovalPrediction.csv`  
Includes applicant details such as gender, income, education, loan amount, credit history, etc.

---

## 🔧 Libraries Used

- `pandas`, `numpy` – Data manipulation
- `matplotlib`, `seaborn` – Data visualization
- `sklearn` – ML models and evaluation

---

Data Preprocessing

- Dropped irrelevant columns (`Loan_ID`)
- Encoded categorical variables using `LabelEncoder`
- Handled missing values by replacing with column mean
- Visualized categorical distribution and correlation heatmaps

---

Models Trained

| Model                  | Train Accuracy | Test Accuracy |
|-----------------------|----------------|---------------|
| Random Forest (Entropy, n=7) | 98.04%         | 82.50%        |
| KNN (k=3)              | 78.49%         | 63.75%        |
| SVC (default)          | 68.71%         | 69.17%        |
| Logistic Regression    | 80.45%         | 80.83%        |

---

 Insights

- Random Forest outperformed others with the highest test accuracy.
- Logistic Regression also performed well and consistently.
- Proper encoding and handling of missing data had a significant impact.
