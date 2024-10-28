### LITA-CAPSTONE-PROJECT

[Data Structure and Columns](data-structure-and-colunms)

#### **TABLE ANALYSIS FOR SALES DATA** : 

 #### ***Data Structure and Columns***

- #### ***ORDER ID***:
  Unique Identifer for each sales transaction.

- #### ***CUSTOMER ID***:
  ID representing Individual customers.

- #### ***PRODUCT***:
 Type of product purchased were Shoes, Jacket, Shirt, Hat, Gloves and Socks.

- #### ***REGION***:
  The region where product was sold were South, North, East and West.

- #### ***ORDER DATE***:
  Date of the order,which include the day, month and year.

- #### ***QUANTITY***:
 Number of items sold per transaction.

- #### ***UNIT PRICE***:
  price per unit of the product.

- #### ***SALES***:
   Total sales amount which I calculated as
  
```
  Quantity * Unit Price.
```


#### TOOLS USED FOR VIRTUALIZATION:

1. #### **POWER BI**
2. #### **EXCEL**
3. ### ***STRUCTURED QUERY LANGUAGE(SQL)***

---
#### ***INSIGHTS OF THE SALES DATA***:
- Uniform pricing and Quantity indicate standardized sales.


### ***Visualization explanation For power BI***:

1. #### ***TABLE: Comparison of Region By Product Sales***:

   - The table explains the sales for each product by region as well as the total sales.
  
   #### ***Key Observations***:
  - The **South** region has the highesr total sales at ***$927,820*** followed by ***East*** at ***$546,300***.
  - ***Shoes*** and ***Shirt*** are the top selling items with total sales of ***$613,380*** and ***$485,600*** respectively.
  - The ***West*** region shows the Lowest contribution overall, with products like ***Gloves*** and ***Hat*** having minimal sales.

2. #### ***Line Chart: Average of Sales by Order Date***:
 - This line graph visualizes how the sales average fluctuates over time from ***April 2023 to July 2024***.
  
     #### ***Key Observations***:
  - The highest sales average occurred in ***April 2024*** at ***$600***, Indicating a peak in sales during that time.
  - The lowest point of sales was in ***June 2023*** with ***$100*** as average sales.
  - Sales show periodic spikes, possibly related to seansonal and promotional events, leading to these fluctuations.

 3. #### ***Product Sales (Bar Chart): Unit Price Impact on Sales***:
 - The bar chart Visualizes the Impact of unit price on total sales, showing which price points contribute the most to overall revenue.

   #### ***Key Observations***:
 - ***Shoes*** and ***Shirts*** Largest significant contributions of ***$620,200*** and ***$358,440*** units respectively.
 - ***Socks*** and ***Jacket*** have the least Impact, contributing only around ***$180,785*** and ***$208,230*** units.


4. #### ***Slicer***:
   The Slicer on the left side of my dashboard image helps filter the data based on ***Product*** Which makes the dashboard Interactive,
   Facilitating detailed analysis for each product.
   


### ***Visualization explanation For Excel***:


 ### TABLE. 

 
#### ***Peak in Sales***

The tables show significant sales data that can help identify when we had a peak:

- ***Sales by Month***: February had the highest sales at **2.75M**. This information is helps us to recognizing seasonal.

- ***Sales by Region***: The **South** region had the highest sales with **4.675M**, indicating a strong market presence or successful regional strategies.

#### ***Product Performance***
The tables also highlight the products with the highest and lowest sales:

***Highest Sales***: Shoes sold **3.1M** units, making them the top performer. This suggests that Shoes are highly popular and should be prioritized in inventory and marketing efforts.

**Lowest Sales**: **Socks** had the lowest sales at  units. This might indicate a need to evaluate the product's appeal or to improve its promotion.   


#### ***Impact On Sales***

***Identification of High-Performing Products***: By analyzing the tables, we can see the products that is driving the most revenue. Shoes being the top seller suggests they should be a focal point for sales strategies.

***Recognition of Underperforming Products***: **Socks** being the lowest seller indicates areas that may need reevaluation or targeted marketing efforts to boost sales.

