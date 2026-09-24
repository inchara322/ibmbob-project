# Global E-Commerce Sales & Customer Analytics using AI

## Project Overview

This project analyzes global e-commerce transaction data to identify sales trends, profitability patterns, customer behavior, product performance, and business insights.

The project uses Python for data analysis and machine learning. Random Forest Regression is used for sales prediction, while K-Means Clustering is used for AI-based customer segmentation. An interactive Streamlit interface is included for visualization and prediction.

## Dataset

Dataset: Global E-Commerce Sales & Customer Data

Source: Kaggle

Dataset Link:
https://www.kaggle.com/datasets/muhammadaammartufail/global-e-commerce-sales-and-customer-data

Dataset Size:
- 2,000 records
- 15 columns

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn
- Streamlit
- Excel
- Power BI
- K-Means Clustering
- Random Forest Regression
- Google Colab
- GitHub

## Machine Learning

### Random Forest Sales Prediction

The Random Forest Regression model predicts Total Sales using:

- Quantity
- Unit Price
- Discount Percentage
- Shipping Cost

Model performance:

- MAE: 18.49
- RMSE: 69.77
- R² Score: 0.96

### K-Means Customer Segmentation

K-Means clustering groups customers based on:

- Total Sales
- Total Orders
- Total Quantity

Three customer groups are identified:

- High-Value Customers
- Medium-Value Customers
- Lower-Value Customers

## Application Features

- Sales analysis
- Profit analysis
- Customer analytics
- Product category analysis
- Country-wise sales analysis
- Monthly sales trends
- AI customer segmentation
- AI sales prediction
- Interactive Streamlit dashboard

## Project Files

- `Inchara_Global_Ecommerce_AI_Analytics.ipynb` – Complete project notebook containing data analysis, machine learning, backend logic, and frontend code.
- `requirements.txt` – Python dependencies.
- `Inchara_Global_Ecommerce_AI_ProjectReport.docx` – Complete project report.
- `README.md` – Project documentation.

## How to Run

1. Install Python.
2. Install the required libraries:

```bash
pip install -r requirements.txt
