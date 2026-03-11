# Olist E-commerce Data Analysis

A business-focused data analysis project based on the Olist Brazilian e-commerce dataset.  
This project explores delivery performance, category-level sales, customer satisfaction, geographic concentration, and customer retention through a structured analytical workflow.

---

## Project Overview

E-commerce platforms generate large amounts of transactional and operational data, but raw data alone does not explain business performance.

This project analyzes the Olist marketplace to answer questions such as:

- How efficient is the delivery process?
- How often are orders delivered on time?
- Which categories generate the most revenue?
- How do delivery delays affect customer satisfaction?
- Where are sales geographically concentrated?
- Are customers returning to purchase again?

---

## Objectives

- Evaluate delivery performance and late delivery behavior
- Identify top-performing product categories
- Measure the impact of logistics on customer reviews
- Analyze customer value using RFM segmentation
- Measure customer retention with cohort analysis
- Extract actionable business insights from marketplace data

---

## Dataset

The project uses the **Olist Brazilian E-commerce Public Dataset**, which includes:

- orders
- order items
- payments
- reviews
- customers
- products
- sellers
- geolocation
- category translation

This dataset allows analysis from operational, commercial, customer, and geographic perspectives.

---

## Project Structure

```text
olist-ecommerce-analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   ├── 03_business_metrics.ipynb
│   └── 04_customer_analytics.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore

---

Workflow Overview
1. Data Cleaning

Preparation of raw data, date conversion, and creation of logistics-related variables such as delivery time, delay days, and on-time delivery status.

2. Exploratory Analysis

Analysis of delivery performance, order status distribution, monthly order trends, and basic sales behavior.

3. Business Metrics

Evaluation of category-level performance, relationship between delays and review scores, and geographic sales concentration.

4. Customer Analytics

Customer segmentation with RFM analysis and retention evaluation through cohort analysis.

Key Findings

- Most delivered orders arrived on time, indicating generally strong logistics performance.
- Late deliveries are associated with lower customer review scores.
- Revenue is concentrated in a relatively small number of product categories.
- Sales are geographically concentrated, especially in southeastern Brazil.
- Most customers purchased only once during the observed period.
- Cohort analysis suggests weak retention and limited repeat purchasing behavior.

Business Value

This project shows how marketplace data can be used to generate insights across multiple business dimensions:

- Operations: delivery performance and delays
- Revenue: top categories and sales patterns
- Customer experience: reviews and satisfaction
- Customer strategy: segmentation and retention

It also demonstrates an end-to-end analytics workflow, from data cleaning to business interpretation.

Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

How to Run
Clone the repository
git clone https://github.com/Ajota3744/Brazilian E-commerce Dataset(Olist).git
cd Brazilian E-commerce Dataset(Olist)

Install dependencies
pip install -r requirements.txt
Open Jupyter Notebook
jupyter notebook

Run notebooks in order

01_data_cleaning.ipynb
02_exploratory_analysis.ipynb
03_business_metrics.ipynb
04_customer_analytics.ipynb

Future Improvements

- build an interactive dashboard
- add seller-level analysis
- compare regions in more detail
- incorporate forecasting or churn-related analysis

Author

Anthony
Electronic Engineer interested in data analysis, artificial intelligence, and data science.