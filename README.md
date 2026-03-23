# Customer_Shopping_Behavior_Data_Analysis_SQL_PowerBI
## 📋 Project Overview
Built an interactive Customer Behavior Dashboard in Power BI.This project analyzes a customer transactions to identify key factors 
influencing customer behavior and revenue generation.It involves  SQL-based analysis to answer important business questions and
support data-driven decision-making.

# 📊 Dataset

**File:** `customer_shopping_behavior.csv`
The dataset contains 3,901 customer transaction records with the following features:

- **Customer ID**: Unique identifier for each customer
- **Age**: Customer age
- **Gender**: Customer gender (Male/Female)
- **Item Purchased**: Product name
- **Category**: Product category (Clothing, Footwear, etc.)
- **Purchase Amount (USD)**: Transaction amount in USD
- **Location**: Customer location (US states)
- **Size**: Product size (S, M, L, XL)
- **Color**: Product color
- **Season**: Season of purchase (Winter, Spring, Summer, Fall)
- **Review Rating**: Product review rating (1-5 scale)
- **Subscription Status**: Whether customer has a subscription (Yes/No)
- **Shipping Type**: Shipping method (Express, Standard, Free Shipping, Next Day Air)
- **Discount Applied**: Whether discount was applied (Yes/No)
- **Promo Code Used**: Whether promo code was used (Yes/No)
- **Previous Purchases**: Number of previous purchases
- **Payment Method**: Payment method used (Credit Card, PayPal, Venmo, Cash, etc.)
- **Frequency of Purchases**: Purchase frequency (Weekly, Fortnightly, Monthly, Quarterly, Annually)

  ## 🛠️ Technologies Used

- **MySQL** - Database management and SQL queries
- **Power BI** - Interactive dashboard for data visualization
  
### 2. SQL Analysis & Business Intelligence

The SQL analysis explores 10 key business questions:

#### Revenue Analysis
1. **Gender-based Revenue**: Total revenue comparison between male and female customers
2. **Discount Impact**: Identified high-value customers who used discounts but still spent above average

#### Product Performance
3. **Top-Rated Products**: Top 5 products with highest average review ratings
4. **Discount Usage by Product**: Products with highest discount usage percentage

#### Shipping & Logistics
5. **Shipping Cost Analysis**: Average purchase amounts for Standard vs. Express shipping

#### Customer Behavior
6. **Subscription Impact**: Average spend and total revenue comparison between subscribers and non-subscribers

#### Product Category Insights
7. **Top Products by Category**: Top 3 most purchased products within each category

#### Demographic Insights
8. **Age Group Revenue**: Revenue contribution analysis across different age groups

## � Interactive Dashboard

### Power BI Dashboard

An interactive Power BI dashboard (`Customer_Behavior_Dashboard.pbix`) visualizes key metrics and insights:

![Customer Behavior Dashboard](./dashboard.png)

### Running SQL Queries

Execute the queries in `Customer_Shopping_Behavior.sql` using:
- MySQL Workbench
- MySQL command line
- Any SQL client connected to your MySQL database

### Opening the Power BI Dashboard

1. **Install Power BI Desktop** (if not already installed)
   - Download from [Microsoft Power BI](https://powerbi.microsoft.com/desktop/)

2. **Open the Dashboard**:
   - Double-click `Customer_Behavior_Dashboard.pbix`
   - Or open Power BI Desktop and select File → Open → Browse to the file

3. **Interact with the Dashboard**:
   - Use filters on the left panel to segment data
   - Hover over visualizations for detailed tooltips
   - Click on chart elements to cross-filter other visuals
     
### Database & SQL Work
- Loaded cleaned data into MySQL database
- Performed analysis using SQL:
- Aggregations (SUM, AVG)
- Group By, Joins
- Subqueries for advanced filtering
- Answered key business questions like:
- Revenue by gender
- Impact of discounts
- Top-rated products

### Dashboard Development (Power BI)
## Created KPI cards:
- Total Customers
- Average Purchase Amount
- Average Review Rating
## Built visualizations:
- Revenue by Category (Bar Chart)
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Status Distribution (Donut Chart)
### Filters / Interactivity
## Added slicers for:
- Gender
- Subscription Status
- Product Category
- Shipping Type
- Enabled dynamic filtering and cross-filtering across visuals
## 🚀 Key Insights
The analysis showed that the Clothing category generates the highest revenue and sales, making it the top-performing segment.
Most customers are non-subscribers, while Young Adults contribute the most to overall revenue.
Discounts and shipping preferences significantly influence customer purchasing behavior and spending patterns.
