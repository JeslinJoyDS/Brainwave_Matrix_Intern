# Brainwave_Matrix_Intern
Data science projects

# Walmart Sales Data Analysis

This project analyzes sales data from Walmart stores to identify key sales trends, top-selling products, and revenue-generating stores.

# Dataset

The dataset consists of:

Date: Date of the sale.

Product: The name of the sold product.

Category: Product category (e.g., Electronics, Home Appliances, Gadgets).

Store: Walmart store where the product was sold.

Quantity: Number of items sold.

Price: Price per unit.

Total Revenue: Computed as Quantity * Price.

# Steps Performed

Load Data: The script reads the Walmart sales dataset (walmart_sales_data.csv).

Data Preprocessing:

Converts the date column to datetime format.

Checks for missing values.

Revenue Analysis:

Computes total revenue for each transaction.

Aggregates revenue on a monthly basis.

Top-Selling Products:

Identifies the top 10 best-selling products based on quantity sold.

Top Revenue-Generating Stores:

Identifies the top 10 Walmart stores generating the highest revenue.

Data Visualization:

Monthly revenue trend using a line plot.

Top-selling products using a bar chart.

Top revenue-generating stores using a bar chart.
# How to Use

# Clone this repository:
git clone https://github.com/JeslinJoyDS/WalmartSales_Data_Analysis.git

cd WalmartSales_Data_Analysis

# Install required Python libraries:

pip install pandas matplotlib seaborn

# Run the analysis script:

python WalmartSales_Data_Analysis.ipynb

# Dependencies

Python 3.x

Pandas

Matplotlib

Seaborn

# Results

This analysis provides insights into Walmart sales trends, helping to make data-driven business decisions.
