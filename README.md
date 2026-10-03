# Olist E-Commerce Sales & Customer Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) of the Olist Brazilian E-Commerce dataset using Python.

The analysis explores sales performance, customer purchasing behavior, product category performance, delivery patterns, customer reviews, and geographic sales distribution to identify business trends and insights.

## Project Objectives

* Analyze sales and order trends over time.
* Understand customer purchasing and spending behavior.
* Identify top-performing product categories.
* Evaluate order delivery performance.
* Examine customer review scores.
* Analyze sales distribution across Brazilian states.

## Tools & Technologies

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib

## Dataset

The project uses the Olist Brazilian E-Commerce Public Dataset, which contains information about orders, customers, products, payments, reviews, sellers, and geolocation.

**Dataset Source:** [Olist Brazilian E-Commerce Dataset – Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

## Data Preparation & Quality Checks

* Loaded and explored multiple datasets.
* Checked missing values and duplicate records.
* Reviewed data types.
* Converted date columns into datetime format.
* Removed duplicate records from the geolocation dataset.
* Checked primary key uniqueness.
* Validated foreign key relationships.
* Created order-level product, freight, and payment summaries.
* Merged datasets to create a core order-level sales dataset.

## Exploratory Data Analysis

### Sales Performance Analysis

* Total sales value
* Total freight value
* Average order value
* Monthly sales trends
* Monthly order trends
* Order status distribution
* Payment method analysis

### Product Performance Analysis

* Sales by product category
* Top 10 product categories by sales
* Top product categories by order volume

### Customer Behavior Analysis

* Customer order frequency
* One-time versus repeat customers
* Repeat customer rate
* Customer spending patterns
* Top 10 customers by spending

### Delivery Performance Analysis

* Actual delivery time
* Average delivery duration
* Actual versus estimated delivery
* On-time, late, and not-delivered order classification
* On-time delivery rate calculation

### Customer Review Analysis

* Review score distribution
* Average customer review score
* Review scores by delivery-time groups

### Geographic Sales Analysis

* Sales distribution by customer state
* Top 10 Brazilian states by sales

## Key Business Insights

* Customer satisfaction was generally high, with 5-star reviews being the most common.
* Average review scores tended to decrease as delivery time increased, particularly for orders taking 22+ days.
* Sales were concentrated in a limited number of Brazilian states.
* Product categories differed in their contribution to sales and order volume.
* Monthly sales and order volumes varied over time, indicating changes in customer demand.

## Business Recommendations

* Monitor monthly sales and order trends for business planning.
* Focus on product categories contributing significantly to sales.
* Improve delivery operations to support customer satisfaction.
* Develop customer retention strategies based on purchasing behavior.
* Monitor regional sales performance to identify business opportunities.

## Project File

**Olist_Ecommerce_Analysis(6).ipynb**

The notebook contains the Python code, data preparation, analysis, visualizations, and business insights.

## How to Run

1. Download the dataset from the Kaggle source.
2. Extract the required CSV files.
3. Place the CSV files in the notebook's working directory.
4. Install the required Python libraries:

   * pandas
   * numpy
   * matplotlib
5. Open the notebook in Jupyter Notebook or Google Colab.
6. Run the cells sequentially.

## Conclusion

This project demonstrates the use of Python for e-commerce data analysis, data quality checks, exploratory analysis, visualization, and deriving business insights from transactional data.