***Regional Analysis***: The data shows where the sales are strongest geographically. The South region’s high sales mean strategies used there could be analyzed and potentially applied to other regions.

***Seasonal Trends***: Sales peaking in February suggest the need for enhanced inventory and marketing plans during this period to capitalize on the increased demand.

 The  breaking down and analyzing of these pivot tables, we are more informed about the decisions to optimize sales strategies, inventory management, and marketing efforts.



#### Charts.

****SUM OF PRODUCT SOLD IN 2023 AND 2024:****

- This bar chart compares the total sales of different products across the years ***2023*** and ***2024***.

- The x-axis represents the products ***(Glove, Hat, Jacket, Shirt, Shoe, Socks).***

- The y-axis represents the total sales in units.

Each product has two bars, one for ***2023*** and one for ***2024***, allowing for a direct comparison of sales performance between the two years.


****SALES BY REGION:****

- This line chart shows the sales performance across different regions.

- The x-axis represents the regions (East, North, South, West).

- The y-axis represents the sales in units.

The line connects the sales data points for each region, providing a visual trend of sales performance across regions.

****SALES BY ORDER DATE:****

- This bar chart displays sales data based on the order date.

- The x-axis represents the order dates.

- The y-axis represents the sales in units.

Each bar represents the sales for a specific order date, allowing for an analysis of sales trends over time.


****SQL:****

Questions that was used to analyse the sales data where:

- retrieve the total sales for each product category.
- find the number of sales transactions in each region.
- find the highest-selling product by total sales value.
- calculate total revenue per product.
- calculate monthly sales totals for the current year.
- find the top 5 customers by total purchase amount.
- calculate the percentage of total sales contributed by each region.
- identify products with no sales in the last quarter.


  #### ***VITUALIZATION IMAGES***:

##### **POWER BI**
  
