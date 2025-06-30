# SQL Project: Restaurant Order Analysis

## Project Overview

This project involves an in-depth analysis of a restaurant's order database. The primary goal is to use SQL to query the data and uncover key insights related to menu performance, customer ordering patterns, and operational trends. The findings from this analysis are then used to provide data-driven recommendations that can help the restaurant optimize its operations and improve profitability.

---

## Data Source

The dataset consists of two main tables:
* **`menu_items`**: Contains information about each menu item, including its name, category, and price.
* **`order_details`**: Contains transactional data, including order IDs, timestamps, and the specific menu items included in each order.

### Entity Relationship Diagram (ERD)
![ERD](https://github.com/user-attachments/assets/112eac84-7f03-4d06-a074-ced6c70f6561)

---

## Tools Used
* **SQL (MySQL Workbench)**: For data querying, analysis, and manipulation.

---

## Analysis Process

The analysis was conducted by writing a series of SQL queries to answer specific business questions. The process was structured into three main parts:

1.  **Menu Analysis**: Understanding the composition, price, and categories of all items on the menu.
2.  **Order Analysis**: Analyzing the volume and trends of orders over time to identify peak periods.
3.  **Sales Performance Analysis**: Joining menu and order data to identify best-selling items and overall customer purchasing behavior.

---

## Key Questions Addressed

1.  What is the total number of items available on the menu?
2.  What are the least and most expensive items on the menu?
3.  How many orders were placed in total?
4.  Which menu items were ordered the most and least frequently?
5.  What were the total orders placed for each category?
6.  What were the peak dining hours for the restaurant?
7.  What was the average number of items per order?

---

## Key Findings

* The restaurant's menu consists of **122 unique items**.
* The price of menu items ranges from **$1.99 to $29.99**.
* A total of **12,234 orders** were analyzed.
* The most frequently ordered item was **'edamame'**, while the least ordered items were **'house salad'** and **'french fries'**.
* The **'Italian'** category had the highest number of orders.
* The peak dining hours were between **12:00 PM - 1:00 PM** and **5:00 PM - 7:00 PM**.
* On average, each order contained **2.7 items**.

---

## Recommendations

Based on the analysis, the following recommendations were provided:

* **Menu Optimization**: Highlight and promote popular items from the 'Italian' category. Consider re-evaluating or creating special promotions for the least popular items like 'house salad' and 'french fries' to boost their sales.
* **Staffing & Operations**: Adjust staff schedules to ensure adequate coverage during the identified peak hours (12-1 PM and 5-7 PM) to improve service speed and customer satisfaction.
* **Marketing Strategy**: Create targeted marketing campaigns, such as lunch specials, to further capitalize on the high volume of orders during the midday peak.
