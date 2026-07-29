# Bangalore Restaurant Analytics Dashboard | Power BI

This project is a **business-focused restaurant analytics dashboard** built using **Power BI** and the Zomato Bangalore dataset. The goal of the project was to analyze restaurant performance, customer behavior, locality-level competition, and pricing patterns in Bangalore and convert raw data into actionable business insights.

## Project Overview

I cleaned and transformed the dataset in **Power Query**, created calculated columns and DAX measures in **Power BI**, and designed an interactive multi-page dashboard. The report helps answer questions such as:

* Which localities have the highest restaurant concentration?
* Which restaurants receive the most customer engagement?
* What cuisines are most popular among customers?
* How do ratings relate to votes and popularity?
* Which price segments perform best in Bangalore?

## Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* **Microsoft Excel**
* Data Visualization & Business Intelligence

## Data Preparation

The raw dataset contained duplicate restaurant records across cities and inconsistent categorical values. I performed several data-cleaning steps before building the dashboard:

* Filtered the dataset to **Bangalore only**
* Removed duplicate restaurant records where required
* Handled blank and null values
* Corrected data types for numeric and text fields
* Created a **Rating Group** column
* Created a **Price Segment** column (0–300, 300–500, 500–1000, 1000–2000, 2000–4000, 4000–6000, 6000+)

## Dashboard Pages

### 1. Executive Overview
<img width="1321" height="740" alt="image" src="https://github.com/user-attachments/assets/b8d78803-7f19-4646-bdfd-7a77a09f3d38" />


High-level KPIs including total restaurants, average rating, average cost for two, total votes, and cuisine coverage.

### 2. Business Performance
<img width="1318" height="739" alt="image" src="https://github.com/user-attachments/assets/9d070981-59fd-45b7-8842-2321f0243461" />


Analyzes top restaurants by votes and ratings and explores the relationship between customer ratings and engagement.

### 3. Market Analysis
<img width="1313" height="737" alt="image" src="https://github.com/user-attachments/assets/1888d996-e70c-48d8-9923-e4f9c03b9335" />


Compares Bangalore localities using restaurant count, average rating, and opportunity analysis to identify competitive and growth areas.

### 4. Customer Insights
<img width="1315" height="737" alt="image" src="https://github.com/user-attachments/assets/b394855f-7473-4e69-af93-1ff66e279c24" />


Examines customer preferences, online ordering behavior, table booking impact, cuisine popularity, and engagement patterns.

### 5. Pricing Analysis
<img width="1309" height="738" alt="image" src="https://github.com/user-attachments/assets/4bd8f5d7-55e2-4160-a401-0de6ee2b34b5" />


Studies restaurant distribution across price ranges and the relationship between cost, ratings, and customer votes.

## Key DAX Measures

Examples of measures used in the report:

* Total Restaurants (Distinct Count)
* Average Rating
* Average Votes per Restaurant
* Online Order %
* Table Booking %
* Highest Rated Locality
* Most Competitive Locality

## Key Insights
<img width="1311" height="738" alt="image" src="https://github.com/user-attachments/assets/b03a7b5a-6c24-4b33-9ac3-199c2f17223d" />


* Bangalore contains **8.7K+ restaurants**, indicating a highly competitive food market.
* Restaurants rated **3–4 stars form the largest segment** of the market.
* Premium restaurants generally receive **higher ratings and customer engagement**.
* Localities such as **BTM and Koramangala** show strong restaurant concentration and customer activity.
* Online ordering represents a significant share of restaurant availability, highlighting strong delivery demand.

## What I Learned

Through this project I practiced:

* End-to-end data cleaning in Power Query
* Data modeling in Power BI
* Writing DAX measures and calculated columns
* Building interactive dashboards with slicers and navigation
* Designing business-oriented visualizations
* Converting analytical findings into executive insights

## Files Included

* 'zomato_business_intelligence_dashboard.pbix'

## Dataset

Public Zomato restaurant dataset from Kaggle (Bangalore subset used for analysis).
'https://www.kaggle.com/datasets/rajeshrampure/zomato-dataset'

## Author

**Abhishek Kumar**

Aspiring Data Analyst | Power BI | SQL | Excel
