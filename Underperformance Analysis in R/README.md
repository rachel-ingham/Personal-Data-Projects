# Personal Project - Motorcycle Sales Underperformance Analysis in R

### The Prompt
You work in the accounting department of a company that sells motorcycle parts. The company operates three warehouses in a large metropolitan area. You want to analyze their summer sales data. Your colleague wants to capture sales by payment method. She also needs to know the average unit price for each product line. The company would also like to know if there are any major differences between the sales at the three different warehouses so they can address any underperformance issues.

To further investigate the sales at the different warehouse locationhs, I decided to explore the following questions using the sales data:
  1. Which warehouse made the most money?
  2. Which product lines are being sold the most and where?
  3. How are the sales distributed between retail and wholesale clients at each warehouse?
  4. Which month was best for sales at each warehouse?

### The Data
The sales data has the following fields:

- `'date'` The date, from June to August 2021
- `'warehouse'` The company operates three warehouses: North, Central, and West
- `'client_type'` There are two types of customers: Retail and Wholesale
- `'product_line'` Type of products purchased
- `'quantity'` How many items were purchased
- `'unit_price'` Price per item sold
- `'total'` Total sale = quantity * unit_price
- `'payment'` How the client paid: Cash, Credit card, Transfer

![image](https://github.com/user-attachments/assets/fc1a8eb5-15ad-4e83-9e5e-4b350b90833a)

### The Process
- #### Finding Total Sales for each payment method
  - Data was grouped by payment method and summarized to find the total sales amount. A column chart displays the results.  
![image](https://github.com/user-attachments/assets/170ae85d-c2be-4f39-962f-4d148cbb5a70)

- #### Finding Average Unit Price for Each Product Line
  - Data was grouped by product line and summarized to find the average unit price, ordered from highest to lowest. A column chart displays the results.
![image](https://github.com/user-attachments/assets/cb517ac2-e055-498d-8e2f-75fa44e557bd)

- #### Unit Price Spread Boxplot
  - To further confirm that the Engine product line has the highest unit prices (and not just a few high price items that would skew the average unit price), a boxplot comparing the spread of unit prices in each product line is below.
![image](https://github.com/user-attachments/assets/a5b7bfbf-4859-4c43-b712-e573b153beb2)

- #### Finding Total Sales and Top Sellers
  - To answer the questions, "which warehouse made the most money?" and to analyze how sales are distributed between retail and wholesale clients, I grouped data by warehouse and client type, creating a stacked column chart to display the results.
![image](https://github.com/user-attachments/assets/af471111-49e7-4a84-b88c-08c4518422d0)

![image](https://github.com/user-attachments/assets/9462e535-2346-4b80-869b-c75d4efc05e8)

  - To explore which product lines are top sellers at which warehouse, I first found the total quantity of products sold at each warehouse. Then I focused on grouping the data by warehouse and product line to identify differences in sales at the 3 locations. I created a gridded column chart to be able to compare the information at a quick glance. 
![image](https://github.com/user-attachments/assets/bb011c9f-50ce-40e7-99fc-00a1d639b461)

![image](https://github.com/user-attachments/assets/6d5e3e91-fbb3-43df-bee3-7ca6f48481a7)


- #### Month to Month Warehouse Comparison
  - Lastly to determine if sales had any correlation with the month, I grouped the data by month and warehouse then displayed the total sales on a line graph. This allows for easy analysis of the top performing Central warehouse and the underperforming West warehouse.
![image](https://github.com/user-attachments/assets/06e6b4df-4c30-4b14-8126-4d7e3c01af97)


### Results
The majority of the company's sales in June, July, and August come from transfer and credit card payments. Transfer payments account for the most total sales at \$159,642.30 followed by \$110,271.60 total sales in credit card payments. Only about 7% of the total sales are from cash payments. The Engine product line has the highest average unit price at about \$60. The Breaking System product line has the lowest average unit price at just under \$18.

The Central Warehouse had the most summer sales overall, while the West Warehouse had the least sales in both Wholesale and Retail client categories. The sales in each warehouse location are pretty evenly split between the client types, although the West warehouse is the only location where the Retail total sales was slightly higher than the Wholesale total sales. The West warehouse sold about half as many items as the other two locations, which would result in the lowest overall sales. The Central warehouse has increased sales over the summer months, while the West warehouse has seen a decrease in sales. 

### Recommendations
The summer sales data shows that the West warehouse is an underperformer when compared to the other two warehouse locations. There could be many reasons for the lower sales at the West location, so further investigation is needed. Of greatest concern, is the decreasing sales numbers at the West warehouse (almost a 28% decrease). Some possible recommmendations for next steps include: 
  - Investigate if sales techniques are different at the three warehouse locations, can teh Central location provide successful methods?
  - Move some salespeople from the Central location to the West warehouse to improve sales at that location.
  - Analyze where clients are located to determine if clients in the general vicinty of the West warehouse are still chosing to make purchases at Central or North locations. 
  - Increase marketing and advertisements about the West warehouse location, especially if this location is relatively new.
  - Make the West warehouse location specialize in Engine work, since this product line has the highest unit prices and would increase sales totals significantly. Also, this would not conflict with Breaking Systems that are most often sold at the Central location and Suspension products that are most often sold at the North location. 


### Project Link
https://www.datacamp.com/datalab/w/dc4e4c3b-93c0-40b6-8950-f565d873fb18/edit
