# Data Analytics Strategic Plan – Retail Sales Analysis

**Author:** Anuska Dhar

## Project Overview

This project demonstrates a Python-based data analytics workflow designed to support business decision-making through data-driven insights. It focuses on analyzing retail sales data to identify revenue trends, evaluate product and regional performance, calculate key performance indicators (KPIs), and develop strategic business recommendations.

The project uses a synthetic retail sales dataset to demonstrate data acquisition, data cleaning, exploratory data analysis, KPI calculation, and data visualization. The insights generated can help illustrate how organizations can use analytics to improve operational efficiency, understand sales performance, and identify potential business opportunities.

## Objectives

- Develop a practical data analytics workflow using Python.
- Clean and preprocess raw sales data.
- Analyze revenue, estimated profit, sales volume, and average order value.
- Identify sales trends across products, regions, and months.
- Define KPIs to evaluate business performance.
- Generate visualizations to communicate analytical findings.
- Recommend data-driven strategies for business improvement.

## Technologies Used

- **Python** – Core programming language.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical computations.
- **Matplotlib** – Data visualization.
- **CSV** – Data storage and exchange.
- **Git and GitHub** – Version control and project hosting.

## Project Structure

```text
Data_Analytics_Strategic_Project/
│
├── data/
│   └── retail_sales_raw.csv
│
├── src/
│   └── analysis.py
│
├── outputs/
│   ├── cleaned_sales.csv
│   ├── kpi_summary.txt
│   ├── monthly_revenue.png
│   ├── revenue_by_product.png
│   └── revenue_by_region.png
│
├── PROJECT_REPORT.md
├── requirements.txt
└── README.md
```

## Methodology

### 1. Data Acquisition
Import the retail sales dataset from a CSV file using Pandas.

### 2. Data Cleaning and Preprocessing
- Identify missing values and duplicate order IDs.
- Standardize text fields and convert data types.
- Remove duplicate transactions and records missing essential fields.
- Validate quantities and revenue values.
- Prepare the dataset for analysis.

### 3. Exploratory Data Analysis
Analyze sales performance by month, product, and region to identify patterns and potential opportunities.

### 4. KPI Calculation
Calculate important business metrics, including:
- Total revenue
- Estimated profit
- Number of unique orders
- Average order value
- Total units sold
- Critical-field data completeness

### 5. Data Visualization
Generate charts to communicate monthly revenue trends and compare product and regional performance.

### 6. Strategic Recommendations
Use the analytical outputs to identify areas for further investigation, improve inventory planning, and support promotional and operational decisions.

## Key Performance Indicators (KPIs)

| KPI | Purpose |
|---|---|
| Total Revenue | Measures sales generated |
| Estimated Profit | Estimates revenue remaining after estimated costs |
| Average Order Value | Measures average revenue per order |
| Units Sold | Tracks product sales volume |
| Monthly Revenue | Helps identify sales trends |
| Data Completeness | Evaluates the quality of critical fields |

## How to Run the Project

**Prerequisites:** Python 3.10 or newer and pip.

1. Clone or download the repository.
2. Open the project folder in VS Code or a terminal.
3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Execute the analysis script:

```bash
python src/analysis.py
```

5. Check the `outputs` folder for the cleaned dataset, KPI summary, and charts.

## Expected Outcomes

- A cleaned and analysis-ready dataset.
- A reproducible Python analytics workflow.
- Business performance indicators and visual reports.
- Better understanding of product, regional, and monthly sales patterns.
- Practical recommendations for evidence-based decision-making.

## Limitations

The dataset is synthetic and does not represent an actual business. Estimated costs are simulated, and the analysis is descriptive. The findings do not establish causation or guarantee future business performance.

## Future Enhancements

- Implement time-series forecasting for future sales.
- Develop an interactive dashboard using Streamlit or Power BI.
- Introduce automated data-quality tests.
- Incorporate authorized real-world datasets.
- Evaluate business interventions against a defined baseline.

## Conclusion

This project demonstrates how Python-based data analytics can transform raw data into meaningful business information. By combining data cleaning, exploratory analysis, KPI measurement, and visualization, the project establishes a foundation for strategic planning and evidence-based decision-making.

**Project Status:** Initial analytics workflow implemented and tested.
