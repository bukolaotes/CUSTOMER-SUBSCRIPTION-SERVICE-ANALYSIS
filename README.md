## Customer Segmentation Analysis for Subscription Service
---

### Introduction

### Purpose:

### The purpose of this analysis is to segment customers of the subscription service to better understand their behaviors, preferences, and potential lifetime value. This segmentation will help inform personalized marketing strategies, improve customer retention, and optimize product offerings.

### Business Context: 
### The subscription service offers three tiers: Basic, Premium, and Standard. By understanding customer patterns and segmenting them based on subscription type, region, and behavior (e.g., churn likelihood, duration of subscription), we aim to enhance decision-making and revenue growth.


### Data Overview

###The dataset used for this analysis includes customer demographics, subscription details, revenue, and cancellation status. Key columns include:

- CustomerID: Unique identifier for each customer.

- SubscriptionType: Indicates whether a customer is subscribed to Basic, Premium, or Standard.

- SubscriptionStart and SubscriptionEnd: Start and end dates of subscriptions.

- Revenue: Revenue generated by each customer.

- Region: Geographical region of the customer.

- Canceled: Indicates whether a customer has canceled their subscription (True/False).


Data Cleaning: Duplicates were removed from the table

3. Methodology

Segmentation Criteria: The customers were segmented based on several criteria:

1. Demographics: Segmentation by Region to identify geographical trends.


2. Subscription Type: Grouping by SubscriptionType (Basic, Premium, Standard).


3. Behavioral: Segmentation by subscription duration and revenue to understand customer engagement and value.


  ### Tools

- Excel - Data cleaning and creating of pivot tables
- postgresql - Data Analytics
- Power BI - Creating of reports

- ### Data Cleaning/Prepearation


1.	Removed duplicate rows .
2.	standardized product names for consistent analysis across the dataset




4. Analysis and Results
•	The East region made the highest revenue which came from basic subscription type 20,332,506 in year 2022 and 13,444,229 in year 2023.In year 2022. 
•	It was also observed that no revenue was made from the south from quarter 3 of year 2022 based premium type and also quarter 3 of year 2023 also based on premium type. 
•	East Region has the highest number of customers which 18,612(25%) of total number of customers which is 33,787 in which the customers are on Basic type of subscription.
•	There 18612 number of active subscribers which is 55% of the total customers and 15175 numbers of subscribers that canceled their subscription which is 45% of total customers.
•	Number of customers in year 2022 was 20,275 while in 2023 it was 13,512.

![image](https://github.com/user-attachments/assets/a9112080-6ff6-4db9-b0a4-19cd0d7d1dea)

![image](https://github.com/user-attachments/assets/114c87a2-5fcd-4809-b6de-133d6c419d08)

. Key Findings
•	 There was no revenue from south and west based on Basic subscription type in year 2022 and 2023
•	It was also observed that no revenue was made from the south from quarter 3 of year 2022 based premium type and also quarter 3 of year 2023 also based on premium type. There was no revenue from the standard type in quarter 1 in year 2022 and standard type quarter 1 in year 2023 from the west region

•	It was observed that in west region the customers only subscribed to Standard type subscription
•	The number of customers reduced by 6,762


 Recommendations

Retention Campaigns for At-Risk Customers: Implement retention strategies (e.g., loyalty rewards, targeted offers) for customers in. Personalized emails could be sent after 6 months of subscription to encourage renewal.

Upselling Opportunities: Focus on upselling Basic subscribers who show potential for higher engagement,. Offering limited-time discounts to upgrade to Premium could incentivize longer subscriptions.

Targeted Marketing: Direct marketing efforts to the East region to address the high churn rate among Basic subscribers. Offering better customer support or incentives like a free trial extension may reduce early cancellations.


7. Conclusion

This customer segmentation analysis has provided valuable insights into customer behavior across different regions and subscription types. The segmentation reveals patterns that can be leveraged to improve marketing strategies, reduce churn, and increase customer lifetime value.





