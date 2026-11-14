# 03 - Customer Segmentation (RFM + K-Means)

**Goal:** Group customers into segments based on purchasing behaviour so each group can get targeted marketing.

**Tools:** Python, pandas, scikit-learn (KMeans), matplotlib, seaborn, Jupyter Notebook

**Dataset:** _(add the dataset name and link here)_

## Approach
1. Cleaned the transactions (missing IDs, cancellations, invalid prices)
2. Built RFM features (Recency, Frequency, Monetary)
3. Scaled the features with StandardScaler
4. Chose K with the Elbow Method (and silhouette score)
5. Clustered with K-Means and profiled each segment

## Segments and recommended actions
| Segment | Description | Action |
|---|---|---|
| _name_ | _description_ | _action_ |

## Screenshots
_(add the elbow plot and cluster scatter plot here)_

## How to run
1. `pip install pandas numpy matplotlib seaborn scikit-learn jupyter`
2. Open `customer_segmentation.ipynb` in Jupyter and run all cells.
