# Customer behaviour Analysis
## Objective:
To analyze customer behavior trends, identify areas of strength and weakness, and provide strategic recommendations for improving customer retention and business performance.
## Data:
- The analysis is based on a dataset containing Customer records across 13 columns, including transaction details, customer information, product details.
- Dataset [link](https://www.kaggle.com/datasets/bhanupratapbiswas/customer-behavior-analysis)
## Tool Used:
Power BI (DAX, Created Measures, Columns)
## Data Preparation:
- The Customer ID column was converted from a whole number data type to text.
- The Date and Time columns were extracted separately from the original datetime column.
- Null values in the Returns column were replaced with 0 (representing "No").
- The Age column was deleted, as it was a duplicate of the Customer Age column.
- Values in the Returns and Churn columns were replaced: 0 with "No" and 1 with "Yes."
- The Revenue column was calculated by multiplying the Product Price and Quantity columns.
## Key Findings:
- New Customer Acquisition: Sharply declined after an initial strong start in 2020.
- Customer Churn: Exhibits a concerning upward trend.
- Gender Distribution: Customer base is evenly split between female and male.
- Age Distribution: Churn rates vary across age groups without a clear linear pattern, suggesting complex underlying factors.
- Payment Method: Credit Card is the dominant payment method among customers.
- Product Category Engagement: Clothing and Books have higher customer engagement than Electronics and Home.
- Return Rates: Consistently high across product categories, indicating a potential systemic issue.
- Purchase Frequency & Returns: Return rates tend to increase with purchase frequency but drop for the most frequent buyers.
- Age, Gender & Product Category: Middle-aged females are key demographics for Books and Clothing.
- Transaction Trends: Transaction volume remained stable within years but saw a significant drop in Q3 2023.
- Average Purchase Value: Older customers exhibit the highest average purchase value.
- Price Sensitivity: Customer distribution is relatively even across most product price points, with a drop at the highest prices.
- Churn & Returns vs. Revenue: Churn and return rates are generally stable across revenue levels, except for a high return spike at the top revenue segment.
## Areas Performing Well:
- The near-equal distribution of female and male customers indicates a broad appeal across genders.
- The high number of new customers in 2020 suggests effective initial market penetration or a successful launch.
- The higher engagement with Clothing and Books suggests these categories are performing well and resonate with the customer base.
- The even distribution of customers across most price points indicates a broad appeal across different spending levels.
- Older customers have the highest average purchase value.
## Areas for Improvement:
- The sharp decline in new customer acquisition is a significant concern and requires immediate attention.
- The increasing churn rate indicates a growing dissatisfaction or lack of engagement, which needs to be addressed to retain valuable customers.
- The consistently high return rates across product categories suggest underlying issues with product quality, fit, or customer expectations.
- The noticeable drop in transactions in Q3 2023 requires investigation to identify the cause and mitigate future impact.
## Recommendations:
- Develop a loyalty program, personalized offers, and proactive communication to increase customer engagement and reduce churn.
- Analyze the effectiveness of current acquisition channels and explore new, cost-effective strategies to attract new customers.
- Investigate the reasons for high return rates through customer surveys, feedback analysis, and process reviews.
- Enhance product descriptions, images, and sizing information to reduce returns due to unmet expectations.
- Develop targeted marketing campaigns and product offerings that appeal to the preferences and needs of older customers.
## Dashboard:
<img width="500" alt="Image" src="https://github.com/user-attachments/assets/98991daf-efe2-4f3f-b878-dddaa38866fc" />
