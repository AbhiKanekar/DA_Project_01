🧠 Overview

This project focuses on analyzing e-commerce sales data to uncover meaningful insights about customer behavior, product performance, and regional sales distribution.
It demonstrates end-to-end data analysis skills, from data cleaning and transformation to visualization and SQL-based exploration.

🚀 Objectives

Understand customer purchase patterns

Identify top-performing products and categories

Analyze revenue trends per seller and region

Build visual dashboards using Seaborn and Matplotlib

Perform advanced SQL queries to extract insights from relational data

🧰 Tech Stack
Tool / Library	Purpose
Python	Data processing and visualization
Pandas	Data cleaning, transformation, and analysis
Matplotlib / Seaborn	Visual analytics and dashboards
MySQL	Database management and querying
Docker	Containerization for consistent environment
Jupyter Notebook / VS Code	Development and analysis environment

🧩 Dataset Information

The dataset used in this project includes:
Customers – Customer details and location
Orders – Order IDs, timestamps, and payment data
Products – Product names and categories
Sellers – Seller IDs and regions
Payments – Payment values and types


💾 Data Access Process

In this project, a Docker-based MySQL server was used to simulate a real-world database environment — similar to how organizations host their data on remote servers.

Here’s the process followed:

Set up the MySQL server in Docker

The MySQL database was containerized using Docker for easy management and isolation.

CSV files (customers, orders, products, sellers, payments) were imported into the MySQL database.

Create and manage database tables

Each CSV file was loaded as a separate table (e.g., customers, orders, products, etc.).

Proper relationships were established using primary and foreign keys.

Access the data remotely via Python

Used the mysql.connector library to establish a connection between Python and the MySQL server.

Retrieved the data directly into Pandas DataFrames for analysis.


🧠 Future Improvements

Automate analysis with Python scripts

Add Power BI / Tableau dashboards

Integrate predictive models for demand forecasting

Create a web dashboard with Flask or Streamlit

👨‍💻 Author

Mrunmay Ravindra Kanekar
📧 mrunmaykanekar@gmail.com