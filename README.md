# AWS-SaaS-Sales-Analysis
## Context
This project explores how AWS SaaS can grow sustainably by balancing sales volume and profitability. Using historical transaction data, it identifies how discounts, product performance, and customer segmentation influence profit outcomes — turning raw data into actionable business insights.

## Problem Statement
Over the past four years, AWS SaaS has shown significant fluctuations in both sales and profitability. Transaction values range from just a few dollars to over $23 million, yet profit performance remains inconsistent — including several cases of negative profit, particularly in transactions with high discount rates. These irregularities indicate inefficiencies in pricing and discount strategies. While discounts are commonly used to boost sales volume, the data suggests that in certain cases, they may actually reduce profitability instead.

Hence, this analysis focuses on understanding **why negative profit transactions occur and how AWS SaaS can optimize its discount and pricing policy to achieve sustainable growth.**

To address this, the following areas of analysis were defined:  

**Scopes of Analysis**

**1. Product Performance Analysis**   
- Which products generate the highest sales and profit?  
- Do the most sold products give the highest sales and profit?  
- Which products have strong margin efficiency?  

**2. Discount Impact Analysis**  
- Do discounts help increase sales, or do they reduce profitability?  
- At what discount level does profit start to drop sharply?  

**3. Time Series Analysis**  
- How have sales and profit changed over the past four years?  
- Which year has the highest performance?  

**4. Regional Analysis**  
- Which country show the strongest and weakest financial performance?  
- Country x Discount x Profit

**5. Customer Segment Analysis**   
- Which customer segments contribute the most to sales and profit?   

**6. Negative Profit Check**   
- How many transactions result in negative profit, and why does it occur?   
- Does discount was the reason or is there any other reasons behind it?  

**7. High Discount Transaction Analysis**    
- What is the impact of transactions with discounts greater than 50%?

## Dataset
This project using AWS SaaS Sales.csv. [Download here.](https://drive.google.com/drive/folders/1dlpJfgvs8P_IyXqWB4WrNwk91fx0XAzU?usp=drive_link)

**Column Description**

| **Column Name** | **Description** |
|------------------|-----------------|
| Row ID | A unique identifier for each transaction. |
| Order ID | A unique identifier for each order. |
| Order Date | The date when the order was placed. |
| Date Key | A numerical representation of the order date (YYYYMMDD). |
| Contact Name | The name of the person who placed the order. |
| Country | The country where the order was placed. |
| City | The city where the order was placed. |
| Region | The region where the order was placed. |
| Subregion | The subregion where the order was placed. |
| Customer | The name of the company that placed the order. |
| Customer ID | A unique identifier for each customer. |
| Industry | The industry the customer belongs to. |
| Segment | The customer segment (SMB, Strategic, Enterprise, etc.). |
| Product | The product that was ordered. |
| License | The license key for the product. |
| Sales | The total sales amount for the transaction. |
| Quantity | The total number of items in the transaction. |
| Discount | The discount applied to the transaction. |
| Profit | The profit from the transaction. |

> **Note:** Additional columns such as `Profit Margin`, `Year`, and others were created during data transformation for further analysis.

## Data Analysis and Conclusion
Refer to Jupyter Notebook. Click [here]

## Dashboard
Take a look at overall dashboard by clicking in [here.](https://public.tableau.com/app/profile/ajeng.aulia.salshabila/viz/CapstoneProject2_17626039965860/AWSSaaSPerformanceAnalysis?publish=yes)
