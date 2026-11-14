# 06 - Fraud Detection

**Goal:** Detect fraudulent transactions in a heavily imbalanced dataset.

**Tools:** Python, pandas, scikit-learn, imbalanced-learn (SMOTE), matplotlib, seaborn, Jupyter Notebook

**Dataset:** _(add the dataset name and link here)_

## Approach
1. Measured the class imbalance and explored amount and time-of-day patterns
2. Showed why accuracy is misleading on imbalanced data
3. Stratified train/test split, then SMOTE on the training set only
4. Trained Logistic Regression and Random Forest
5. Evaluated with precision, recall, F1 and AUC-ROC
6. Analysed the precision/recall trade-off and feature importance

## Results
| Model | Precision | Recall | F1 | AUC-ROC |
|---|---|---|---|---|
| _Logistic Regression_ | _value_ | _value_ | _value_ | _value_ |
| _Random Forest_ | _value_ | _value_ | _value_ | _value_ |

## Key findings
- _Finding 1_
- _Finding 2_

## How to run
1. `pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter`
2. Open `fraud_detection.ipynb` and run all cells.
