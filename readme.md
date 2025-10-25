# Grocery Sales Analysis & Visualization

## Project Overview
This project analyzes supermarket sales data to uncover insights about products, branches, customers, and sales trends. The goal is to understand which product lines perform best, customer purchasing behavior, and how sales vary over time. This type of analysis is highly relevant for business decision-making and data operations roles.

---

## Dataset
The dataset contains supermarket transactions with the following columns:

- **Invoice ID**: Unique identifier for each transaction  
- **Branch**: Store branch (A, B, C)  
- **City**: City of the store  
- **Customer type**: Member or Normal  
- **Gender**: Male or Female  
- **Product line**: Category of product sold  
- **Unit price**: Price per unit  
- **Quantity**: Number of items purchased  
- **Tax 5%**: Tax applied on the sale  
- **Sales**: Total sales amount  
- **Date**: Transaction date  
- **Time**: Transaction time  
- **Payment**: Payment method (Cash, Credit Card, E-wallet)  
- **COGS**: Cost of goods sold  
- **Gross margin percentage**: Profit margin %  
- **Gross income**: Profit from the sale  
- **Rating**: Customer satisfaction rating (1–10)

Dataset source: [Kaggle – Supermarket Sales](https://www.kaggle.com/datasets/faresashraf1001/supermarket-sales)

---

## Tools Used
- **Python 3**  
- **Google Colab** (cloud-based environment)  
- **Pandas** (data manipulation)  
- **Matplotlib & Seaborn** (data visualization)

---

## Methodology
1. **Data Loading & Exploration**  
   - Loaded CSV dataset into Pandas DataFrame  
   - Explored dataset columns, types, and missing values  

2. **Data Cleaning**  
   - Converted Date column to datetime format  
   - Checked for duplicates and missing data  

3. **Exploratory Data Analysis (EDA)**  
   - Analyzed total sales by **product line** and **branch**  
   - Compared sales by **customer type** and **gender**  
   - Examined **payment methods** and average transaction amounts  
   - Visualized **monthly sales trends** and **profitability metrics**  

4. **Visualization**  
   - Bar charts, line plots, and pie charts to highlight key insights  
   - Saved visualizations for inclusion in README and reports  

---

## Key Insights
- **Top-selling products:** Beverages, Snacks, and Fruits are the most popular product lines  
- **Branch performance:** Branch A generates the highest total sales  
- **Customer behavior:** Members spend more on average than Normal customers  
- **Time trends:** Peak sales occur around noon, and monthly trends show higher sales in certain months  
- **Payment methods:** Cash is the most common payment method  
- **Profitability:** Gross income is highest for product lines with higher margins like Beverages  

---

## Visualizations
*(Include your saved plot images here, for example:)*

![Top Product Sales](images/top_products.png)  
![Monthly Sales Trend](images/monthly_sales_trend.png)  
![Branch Sales Comparison](images/branch_sales.png)  

---

## Conclusion
This project demonstrates skills in **data cleaning, exploratory data analysis, visualization, and insight generation**. The analysis can help supermarket managers optimize inventory, target promotions, and understand customer behavior.

---

## How to Run
1. Open the notebook `Grocery_Sales_Analysis.ipynb` in Google Colab  
2. Upload the dataset CSV if not already in the notebook  
3. Run all cells to reproduce analysis and visualizations  

---

## Repository Structure
