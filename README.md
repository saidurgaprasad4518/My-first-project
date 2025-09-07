# My-first-project
This is my first Repository Author- saidurgaprasad
Sales-Analytics-Dashboard
A simple, end-to-end data analysis project that demonstrates key skills in Python, SQL, and data visualization. The project connects to a local SQLite database, performs an analysis of mock sales data, and generates a set of professional-quality charts as PNG images.

This project is ideal for a data analyst portfolio, as it showcases the full workflow from data access to visual communication.

Key Features
Database Interaction: Connects to and queries a local SQLite database using Python's sqlite3 library.

Data Analysis: Uses the Pandas library to manipulate and analyze sales data.

Data Visualization: Generates a set of professional charts using Matplotlib and Seaborn.

Reproducible Workflow: A single Python script handles the entire process, making the analysis easy to run and reproduce.

How to Run the Project
Follow these steps to generate the dashboard visualizations on your machine.

1. Requirements
Make sure you have Python 3 installed on your system. You'll also need the following libraries:

pandas

matplotlib

seaborn

You can install all of them at once using pip:

pip install pandas matplotlib seaborn

2. Project Files
Download the following two files and save them in the same directory:

schema.sql (Contains the database schema and sample data)

generate_dashboard.py (The main Python script)

3. Setup and Execution
Open your terminal or command prompt and navigate to the project directory.

Create the Database: Run the SQL schema script to set up the database and populate it with data. The sqlite3 command-line tool is required for this.

sqlite3 company_database.db < schema.sql

This command will create a new file named company_database.db in your directory. If the command sqlite3 is not recognized, you may need to install it or ensure it's in your system's PATH.

Run the Python Script: With the database set up, you can now run the Python script.

python generate_dashboard.py

4. Output
After the script completes, a new folder named dashboard_visuals will be created. Inside, you will find five PNG image files that form your sales analytics dashboard.

1_monthly_revenue_trend.png

2_revenue_by_category.png

3_units_sold_by_product.png

4_sales_by_country.png

5_price_vs_quantity.png
