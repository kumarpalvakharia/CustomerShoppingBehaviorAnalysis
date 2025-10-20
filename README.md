# Customer Shopping Behavior Analysis & Dashboard
This project is an end-to-end data science analysis of customer shopping behavior. It follows a complete data pipeline, starting from data extraction, performing in-depth exploratory data analysis (EDA) and cleaning with Pandas, and culminating in a final interactive Power BI dashboard to visualize key business insights.

This project was developed as a comprehensive demonstration of skills in data analysis, data visualization, and business intelligence.

## 📊 Power BI Dashboard Preview
Here is a preview of the final interactive dashboard. The live .pbix file can be opened with Power BI Desktop.
<img width="1470" height="795" alt="image" src="https://github.com/user-attachments/assets/f86129da-7612-49e1-929d-8ebab554f7c8" />




## 💡 Key Features & Insights
The analysis and dashboard are designed to answer critical business questions:

Demographic Analysis: Which age groups and genders contribute the most to revenue?

Geographic Insights: What are the top-performing locations by sales?

Product Performance: Which product categories are most popular?

Behavioral Patterns: What is the average purchase value, and how does it vary by customer segment?

Seasonal Trends: Are there specific months or seasons that show peak sales?

## ⚙️ Tech Stack
Database: SQL (PostgreSQL)

Data Analysis: Python, Pandas, NumPy

Development: Jupyter Notebook

Data Visualization: Power BI, Matplotlib/Seaborn

## 📈 Project Workflow
This project follows a systematic 3-stage data analysis workflow:

1. Data Extraction (From .csv file)
The initial data was in csv file 

2. Data Cleaning & Analysis (Jupyter Notebook)
The core analysis is performed in the Customer_Shopping_Behavior_Analysis.ipynb notebook. This file includes:

Loading: The raw data (CSV) is loaded into a Pandas DataFrame.

Cleaning: Handling any missing values, correcting data types, and checking for duplicates.

Exploratory Data Analysis (EDA): Using Pandas and Matplotlib/Seaborn to generate descriptive statistics and visualize data distributions.

Feature Engineering: Creating new, insightful columns (e.g., Age Group, Price per Unit) to improve the analysis.

Exporting: Saving the final, clean dataset as a new database in postgre localhost , ready for visualization in PowerBI.

3. Dashboarding & Visualization (Power BI)
The final, clean dataset was imported into Power BI to create the customer_behavior_analysis.pbix dashboard. This dashboard provides an interactive and user-friendly interface to explore key business metrics, filter by different segments (like location or category), and derive actionable insights.

## 🚀 How to Use This Project
Clone the repository:

git clone https://github.com/kumarpalvakharia/CustomerShoppingBehaviorAnalysis.git
Review the Analysis:

Open and run the Customer_Shopping_Behavior_Analysis.ipynb in Jupyter Notebook or VS Code to see the full data cleaning and EDA process.

Interact with the Dashboard:

Ensure you have Power BI Desktop installed.

Open the customer_behavior_analysis.pbix file to explore the interactive dashboard.
