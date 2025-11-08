
# Shopify Sales Funnel Dashboard

![](https://github.com/subrata-dey7/shopify-sales-funnel-dashboard/blob/main/shopify_sales_funnel_dashboard.png)

![](https://github.com/subrata-dey7/shopify-sales-funnel-dashboard/blob/main/shopify_sales_funnel_details_tab.png)

## **Executive Summary**:

This project presents a **Shopify Sales Funnel Dashboard** designed to monitor and evaluate **key performance indicators (KPIs)** related to **transaction performance, customer behavior, and regional sales distribution**. The objective was to develop a comprehensive visualization that provides business stakeholders with actionable insights into **sales trends, customer retention, and product performance.**

The analysis reveals total **net sales of $4.18 million** from **7,534 products sold**, averaging **$562.6 per order**. With **4,431 total customers**, about **46% are repeat buyers**, indicating a strong loyalty rate. The **average lifetime value (LTV)** per customer stands at **$943.6**, while **Shopify Payments** dominate the payment gateway landscape, accounting for **58.45%** of transactions.

This report documents the dashboard’s analytical process, visualizations, findings, and business implications, concluding with strategic recommendations to further enhance Shopify sales and customer engagement.

## **Table of Contents**:

    1. Introduction    
    2. Objectives and Scope  
    3. Data Description
    4. Methodology
    5. Analysis and Visualisations
    6. Insights and Interpretation
    7. Recommendations
    8. Conclusion
    9. References
    10. License

### 1. Introduction

In today’s digital e-commerce ecosystem, tracking customer behavior and sales funnel efficiency is vital to improving profitability and marketing effectiveness. This project focuses on developing a Shopify Sales Funnel Dashboard to analyze sales performance, regional demand, payment methods, and customer loyalty metrics.

The motivation behind this project was to enable data-driven decision-making for sales strategies, customer retention, and channel optimization in a competitive e-commerce environment.


### 2. Objectives and Scope

🔹 **Objectives:**

- To visualize key Shopify sales KPIs in a single, interactive dashboard.
- To analyze transaction performance, customer purchase behavior, and regional trends.
- To identify top-performing regions, products, and payment methods.
- To measure customer loyalty using repeat rate and purchase frequency.

🔹 **Scope:**

The analysis covers:

- Shopify transaction data including sales, quantities, and order values.
- Customer segmentation between single-order and repeat buyers.
- Payment gateway distribution and product-type performance.
- Geographic sales distribution across U.S. cities and provinces.

### 3. Data Description

The data was sourced from Shopify’s sales records, aggregated and processed for visualization.

🔹 **Key attributes include:**

- **Transaction Data:** Net Sales, Total Quantity, Net Average Order Value.
- **Customer Data:** Total Customers, Repeat Customers, Single-Order Customers.
- **Geographic Data:** Provinces, Cities, and Sales Volume.
- **Payment Gateway Data:** Shopify Payments, PayPal, Gift Cards, Amazon Payments, and Manual Entries.
- **Product Data:** Product Categories (Running Shoes, Tennis Shoes, Wallets, etc.)

🔹 **Initial exploration showed:**

- **46%** repeat customer rate.
- Average order value: **$562.6**.
- Shopify Payments: **58.45%** of total sales.

### 4. Methodology

The analytical process involved:

**A) Data Cleaning & Preparation:**

- Removal of duplicates and incomplete records.
- Standardization of monetary values and time formats.

**B) Data Transformation:**

- Aggregated sales by city, province, and product category.
- Categorized customer types (single vs. repeat).
- Grouped payment data by gateway type.

**C) Visualization Development:**

The dashboard was created using **Power BI**, integrating multiple visuals:

- Time series line chart (Net Sales Trend).
- Donut chart (Payment Method Share).
- Bar charts (Sales by City, Product Type).
- Map visualization (Regional Distribution).

### 5. Analysis and Visualisations

**A) Transaction Performance:**

- **Net Sales:** $4,180,874
- **Total Quantity:** 7,534 units
- **Average Order Value:** $562.6

These figures suggest a strong average sales performance per order, indicative of a premium pricing strategy.

**B) Customer Purchase Behavior:**

