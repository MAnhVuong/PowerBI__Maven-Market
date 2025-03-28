# Maven Market Power BI Dashboard
## Overview
This Power BI dashboard provides an interactive analysis of **Maven Market**, a grocery chain, with insights into sales transactions, product performance, customer demographics, and store operations.


## Key Features
### Sales & Profit Tracking
- Current month transactions vs. goals
- Net sales, amounts, and profit margins

### Product Performance
- Breakdown by brand (e.g., ADJ, Akron, American)
- Discount pricing, cost, and profit analysis

### Customer Insights
- Customer demographics (birth year, location)
- Transaction history

### Store & Regional Data
- Store locations, size (grocery sqft), and remodel dates
- Sales by region and district

### Returns Analysis
- Historical returns data (1997-1998)


## Data Sources
| Dataset          | Key Fields                                                                 |
|------------------|---------------------------------------------------------------------------|
| **Customers**    | ID, birthdate, address, city, country                                     |
| **Products**     | Brand, cost, price tier, discount price, nutritional info                 |
| **Stores**       | Location, size, opening/remodel dates, region                             |
| **Transactions** | Date, quantity, customer/product/store associations                       |
| **Returns**      | 1997-98 return data for product performance analysis                      |


## How to Use
**1. Open in Power BI Desktop**:
- Download the ```.pbix``` file and open it in Power BI.
- Refresh data connections if needed.

**2. Interactive Filters**:

Use slicers to filter by:
- Date range
- Product brand
- Store location
- Key Metrics
- Current Month Transactions (vs. goal)
- Profit Margins by product category
- Customer Age & Location Trends


## Sample Insights
**1. Top-Performing Brands:**
- Best Choice: Highest revenue ($25,901)
- BBB Best: Most transactions (16,395)

**2. Lowest Margin Products:**
- Big City: Only 0.71% margin

**3. Regional Sales:**
- Filter by sales_region to compare performance.

## Requirements
- Power BI Desktop (latest version)
- Access to data sources (CSV/SQL/Excel)
