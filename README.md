# Customer Shopping Behavior Analysis

## Project Overview
This project explores customer purchasing patterns using a multi-tool approach. By analyzing demographics, purchase history, and subscription status, the project identifies key drivers of revenue and segments customers to help drive targeted marketing strategies.

## Workflow
1. **Data Processing (Python)**: Initial data loading and exploration using Pandas, with automated export to a PostgreSQL database via SQLAlchemy.
2. **Database Management (SQL)**: Advanced querying to perform customer segmentation (New, Returning, Loyal), revenue analysis by gender, and shipping method comparisons.
3. **Visualization (Power BI)**: An interactive dashboard to visualize KPIs such as average review ratings, subscription impacts, and top-performing product categories.

## Key Insights
* **Segmentation**: Classified customers into 'New', 'Returning', and 'Loyal' based on previous purchase frequency.
* **Revenue Drivers**: Analyzed the correlation between discount application and total purchase amounts.
* **Shipping & Subscriptions**: Evaluated if subscribed members yield a higher lifetime value compared to non-subscribers.

## Dashboard Snapshot
Below is the main view of the Customer Behavior Dashboard:

![Customer Behavior Dashboard](https://github.com/R1gh1v/Customer-Segmentation-Behavior-Analysis/blob/main/Screenshot%202026-04-18%20011217.png?raw=true)

## Repository Structure
* `customer_shopping_behavior.csv`: The raw dataset.
* `Data_Analysis_Project_customer_behaviour.ipynb`: Python notebook for data ingestion.
* `Customer_behaviour_SQL.sql`: SQL script containing segmentation and analysis queries.
* `Customer_behaviour_dashboard.pbix`: Power BI dashboard file.

## Tools Used
* **Python**: Pandas, SQLAlchemy
* **PostgreSQL**: Data storage and complex business logic
* **Power BI**: Interactive reporting and DAX
