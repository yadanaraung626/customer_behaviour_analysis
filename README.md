# customer_behaviour_analysis
Customer Behavior Data Analytics Project
📌 Overview

This project focuses on analyzing customer shopping behavior using Python and SQL Server. The goal is to extract meaningful insights from raw data through data cleaning, exploratory data analysis (EDA), and SQL-based analysis.

The project demonstrates core data analyst skills including data preprocessing, feature engineering, and querying structured data for business insights.

📂 Dataset
The dataset contains customer shopping behavior information such as:
Customer demographics (age, gender)
Purchase details (item purchased, purchase amount)
Review ratings
Purchase frequency
Previous purchase history

🛠️ Tools & Technologies
Python (Pandas, NumPy)
Jupyter Notebook
Microsoft SQL Server
SQLAlchemy & PyODBC
Data Visualization (Matplotlib, Seaborn)

🔄 Project Steps
1. Data Loading
Loaded dataset using Pandas
Verified structure and data types
2. Data Cleaning
Handled missing values (e.g., filled review ratings using median)
Standardized column names (lowercase, removed spaces)
Removed unnecessary columns
Fixed inconsistent data formats
3. Feature Engineering
Created new features such as:
age_group (customer segmentation)
purchase_frequency_days (numerical conversion)
4. Exploratory Data Analysis (EDA)
Analyzed distributions and trends
Identified relationships between variables
Generated summary statistics
5. Database Integration
Connected Python to SQL Server using SQLAlchemy
Uploaded cleaned dataset into SQL Server
6. SQL Analysis
Performed analytical queries such as:

Top-rated products
Customer segmentation (New, Returning, Loyal)
Purchase behavior analysis

📊 Dashboard / Insights
Key insights from the analysis include:

Identification of top-performing products based on customer ratings
Customer segmentation based on purchase behavior
Patterns in purchase frequency and spending

📈 Results
Clean and structured dataset ready for analysis
Improved data consistency and usability
Extracted actionable insights for business decision-making
