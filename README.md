# Jumia Product Performance Dashboard 

An interactive dashboard analyzing Jumia product pricing, discounts, ratings, and reviews to uncover product performance insights.

## Project Objective
The objective of this project is to analyze Jumia product data to understand how pricing, discounts, ratings, and customer reviews influence product performance and customer engagement. The dashboard is designed to support data-driven decision-making in e-commerce and retail analytics.

## Dataset
The dataset contains product-level information collected from Jumia, including pricing details, discounts, customer ratings, and review counts. Each row represents a unique product and its associated performance metrics.

Key variables include:
- Product name
- Current price (KSh)
- Old price (KSh)
- Discount percentage (%)
- Number of reviews
- Product rating (out of 5)

## Data Cleaning
Several data cleaning steps were performed to ensure accuracy, consistency, and reliability of this analysis before building the dashboard.

Cleaning steps included:
- Handling missing values, particularly in reviews and ratings
- Removing duplicate product entries
- Converting price columns from text to numeric format by removing currency symbols
- Ensuring discount values were numeric and properly formatted as percentages
- Converting rating values into numeric format (e.g., "4.5 out of 5" → 4.5)
- Correcting invalid or negative review counts where applicable

## Data Enrichment
Additional calculated fields were created to enhance analysis and enable clearer segmentation of products within the dashboard.

New columns created include:
- **Discount Amount (KSh):** Calculated as Old Price minus Current Price
- **Rating Category:** 
  - Poor: rating < 3  
  - Average: rating between 3 and 4.4  
  - Excellent: rating ≥ 4.5
- **Discount Category:**
  - Low Discount: < 20%  
  - Medium Discount: 20%–40%  
  - High Discount: > 40%

## Analysis Questions Answered

### Descriptive Analysis

- What is the average current price, old price, discount percentage, and rating across products?
- Which products are the most and least expensive?
- How do average ratings and discounts vary by discount category?
- How are products distributed across rating categories?
  
### Trend and Relationship Analysis


- Is there a relationship between discount percentage and number of reviews?
- Do higher-rated products receive more customer reviews?
- Do heavily discounted products show higher customer engagement?

 ### Product Performance Highlights

- Top 10 products with the highest discounts
- Top 10 products with the highest number of reviews
- Top 5 highest-rated and bottom 5 lowest-rated products
- Comparison between high-discount and low-discount products in terms of ratings and reviews

## Dashboard Features

### Key Performance Indicators (KPIs)

- Total number of products
- Average product rating
- Average discount percentage
- Total number of customer reviews

### Visual Analysis

- Top products by rating, number of reviews, and discount percentage
- Charts showing relationships between discounts, ratings, and reviews
- Category-based breakdowns for rating and discount groups

 ### Interactivity

 - Slicers for filtering products by rating category and discount category
- PivotTables used as the primary data source for dynamic updates
- Conditional formatting to highlight high discounts and low-rated products

## How to Use the Dashboard

1. Download the Excel dashboard file from this repository.
2. Open the file using Microsoft Excel (desktop version recommended for full functionality).
3. Use the slicers and filters to explore product performance by rating and discount categories.
4. Review KPIs and charts to identify high-performing and underperforming products.

## Files in This Repository

- `jumia_dashboard.xlsx` — Final interactive Excel dashboard
- `dashboard_preview.png` — Screenshot preview of the dashboard
- `README.md` — Project documentation

## Tools Used

- Microsoft Excel (PivotTables, PivotCharts, Slicers, Conditional Formatting)


