# Order Management Database and Analysis

This project involves the analysis of sales data from a sample dataset sourced from Kaggle. The primary goal of this analysis is to gain insights into sales trends, customer behaviors, and product performance. The data has been ingested into a PostgreSQL database hosted on Azure Data Studio, and is being queried for analytical insights.

## Project Overview

1. **Initial Data Handling with Excel**: 
    - Enhanced naming conventions for better clarity and consistency.
    - Initial exploration of the dataset to identify potential trends and outliers.

2. **Entity Relationship Diagram (ERD)**:
    - Designed a database schema using an ERD to structure the tables and relationships.

3. **Database Setup**: 
    - Used PostgreSQL in Azure Data Studio.
    - Established table schemas based on the ERD.
    - Ingested data into the tables from the CSV file.

4. **Data Analysis**:
    - Used SQL queries to extract insights such as top-performing products, sales trends by region, and customer behaviors.

## Dataset

The dataset used in this project is sourced from Kaggle and can be found here: [Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data).

The dataset contains details such as:
- Order and shipment details
- Customer information
- Product details including pricing

## Tools & Technologies Used

- **Excel**: For preliminary data cleanup and exploration.
- **Azure Data Studio**: For setting up and hosting the PostgreSQL database.
- **PostgreSQL**: The relational database system used for storing and querying the data.
- **Python**: For data processing and insertion into the database.

## Queries and Analysis

A few of the analytical queries run on the dataset include:
1. Finding the top 10 products by sales.
2. Determining sales trends by month and year.
3. Identifying the top customers by order value.
4. Calculating the average order value by country.

## How to Run the Analysis

1. Setup the PostgreSQL database in Azure Data Studio.
2. Create the tables based on the provided schemas.
3. Use the Python script to read the CSV file and populate the tables.
4. Run the SQL queries to perform the analysis.

## Future Enhancements

- Consider integrating with data visualization tools such as Tableau or Power BI for more intuitive insights.
- Expand the analysis to include predictive modeling for sales forecasting.

---

This README serves as a high-level overview of the project. Depending on the audience and the context in which this README will be used, you might consider adding, removing, or expanding certain sections.