# AI-Driven Retail Business Analytics & Sales Prediction

## Project Description
This project analyses the supplied Superstore retail transaction dataset to identify sales, profitability, customer, product and regional performance patterns. It combines data cleaning, exploratory data analysis, business KPIs, profitability diagnostics, machine learning and sales prediction.

The notebook is the source of truth for all numerical results used in the report.

## Dataset
The project uses the Superstore CSV supplied with this submission.

- Records: 9,994
- Fields: 21
- Analysis period: November 2014 to December 2017
- Public reference: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

Place the dataset at:

```text
data/superstore.csv
```

## Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

```text
AI_Retail_Business_Analytics/
├── data/
│   └── superstore.csv
├── outputs/
├── JayalaxmiT_AIRetailBusinessAnalytics.ipynb
├── requirements.txt
├── README.md
└── JayalaxmiT_ProjectReport.docx
```

## Setup

1. Install Python 3.10 or later.
2. Open a terminal in the project folder.
3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `JayalaxmiT_AIRetailBusinessAnalytics.ipynb`.
6. Run all cells from top to bottom.

## Analysis Included

The notebook produces:

- Data-quality checks
- Executive KPI summary
- Monthly sales trend
- Monthly profit trend
- Sales by category
- Profit by region
- Segment performance
- Customer analysis
- Discount-band profitability analysis
- Sub-category profitability
- Machine-learning model comparison
- Actual-vs-predicted sales chart
- Six-month sales forecast
- Verified business findings

## Machine Learning

Monthly sales are predicted using:

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor

The evaluation uses a chronological train/test split and reports:

- MAE
- RMSE
- R²

The model used for the displayed forecast is selected using the lowest test RMSE.

## Verified Results From This Run

- Total Sales: ₹2,297,200.86
- Total Profit: ₹286,397.02
- Overall Profit Margin: 12.47%
- Unique Orders: 5,009
- Unique Customers: 793
- Unique Products: 1,862
- Selected Forecast Model: Linear Regression
- Test MAE: 12,659.93
- Test RMSE: 16,198.12
- Test R²: 0.534

## Reproducibility

The report figures and metrics were generated directly from the supplied CSV by executing the notebook. If the dataset is changed, rerun the notebook so that the report outputs can be refreshed.

## Author

**Jayalaxmi T**

**Project:** AI-Driven Retail Business Analytics & Sales Prediction
