# Veda Technology

# Exploratory Data Analysis (EDA) – Superstore Sales Dataset

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Superstore Sales Dataset using Python. The objective is to understand the structure of the data, identify patterns and relationships, detect potential outliers, and generate meaningful business insights through statistical analysis and data visualization.

The analysis was performed using **Pandas, Matplotlib, and Seaborn** in a Jupyter Notebook.

## Objective

The primary objectives of this analysis are:

- Understand the structure and characteristics of the dataset.
- Perform data quality checks and identify missing values.
- Generate summary statistics for numerical variables.
- Analyze distributions and relationships between important variables.
- Identify potential outliers.
- Compare sales and profitability across different business segments.
- Extract actionable insights from the data.

## Tools & Technologies

- **Python**
- **Pandas** – Data loading, cleaning, transformation, and analysis
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Analysis and documentation environment

## Dataset

The analysis uses the **Superstore Sales Dataset**, which contains information related to orders, customers, products, sales, quantity, discounts, and profit.

The complete dataset is loaded into a Pandas DataFrame while only selected rows are displayed during exploration to keep the notebook readable and efficient.

```python
import pandas as pd

df = pd.read_csv("SuperStore_Sales_Dataset.csv")

df.head()
