# Diwali-Sales-Analysis-Python

Overview:

This project performs Exploratory Data Analysis (EDA) on a Diwali sales dataset to understand customer demographics, purchasing behavior, and product performance during the festive season. The analysis uses Python libraries to clean data, perform aggregations, and visualize meaningful insights that can help businesses improve festive sales strategies.


Problem Statement:
Businesses experience a surge in sales during Diwali. Understanding-
1. Who buys more
2. Which age group spends the most
3. Which occupations and product categories dominate sales
this can help companies optimize marketing, inventory, and targeting strategies.

Tools & Libraries:

1. Python
2. Pandas – data cleaning & manipulation
3. NumPy – numerical operations
4. Matplotlib – basic visualizations
5. Seaborn – advanced visualizations
6. Jupyter Notebook
   
Dataset Information:
1. File name: Diwali Sales Data.csv
2. Encoding used: latin1
3. Type: Retail sales data
4. Contains: Customer demographics, orders, sales amount, product categories

Data Cleaning & Preprocessing:
The following steps were performed-
1. Removed unnecessary columns: Status, Unnamed column
2. Checked and handled missing values
3. Dropped null records
4. Converted Amount column from float to integer
5. Verified data types and structure

# Exploratory Data Analysis (EDA)

Gender-wise Analysis:
1. Count of male vs female customers.
2. Total sales amount by gender.
3. Insight: Female customers contribute higher overall sales compared to males.

Age Group Analysis:
1. Purchase distribution across age groups.
2. Gender-wise age group comparison.
3. Insight: Age group 26–35 years shows the highest purchasing power.   

State-wise Sales:
1. Top performing states based on total sales amount.
2. Insight: A few states contribute a major share of festive sales.

Marital Status Analysis:
1. Sales comparison based on marital status.
2. Insight: Married customers show higher purchasing trends.

Occupation-wise Analysis:
1. Sales distribution by customer occupation.
2. Insight: Customers from IT, Healthcare, and Aviation sectors spend more during Diwali.

Product Category Analysis:
1. Order count per product category.
2. Total sales amount per category.
3. Insight: Food, Clothing, and Electronics are the top-performing product categories.

Top Products Analysis:
1. Identified Top 10 most sold products.
2. Analyzed order volume by product ID.
3. Insight: A small set of products generates a large portion of total orders.   


How to Run This Project:
1. Clone the repository- 
   git clone https://github.com/himanshp07/Diwali-Sales-Analysis-Python.git
2. Open Jupyter Notebook:
3. Run   Diwali_Sales_EDA.ipynb


Conclusion:

This project analyzed Diwali sales data using Python to identify key customer and product trends. The results show that female customers and the 26–35 age group contribute the most to sales, with Food, Clothing, and Electronics emerging as top-performing categories. These insights highlight how data analysis can support better marketing, inventory planning, and festive sales strategies.


