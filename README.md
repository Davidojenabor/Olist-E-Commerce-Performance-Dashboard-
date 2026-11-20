# Olist E-Commerce Performance Analysis | Power BI

## Project Overview

This project focuses on analyzing the operational and commercial performance of Olist, a Brazilian e-commerce marketplace, using Power BI, DAX, and MySQL.

The objective was to transform raw e-commerce data into an interactive business intelligence dashboard that provides visibility into revenue performance, order trends, geographical sales distribution, order fulfilment, and customer satisfaction.

The analysis helps stakeholders understand business performance, identify high-performing regions, monitor order cancellations, and evaluate customer experience through review scores.

## Business Problem

E-commerce businesses generate large volumes of transactional data, but without proper analysis, identifying performance trends and operational weaknesses becomes difficult.

Olist needed a consolidated view of its business performance to understand:

- How revenue performed over time.
- Which geographical regions contributed the most to revenue.
- How orders were distributed across different fulfilment statuses.
- What proportion of orders were cancelled.
- How customers rated their purchasing experience.

This project addresses these questions through structured data modelling, analytical calculations, and interactive Power BI visualizations.

## Business Questions

The analysis was designed to answer the following questions:

1. What is the total revenue generated across the business?
2. How many orders were placed during the analysis period?
3. What is the average order value?
4. How did revenue trend between 2016 and 2018?
5. Which Brazilian states generated the highest revenue?
6. How are orders distributed across different order statuses?
7. What percentage of orders were cancelled?
8. What is the average customer review score?

## Tools & Technologies

| Tool | Application |
|---|---|
| MySQL | Data querying and extraction |
| Power BI | Dashboard development and visualization |
| DAX | Measures and business KPI calculations |
| Power Query | Data transformation and preparation |
| Data Modelling | Star schema design |
| Date Table | Time-based analysis |

## Data Modelling

The project uses a Star Schema approach to organize the e-commerce data for analytical reporting.

A custom Date table was created to support time-based analysis and improve the calculation of historical performance metrics.

The model was designed to support efficient filtering, aggregation, and reporting across relevant business dimensions.

## Key Performance Indicators (KPIs)

The dashboard tracks the following business metrics:

| KPI | Result |
|---|---:|
| Total Revenue | 16.01M |
| Total Orders | 99K |
| Average Order Value | 160.99 |
| Cancellation Rate | 0.63% |
| Average Review Score | 4.09 |

## Dashboard Features

### 1. Revenue Performance
- Monitors revenue trends across 2016–2018.
- Provides visibility into changes in business performance over time.
- Supports historical revenue comparisons.

### 2. Geographical Revenue Analysis
- Ranks the top 10 Brazilian states by revenue.
- Identifies the strongest revenue-contributing geographical markets.
- Supports regional performance comparisons.

### 3. Order Status Analysis
- Tracks order distribution across different statuses.
- Provides visibility into delivered, shipped, cancelled, unavailable, and other order statuses.
- Helps monitor order fulfilment performance.

### 4. Customer Experience
- Tracks average customer review scores.
- Provides an overview of customer satisfaction.

### 5. Interactive Filtering
- Year slicer for filtering performance across different years.
- Order status slicer for exploring specific fulfilment categories.

## Key Findings

The analysis revealed the following:

- The business generated approximately 16.01M in total revenue across 99K orders.
- Average Order Value stood at 160.99.
- The cancellation rate was approximately 0.63%.
- The average customer review score was 4.09.
- São Paulo (SP) emerged as the leading revenue-generating state, significantly outperforming other states.
- The majority of orders were successfully delivered, accounting for approximately 96K orders.
- Revenue performance fluctuated throughout the 2016–2018 analysis period.

## Business Recommendations

Based on the dashboard findings:

1. **Regional Growth:** Investigate the factors driving São Paulo's revenue contribution and identify opportunities to strengthen performance in other states.
2. **Order Management:** Monitor cancelled and unavailable orders to identify potential fulfilment and operational issues.
3. **Revenue Monitoring:** Track historical revenue fluctuations to identify periods of growth and potential performance weaknesses.
4. **Customer Experience:** Monitor customer review scores and investigate the factors influencing lower-rated purchasing experiences.

## Technical Implementation

The project involved:

- Structuring analytical data using a star schema.
- Creating a custom Date table for time intelligence.
- Developing eight DAX measures to calculate business performance indicators.
- Building interactive Power BI visualizations.
- Implementing slicers for dynamic analysis across different business dimensions.


---

## 🔗 Connect With Me

- **LinkedIn:** [linkedin.com/in/davidojenabor](https://linkedin.com/in/davidojenabor)
- **GitHub:** [github.com/Davidojenabor](https://github.com/Davidojenabor)

---
## Dashboard Preview



![Olist Dashboard](Olist-Ecommerce-Performance-Dashboard.png)

