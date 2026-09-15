# E-Commerce Profitability Dashboard

## Project Overview

An interactive Power BI dashboard designed to analyze e-commerce
sales performance, customer behavior, product performance,
profitability, returns, and operational efficiency.

##  Business Objective

The objective of this project is to transform e-commerce transaction
data into actionable business insights by analyzing:

- Sales and revenue trends
- Customer segments and loyalty
- Product performance
- Contribution margin
- Returns and return losses
- Lost sales
- Fulfillment and delivery performance

##  Tools & Technologies

- Power BI
- Power Query
- DAX
- Microsoft Excel

##  Data Model

The project follows a dimensional/star-schema style model.

### Fact Table
- tblFactOrderLine

### Dimension Tables
- tblDimDate
- tblDimCustomer
- tblDimProduct
- tblDimGeography
- tblDimFulfillment
- tblDimPromotion
- tblDimReturnReason
- tblDimSalesChannel
- tblDimCohortAge

Relationships were created between the dimension tables and the
fact table to support interactive filtering and analysis.

## Dashboard Pages

### 1. Executive Overview

Provides a high-level view of:

- Total Revenue
- Total Orders
- Total Quantity
- Contribution Margin
- Contribution Margin %
- Return Rate
- Revenue trends
- Revenue by category
- Revenue by region

### 2. Sales Analysis

Analyzes:

- Monthly revenue trends
- Revenue by sales channel
- Revenue by region
- Revenue by product category
- Sales performance using interactive filters

### 3. Customer & Product Analysis

Analyzes:

- Customer segment performance
- Loyalty tier performance
- Top products by revenue
- Top products by contribution margin
- Customer cohort performance

### 4. Profitability & Returns

Analyzes:

- Contribution margin
- Contribution margin %
- Returns by reason
- Return loss
- Lost sales
- Fulfillment performance
- Average delivery days
- On-time delivery %

##  Key Business Insights

### Sales & Revenue

1. **Electronics revenue:** Electronics is the top-performing
   category, contributing approximately €0.2M in revenue.

2. **Western Europe dominance:** Western Europe leads regional sales,
   generating close to €200K in revenue.

3. **Revenue growth:** Revenue increased from approximately €0.2M in
   2024 to €0.4M in 2025, indicating strong year-over-year growth.

4. **Contribution margin:** The business generated approximately
   €128K in contribution margin, with a contribution margin of around
   20%.

5. **Return rate:** The return rate is approximately 10%, making
   returns an important area for further investigation.

### Customer & Product

6. **Loyal and Growth segments:** These customer segments are the
   strongest revenue contributors, each generating approximately
   €150K.

7. **At-Risk and Deal-Seeker segments:** These segments generate
   comparatively lower revenue, indicating opportunities for targeted
   re-engagement strategies.

8. **Loyalty opportunity:** Customers without a loyalty tier generate
   approximately €0.2M, suggesting an opportunity to convert these
   customers into loyalty-program members.

9. **Top revenue product:** Tech Audio Pro is the leading individual
   revenue-generating product, contributing approximately €30K.

10. **Top margin product:** Aura Haircare Elite generates the highest
    contribution margin at approximately €6K, demonstrating that
    high-revenue products are not necessarily the highest-margin
    products.

11. **Cohort performance:** Month 1 customers generate the highest
    revenue, while revenue declines across later cohorts, highlighting
    the importance of customer retention.

12. **Revenue concentration:** A relatively small number of products
    and customer segments contribute a significant share of revenue,
    creating an opportunity to diversify revenue sources.

##  Business Recommendations

- Strengthen retention strategies for Loyal and Growth customers.
- Investigate reasons for customer returns and identify products with
  unusually high return rates.
- Promote high-margin products alongside high-revenue products.
- Develop loyalty-program campaigns for customers without a loyalty
  tier.
- Explore growth opportunities in lower-performing regions.
- Use cross-selling and product-bundling strategies to increase
  average order value.
- Monitor fulfillment centers with weaker delivery performance.

## 📷 Dashboard Screenshots

Add screenshots of all four Power BI pages here.

##  Key KPIs

- Total Revenue
- Total Orders
- Total Quantity
- Contribution Margin
- Contribution Margin %
- Return Rate
- Return Loss
- Lost Sales
- Average Delivery Days
- On-Time Delivery %

##  Conclusion

The dashboard provides an interactive view of e-commerce performance
across sales, customers, products, profitability, returns, and
fulfillment operations. It demonstrates the use of data modeling,
DAX measures, interactive visualization, and business-oriented
analysis in Power BI.
