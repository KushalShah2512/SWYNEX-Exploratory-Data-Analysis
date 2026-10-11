# SWYNEX Exploratory Data Analysis

## Task 2 — Exploratory Data Analysis

This project was completed as part of my **Data Analytics Internship at SWYNEX Technologies**.

The objective of this task was to perform **Exploratory Data Analysis (EDA)** on the cleaned **Online Retail II** dataset using Python and identify meaningful patterns, trends, and business insights.

---

## Objective

The analysis focuses on:

- Understanding the structure of the dataset
- Examining data quality
- Performing descriptive statistics
- Analyzing revenue trends
- Identifying top-performing products
- Analyzing country-level performance
- Understanding customer contribution
- Examining cancellations and adjustments
- Detecting potential high-value statistical outliers
- Generating actionable business insights

---

## Dataset

The project uses the **Online Retail II** dataset.

The cleaned dataset contains:

- **1,033,031 transaction records**
- **16 columns**
- **5,305 unique products**
- **43 countries**
- **5,942 identified customers**

The dataset was cleaned and prepared during **Task 1** before being used for this analysis.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```text
SWYNEX-Exploratory-Data-Analysis/
│
├── data/
│   └── cleaned/
│       └── online_retail_II_cleaned.csv
│
├── notebooks/
│   └── 02_Exploratory_Data_Analysis.ipynb
│
├── output/
│   └── Analysis result CSV files
│
├── visualizations/
│   └── EDA charts and visualizations
│
├── .gitattributes
├── .gitignore
├── README.md
└── requirements.txt
```

> The large cleaned dataset is tracked using **Git LFS**.

---

## Analysis Performed

### 1. Data Quality Analysis

- Checked dataset dimensions and column names
- Examined data types
- Checked missing values
- Verified duplicate records
- Generated descriptive statistics

### 2. Transaction Analysis

- Analyzed transaction types
- Examined sales, cancellations/returns, and adjustments
- Calculated transaction-level revenue

### 3. Revenue Analysis

- Analyzed total net revenue
- Compared yearly revenue
- Examined monthly revenue trends
- Identified the peak revenue month

### 4. Product Analysis

- Identified top products by revenue
- Identified top products by quantity
- Examined the revenue contribution of top products
- Investigated unusual product descriptions such as **"Manual"**

### 5. Country Analysis

- Compared revenue across countries
- Identified the highest-performing country
- Visualized country-level revenue

### 6. Customer Analysis

- Analyzed revenue contribution by identified customers
- Identified the highest-revenue customer
- Examined the revenue concentration of the top customers

### 7. Cancellation and Return Analysis

- Analyzed cancellation and return transactions
- Examined their monthly impact on revenue
- Compared positive and negative revenue transactions

### 8. Anomaly Analysis

- Used the **Interquartile Range (IQR)** method to identify potential high-value statistical outliers
- Retained these records because statistical outliers are not necessarily errors or fraudulent transactions

---

## Key Business Insights

### 1. United Kingdom Dominates Sales

The **United Kingdom** generated approximately **£17.41 million** in sales revenue, making it the strongest market in the dataset.

This represents approximately **91.6% of total net revenue**, indicating a strong concentration of business activity in the UK.

### 2. Revenue Is Broadly Distributed Across Products

The top 10 products contributed approximately **10.12% of total product revenue**.

This indicates that revenue was distributed across a relatively broad range of products rather than being dependent on only a small number of products.

### 3. High-Value Customer Identified

Customer **18102** generated approximately **£580,987** in identified customer revenue, making this customer the highest-revenue identified customer in the dataset.

The top 10 customers contributed approximately **16.04% of customer-attributed revenue**.

### 4. November 2011 Was the Peak Revenue Month

The highest monthly net revenue occurred in **November 2011**, reaching approximately **£1.46 million**.

This indicates a significant increase in sales activity during this period.

### 5. Potential High-Value Outliers Detected

Using the IQR method, **84,954 potential high-value statistical outlier records** were identified.

These records were not removed because high-value transactions may represent legitimate business activity and require further investigation before any decision is made.

### 6. Unusual Product Entry Requires Investigation

The product description **"Manual"** generated approximately **£339,226** in revenue and appeared as the highest-revenue product entry.

Because **"Manual"** is an unusual product description compared with standard product names, it should be investigated separately before interpreting it as a normal product-performance result.

---

## Overall Results

| Metric | Result |
|---|---:|
| Total Records | 1,033,031 |
| Columns | 16 |
| Unique Products | 5,305 |
| Countries | 43 |
| Identified Customers | 5,942 |
| Total Net Revenue | £19.01M |
| Top Country | United Kingdom |
| UK Sales Revenue | £17.41M |
| Top Identified Customer | 18102 |
| Top Customer Revenue | £580,987 |
| Peak Revenue Month | November 2011 |
| Peak Monthly Revenue | £1.46M |
| Potential High-Value Outliers | 84,954 |

---

## Visualizations

The project includes visualizations for:

- Transaction type distribution
- Yearly revenue
- Monthly revenue trends
- Top countries by revenue
- Top products by revenue
- Top products by quantity
- Top customers by revenue
- Monthly return and adjustment impact

All generated charts are available in the `visualizations/` directory.

---

## Output Files

The `output/` directory contains the generated analytical results, including:

- Country analysis
- Customer analysis
- Customer revenue
- Data quality summary
- EDA summary
- Final business insights
- High-value anomaly records
- Key insight evidence
- Monthly return impact
- Monthly revenue
- Revenue by year
- Summary statistics
- Top products by quantity
- Top products by revenue
- Transaction summary
- Yearly revenue

---

## Data Quality

Final validation confirmed:

```text
Dataset shape       : (1033031, 16)
Duplicate records   : 0
Missing dates       : 0
Total net revenue   : £19,014,209.84
Number of products  : 5,305
Number of countries : 43
Customers identified: 5,942
```

The dataset contains **zero duplicate records** after cleaning and **no missing transaction dates**.

---

## Learning Outcomes

Through this task, I gained practical experience in:

- Exploratory Data Analysis using Python
- Data exploration using Pandas
- Statistical analysis using NumPy
- Data visualization using Matplotlib and Seaborn
- Revenue and customer analysis
- Identifying business trends and patterns
- Detecting potential statistical anomalies
- Converting analytical results into business insights
- Organizing analytical outputs for further reporting

---

## Conclusion

The EDA provided a detailed understanding of the **Online Retail II** dataset and revealed important patterns in revenue, products, customers, countries, and transactions.

The analysis highlighted the strong contribution of the United Kingdom, identified key customers and revenue periods, examined cancellations and adjustments, and detected potential high-value statistical outliers for further investigation.

The results provide a strong analytical foundation for the next stage of the project, where the insights can be presented through a **business dashboard**.

---

## Internship

**Data Analytics Internship — SWYNEX Technologies**

**Task 2: Exploratory Data Analysis**