![Screenshot 2024-10-27 102601](https://github.com/user-attachments/assets/ddddfe90-ec33-4742-bbc6-870df6344f09)



##### ***EXCEL***


![Screenshot 2024-10-25 015555](https://github.com/user-attachments/assets/c065d506-d201-46fe-8c3c-92b1950f4b52)


![Screenshot 2024-10-27 093054](https://github.com/user-attachments/assets/80fab911-e8f3-4909-b3dd-641e800a613e)


![Screenshot 2024-10-25 015531](https://github.com/user-attachments/assets/afddfebe-6f20-4c43-aae3-20c4614987a1)



#### ***SQL***


![Screenshot 2024-10-25 012832](https://github.com/user-attachments/assets/a988d66b-124d-40aa-ad64-43c2384d55db)


![Screenshot 2024-10-25 013013](https://github.com/user-attachments/assets/b2e1d213-5550-4905-a807-67166d1da66b)



![Screenshot 2024-10-25 013219](https://github.com/user-attachments/assets/d2a53113-6a2a-4b6d-941d-4272573b2ab7)





### ***Conclusion:*** 
   From analyzing the sales data, It indicates that ***North*** region and the products **Socks** and **Shirts** are the key drivers of total sales, There is a clear increase in sales around **February 2024** and unit price seems to have a substsantial impact on the total sales volume. The increase in sales of products during specific period shows that the higher demand of product is based on seasons.

  
---


### ***TABLE ANALYSIS FOR CUSTOMER DATA*** : 

### ***Visualization explanation***:

The table provides subscription data for various customers. It includes comprehensive details about various aspects of subscriptions, highlighting key financial and subscription status information. Here’s the detailed breakdown:

#### ***Subscription Details***

 ****SubscriptionType:****

 ****Basic, Standard, Premium****

***SubscriptionEnd:***
 This column shows the end date of each subscription. All entries have the different end date.

 #### ****TOOLS USED FOR VISUALIZATION AND ANALYZING THE TABLE:****

1. ##### **POWER BI**
2. ###### **EXCEL**
3. ##### **STRUCTURED QUERY LANGUAGE(SQL)**

   


 #### ***Key Metrics***

  ***Powerbi***
   
- A Card showing the duration of all subscription to be **One year**. 
- Total Number of Subscribers: ***18,612***
- Total Number of Subscribers who Cancelled:***15,175***
- Average Quarterly Revenue per Customer: ***$1,999***
- A slicer tool that contains the different subcription type, which help to analyze each visuals.


##### ***Excel***
  - A pivot table analyzing the mosth popular subscription type by revenue
  - Customer subscription type by start and end Month.
  - Top ***ten*** customers by revenue.
  - duration of subscription by Revenue.

  #### ***SQL***

  Queries used to analyze the data where:

 - retrieving the total number of customers from each region.
- find the most popular subscription type by the number of customers.
- find customers who cancelled their subscription within 6 months.
- calculate the average subscription duration for all customers.
- find customers with subscriptions longer than 12 months.
- calculate total revenue by subscription type.
- find the top 3 regions by subscription cancellations.
- find the total number of active and canceled subscriptions.

  #### DATA EXPLANATION:
  
1. ### ***Revenue by Subscription Type***

- Bacic Subscription: Generates the highest revenue.
- Premium Subscription: Generates moderate revenue.
- Standard Subscription: Generates the least revenue.
  
2. #### ***Revenue by Region***
  
- East Region: Contributes the most revenue with ***$16,958,763.***
- West Region: Second highest revenue contributor.
- North Region: Third highest revenue contributor.
- South Region: Contributes the least revenue.

3. ####  ***Top Five Customers by Revenue***
The charts and query shows the top five customers which was filtered based on customers who did not cancel their subscription, Indicating **Liam** as the leading top customer with the highest revenue of ***$3,437,444*** spent in subscription.



### ***Visualization***

****POWER BI****

![WhatsApp Image 2024-10-26 at 22 15 18_d3e7fde5](https://github.com/user-attachments/assets/3a0b1637-b645-4875-8c45-ac07bebb64c4)



****EXCEL****


![Screenshot 2024-10-25 015555](https://github.com/user-attachments/assets/cdf35785-6f59-4e9d-8dce-5681502a7c7c)




![Screenshot 2024-10-25 015858](https://github.com/user-attachments/assets/6e6c6bca-1e2a-493a-b079-9410a9ff4702)




![Screenshot 2024-10-25 020036](https://github.com/user-attachments/assets/70638778-22db-41b4-b0ab-1cacd3117f58)





****SQL****



![Screenshot 2024-10-25 013400](https://github.com/user-attachments/assets/071461a8-a2c3-43ff-b0ab-eafabda11a09)


![Screenshot 2024-10-25 013427](https://github.com/user-attachments/assets/5c3486f6-72c5-4002-a2bb-e293afeaddb2)


![Screenshot 2024-10-25 013449](https://github.com/user-attachments/assets/1131c023-e1f7-49e0-910c-e4257d03a6f5)



![Screenshot 2024-10-25 013657](https://github.com/user-attachments/assets/12e155f3-1262-4f10-86d0-a867e9f0932a)






#### ***Conclusion***

The dashboard provides a comprehensive overview of customer subscriptions and revenue distribution. Key insights include:

- The ***Basic*** subscription type is the most lucrative.
- The ***East*** region is the top revenue generator, indicating strong market presence and customer engagement in that area.
- The high cancellation rate is a concern and needs to be addressed to improve customer retention.

  
***Basic Subscription Dominance***: The Basic subscription leads significantly in revenue, showing it is the most popular and widely used.

***Premium and Standard Segmentation***: Both Premium and Standard have moderate revenues, indicating more specific,targeted subscription.

***Subscription Periods and Trends***: Many Basic subscriptions start and end within the same month suggesting possible monthly renewals. 
Premium and Standard show more diverse start and end dates, suggesting varied customer needs or trial periods.

With this analysis, it’s clear which subscriptions are driving revenue and how customer behavior varies across different subscription types.
  
 #### ***Focusing on the South region and understanding the reasons behind cancellations could help in increasing overall revenue and customer satisfaction***.

This detailed analysis can help  the business in strategic planning, identifying areas for improvement, and making informed decisions to drive the business growth. 


