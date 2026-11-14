# 07 - Sentiment Analysis

**Goal:** Classify review text as positive, negative or neutral.

**Tools:** Python, pandas, scikit-learn, NLTK, matplotlib, seaborn, WordCloud, Jupyter Notebook

**Dataset:** _(add the dataset name and link here)_

## Approach
1. Inspected the class distribution
2. Preprocessed text: lowercase, punctuation removal, stopword removal (keeping negations), tokenisation, lemmatization
3. TF-IDF features (unigrams and bigrams), 80/20 split
4. Trained Naive Bayes and Logistic Regression
5. Evaluated with accuracy, precision, recall, F1 and confusion matrices
6. Analysed 5 misclassified reviews

## Results
| Model | Accuracy | Macro F1 |
|---|---|---|
| _Naive Bayes_ | _value_ | _value_ |
| _Logistic Regression_ | _value_ | _value_ |

## Key findings
- _Finding 1_
- _Finding 2_

## How to run
1. `pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud jupyter`
2. Open `sentiment_analysis.ipynb` and run all cells (NLTK data downloads automatically).
