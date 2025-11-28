# E-commerce Performance Overview

## Business Problem
E-commerce businesses need to understand customer shopping patterns to optimize marketing strategies, improve customer retention, and maximize revenue. This project analyzes transactional data to uncover insights about customer behavior, product performance, and subscription effectiveness, enabling data-driven decisions for business growth.

## Technical Details
- **Dataset**: 3,900 customer transactions with 18 features including demographics, purchase history, and shopping preferences
- **Data Sources**: Customer shopping behavior dataset
- **Tools**: Python (Pandas, NumPy, Matplotlib), Power BI
- **Analysis Approach**: Comprehensive data analysis from cleaning to visualization

### Data Preparation & Feature Engineering
- **Data Cleaning**: Handled 37 missing values in review ratings using median imputation
- **Feature Engineering**:
  - Created age groups for customer segmentation
  - Converted purchase frequency to standardized day counts
  - Engineered customer segments based on purchase history
- **Data Validation**: Ensured data consistency and removed redundant columns

### Key Analysis Performed
1. **Revenue Analysis**: Total revenue by gender and age groups
2. **Customer Segmentation**: New, Returning, and Loyal customers based on purchase history
3. **Product Performance**: Top-rated products and category-wise bestsellers
4. **Discount Strategy**: Identified discount-dependent products and high-spending discount users
5. **Subscription Impact**: Compared spending patterns between subscribers and non-subscribers
6. **Shipping Preferences**: Analyzed spending differences between Standard and Express shipping
7. **Customer Behavior**: Examined repeat buyers and their subscription likelihood

### Advanced Techniques
- RFM (Recency, Frequency, Monetary) analysis for customer segmentation
- Statistical comparisons across customer demographics
- Data-driven customer lifetime value estimation
- Interactive dashboard creation for stakeholder reporting

## Key Findings
- **Revenue Patterns**: Significant revenue differences across gender and age segments
- **Customer Loyalty**: Clear segmentation between new, returning, and loyal customers with distinct spending behaviors
- **Subscription Impact**: Subscribers demonstrate higher average spending and better retention
- **Discount Strategy**: Certain products show high dependency on discounts, requiring strategic pricing review
- **Shipping Preferences**: Express shipping users tend to have higher average order values
- **Product Performance**: Identified top-rated products and category leaders for marketing focus

## Business Recommendations
1. **Subscription Optimization**: Enhance subscriber benefits to increase conversion rates from high-value customer segments
2. **Targeted Marketing**: Develop age-specific and gender-focused marketing campaigns based on revenue contribution patterns
3. **Discount Strategy Review**: Re-evaluate discount dependency for certain products to protect profit margins
4. **Customer Loyalty Programs**: Implement tiered rewards systems to move customers from "Returning" to "Loyal" segments
5. **Product Positioning**: Highlight top-rated and best-selling products in promotional campaigns
6. **Shipping Incentives**: Consider free express shipping thresholds to increase average order values

## Project Structure
