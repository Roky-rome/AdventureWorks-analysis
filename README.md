# AdventureWorks-analysis

## Project Overview

This project presents an interactive **Power BI analysis of the AdventureWorks dataset**, sourced from **Kaggle**.

The analysis focuses on sales performance, profitability, product categories, customer behavior, product characteristics, order trends, and revenue growth.

The objective of the project is to transform raw business data into meaningful insights that can support **sales strategy, product management, customer targeting, and profitability improvement**.

---

## Dataset

The project uses the **AdventureWorks dataset**, a widely used sample dataset for business intelligence and data analytics projects.

The dataset contains information relating to:

* Sales
* Products
* Product categories
* Customers
* Employees
* Orders
* Costs
* Revenue
* Profit
* Product attributes
* Customer occupations

The dataset was sourced from **Kaggle** and analyzed using Microsoft Power BI.

---

# Tools & Technologies

### Data Analysis & Visualization

* **Microsoft Power BI**
* **Power Query**
* **DAX**

### Data Source

* AdventureWorks Dataset
* Kaggle

### Version Control

* Git
* GitHub

---

# Dashboard Overview

The Power BI report consists of two main analytical pages:

1. **Executive Summary**
2. **Detailed Insights**

The dashboard provides both a high-level view of business performance and a more detailed analysis of sales, customers, products, and monthly trends.

---

# Executive Summary

The Executive Summary provides an overview of the overall financial performance of the business.

### Key Performance Indicators

| KPI                    |      Result |
| ---------------------- | ----------: |
| **Total Revenue**      | **$24.91M** |
| **Total Profit**       | **$10.46M** |
| **Profit Margin**      |  **41.97%** |
| **Revenue YoY Growth** |  **58.40%** |

### Key Insight

The business generated **$24.91 million in revenue** and **$10.46 million in profit**, resulting in a strong **41.97% profit margin**.

The reported **58.40% year-over-year revenue growth** indicates significant expansion in sales performance.

This suggests that the business has a strong revenue-generating model and is converting a substantial proportion of its sales into profit.

---

# Revenue Trend

The Executive Summary shows a strong increase in revenue from **2015 to 2016**, followed by a slight stabilization in 2017.

### Key Insight

* Revenue increased significantly between **2015 and 2016**.
* Performance remained relatively stable between **2016 and 2017**.
* The rapid growth followed by stabilization suggests that the business experienced a major expansion phase before entering a more mature period.

### Business Implication

The business should investigate what drove the strong 2015–2016 growth and determine whether those factors can be replicated.

Potential drivers could include:

* Product demand
* Increased customer acquisition
* Strong-performing product categories
* Pricing strategy
* Market expansion
* Increased order volumes

---

# Revenue by Product Category

The dashboard shows a significant difference in revenue contribution across product categories.

### Key Finding

**Bikes are by far the dominant revenue-generating category.**

The other categories, including:

* Accessories
* Clothing

contribute substantially less revenue compared with Bikes.

### Business Implication

The business is highly dependent on the Bikes category for revenue generation.

This creates both an **opportunity and a risk**.

The opportunity is to continue investing in the strongest category.

The risk is that excessive dependence on one category could make overall revenue vulnerable to changes in customer demand, pricing, competition, or supply.

---

# Profit by Product Category

The profit analysis follows a similar pattern to revenue.

**Bikes generate the largest share of total profit.**

This indicates that Bikes are not only the highest-revenue category but also the primary contributor to the company's profitability.

### Key Insight

The strong performance of Bikes suggests that resources such as:

* Inventory
* Marketing
* Product development
* Sales promotions
* Customer engagement

should be carefully aligned with the performance of this category.

However, lower-performing categories should also be assessed to determine whether they can be improved rather than immediately discontinued.

---

# Cost Analysis

The dashboard reports:

### **Total Cost: $14.46M**

Compared with total revenue of **$24.91M**, the business maintains a strong overall profit position.

### Key Insight

The difference between revenue and cost produces approximately **$10.46M in profit**, supporting the reported **41.97% profit margin**.

This indicates relatively strong cost efficiency at the overall business level.

---

# Detailed Sales Insights

The Detailed Insights page provides a closer look at sales volume and order activity.

### Key Performance Indicators

| KPI                     |      Result |
| ----------------------- | ----------: |
| **Total Quantity Sold** |  **84,174** |
| **Total Orders**        |  **56,046** |
| **Total Cost**          | **$14.46M** |
| **Revenue YTD**         |  **$9.19M** |

---

# Orders & Quantity Sold by Month

The monthly trend shows that orders and quantity sold generally follow a similar pattern.

### Key Finding

Sales activity:

* Starts relatively strong at the beginning of the year
* Increases toward May and June
* Experiences a **significant drop in July**
* Recovers from August onward
* Ends the year with a strong increase in December

### Important Observation

The sharp July decline represents a potential **seasonality or operational issue** that deserves further investigation.

The strong December performance suggests increased demand toward the end of the year.

### Business Implication

The company could use historical seasonality to improve:

