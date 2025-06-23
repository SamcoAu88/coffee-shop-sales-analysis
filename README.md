# Coffee Shop Sales Analysis

![Coffee Shop ERD](images/coffee_shop.jpeg)

This project analyzes a dataset of coffee shop transactions spanning 181 days. The dataset includes information on individual transactions, product details (category, type, size), store locations, and timestamps. The goal of this analysis is to identify key sales trends, understand product performance, evaluate store performance, and uncover actionable insights to inform business decisions.

## Summary and Key Findings

In conclusion, this analysis of the coffee shop sales data has revealed several important trends and insights:

**Overall Sales Performance:**
- The dataset comprises 149,116 transactions across 181 days, revealing key sales patterns and store performance.
- Total revenue generated is $698,812.33, with an average transaction value of $4.69.
- The business demonstrates a positive growth trend in revenue over the past five months.

**Time-Based Sales Trends:**
- Peak sales activity occurs between 8:00 AM and 10:00 AM.
- Monday is the busiest day for sales, while Saturday experiences the lowest sales volume.
- Monthly revenue showed a slight dip after the first month but exhibited consistent growth in the subsequent months.
- Within each month, sales tend to peak around the 6th and then gradually decline significantly after the 27th. This pattern may correlate with customer salary cycles and budget constraints towards the month's end.

**Product Performance:**
- The leading product categories by sales volume are "coffee" and "tea", significantly outperforming others.
- "Package chocolate" and "branded" items are the least sold product categories.
- The top three best-selling individual products are "Brewed Chai tea", "Gourmet brewed coffee", and "Barista espresso".
- The least selling individual items include 'green beans', 'green tea', 'house blend beans', 'organic chocolate', and 'clothing'.

**Size Category Analysis:**
- The distribution of product sales by identified size categories shows "Regular" and "Large" sizes are very close in popularity, each accounting for approximately 30% of sales where size could be determined.
- "Small" size products represent around 9% of sales with identified sizes.
- A significant portion (almost 30%) of products do not have clearly identifiable size categories in their details.

**Store Performance:**
- Revenue distribution is relatively balanced across the three stores.
- "Hell's Kitchen" is the top-performing store in terms of total revenue, generating $236,511 and accounting for approximately 33.8% of total revenue.
- "Lower Manhattan" has the highest average transaction value at $4.81, representing a 34.2% share of the average transaction value.
- In terms of total quantity sold, the distribution across the three stores is also quite similar, with "Lower Manhattan" having a slightly higher volume at approximately 33.5% of the total (71,742 items sold).

**Operational Insights:**
- The "Astoria" store appears to be closed at 6:00 AM and 8:00 PM, as indicated by zero transactions during these hours.
- The "Lower Manhattan" store experiences a noticeable drop in sales by 7:00 PM and a significant decline by 8:00 PM (around 75 fewer transactions compared to earlier times), suggesting a potential opportunity to evaluate closing hours.
- The largest individual transactions in terms of revenue are frequently associated with the sale of packaged coffee beans, primarily at the "Hell's Kitchen" location.

**Overall Conclusion:**
- The coffee shop demonstrates strong overall sales with a positive growth trajectory. Understanding the impact of salary cycles on monthly sales could inform targeted promotions or strategies.
- Focusing on the popular "coffee" and "tea" categories and the top-selling individual products is crucial. Investigating strategies to boost sales in underperforming categories and products may be beneficial.
- The similarity in total quantity sold across stores suggests a relatively even distribution of customer traffic, although "Lower Manhattan" handles a slightly higher volume.
- The near-equal popularity of "Regular" and "Large" sizes could inform inventory and purchasing decisions. Addressing the significant portion of products with unidentified sizes might improve future size-based analysis.
- Operational adjustments, such as reviewing opening/closing hours for the "Astoria" and "Lower Manhattan" stores, could potentially optimize resource allocation and profitability.

## Libraries Used

- pandas
- matplotlib
- seaborn
