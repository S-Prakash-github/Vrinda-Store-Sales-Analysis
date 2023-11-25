# Vrinda-Store-Sales-Analysis🛒
<a href="[https://docs.google.com/spreadsheets/d/your_spreadsheet_id/edit](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/blob/main/Vrinda%20Store%20DASHBOARD.xlsx)" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Google%20Sheets-Open%20Document-brightgreen" alt="Google Sheets"></a>

#### Project Objective
The Vrinda Store wants to create an annual sales report for 2022. So that, the owner of the Vrinda store can understand their customers and grow more sales in 2023.

## Data Cleaning 
- Fix spelling Mistakes in Gender Column:Use the find and replace method to correct spelling mistakes and variations in the 'Gender' column. Create a mapping dictionary to standardize gender values (e.g., 'to'male', 'female' to 'Female', 'f' to 'Female').Clean Duplicates in order_id:

- Remove duplicate rows based on the 'order_id' column to ensure uniqueness.
- Create Age Bracket Column: Used the if function to categorize ages into brackets. For example, create an 'Age Bracket' column with labels like 'Teenage' for ages till 29, 'Adult' for ages 30 to 49, and 'Senior' for ages 50 and above.
Create Month Column from Date:
- Extract the month from the 'Date' column and create a new column, 'Month', to represent the month in a readable format (e.g., 'January', 'February', etc.).


## FINAL DASHBOARD
[View Dashboard](https://docs.google.com/spreadsheets/d/e/2PACX-1vQ37boO88R6UBJxP5mvcDLrO8zk1rU-LRICCJR04XHl9k_OOo_lTNfSQEmeh40PBA/pubhtml)

[Dashboard](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/blob/main/Vrinda%20Store%20DASHBOARD.xlsx)

![Screenshot 2023-11-25 170938](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/413ba19b-0ae7-4beb-bed1-9208db859211)



### 💢 FILTERS
![Screenshot 2023-11-25 164121](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/8b2e35f6-9773-47dc-a936-92418cbb438e)
>The incorporation of dynamic filters for month, status, and category enhances the interactivity and analytical depth of the dashboard. Users can easily navigate and explore deep insights by dynamically adjusting these filters. Whether examining sales trends over specific months, monitoring the status of orders, or delving into product categories, the dynamic filters provide a user-friendly and efficient means of interacting with the dashboard.



## Objective

### 💢To find the Sales and number of orders in a single chart? Which Month is having the highest sales?

![Screenshot 2023-11-25 134525](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/fff1db31-c6bd-4a21-92b4-1d98fdf71c43)

- Pivot Table Creation:Generated a pivot table that aggregates sales data by month, calculating both the total sales amount and the count of orders for each month. This provides a concise summary of sales performance over time.
- Combo Chart Visualization: Utilized a combo chart to visually represent the sales data. The chart comprises columns to depict the sales amount and a trend line to illustrate the quantity of products sold for each corresponding month.
- Key Observations: Identified March as the most successful month based on the visual representation.Noted a substantial sales amount of over 19 lakh and a high quantity of products sold, with approximately 2800 items in that particular month.
  

### 💢 Who purchased more Men or Women?

![Screenshot 2023-11-25 134208](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/8588a602-81c7-4293-92d3-61066f1ddab3)

- Analysis of Purchases by Gender:Conducted an examination to determine the purchasing behavior based on gender.
- Pivot Table Creation: Developed a pivot table with 'Gender' as one axis and the 'Amount' column to quantify the purchase amounts made by both men and women.
- Pie Chart Visualization: Utilized a pie chart to visually represent the distribution of purchases between men and women. The chart segments were based on the aggregated purchase amounts.
- Key Findings: Discovered that women make a substantial contribution to the overall purchases, constituting a significant share of 64%.Men, while still making notable purchases, represented a slightly smaller share at 35%.
> In summary, the analysis and visual representation, through the pivot table and pie chart, revealed that women contribute more significantly to the total purchase amounts compared to men, holding a majority share in the observed data.



### 💢 What are the different order statuses?
![Screenshot 2023-11-25 161422](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/64417ed3-eec3-4092-853d-ac2698c4f0f6)

-Order Status Analysis: Examined the distribution of orders based on different order statuses, which include 'Return,' 'Refunded,' 'Delivered,' and 'Cancelled.'
- Pie Chart Visualization: Created a pie chart to visually represent the share of each order status category. Each slice of the pie corresponds to one of the order status categories.
- Key Observations: Noted that the 'Delivered' status dominates the order distribution, contributing a substantial 92% share.The remaining 8% is distributed among other order statuses, including 'Return,' 'Refunded,' and 'Cancelled.'
> In conclusion, the pie chart provides a clear overview of the order status distribution, emphasizing that the majority of orders are successfully delivered. The visualization highlights the relative proportions of each order statuscategory, with 'Delivered' standing out as the predominant status.



### 💢 List top 5 States?
![Screenshot 2023-11-25 154601](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/d9fbdef8-19c1-4957-9897-2899f29d159c)
- Objective:Aimed to visually represent the distribution of sales across different states, focusing specifically on identifying the top 5 states with the highest sales.
- Histogram Chart Creation:Constructed a histogram chart to display the sales distribution among various states. The chart highlights the frequency or count of states falling within different sales ranges.
> The histogram chart analysis reveals that this 5 states stands out as the highest sales among the dataset. This insight provides a clear understanding of the geographic concentration of sales, emphasizing the significance of Maharashtra in contributing to the overall sales figures.



### 💢 Total Sales and Quantity Sold 
![Screenshot 2023-11-25 154549](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/1a65cee4-4461-4f93-b718-47e669ec4358)
- This card visual was introduced to offer a quick and concise representation of key metrics. The card visual prominently displays the aggregate sales and quantity sold, providing at-a-glance insights into the overall performance.
> By applying filters, it becomes apparent that more than 2600 products have been successfully delivered, contributing to total sales surpassing 19.7 lakh. This dynamic modification capability provides users with a more granular and focused view of specific metrics, fostering a deeper understanding of the dataset and facilitating more informed decision-making.



  
### 💢Relationship between age and gender with orders?
![Screenshot 2023-11-25 154535](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/8e162790-12f1-422f-86d1-3701ed519ff0)

- Objective: Explored the distribution of sales across various age groups based on gender, with a focus on understanding the sales contribution of women compared to men.
- Pivot Table Creation: Developed a pivot table to aggregate sales data by gender and age groups, facilitating a detailed analysis of sales distribution.
- Column Chart Visualization: Utilized a column chart to visually represent the percentage share of sales for each gender within different age groups. Notably, the chart highlights the higher contribution of women compared to men.
- Key Insights: The column chart underscores that women make a substantial contribution to the overall sales, surpassing the contribution from men.Approximately 50% of the total sales share is attributed to the adult age group, with the remaining sales distributed among the teenager and senior age groups.
> In conclusion, the visual representation reveals that women play a significant role in contributing to sales, and the majority of sales are concentrated in the adult age group. This analysis provides valuable insights into the gender-wise and age-wise dynamics of sales distribution.


### 💢 Which channel is contributing the maximum sales?
![Screenshot 2023-11-25 154541](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/b438446b-db91-4fc4-8eaf-41d52594456e)

>A bar chart analysis underscores Amazon's clear dominance as the top-performing channel. The visual representation highlights Amazon's substantial contribution compared to other channels, providing a quick and easily interpretable insight into the hierarchy of sales channels. This observation can guide strategic decisions and resource allocation to further leverage the strength of Amazon in the overall sales strategy.

### 💢Highest Selling Category
![Screenshot 2023-11-25 170500](https://github.com/S-Prakash-github/Vrinda-Store-Sales-Analysis/assets/91363429/61a51dd8-3759-4c74-8b99-8d63c4583c7b)
> The highest selling category is Set

## Insights Report:

### 1. Demographic Analysis:

Gender Preference: Women dominated our customer base with a significant 65% more purchases than men. This underscores the importance of catering to the preferences of our female audience.
Age Group Trends: Adults, particularly those aged 30 and above, emerged as our primary buyers. This suggests a market stronghold in this age demographic.
### 2. Channel and Regional Performance:

Sales Channels: Amazon, Flipkart, and Myntra were standout performers, indicating a strong market presence on these platforms.
Top Selling State: Maharashtra emerged as the top-selling state, showcasing a geographical stronghold.
### 3. Order and Delivery Insights:

Order Fulfillment: The majority of orders were successfully delivered, indicating a reliable delivery channel.
Implication: Maintaining the current delivery infrastructure seems viable for the time being.
### 4. Opportunities for Improvement:

Targeting Male Audience: To boost sales, a targeted approach towards the male demographic is recommended. Consider diversifying product offerings to include more male-oriented items.
Product Portfolio: The 2022 product lineup leaned heavily towards women's items. In 2023, a strategic shift to include more sections for males could tap into an untapped market.
Marketing Strategy: Run targeted advertisements to inform male customers about the expanded product range, emphasizing that their preferences have been acknowledged.
### 5. Senior Citizen Engagement:

Observation: Senior citizens seem less engaged, possibly due to navigation challenges on our platform.
Recommendations: Develop a user-friendly introductory guide for using our platform, simplifying the shopping experience for seniors. Additionally, implement targeted ads and coupon codes to encourage sales across all age sectors.
### Conclusion:
The insights gathered present a comprehensive understanding of our customer base, sales channels, and potential areas for improvement. By addressing the highlighted opportunities and refining our product strategy, we can further enhance customer satisfaction and drive increased sales in 2023.

