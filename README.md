# Project Title: Amazon_Product_Review_Project
This repository documents the process and steps take on build the DSA Captone project on Excel, Amazon Product Review.

### Project Topic: Amazon Project Review

### Project Overview
This data analysis project aims at analysing product and customer review data to generate insights that can 
guide product improvement, marketing strategies, and customer engagement. As Data Analyst at RetailTech Insights, we have been tasked with carrying out Exploratory Data Analysis on the given data set.

### Data Sources
The primary source of Data used is Amazon Product Review.xlsx and this is a data that can be easily sourced from an open surce online from Kaggle among others.

<img src="Microsoft Excel Image.jpg" />

Microoft Excel

- MS Excel for Data Cleaning [Download Here](https://www.microsoft.com)
  - For Data Collection
  - For Data Cleaning
     1. Data Manipulaton
     2. Data Munching

### Data Cleaning and Preparation
At the preliminary stage of this, I performed Data Cleaning and Preparations. These include: 
1.	Data loading and Inspection,
2.	Data Cleaning and Formatting.

### Questions KPI
This involves x-raying the analytic questions and providing answers to the questions sch as:
 
1. What is the average discount percentage by product category? 
2. How many products are listed under each category? 
3. What is the total number of reviews per category? 
4. Which products have the highest average ratings? 
5. What is the average actual price vs the discounted price by category? 
6. Which products have the highest number of reviews? 
7. How many products have a discount of 50% or more? 
8. What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)? 
9. What is the total potential revenue (actual_price × rating_count) by category? 
10. What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)?11. How does the rating relate to the level of discount? 
12. How many products have fewer than 1,000 reviews? 
13. Which categories have products with the highest discounts? 
14. Identify the top 5 products in terms of rating and number of reviews combined

### Mode of Answer Delivery: 
Each question is raised, the formular used and pictorial output is provided.


#### 1. What is the average discount percentage by product category?

<img src="Average Discount Percentage.png" />

From the table given, I took the following steps to calculate discount percentage column:
-	Insert new column after discounted price.
-	Type out the function shown below:

``` Excel
=(Actual Price - Discounted Price)/Actual Price * 100

```

### 2. How many products are listed under each category? 

<img src="Number of Products.png" />

From the Pivot table, supply:

``` Excel
-	Row: Category 4
-	 Values: Product name (Distinct Count) 

```

### 3. What is the total number of reviews per category? 

<img src="Sum of Reviews.png" />

From the Pivot table, supply:

``` Excel
-	Row: Category 4
-	Values: Rating Count (Sum)

```

### 4. Which products have the highest average ratings? 

The Rating Column was sorted by Average. It was also arranged in descending order. The top entries are as shown in the image below.

<img src="Product With Highest Average Rating.png" />

### 5. What is the average actual price vs the discounted price by category? 

<img src="Actual Prive VS Discounted Price.png" />

From the Pivot table, supply:

``` Excel
-	Row: Category 4
-	Values: Actual Price (Average), Discounted Price (Average)

```

### 6. Which products have the highest number of reviews? 

The Rating Coun Column was sorted. It was also arranged in descending order. The top entry is as shown in the image below.

<img src="Product With Highest Number of Reviews.png" />