* Inventory planning
* Marketing campaigns
* Staffing
* Promotional timing
* Production planning

For example, inventory and marketing resources could be increased ahead of the stronger May–June and December periods.

---

# Monthly Revenue Performance

The monthly revenue comparison between the current and previous year shows stronger performance during the first half of the year.

Revenue increases from January through June before dropping around July and remaining relatively lower through the middle of the second half.

December shows a strong recovery.

### Key Insight

The business appears to experience meaningful seasonal variation.

The strongest opportunity appears to be around:

* May
* June
* December

while July requires particular attention.

---

# Product Color Analysis

The dashboard provides a breakdown of quantity sold by product color.

### Quantity Distribution

| Product Color | Share of Quantity Sold |
| ------------- | ---------------------: |
| **NA**        |             **60.68%** |
| **Black**     |             **12.58%** |
| **Multi**     |              **6.84%** |
| **Yellow**    |              **5.51%** |
| **Red**       |              **4.77%** |
| **Blue**      |              **4.49%** |
| **Silver**    |              **3.87%** |

### Key Insight

The **NA category represents 60.68% of total quantity sold**, making it significantly larger than every other color category.

Black is the second-largest category at **12.58%**.

### Business Implication

The unusually large NA share should be investigated.

It may indicate:

* Products where color is not applicable
* Missing product attribute information
* Product categories where color is not relevant
* Data quality issues

Improving product attribute completeness could provide more useful insights into customer preferences.

---

# Customer Performance Analysis

The dashboard analyzes customers by occupation.

| Occupation         |     Orders | Quantity Sold |            Revenue | Profit Margin |
| ------------------ | ---------: | ------------: | -----------------: | ------------: |
| **Clerical**       |      8,850 |        13,090 |      $3,988,370.84 |        41.52% |
| **Management**     |      9,791 |        14,688 |      $4,624,925.95 |        42.24% |
| **Manual**         |      6,509 |         9,993 |      $2,464,077.51 |        41.74% |
| **Professional**   | **17,756** |    **26,622** |  **$8,466,167.76** |        42.18% |
| **Skilled Manual** |     13,140 |        19,781 |      $5,371,044.91 |        41.86% |
| **Total**          | **56,046** |    **84,174** | **$24,914,586.98** |    **41.97%** |

---

# Customer Segment Insights

### Professional Customers

Professional customers are the strongest customer segment in the dashboard.

They account for:

* **17,756 orders**
* **26,622 units sold**
* **$8.47M revenue**
* **42.18% profit margin**

### Key Insight

The Professional segment generates the highest revenue, order volume, and quantity sold among the occupations analyzed.

This makes the segment particularly important for customer retention and targeted marketing.

---

### Skilled Manual Customers

Skilled Manual customers are the second strongest segment by revenue.

They generated:

**$5.37M revenue**

with:

* 13,140 orders
* 19,781 units sold
* 41.86% profit margin

This represents another valuable customer segment.

---

### Management Customers

Management customers generated:

**$4.62M revenue**

and achieved the highest profit margin among the occupation groups:

**42.24%**

Although their revenue is lower than the Professional segment, their slightly higher margin indicates strong profitability.

---

### Clerical Customers

Clerical customers generated:

**$3.99M revenue**

with a **41.52% profit margin**.

The segment is profitable but has a slightly lower margin than Management and Professional customers.

---

### Manual Customers

Manual customers generated:

**$2.46M revenue**

with:

* 6,509 orders
* 9,993 units sold
* 41.74% profit margin

This is the smallest segment by revenue and order volume among the occupations shown.

---

# Overall Key Insights

Based on the dashboard analysis, several important findings emerge.

### 1. Strong Overall Profitability

The company generated:

**$24.91M revenue**

and

**$10.46M profit**

with a **41.97% profit margin**.

This indicates strong overall financial performance.

---

### 2. Significant Revenue Growth

The dashboard reports **58.40% YoY revenue growth**, indicating strong business expansion.

---

### 3. Bikes Drive the Business

Bikes dominate:

* Revenue
* Profit
* Category performance

This makes Bikes the core business category.

---

### 4. Professional Customers Are the Most Valuable Segment

Professional customers generate the highest:

* Orders
* Quantity sold
* Revenue

They should therefore be a major focus of customer retention and targeted marketing initiatives.

---

### 5. Sales Show Seasonal Patterns

Sales activity peaks around **May–June** and **December**, while July experiences a substantial decline.

This suggests an opportunity for more effective seasonal planning.

---

### 6. Product Attribute Data Needs Attention

The **NA product color category accounts for 60.68%** of quantity sold.

This may represent legitimate non-color products, but it could also indicate incomplete product information.

Improving data quality would make product preference analysis more reliable.

---

# Business Recommendations

## 1. Protect and Expand the Bikes Category

Since Bikes generate the majority of revenue and profit, the company should prioritize the category through:

* Inventory availability
* Targeted marketing
* Product innovation
* Competitive pricing
* Customer loyalty programs
* Cross-selling opportunities

However, the company should avoid excessive dependence on Bikes by gradually developing other profitable categories.

