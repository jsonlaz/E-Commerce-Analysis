# E-commerce Customer Segmentation and Behavior Analysis

This project explores an e-commerce dataset to understand customer behavior, segment customers based on purchasing patterns, and analyze churn. The analysis aims to provide actionable insights for targeted marketing campaigns and improved customer retention strategies.

## Dataset

The dataset contains customer transaction data. [Click Raw Data](https://www.kaggle.com/datasets/shriyashjagtap/e-commerce-customer-for-behavior-analysis) to see the dataset on Kaggle and the data description.

## Analysis

The analysis is performed in Python using Pandas, Matplotlib, and Seaborn libraries. It consists of the following key steps:

1. **Data Cleaning:**
    - Handle missing values in relevant columns.
    - Convert data types to appropriate formats (e.g., DateTime for purchase date).
    - Create and add (if needed) new columns for analysis.
    - Address inconsistencies in customer IDs and names.
    - Remove unwanted columns.

2. **Customer Segmentation (RFM):**
    - Calculate each customer's Recency, Frequency, and Monetary (RFM) values.
    - Segment customers into distinct groups (i.e., High Valued Customers, Loyal Customers, At Risk Customers, etc.) based on their RFM scores.

3. **Customer Behavior Analysis:**
    - Analyze purchase patterns by product category, payment method, and customer segment.
    - Visualize sales trends over time.
    - Identify preferred payment methods by customer segment.

4. **Churn Analysis:**
    - Calculate the overall churn rate.
  
5. Time Series Analysis
   - Sales Trends Over Time

## Visualizations

The analysis includes various visualizations to provide clear insights into the data. The visualizations were done using Power BI; Exported and saved the relevant datasets as CSV from Python to computer and joined the datasets in Power BI.

[Interactive Visualization Using Power BI](https://github.com/jsonlaz/E-Commerce-Analysis/blob/main/visualization/E-commerce%20Customer%20Behavior%20Analysis.pbix)

The visualization includes:

- **Sales trends over time:** Line charts and area charts to show the overall sales performance and product category performance.
- **Sales by product category:** Bar charts and column charts to identify top-selling categories.
- **Payment method preferences:** Pie chart to show payment method popularity overall and within customer segments.
- **RFM segmentation:** Bar charts to visualize customer distribution across segments.
- **Churn analysis:** Line charts and Gauge to show churn rates over time.
- **Demographics:** Bar charts and pie charts to show gender and age distribution.

## Results:

- ﻿﻿The customer churn Rate was 23.37%. Count of Churn trended down, resulting in a 53.02% decrease between January 2020 and September 2023. Count of Churn started trending down on May 2023, falling by 52.99% (3,012) in 4 months. ﻿Count of Churn was trending up between June 2022 and March 2023 with a rise of 226 but had a significant change in trend and dropped by 3,012 starting May 2023.
- Credit card was the most preferred payment method, accounting for 40.19% of the payment methods
- ﻿﻿Loyal Customers accounted for 96.28% of Customers.﻿﻿ ﻿﻿Loyal Customers had 38,433 Customers and Regular Customers had 1,487.﻿﻿ 
- The sum of Total Purchase Amount dropped from 15399935 to 7381783 during its steepest decline between May 2023 and September 2023.﻿﻿ The Total Purchase Amount was unexpectedly low on September 2023, having a value of 7381783, which is outside the expected range of 11112320-19878580.
- Michael Smith had the maximum customer frequency with 107 days.
- Most customers were between the age of 20-69, with the 20-29 age bracket accounting for a majority of customers. Very few customers were in their 70s.
- ﻿﻿﻿Books had the highest Sum of Total Purchase Amount at 204939601, followed by Clothing, Electronics, and Home.﻿﻿ ﻿At 204939601, Books had the highest Sum of Total Purchase Amount and was 51.50% higher than Home, which had the lowest Sum of Total Purchase Amount at 135271210.
﻿﻿
﻿

## Conclusion

This analysis provides a comprehensive understanding of customer behavior and segmentation within the e-commerce dataset. The insights gained can be used to develop targeted marketing campaigns, personalize customer experiences, and implement effective churn reduction strategies.  Further analysis could explore predictive modeling for churn and customer lifetime value.

## Contributing

If you'd like to contribute to this project (e.g., by suggesting improvements or adding new analysis), please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

