# Olist E-Commerce Sales & Order Performance Analysis
## 1. Project Overview
This project focuses on analyzing the Olist Brazilian E-Commerce Public Dataset to understand e-commerce sales performance, customer orders, product categories, payment methods, order status, and delivery-related information.
The project combines Python-based data analysis and visualization with an interactive Power BI dashboard to identify important business insights and provide data-driven recommendations.

## 2. Problem Statement
E-commerce businesses generate large amounts of data related to orders, products, sales, payments, and delivery. Analyzing this data can help businesses understand sales performance, identify high-performing product categories, monitor order trends, and improve operational decision-making.
The objective of this project is to analyze the Olist e-commerce dataset and transform the raw data into meaningful insights using Python and Power BI.

## 3. Dataset Description
The project uses the **Olist Brazilian E-Commerce Public Dataset**.
The dataset contains approximately 100,000 orders from the Brazilian e-commerce marketplace and includes information about:
* Customers
* Orders
* Order items
* Products
* Sellers
* Payments
* Reviews
* Geolocation
* Product categories
The main datasets used for the analysis and Power BI dashboard were:

* `olist_orders_dataset`
* `olist_order_items_dataset`
* `olist_products_dataset`
* `olist_order_payments_dataset`

## 4. Tools Used
The following tools and technologies were used:
* **Python** – Data analysis and visualization
* **Pandas** – Data manipulation and cleaning
* **Matplotlib** – Data visualization
* **Google Colab** – Python development environment
* **Power BI** – Interactive dashboard and business analysis
* **Git** – Version control
* **GitHub** – Project repository and documentation

## 5. Data Cleaning Process
The dataset was inspected and prepared before analysis.
The following steps were performed:
* Loaded the required Olist CSV datasets.
* Inspected the structure and columns of the datasets.
* Identified the data types of important columns.
* Checked for missing values.
* Checked for duplicate records.
* Converted relevant order-date columns into proper datetime format.
* Retained missing delivery-related dates where appropriate because they represent orders that had not reached the corresponding stage of the delivery process.
* Prepared the cleaned datasets for Exploratory Data Analysis and Power BI visualization.

## 6. Exploratory Data Analysis (EDA)
Exploratory Data Analysis was performed to understand the characteristics and patterns in the dataset.
The analysis included:
* Descriptive statistics
* Missing-value analysis
* Duplicate checking
* Product price analysis
* Freight analysis
* Correlation analysis
* Order-status analysis
* Monthly order trends
* Product-category analysis
* Outlier analysis

### Important EDA Findings
* The average product price was approximately **R$120.65**.
* The median product price was approximately **R$74.99**.
* Product prices showed a **right-skewed distribution**, indicating that most products had lower prices while a smaller number of products had considerably higher prices.
* The correlation between product price and freight value was approximately **0.414**, indicating a moderate positive relationship.
* Monthly order activity increased toward the later part of 2017.
* Some product categories contributed significantly more items and sales than others.
* High-price observations were identified through IQR-based outlier analysis. These observations were retained because they may represent genuine high-value products.

## 7. Data Visualizations
Python was used to create visualizations for understanding the dataset.
The following visualizations were created:
1. **Distribution of Product Prices**
   A histogram was used to understand the distribution of product prices.
2. **Product Price vs Freight Value**
   A scatter plot was used to examine the relationship between product price and freight value.
3. **Orders by Status**
   A bar chart was used to compare different order statuses.
4. **Monthly Number of Orders**
   A line chart was used to identify changes in order activity over time.
5. **Top 10 Product Categories by Items Sold**
   A bar chart was used to identify the most frequently sold product categories.
The visualization files are available in the `visualizations` folder of this repository.
## 8. Power BI Dashboard
An interactive Power BI dashboard titled:
**Olist E-Commerce Sales & Order Performance Dashboard**
was developed to provide an overview of sales and order performance.

### Key Performance Indicators
* **Total Orders:** 99,441 unique orders
* **Total Sales:** approximately R$13.59 million
* **Total Freight:** approximately R$2.25 million

### Dashboard Visuals
The dashboard includes:
* Monthly Number of Orders
* Orders by Status
* Sales by Product Category
* Top 10 Product Categories by Sales
* Sales by Payment Type
The dashboard also includes slicers for:
* Order Date
* Order Status
* Product Category
The Power BI dashboard file is included in this repository.

## 9. Key Insights
The major insights obtained from the analysis are:
1. The dataset contains **99,441 unique orders**, with **96,478 orders delivered**.
2. Total sales generated from the analyzed order-item data were approximately **R$13.59 million**.
3. Total freight value was approximately **R$2.25 million**.
4. **Credit card payments** represented the highest payment value among the payment types analyzed.
5. Product prices were right-skewed, with the mean price higher than the median price.
6. Product price and freight value showed a moderate positive correlation.
7. Order activity increased toward the later months of 2017.
8. Sales were concentrated in a smaller number of high-performing product categories.

## 10. Business Recommendations
Based on the analysis, the following recommendations can be made:

### Improve Logistics
Analyze freight costs by product category, seller, location, and order characteristics to identify opportunities for reducing shipping expenses and improving delivery efficiency.
### Focus on High-Performing Categories
Businesses should prioritize inventory planning and marketing efforts for product categories that generate higher sales and order volumes.
### Leverage Payment Preferences
Since credit card payments represent a major share of payment value, businesses can consider offers such as cashback, discounts, and installment-based promotions to encourage purchases.
### Monitor Order Performance
Order-status analysis can help identify cancellations, unavailable orders, and other operational issues that may affect customer satisfaction.
### Use Data-Driven Inventory Planning
Historical sales trends can be used to improve demand forecasting and maintain appropriate inventory levels for popular product categories.
## 11. Conclusion
This project demonstrates how real-world e-commerce data can be transformed into meaningful business insights using Python and Power BI.
The analysis covered data preparation, exploratory data analysis, statistical investigation, visualization, and interactive dashboard development. The findings provide useful information about sales performance, product categories, payment methods, order trends, and logistics.
The project also demonstrates the use of Git and GitHub for version control, project organization, and professional documentation.
Overall, the analysis shows how data analytics can support better business decisions in the e-commerce domain.

## 12. Project Files
The repository contains the following project resources:
* `README.md` – Project documentation
* `Final_Data_Analytics_project.ipynb` – Python analysis notebook
* Power BI dashboard file
* `practice.txt` – Git workflow practice file
* `visualizations/` – Python and Power BI visualization screenshots

---
### Project Workflow

**Data Collection → Data Inspection → Data Cleaning → EDA → Visualization → Power BI Dashboard → Insights → Business Recommendations**