---

## 2. Develop Accessories and Clothing

Accessories and Clothing contribute considerably less revenue than Bikes.

Instead of treating these categories simply as underperformers, the company should investigate opportunities to increase their contribution.

For example:

* Bundle accessories with bike purchases
* Offer discounts on complementary products
* Create bike-and-accessory packages
* Use cross-selling recommendations
* Develop targeted campaigns

This could increase **average order value** while diversifying revenue.

---

## 3. Target Professional Customers

Professional customers are the highest-value occupation segment based on the dashboard.

The company should develop targeted strategies such as:

* Personalized promotions
* Loyalty programs
* Premium product recommendations
* Corporate or professional customer offers
* Retention campaigns

The goal should be to increase both customer lifetime value and repeat purchases.

---

## 4. Investigate the July Sales Drop

The significant July decline in orders and quantity sold should be investigated.

Management should determine whether the decline is caused by:

* Seasonality
* Inventory shortages
* Pricing
* Marketing activity
* Product availability
* Operational disruptions
* Customer demand patterns

Understanding the cause would allow the company to take corrective action before future July periods.

---

## 5. Prepare for High-Demand Periods

The strong performance around May–June and December suggests that the company should plan ahead for these periods.

Recommended actions include:

* Increase inventory before peak periods
* Launch promotional campaigns early
* Optimize staffing
* Strengthen supply-chain planning
* Increase digital marketing activity
* Prepare targeted offers for high-value customer segments

---

## 6. Improve Product Data Quality

The large **60.68% NA product-color share** should be investigated.

The company should review its product master data and determine whether the NA values represent:

* Missing data
* Products without applicable colors
* Incorrect categorization

Better product data would improve future customer preference and product-performance analysis.

---

## 7. Diversify Revenue Sources

Because Bikes dominate the business, the company should gradually increase the contribution of other categories.

A diversified product portfolio can reduce the risk associated with relying heavily on one category.

Accessories are particularly attractive because they can be marketed as complementary purchases to Bikes.

---

# Recommended Business Strategy

Based on the analysis, the recommended strategy is:

> **Protect the core Bikes business while increasing customer value through targeted Professional-segment marketing, cross-selling Accessories, improving product data quality, and using seasonal demand patterns to optimize inventory and promotional planning.**

This approach balances **revenue growth, profitability, customer retention, and risk diversification**.

---

# Expected Business Impact

Implementing these recommendations could potentially help the business:

* Increase revenue
* Improve customer retention
* Increase average order value
* Improve cross-selling
* Reduce dependence on Bikes
* Improve inventory planning
* Strengthen customer targeting
* Reduce seasonal performance gaps
* Improve product data quality
* Support better strategic decision-making

---

# Dashboard Summary

| Area                            | Key Finding                     |
| ------------------------------- | ------------------------------- |
| **Revenue**                     | $24.91M                         |
| **Profit**                      | $10.46M                         |
| **Profit Margin**               | 41.97%                          |
| **Revenue YoY Growth**          | 58.40%                          |
| **Orders**                      | 56,046                          |
| **Quantity Sold**               | 84,174                          |
| **Total Cost**                  | $14.46M                         |
| **Revenue YTD**                 | $9.19M                          |
| **Top Category**                | Bikes                           |
| **Top Customer Segment**        | Professional                    |
| **Top Customer Revenue**        | $8.47M                          |
| **Highest Occupation Margin**   | Management — 42.24%             |
| **Largest Product Color Share** | NA — 60.68%                     |
| **Notable Sales Pattern**       | July decline; December recovery |

---

# Skills Demonstrated

This project demonstrates practical experience in:

* Data Cleaning
* Data Transformation
* Data Modeling
* Data Analysis
* Business Intelligence
* Power BI
* Power Query
* DAX
* KPI Development
* Data Visualization
* Customer Segmentation
* Sales Analysis
* Profitability Analysis
* Business Reporting
* Business Recommendation Development

---

# Future Improvements

Future versions of the analysis could include:

* Customer Lifetime Value (CLV)
* RFM Customer Segmentation
* Customer Retention Analysis
* Sales Forecasting
* Product-level profitability
* Regional sales analysis
* Customer churn prediction
* Basket analysis
* Advanced product cross-selling analysis
* Seasonal demand forecasting
* Predictive analytics using Python
* Machine learning models

---

# Data Source

**Dataset:** AdventureWorks Dataset
**Source:** Kaggle
**Category:** E-Commerce / Sales / Business Intelligence

The dataset was used to demonstrate practical data analysis and business intelligence techniques using Power BI.

---

# Author

## Roky-Rome

This project forms part of my **data analytics portfolio**, demonstrating my ability to transform business data into actionable insights.

The project follows the analytical process:

**Raw Data → Data Cleaning → Data Modeling → Analysis → Visualization → Insights → Business Recommendations**

---

# Project Status

**Status: Completed — Power BI Sales Analysis**

The project demonstrates an end-to-end business intelligence workflow using the AdventureWorks dataset.

---
