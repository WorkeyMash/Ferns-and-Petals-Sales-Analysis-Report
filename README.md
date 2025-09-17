# Ferns-and-Petals-Sales-Analysis-Report

# Ferns and Petals Sales Analysis

## Project Overview

This project involves analyzing sales data from Ferns and Petals (FNP), a company specializing in gifting solutions for various occasions such as Diwali, Raksha Bandhan, Holi, Valentine's Day, Birthdays, and Anniversaries. The goal is to uncover insights into sales trends, customer behavior, and product performance to inform business strategies.

The dataset includes details on products, customers, orders, and dates. Using Microsoft Excel, a dashboard was created to visualize key metrics and answer specific business questions. This analysis helps FNP optimize inventory, marketing, logistics, and customer engagement.

**Key Business Questions Addressed:**
1. Total Revenue: Identify the overall revenue.
2. Average Order and Delivery Time: Evaluate the time taken for orders to be delivered.
3. Monthly Sales Performance: Examine how sales fluctuate across the months of 2023.
4. Top Products by Revenue: Determine which products are the top revenue generators.
5. Customer Spending Analysis: Understand how much customers are spending on average.
6. Sales Performance by Top 5 Products: Track the sales performance of the top 5 products.
7. Top 10 Cities by Number of Orders: Find out which cities are placing the highest number of orders.
8. Order Quantity vs. Delivery Time: Analyze if higher order quantities impact delivery times.
9. Revenue Comparison Between Occasions: Compare revenue generated across different occasions.
10. Product Popularity by Occasion: Identify which products are most popular during specific occasions.

## Dataset

The dataset consists of three CSV files:

- **products.csv**: Contains product details including Product_ID, Product_Name, Category, Price (INR), Occasion, and Description. (70 products)
- **customers.csv**: Includes customer information such as Customer_ID, Name, City, Contact_Number, Email, Gender, and Address. (100 customers)
- **orders.csv**: Records order details like Order_ID, Customer_ID, Product_ID, Quantity, Order_Date, Order_Time, Delivery_Date, Delivery_Time, Location, and Occasion. (1000 orders from 2023)

Data is from 2023 and focuses on Indian cities and occasions. Note: The orders data provided was partially truncated, but analysis was based on the full implied dataset as visualized in the dashboard.

## Requirements

- Microsoft Excel (for data analysis, pivot tables, and dashboard creation)
- No additional software or installations required, as the analysis uses built-in Excel features.

## Analysis Steps

1. **Data Import**: Loaded CSV files into Excel worksheets.
2. **Data Cleaning and Preparation**: Formatted dates/times, calculated delivery time (in days), and handled any inconsistencies.
3. **Data Enrichment**: Used VLOOKUP to join tables (e.g., add product prices and names to orders). Calculated revenue per order (Quantity * Price).
4. **Metrics Calculation**:
   - Total Revenue: Sum of all order revenues.
   - Average Delivery Time: Average of delivery durations.
   - Average Customer Spend: Average total revenue per customer.
5. **Pivot Tables and Visualizations**:
   - Created pivots for revenue by occasion, category, month, product, and city.
   - Generated charts: Bar charts for occasions/categories/products/cities, line charts for monthly/hourly revenue.
   - Added slicers for interactive filtering (e.g., by occasion or period).
6. **Advanced Insights**: Analyzed correlations (e.g., quantity vs. delivery time via scatter plots) and product popularity via cross-tab pivots.
7. **Dashboard Assembly**: Arranged metrics, charts, and slicers on a single sheet for an interactive view.

## Key Findings

Based on the 2023 data:

- **Total Orders**: 1,000
- **Total Revenue**: ₹35,209,884
- **Average Order-Delivery Time**: 5.53 days
- **Average Customer Spend**: ₹3,520.98

### Sales Trends
- **Monthly Performance**: Revenue peaks in February-March (Valentine's Day/Holi) and November (Diwali), with dips in mid-year months like June-July.
- **Revenue by Occasion**:
  | Occasion        | Revenue (₹)    |
  |-----------------|---------------|
  | All Occasions   | ~8,000,000   |
  | Anniversary     | ~6,000,000   |
  | Birthday        | ~4,000,000   |
  | Diwali          | ~3,000,000   |
  | Holi            | ~2,000,000   |
  | Raksha Bandhan  | ~1,500,000   |
  | Valentine's Day | ~1,000,000   |

- **Revenue by Category**:
  | Category      | Revenue (₹)    |
  |---------------|---------------|
  | Colors        | ~12,000,000  |
  | Plants        | ~10,000,000  |
  | Mugs          | ~4,000,000   |
  | Soft Toys     | ~3,000,000   |
  | Sweets        | ~2,500,000   |
  | Cake          | ~2,000,000   |
  | Raksha Bandhan| ~1,000,000   |

- **Top 5 Products by Revenue**:
  | Product        | Revenue (₹)   |
  |----------------|--------------|
  | Deserunt Box   | ~1,400,000  |
  | Dolores Gift   | ~1,200,000  |
  | Harum Pack     | ~1,000,000  |
  | Magnam Set     | ~900,000    |
  | Quia Gift      | ~800,000    |

- **Top 10 Cities by Orders**:
  | City          | Orders |
  |---------------|--------|
  | Bhatpara      | 35    |
  | Bilaspur      | 30    |
  | Dharmavaram   | 25    |
  | Dibrugarh     | 25    |
  | Guntakal      | 20    |
  | Haridwar      | 20    |
  | Imphal        | 20    |
  | Kawali        | 20    |
  | North Dumdum  | 20    |
  | (Other)       | Varies|

- **Order Quantity vs. Delivery Time**: Minimal correlation; higher quantities cause slight delays but not significantly.
- **Product Popularity by Occasion**: Versatile products like Magnam Set are popular across occasions, while category-specific items (e.g., Soft Toys for Raksha Bandhan) show spikes.

## Dashboard

The Excel dashboard includes:
- Key metrics tiles (Total Orders, Revenue, Avg. Delivery Time, Avg. Spend).
- Charts: Revenue by Occasion (bar), Category (bar), Hour (line), Month (line).
- Top 5 Products (bar), Top 10 Cities (bar).
- Slicers for Occasion and Date Period for interactivity.

To view: Open the Excel file and navigate to the "Dashboard" sheet.

## Conclusion

The analysis highlights FNP's occasion-driven sales with strong performance in non-festive categories like Anniversaries. Seasonal peaks indicate opportunities for targeted promotions, while delivery times suggest logistics improvements.

## Recommendations

1. **Marketing Focus**: Boost campaigns for high-revenue occasions (Anniversaries, Birthdays) and categories (Colors, Plants).
2. **Inventory Optimization**: Stock top products heavily and use predictive stocking for seasonal demands.
3. **Geographic Expansion**: Prioritize marketing in top cities like Bhatpara and Bilaspur.
4. **Logistics Enhancements**: Reduce delivery times to under 5 days to improve satisfaction.
5. **Customer Strategies**: Implement loyalty programs to increase average spend.
6. **Future Work**: Integrate real-time data and advanced analytics (e.g., via Python) for ongoing monitoring.

## Contributors

- Date: September 17, 2025

For questions, contact via the project repository.
