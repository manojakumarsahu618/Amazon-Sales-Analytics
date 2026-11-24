# Amazon Sales Analytics | Power BI Dashboard

## Project Overview

This project focuses on analyzing Amazon e-commerce sales data to understand sales performance, order distribution, product category trends, and geographical sales patterns.

An interactive Power BI dashboard was developed to transform raw sales data into meaningful business insights. It provides an overview of key performance indicators (KPIs), order statuses, customer locations, product categories, and B2B transactions.

The dashboard helps understand business performance and supports data-driven decision-making.

## Dashboard Preview

![Amazon Sales Analytics Dashboard](images/amazon-sales-dashboard.png)

## Business Objectives

- Analyze overall sales performance and order quantity.
- Monitor order distribution based on order status.
- Identify states and cities contributing to sales volume.
- Understand product category performance.
- Analyze B2B versus non-B2B order distribution.
- Provide an interactive dashboard for business reporting.

## Key Performance Indicators (KPIs)

| KPI | Dashboard Value |
|---|---:|
| Total Sales Amount | 78.59M |
| Total Quantity Sold | 117K |
| Unique/Counted Shipping Postal Codes | 9.46K |
| Total Order IDs (Count) | 129K |

*Note: These are the displayed dashboard values. The postal-code KPI is a count, not necessarily a count of distinct postal codes.*

## Dashboard Features

### 1. Sales and Order Analysis
- Total sales amount.
- Total quantity sold.
- Order ID count.
- Order status distribution.

### 2. Geographical Analysis
- Order distribution by shipping state.
- Quantity distribution by shipping city.
- Identification of major geographical sales markets.

### 3. Product Category Analysis
- Quantity sold across product categories.
- Category-wise sales amount.
- Comparison of leading product categories.

### 4. B2B Order Analysis
- Comparison of B2B and non-B2B orders.
- Percentage distribution of B2B transactions.

### 5. Interactive Filters
- Category filter.
- Order status filter.
- Clear Filters option to reset dashboard selections.

## Tools & Technologies

- **Microsoft Power BI** – Interactive dashboard development and data visualization.
- **Power Query** – Data preparation and transformation, if used in the project.

## Key Observations

Based on the dashboard:

1. The dashboard reports a total sales amount of 78.59M.
2. The total quantity sold is approximately 117K.
3. The order ID count is approximately 129K.
4. The B2B order distribution shows approximately 99.32% non-B2B orders and 0.68% B2B orders.
5. Maharashtra, Karnataka, Tamil Nadu, Telangana, and Uttar Pradesh appear among the leading shipping states in the displayed order-count chart.
6. Set and Kurta are among the leading categories by quantity in the dashboard.
7. The city-wise quantity chart highlights Bengaluru among the leading cities.

*These observations describe the displayed dashboard and are not independent conclusions about profitability or customer behavior.*

## Repository Structure

```text
Amazon-Sales-Analytics/
│
├── images/
│   └── amazon-sales-dashboard.png
│
├── dashboard/
│   └── Amazon-Sales-Analytics.pbix
│
├── dataset/
│   └── README.md
│
└── README.md
```

## How to Explore the Project

1. Clone or download this repository.
2. Open the `.pbix` dashboard file using Microsoft Power BI Desktop.
3. Explore the dashboard visualizations.
4. Use the Category and Status filters to interact with the report.
5. Select Clear Filters to reset the dashboard.

## Future Improvements

- Add monthly and yearly sales trend analysis.
- Develop profit and revenue performance metrics if the required data is available.
- Add customer segmentation and RFM analysis.
- Perform deeper geographical and product-level analysis.
- Improve the dashboard with additional business KPIs.

## Author

**Manoja Kumar Sahu**

MCA Graduate | Aspiring Data Analyst

- GitHub: https://github.com/manojakumarsahu618
- LinkedIn: https://linkedin.com/in/manoja-kumar-sahu-7477642aa

---

If you find this project useful, feel free to explore the repository and connect with me on LinkedIn.

**Thank you for visiting!**
