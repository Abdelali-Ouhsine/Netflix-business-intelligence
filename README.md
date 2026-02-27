# Create the README.md file using pypandoc
import pypandoc

readme_content = """
# 📊 Netflix Catalog Analysis – Data Analytics Project

## 📌 Project Context

As a Data Analyst working for a streaming platform, the objective of this project is to analyze the Netflix catalog to help management better understand:

- Content trends and performance  
- Distribution of Movies vs TV Shows  
- Production countries and genres  
- Age classification of content  
- Evolution of the catalog over time  

This project covers the full analytical workflow: exploration, cleaning, preparation, visualization, business insights, and dashboard creation.

Final deliverables:
- Complete analytical report using Python
- Interactive dashboard built with Power BI

---

## 🎯 Project Objectives

- Explore and analyze the Netflix dataset using Python and Pandas
- Produce clear visualizations with Matplotlib and Seaborn
- Answer key business questions
- Identify important catalog trends
- Prepare cleaned data for a Power BI dashboard

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Power BI  

---

## 📅 Project Information

- Work Method: Individual  
- Duration: 5 working days  
- Period: 02/23/2026 – 02/27/2026  

---

# 🗂 Project Stages

## 1️⃣ Data Exploration (EDA)

Objective: Understand the dataset before transformation.

Actions:
- Inspect structure and data types (info(), describe())
- Detect missing values (director, country, rating)
- Analyze distributions (movies vs series, genres, countries)
- Identify duplicates and anomalies
- Create initial visualizations (histograms, countplots, boxplots)

---

## 2️⃣ Data Cleaning & Preparation

Objective: Prepare a structured dataset for analysis and dashboard use.

Actions:
- Handle missing values (remove or replace with "Unknown")
- Remove duplicates
- Transform multi-value columns (country, listed_in)
- Create derived columns (year_added, month_added, duration)
- Standardize date and duration formats

---

## 3️⃣ Business Analysis & Visualizations

Key Questions:
- Distribution by age classification (rating)
- Proportion of Movies vs TV Shows (type)
- Number of contents added each year
- Evolution of the catalog over time
- Production count by country
- Most frequent genres

Visualizations:
- Bar charts
- Pie charts
- Line charts
- Heatmaps

---

## 4️⃣ Business Insights

- Identify top genres and countries
- Highlight dominant content types
- Provide executive summary with actionable insights

---

## 5️⃣ Power BI Dashboard

- Import cleaned dataset
- Apply Power Query transformations if needed
- Create interactive dashboard with filters (type, country, genre, year)
- Highlight KPIs for decision-making

---

##  🚀 Project Value

This project demonstrates:
- End-to-end data analytics workflow  
- Data cleaning and transformation skills  
- Business-oriented analytical thinking  
- Data visualization best practices  
- Dashboard storytelling and reporting  
"""
