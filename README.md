# 📊 Amazon Sales Analysis Project

This project focuses on analyzing Amazon sales data to derive insights into product performance, customer segments, and sales trends. Using SQL for data manipulation and analysis, the project aims to answer key business questions and support decision-making through data-driven insights.

## 📚 Table of Contents
- [Project Overview](#project-overview)
- [Data Wrangling](#data-wrangling)
- [Feature Engineering](#feature-engineering)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Business Questions Answered](#business-questions-answered)
- [GitHub Repository](#github-repository)

## 📈 Project Overview
The project consists of three main analysis categories:
1. **Product Analysis**: Analyzing the performance of different product lines to identify which ones are performing well and which need improvement.
2. **Sales Analysis**: Analyzing the sales trends of products to evaluate the effectiveness of sales strategies.
3. **Customer Analysis**: Identifying different customer segments, their purchase trends, and profitability.

## 🛠️ Data Wrangling
The first step in the project is data wrangling, where we clean the data to handle missing or null values. The following steps were performed:
- **Build a database**: Created a database and inserted the data.
- **Handle NULL values**: No null values were found as all fields were set to NOT NULL during table creation.

## ⚙️ Feature Engineering
Feature engineering was performed to generate new columns for deeper insights:
- **Time of Day**: A new column `timeofday` was created to categorize sales into Morning, Afternoon, and Evening.
- **Day of Week**: A new column `dayname` was created to extract the day of the week for each transaction (Mon, Tue, etc.).
- **Month of Year**: A new column `monthname` was added to indicate the month of the year (Jan, Feb, etc.).

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to answer the business questions listed below. Visualizations and summary statistics were used to uncover insights.

## ❓ Business Questions Answered
1. What is the count of distinct cities in the dataset?
2. For each branch, what is the corresponding city?
3. What is the count of distinct product lines in the dataset?
4. Which payment method occurs most frequently?
5. Which product line has the highest sales?
6. How much revenue is generated each month?
7. In which month did the cost of goods sold reach its peak?
8. Which product line generated the highest revenue?
9. In which city was the highest revenue recorded?
10. Which product line incurred the highest Value Added Tax?
11. For each product line, add a column indicating "Good" if its sales are above average, otherwise "Bad."
12. Identify the branch that exceeded the average number of products sold.
13. Which product line is most frequently associated with each gender?
14. Calculate the average rating for each product line.
15. Count the sales occurrences for each time of day on every weekday.
16. Identify the customer type contributing the highest revenue.
17. Determine the city with the highest VAT percentage.
18. Identify the customer type with the highest VAT payments.
19. What is the count of distinct customer types in the dataset?
20. What is the count of distinct payment methods in the dataset?
21. Which customer type occurs most frequently?
22. Identify the customer type with the highest purchase frequency.
23. Determine the predominant gender among customers.
24. Examine the distribution of genders within each branch.
25. Identify the time of day when customers provide the most ratings.
26. Determine the time of day with the highest customer ratings for each branch.
27. Identify the day of the week with the highest average ratings.
28. Determine the day of the week with the highest average ratings for each branch.

## 📂 GitHub Repository
You can access the full code and dataset in the GitHub repository:

[GitHub Repository: Amazon Sales Analysis Project](https://github.com/SHAIK-07/Amazon-Sales-Analysis-Project-using-SQL.git)

