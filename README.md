# Project-1-
Customer segmentation using RFM analysis on e-commerce data
# 🧠 RFM Customer Segmentation

This project performs an RFM (Recency, Frequency, Monetary) analysis using an e-commerce dataset from Kaggle to segment customers based on their purchasing behavior.

## 📂 Dataset
- Source: [Kaggle - Online Retail Dataset](https://www.kaggle.com/datasets)
- Fields used: `CustomerID`, `InvoiceDate`, `InvoiceNo`, `Quantity`, `UnitPrice`

## 📊 RFM Metrics

| Metric     | Description                                 |
|------------|---------------------------------------------|
| Recency    | Days since last purchase                    |
| Frequency  | Total number of purchases                   |
| Monetary   | Total amount spent                          |

## 🔍 Customer Segments
- **Champions**: Most active and high-value
- **Loyal Customers**: Frequent buyers
- **At Risk**: Haven’t bought in a while
- **Lost**: Inactive customers

## 📈 Visualization
Bar chart showing customer count per segment using `seaborn`.

## 🛠️ Tools
- Python (Pandas, Matplotlib, Seaborn)
- Google Colab
- GitHub

## 📁 Files
- `rfm_analysis.ipynb`: Full notebook with code and plots
- `rfm_segments.csv`: (optional) Exported segmentation results
