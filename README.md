# RFM Analysis Project Summary

## Overview
This project performs RFM (Recency, Frequency, Monetary) analysis on sales data to segment customers and understand their behavior patterns.

## Dataset Description
The dataset contains sales transactions with customer details, including:
- Customer information (ID, Name, Segment)
- Order details (Date, ID, Ship Mode)
- Product information (Category, Sub-Category, Price)
- Financial metrics (Sales, Profit, Discount)
- Geographic data (Country, Region, State, City)

## Analysis Components

### RFM Metrics
- **Recency**: Time since customer's last purchase (using Order Date)
- **Frequency**: Number of purchases (count of Order IDs)
- **Monetary**: Total spending (sum of Sales)

### Customer Segments
1. **Champions**
   - Most recent, frequent, and high-value customers
   - Primary targets for loyalty programs

2. **Loyal Customers**
   - Regular customers with consistent purchasing patterns
   - Focus on retention and upselling

3. **Recent Customers**
   - New customers with potential for development
   - Target for engagement and second purchase

4. **At Risk**
   - Previously active customers showing declining activity
   - Priority for reactivation campaigns

5. **Lost Customers**
   - Inactive customers with low engagement
   - Candidates for win-back campaigns

## Business Applications
- Customer segmentation for targeted marketing
- Personalized communication strategies
- Resource allocation for customer retention
- Early identification of churning customers
- Development of loyalty programs

## Expected Outputs
- Customer segment classifications
- Segment distribution analysis
- Customer value metrics
- Trend analysis over time

## Recommendations for Use
1. Update analysis monthly to track changes
2. Combine with other metrics for deeper insights
3. Adjust segmentation thresholds based on business goals
4. Use insights for marketing campaign planning
5. Monitor segment transitions for early warning signals
