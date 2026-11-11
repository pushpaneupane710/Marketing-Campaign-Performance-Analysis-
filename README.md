# Marketing-Campaign-Performance-Analysis

## Project Overview

This project analyze marketing campaign performance to identify which campaign and communication channel generate the strongest **sales*' results, particularly among **new customers.**

Using Power BI, I developed an interactive dashboard to compare campaign performance, evaluate channel contributions, examine customer conversion behaviour, and translate the findings into actionable business recommendations.

The objective is to help the marketing team make more informed decisions about where to focus future customer acquisition efforts.

## Business Question

**Which campaign + channel combination should the client double down on to grow new-customer sales — and why?**

## To reach Solution, we perform several calculations:

## 1. Dataset Description

The dataset contains **500 marketing interaction records** and the following seven columns:

| Column | Description |
|---|---|
| Interaction ID | Unique interaction identifier |
| Campaign Type | Campaign A or Campaign B |
| Channel | Marketing communication channel |
| Customer Type | New or Existing customer |
| Converted | Conversion indicator (1 = Yes, 0 = No) |
| Time on Site (seconds) | Time spent on the website |
| Sales ($) | Sales generated from the interaction |

## 2. Load and view dataset:

<img width="2052" height="590" alt="image" src="https://github.com/user-attachments/assets/bac41f2c-f863-435b-bf94-43807af2f659" />

## 3. Create a pivot table for existing customers + New customers, calculating sales for both campaign types and 3 different channels:

Pivot tables are a powerful way to summarize large datasets.

They let you group, filter, and compare results quickly without having to write formulas.

- Total Sales by Channel

- Total Sales by Campaign

<img width="2174" height="390" alt="image" src="https://github.com/user-attachments/assets/d53799db-6c38-4677-9721-37d7606f8a4e" />

**Insight:**

1. Email had the highest overall sales, making it the strongest performer in terms of revenue generation. It’s a reliable pick when ROI is a key concern.

2. Campaign B’s more promotional messaging style led to higher total sales, showing it was broadly effective across audiences.

3. When combining top-performing elements, Email + Campaign B stood out as the highest-revenue pairing — strong channel and strong message.

## 4. Filter the new_customers:
<img width="2052" height="516" alt="image" src="https://github.com/user-attachments/assets/58c589d5-b62c-450c-a366-e692a86f52db" />



## 5. Create pivot table for new_customers only and calculating sales for both campaign types and 3 different channels:
<img width="2270" height="430" alt="image" src="https://github.com/user-attachments/assets/e9e9c902-df7a-4db7-bcf5-fc8d4a4ec6dc" />



## Business Recommendation

**Prioritise Campaign A via Email to Drive New-Customer Growth.**

The analysis indicates that:

- Campaign A via Email generated the highest new-customer sales, totalling **$2,124.47**.
- It recorded **29 new-customer conversions**, the highest number among the campaign and channel combinations.
- Its new-customer conversion rate was **61.70%**.
- Campaign B via Email achieved a slightly higher conversion rate of **64.52%**, suggesting an opportunity to investigate its messaging and targeting.

### Recommended Actions

1. Prioritise Campaign A via Email when planning new-customer acquisition activities.
2. Investigate what makes Campaign B's Email conversion rate slightly higher.
3. Test improvements to Campaign B's messaging and targeting.
4. Monitor sales, conversions, conversion rates, and campaign costs before increasing marketing investment.

*Note: ROI cannot be established from this dataset because campaign expenditure and customer acquisition costs are not provided.*


## Key Performance Indicators (KPIs)

The dashboard tracks:

- Total Sales
- Total Interactions
- Total Conversions
- Conversion Rate
- Average Time on Site
- Sales per Interaction

## Analysis Performed

The analysis focuses on:

- Overall marketing campaign performance.
- Sales performance by campaign and channel.
- New versus existing customer behaviour.
- Conversion rates across campaigns and channels.
- Channel contributions to total sales.
- Campaign and channel combinations with the strongest new-customer sales.

## Tools and Technologies

- **Power BI Desktop** – Interactive dashboard development and visualisation.
- **DAX** – KPI calculations and measures.
- **Power Query** – Data preparation and transformation.
- **Python(library Pandas)** – Dataset inspection and initial exploration.

## Dashboard Features

- KPI cards for monitoring campaign performance.
- Interactive customer-type slicer.
- Clustered column charts for campaign comparisons.
- Stacked column charts for channel contribution analysis.
- Campaign performance matrix with conditional formatting.
- Dynamic business recommendation based on sales performance.

## Project Deliverables

- Interactive Power BI report (`.pbix`).
- PDF export of the dashboard.
- Project documentation and business recommendations.

## Business Impact

This analysis demonstrates how marketing performance data can support decisions about customer acquisition strategies.

Rather than focusing only on total sales, the project evaluates campaign and channel performance specifically for new customers, helping identify where future marketing experiments and optimisation efforts could be focused.

---

**Author:** Pushpa Neupane  
**Focus:** Data Analytics | Business Intelligence | Data-Driven Decision Making
