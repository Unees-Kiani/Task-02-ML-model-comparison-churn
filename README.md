# Task 02: Build and Compare Machine Learning Models

Customer churn prediction on the Telco Customer Churn dataset (Kaggle, 7,043 records).

## Models compared
Logistic Regression, Decision Tree, Random Forest, KNN, SVM, plus
GridSearchCV tuning of Logistic Regression and Random Forest.

## Results (test set)
| Model | Accuracy | Precision | Recall | F1 | ROC-AUC |
|---|---|---|---|---|---|
| Random Forest (tuned) | 0.774 | 0.556 | 0.715 | 0.626 | 0.842 |
| Logistic Regression (tuned) | 0.747 | 0.515 | 0.758 | 0.613 | 0.840 |
| Logistic Regression | 0.803 | 0.671 | 0.500 | 0.573 | 0.841 |
| Decision Tree | 0.791 | 0.633 | 0.500 | 0.559 | 0.828 |
| KNN | 0.777 | 0.592 | 0.508 | 0.547 | 0.818 |
| SVM (RBF) | 0.794 | 0.665 | 0.449 | 0.536 | 0.788 |
| Random Forest | 0.781 | 0.617 | 0.454 | 0.523 | 0.819 |

**Best model:** tuned Random Forest (highest F1 and ROC-AUC).

## Files
- `churn_model_comparison.ipynb`: full code
- `Task02_ML_Model_Comparison_Report.docx`: written report

## How to run
1. Open the notebook in Google Colab.
2. Upload the dataset CSV.
3. Run the cell.

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
