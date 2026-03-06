# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across different product categories.  
The objective is to identify spending patterns, customer segments, and product preferences to support business decision-making.

## Dataset
- Total Records: 3,900
- Columns: 18

### Key Features
Customer Demographics:
- Age
- Gender
- Location
- Subscription Status

Purchase Details:
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color

Shopping Behavior:
- Discount Applied
- Promo Code Used
- Previous Purchases
- Purchase Frequency
- Review Rating
- Shipping Type

## Data Preprocessing (Python)
- Loaded dataset using pandas
- Checked structure using df.info() and df.describe()
- Handled missing values in Review Rating
- Standardized column names
- Created new features like age_group
- Removed redundant columns
- Loaded cleaned data into PostgreSQL

## SQL Analysis
Key business questions answered using SQL:
- Revenue by gender
- High spending customers using discounts
- Top 5 products by rating
- Shipping type comparison
- Subscribers vs non-subscribers spending
- Discount dependent products
- Customer segmentation (New, Returning, Loyal)
- Top products per category
- Repeat buyers vs subscription status
- Revenue by age group

## Power BI Dashboard
Created an interactive dashboard to visualize insights.

Dashboard Highlights:
- Total Customers: 3.9K
- Average Purchase Amount: $59.76
- Average Review Rating: 3.75

Visualizations include:
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Distribution

## Key Insights
- Clothing category generated the highest revenue.
- Loyal customers form the largest customer segment.
- Express shipping customers tend to spend slightly more.
- Some products depend heavily on discount purchases.

## Business Recommendations
- Promote subscription benefits
- Introduce loyalty programs
- Optimize discount strategy
- Target high revenue customer segments

## Tools Used
- Python
- Pandas
- PostgreSQL
- SQL
- Power BI
