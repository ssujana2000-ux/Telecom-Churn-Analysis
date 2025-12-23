# Telecom-Churn-Analysis
Power BI dashboard analyzing telecom customer churn to identify key drivers and improve retention.
Source - https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics

## 📁 Project Structure

data/  
telecom_churn.csv  

dashboard/  
Telecom_Churn_Analysis.pbix  
Dashboard.png  

README.md



## 📊 Dashboard Preview
![Telecom Churn Dashboard](Dashboard/Dashboard.png)

## Power BI Dashboard
- Interactive churn analysis dashboard
- Key metrics: churn rate, tenure, contract type, refund flag
- Built using Power BI with DAX measures

## Business Statement
The objective of this analysis is to understand customer plan usage, churn reasons and quantify revenue impact inorder to improve customer retention.

##	Data Cleaning and EDA
1.	The dataset was imported into Power BI, data types were corrected, and no missing values were found in key churn, tenure, or revenue fields.
2.	Customer status and churn categories were validated, added calculated columns - Refund flag, offer flag, age category and tenure category.
3.	Performed EDA using simple visuals and marked useful KPI's and insights like
          The primary churn drivers are better competitor offers and customer dissatisfaction, including service and support-related issues.
          Customer churn is highest within the first 6 months, while long-tenure customers show stronger retention.
          The dataset represents approximately 21M in total revenue, with churned customers contributing ~17%, indicating a significant revenue impact.

## 📊 KPI Summary

With high level insights, created measures using DAX functions like SUM,CALCULATE,AVERAGE,DIVIDE etc.

The dashboard tracks key telecom churn metrics:
-total customers
-churn rate
-churned customers
-average tenure
-revenue impact
It also measures revenue lost due to churn, refund amounts, and average revenue per customer. Customer behavior is analyzed across tenure groups, contract types, age segments, offers, and churn reasons to identify high-risk segments and revenue drivers.

## Dashboard Summary

Dashboard displays Churn Rate, Volume, Drivers of Churn and Avg Revenue lost per Churn, Churn rate by Contract & Churn Rate by Tenure

Listed important KPI's in the top of the dashboard using card visual - Total Customers, Revenue, Churn Rate.
Utilized Bar Chart, Column Chart & Pie Chart to analyze Churn by categories like Tenure, Age, Refund and Churn Reasons.
Displayed top 10 churned customers by revenue with help of Top N filter.


## 🔍 Business Insights Summary

Customer churn is highest among early-tenure customers and those on month-to-month contracts. Competitor-related reasons are the primary drivers of churn, often linked to pricing, speed, and device offerings. A small group of high-value customers contributes to a large share of revenue loss, highlighting the need for targeted retention strategies. 


