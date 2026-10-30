# Online Retail Data Analysis

A Big Data practical project based on the **UCI Online Retail Dataset**, using Python to analyze retail transactions, understand customer purchasing behavior, and perform customer segmentation.

## Project Overview

This project focuses on analyzing an online retail dataset containing transactions from December 2010 to December 2011. The objective is to clean the data, explore sales patterns, identify customer behavior, and apply machine learning techniques.

## Dataset

- **Source:** [UCI Machine Learning Repository – Online Retail](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Original Records:** 541,909
- **Columns:** 8
- **Time Period:** December 2010 – December 2011

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Modules

### Module 1: Data Collection and Cleaning

- Loaded the dataset directly using Python.
- Identified and handled missing CustomerID values.
- Detected and removed duplicate transactions.
- Identified and excluded cancelled invoices.
- Removed zero-price transactions from customer analysis.
- Created a cleaned dataset.

**Final cleaned dataset:** 392,692 records.

### Module 2: Exploratory Data Analysis (EDA)

Performed analysis to understand sales and purchasing patterns:

- Monthly revenue analysis.
- Top 10 products by quantity sold.
- Customer purchase frequency.
- Revenue analysis by country.

Visualizations were created using Matplotlib and Seaborn.

### Module 3: Customer Segmentation

Applied RFM (Recency, Frequency, Monetary) analysis to understand customer purchasing behavior.

- Calculated Recency, Frequency, and Monetary values.
- Assigned RFM scores.
- Created customer segments.
- Applied K-Means clustering with 4 clusters.
- Analyzed customer groups based on purchasing behavior.

The analysis identified four customer groups: Occasional, Inactive, Loyal, and High-Value.

### Module 4: Predictive Analytics *(Upcoming)*

- Logistic Regression.
- Random Forest.
- Predicting customer return purchases within the next 30 days.

### Module 5: Interactive Dashboard *(Upcoming)*

- Building a dashboard using Streamlit.
- Displaying sales trends and customer segments.
- Showing predicted customer return probabilities.
- Providing business recommendations.

## How to Run

1. Clone this repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run the cells sequentially.
4. The dataset is loaded directly from the UCI repository using Python.

## Note

The cleaned dataset is prepared for customer-level analysis. Transactions with missing CustomerID, duplicate records, cancelled invoices, and zero-price entries are excluded from the final customer analysis dataset.

## Acknowledgement

Dataset provided by the UCI Machine Learning Repository.

---

**Project Status:** Modules 1, 2, and 3 completed. Modules 4 and 5 are planned.
