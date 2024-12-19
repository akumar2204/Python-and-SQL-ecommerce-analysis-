# Python-and-SQL-ecommerce-analysis-

this is the link of the dataset from kaggle 
https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv

Project Overview

This project focuses on analyzing e-commerce sales data using a combination of Python and SQL. The primary objective is to derive actionable insights from the dataset, such as identifying customer purchase trends, calculating revenue growth, and determining the top customers or sellers based on their contributions to sales.

Key Features

1. SQL Queries
Revenue Analysis: Query to calculate annual revenue and cumulative sales over time.
Top Customers: Identify top customers based on their total payments within a year.
Growth Percentage: Calculate the year-over-year percentage growth in revenue.
Purchase Trends: Determine the number of repeat purchases by customers within a specific time frame.
Seller Analysis: Rank sellers based on their revenue contributions.

2. Python Integration
Use of Python libraries like mysql.connector, pandas, numpy, and matplotlib for:
Connecting to the MySQL database.
Fetching and processing query results into dataframes.
Visualizing trends, distributions, and correlations using matplotlib and seaborn.


Dataset Description
The dataset includes the following tables:
Orders: Contains information on order timestamps and customer IDs.
Payments: Stores payment details, including order IDs and payment values.
Products: Lists product categories and other details.
Order_Items: Links products to orders and provides item-specific details.


Installation and Setup

Prerequisites
Python 3.x
MySQL Server
Python Libraries: mysql-connector-python, pandas, numpy, matplotlib, seaborn



Steps to Set Up
1. Clone the repository:
git clone https://github.com/<your-username>/ecommerce-sales-analysis.git

2. Navigate to the project directory:
cd ecommerce-sales-analysis

3. Install the required Python libraries:
pip install -r requirements.txt

4. Import the dataset into your MySQL database.

5. Update the database credentials in the Python scripts.

6. Run the Python scripts to execute SQL queries and visualize the results.



Project Structure
.
|-- data/                     # Folder for datasets (optional, if provided)
|-- sql_queries/              # Contains all SQL scripts used in the project
|-- python_scripts/           # Python scripts for querying and visualizations
|-- requirements.txt          # List of dependencies
|-- README.md                 # Project documentation (this file)



Sample Insights
1. Top 3 customers for each year ranked by total payment.
2. Monthly cumulative sales trends.
3. Year-over-year revenue growth percentage.
4. Correlation between product prices and purchase frequency.
5. examples


Future Work
1. Extend the analysis to include product-level performance.
2. Implement machine learning models to predict future sales trends.
3. Create a dashboard using tools like Power BI or Tableau.

![Screenshot 2024-12-20 033911](https://github.com/user-attachments/assets/a7598037-3d60-4fbb-95e9-275d0f90797d)
![Screenshot 2024-12-20 033859](https://github.com/user-attachments/assets/e9148ce3-ca67-4fb2-946a-5d483330f8df)
![Screenshot 2024-12-20 033923](https://github.com/user-attachments/assets/6f448dd3-0a2b-4fcf-b259-9619ea1f4aa6)




Contact
For questions or feedback, reach out at:

Email: akumar25850@gmail.com

