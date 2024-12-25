Superstore Sales Analysis

## Overview

This project delves into an in-depth analysis of the sales performance of a fictional superstore dataset. Utilizing **Python (Jupyter Notebook)** for data preprocessing and **Tableau** for interactive data visualization, the project aims to uncover key trends, insights, and business metrics across various dimensions such as region, product category, discount rates, shipping costs, and more.

The final product is a robust and interactive Tableau dashboard hosted on [Tableau Public](#). This dashboard showcases eight compelling visualizations, enabling users to explore patterns and relationships in sales and profit data interactively.

---

## Table of Contents

1. [Dataset Overview](#dataset-overview)
2. [Tools and Technologies](#tools-and-technologies)
3. [Process](#process)
    - Data Cleaning and Preparation
    - Exploratory Data Analysis (EDA)
    - Visualization and Dashboard Creation
4. [Key Visualizations](#key-visualizations)
5. [Insights](#insights)
6. [Dashboard](#dashboard)
7. [File Structure](#file-structure)
8. [How to Run](#how-to-run)
9. [Conclusions](#conclusions)

---

## Dataset Overview

The dataset used for this project is a detailed superstore dataset containing over **50,000 rows** and **26 columns**, covering attributes such as:
- **Sales**
- **Profit**
- **Region**
- **Product Category**
- **Shipping Costs**
- **Discounts**

The dataset was cleaned to remove duplicates, address missing values, and create derived metrics such as **Percentage of Total Sales**.

---

## Tools and Technologies

- **Python (Jupyter Notebook)**: For data cleaning and exploratory data analysis.
- **Libraries**:
  - `Pandas`, `NumPy`: Data manipulation
  - `Matplotlib`, `Seaborn`: Visualization during EDA
- **Tableau Public**: For creating and publishing interactive visualizations and dashboards.

---

## Process

### Data Cleaning and Preparation
- Loaded the dataset and examined key metrics.
- Removed irrelevant or missing data fields.
- Created derived features like **Profit Percentage** and **Discount Impact**.

### Exploratory Data Analysis
- Explored relationships between **Discounts** and **Profit**, **Shipping Costs** across regions, and **Category-wise Sales** using Python visualizations.

### Visualization and Dashboard Creation
- Designed eight individual visualizations in Tableau, including:
  - **Sales by Region**
  - **Profit by Product Category**
  - **Discount vs. Profit**
  - **Top Customers by Sales**
  - **Shipping Costs by Region**
- Combined these visualizations into a cohesive Tableau Dashboard.

---

## Key Visualizations

Here are the major visualizations included in this project:

1. **Sales by Region**:
   - A bar chart illustrating total sales by region.
2. **Profit by Product Category**:
   - Highlights profitability trends across product categories.
3. **Sales vs. Profit Scatter Plot**:
   - Explores the relationship between sales and profit with discount overlay.
4. **Discount vs. Profit**:
   - Investigates how varying discount levels influence profitability.
5. **Shipping Costs by Region**:
   - A bar chart highlighting regional shipping expenses.
6. **Sales and Profit by Year**:
   - Combined bar and line chart showcasing annual sales growth and profitability.
7. **Top 10 Customers by Sales**:
   - Ranking the top-performing customers based on sales.

---

## Insights

### Key Takeaways:
- **Regional Performance**: Central region dominates in sales but also incurs higher shipping costs.
- **Profit Drivers**: Technology outshines other categories in profitability, while Office Supplies exhibit moderate profit margins.
- **Discount Impact**: Higher discounts often correlate with reduced profitability, emphasizing the need for strategic discounting.
- **Customer Insights**: A small percentage of customers contribute significantly to total sales.

---

## Dashboard

The interactive Tableau dashboard is available on [Tableau Public](#). The dashboard combines all eight visualizations, offering a comprehensive overview of sales performance and trends.

---

## File Structure

Global-Superstore-Case-Study/
├── data/
│   ├── superstore_eda_cleaned.csv   # Cleaned dataset
│   ├── superstore.csv               # Raw dataset
├── notebooks/
│   ├── 01_Data_Understanding_and_Cleaning.ipynb   # Notebook for data cleaning
│   ├── 02_Exploratory_Data_Analysis.ipynb         # Notebook for exploratory analysis
├── .gitignore                        # Git ignore file
├── LICENSE                           # License file
├── README.md                         # Project documentation

## Installation

To set up and run this project on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Global-Superstore-Case-Study.git
   cd Global-Superstore-Case-Study
2. **Open Jupyter notebooks**
    ```bash
    jupyter notebook
3. **Access Tableau Dashboard**
    https://public.tableau.com/app/profile/enqi.wu5193/viz/SuperstoreSalesAnalysis_17351509091510/GlobalSaleDashboard

## Usage
1. **Data Cleaning and Understanding**
    Open the 01_Data_Understanding_and_Cleaning.ipynb notebook to explore the raw dataset and observe the cleaning steps applied to prepare the data for analysis.
2. **Exploratory Data Analysis**
    Open the 02_Exploratory_Data_Analysis.ipynb notebook to observe the visualizations and insights derived from the cleaned dataset.

