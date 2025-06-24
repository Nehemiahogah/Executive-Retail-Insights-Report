# Novamart Sales & Product Insights Report
### Project Background
Nova mart Ltd. is an e-commerce company that sells variety of products worldwide through its website and app.

The company has significant amount of data on its sales, products and customers and the region of these customers. This report analyzes this data that spans the range of (2023 - 2024) and will be used by the sales and product team to better enhance the business.

Insights And Recommendation are provided on the following key areas based on what each team wanted to know:

 Sales Team wanted to know;
  - What is the overall monthly sales trend, and are there any clear seasonal peaks or drops?
  - Which regions or states are generating the highest and lowest sales revenue?
  - Who are our most valuable customer segments based on total purchase value?
  - Which brands or products are underperforming and may need attention or replacement?
  - What percentage of total sales comes from our top-performing products or categories?

 Product Team wanted to know;
  - Which product categories are driving the most sales?
  - Which product brands/types are growing or declining over time?
  - Are certain product types more popular in certain regions or segments?
  - How diverse is our product portfolio in terms of sales distribution?
  - What are the top 3 product category in each country that drives our sales
  - What brand drives most sales in each customer segment and age group? 

### Data Structure Overview
  Novamart Ltd. retail transactional data contains information about customers, their purchases, products, and transaction details. The data includes various attributes such as customer ID, name, email, phone, address, city, state, zipcode, country, age, gender, income, customer segment, last purchase date, total purchases, amount spent, product category, product brand, product type, feedback, shipping method, payment method, and order status.
  The company's dataset has a rowcount of over 302,000 rows where each row contains a unique transaction in the company over the course of two years (2023 - 2024)

![Image](https://github.com/user-attachments/assets/c3ad35b3-47f1-4dee-baab-a872e6e9a6c0)

Prior to starting my analysis, I cleaned the data set and the thought process and everything I did in my data leaning process can be found in my issue log here

###   Executive Summary
Novamart Ltd. analysis of over **302k records** across **2023-2024** shows a **20%** **decline** of sales amount in 2024 as compared to 2023, with this **decline** being consistent among the months when compared to months of the previous year showing that there is definitely a factor contributing to this. **Adults(25-64)** contribute **60%** of **total sales**, while our **regular** and **premium customers** contribute **69%** of our total sales.
    For the products **Pepsi** has being the most sold out brand for the last two years. 

Below is the overview page from the excel dashboard and more examples are included throughout the report. The entire interactive dashboard can be seen here

![Image](https://github.com/user-attachments/assets/46e2d404-f796-45dc-b22f-1fe9ff41656b) 

###   Insights Deep Dive
   - Sales Team Insights 
     - Sales peaked in April 2023, recording over 201,000 orders and generating more than $51 million in revenue.
However, starting March 2024, sales experienced a significant drop, with monthly revenue not rising above $6 million primarily due to a decline in order volume throughout the year.

![Image](https://github.com/user-attachments/assets/3aea3d19-638c-4a02-b281-40c79e8e95c3)
     
     - Year-over-year growth was only observed in January and February 2024, attributed to a temporary increase in order quantities during those months.
Other months showed a decline in sales compared to 2023.

![Image](https://github.com/user-attachments/assets/d967ed2a-62de-4b1b-acb0-99dc0e44812e)

     - The United States consistently generates the highest revenue, followed by the United Kingdom. Together, they contribute 52% of total global sales, while Canada lags behind as the lowest-performing country.
On a city level, Chicago contributes the most, whereas Kansas records the lowest sales.
     - The 25–64 age group (Adults) accounts for 60% of total sales, making them the company’s most valuable age demographic. Among customer segments, Regular customers contribute 48% of sales, highlighting their importance in retention and revenue stability.
     - Brands such as Whirlpool, Bluestar, and Mitsubishi are underperforming, generating less than half of the average brand sales value ($11 million).
Additionally, products like Granola Bars, Package AC, Parka, Razer Blade, and Wrench are among the 10 least-performing products.
     - The Top 10 best performing product (alkaline water, artesian water, bottled water, coconut water, distilled water, flavored water, mineral water, mystery, sparkling water, spring water) contribute to 8% of the total sales and for the top performing category (Electronics) contributes 23.6% of total sales.
   - Product Team Insights
     - The Electronics category consistently drives the most revenue across both 2023 and 2024, underscoring the value and demand for everyday tech products.
The Motorola Moto ranks as the highest selling item within this category.
     - Product preferences vary by region:
In the U.S., Water is the most popular product type — likely driven by weather-related demand.
In the U.K., Non-Fiction books top the sales chart, suggesting a strong literary consumption pattern.
     - Our product portfolio shows moderate diversity. Electronics alone contributes 24% of total revenue, while Grocery follows closely with 22%. The remaining categories (Books, Clothing, Home Decor) each contribute around 18%
     - The top three category of products that drives our sales in each country is shown below
     - Pepsi is the most popular brand for the three customer segment (New, Regular and Premium), while for the age brackets (Pepsi is the most popular for adults, Apple brand for children, Samsung for seniors and youths )

### Recommendation
   - Initiate a deep-dive sales audit starting March 2024 to identify key drivers behind the decline (e.g., supply chain, seasonality, product availability).
Launch recovery campaigns or incentive promotions in historically strong months to regain momentum.
   - Analyze marketing, pricing, and product strategy during these two months. Replicate successful tactics in upcoming quarters and incorporate them into a seasonal sales playbook.
   - Double down on high-performing markets (USA & UK) with localized promotions and supply optimization, while conducting a market potential assessment for Canada to decide on investment vs divestment strategies.
   - Review these poor-performing brands and products to understand why they’re not selling well (e.g., too expensive? not popular?). If there’s no improvement, consider removing them or replacing them with better-selling products. Also, talk to the sales or product team about discounting or promoting these items to help clear out slow-moving stock.
   - In the U.S., run water product deals or features. In the U.K., push non-fiction books more — both online and in promotions. This will help give people what they already like, and improve sales.
   - Target ads based on age:
     - Promote Pepsi to adults
     - Use fun Apple-themed ads for kids
     - Highlight Samsung’s features for young and older people. This way, each age group sees the brand they like, and we can improve sales by speaking directly to their preferences.

          



          

 