- **Total Customers:** 4,431
  - **Single-Order Customers:** 2,392 (≈54%)
  - **Repeat Customers:** 2,039 (≈46%)

- **Purchase Frequency:** 1.68 times per customer.

The high proportion of repeat customers signifies effective retention and satisfaction strategies.

**C) Retention & Value KPIs:**

- **Lifetime Value (LTV):** $943.6 per customer
- **Repeat Rate:** 46%

Indicates sustained customer engagement and potential for loyalty program expansion.

**D) Sales Trends Over Time:**

- Peak sales reached **$683,843** during period 24.
- Lowest point recorded at **$525,711** during period 18.
- Sales fluctuated seasonally, possibly correlating with promotional cycles.

**E) Regional Overview:**

- *Top Regions by Net Sales:*

  1. Washington
  2. Houston
  3. New York City
  4. El Paso
  5. Dallas

These top 5 cities represent roughly 35% of total sales volume.
Strong coverage across the U.S. indicates a well-distributed market base.

**F) Net Sales by Gateway Payment Method:**

- **Shopify Payments:** $2,443,740 (58.45%)
- **Amazon Payments:** $736,864 (17.62%)
- **PayPal:** $681,230 (16.29%)
- **Manual:** $236,637 (5.66%)

Shopify Payments clearly dominate, suggesting seamless integration and user preference for the native gateway.

**G) Net Sales by Product Type:**

- **Running Shoes:** $1.5M (≈35.8%)
- **Tennis Shoes:** $0.9M (≈21.5%)
- **Wallets:** $0.6M (≈14.3%)
- **Cycling Shoes:** $0.5M (≈12%)

The footwear category drives the majority of revenue, making it a core business driver.

### 6. Insights and Interpretation

- The **high repeat rate (46%)** demonstrates strong brand loyalty and customer satisfaction.
- **Shopify Payments’** dominance (58%) underscores the convenience and trust customers associate with in-platform transactions.
- The **regional concentration** in large urban centers like Washington and Houston suggests targeting similar metropolitan markets for expansion.
- **Running and Tennis Shoes** account for over **57%** of total sales, suggesting demand focus on athletic products.
- Sales trends indicate potential for **seasonal marketing campaigns** to boost performance during off-peak months.

### 7. Recommendations  

- **Expand Loyalty Programs:**  

  With 46% repeat customers, enhancing loyalty incentives (points, referral bonuses) could lift LTV beyond $1,000.  

- **Leverage Top-Performing Payment Gateways:**

  Optimize promotions around Shopify Payments to further reduce transaction abandonment rates.

- **Regional Marketing:**

  Replicate successful campaigns from Washington and Houston in other high-potential metro areas.

- **Product Diversification:**

  Introduce variations in the top-performing categories (e.g., limited-edition running shoes).

- **Data-Driven Promotions:**

  Align seasonal discounts with low-performing periods (periods 19–21) to stabilize revenue flow.

### 8. Conclusion

The Shopify Sales Funnel Dashboard effectively consolidates critical e-commerce KPIs into a single analytical interface. The findings highlight strong revenue performance, significant customer retention, and dominant payment methods. Continued optimization around repeat customers and regional sales strategies can enhance growth and profitability.

### 9. References

- Shopify Analytics Documentation (Source - Internet).
- Internal Shopify weekly Sales Data (Source - Internet)
- Power BI Visualization Guides

- **Tools used:**
    - 🧮 Excel - used as it provides easy-to-use tools for organizing, calculating, visualizing, and interpreting data.
    - 📊 Power BI Desktop - Main data visualization platform used for report creation.
    - 📂 Power Query - Data transformation and cleaning layer for reshaping and preparing the data.
    - 🧠 DAX (Data Analysis Expressions) - Used for calculated measures, dynamic visuals, and conditional logic.
    - 📝 Data Modeling - Relationships established among tables to enable cross-filtering and aggregation.
    - 📁 File Format - .pbix for development and .png for dashboard previews.


### 10. 📜 License

This project is open source and free to use for educational purposes.


🎉🎉 Thank you for checking out the - “Shopify Sales Funnel Dashboard” project !!!
