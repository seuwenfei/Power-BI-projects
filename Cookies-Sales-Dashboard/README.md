# Cookies Sales Dashboard

The data files used in Power BI consist of four separate Order Data files for the years 2022, 2021, 2020, and 2019. Additionally, there is an Additional Information file that contains the customer ID and customer names.

To enrich the Order Data files with customer names, the Additional Information file is utilized. This is achieved through the process of merging queries in the Power Query Editor. The merge operation combines the Order Data files with the Additional Information file based on the common Customer ID column. Since the Order Data files do not have a column for customer names, merging them with the Additional Information file allows the inclusion of customer names in the analysis.

Furthermore, during the query editing process, two additional columns are created: Profit and Lead Time. These columns are derived from the existing data in the order data files through calculations applied within the query editor. The Profit column represents the profitability associated with each order, while the Lead Time column provides information on the time it takes to fulfill and deliver the orders.

Overall, by combining the Order Data files with the Additional Information file and incorporating calculated columns like Profit and Lead Time, the data is enriched and transformed in the query editor, enabling more comprehensive and insightful analysis within Power BI.

## Dashboard
Power BI Dashboard: Cookies Sales

<img width="614" alt="Screenshot (385)" src="https://github.com/seuwenfei/Power-BI-projects/assets/118715799/a2a81d1e-597e-4ad2-bc45-63fd5f1dd50e">

1. **Scorecard**: 
    * **Sum of Sales**: This metric represents the total revenue generated from cookie sales within a specific year. It provides an overview of the overall financial performance, showing the total amount of money earned through sales transactions.
    * **Sum of Cost**: This metric reflects the total expenses incurred in producing and selling the cookies. It includes factors such as raw material costs, manufacturing expenses, packaging, and other associated costs. Monitoring the sum of costs helps assess profitability by comparing it to the sum of sales.
    * **Sum of Profit**: This metric indicates the net income or profit earned after deducting the total costs from the total sales. It represents the financial gain achieved by the business during the specified year.
    * **Sum of Cookies Shipped**: This metric shows the total number of cookies shipped or sold during the given year. It provides insights into the volume of products sold and helps track demand and production requirements.
    * **Average of Lead Time**: This metric represents the average duration from receiving an order to fulfilling it and delivering the cookies to customers. Monitoring the average lead time is crucial for evaluating the efficiency and effectiveness of order processing, production, and delivery operations.


3. **Dual Line and Column Chart**: Utilize a line chart to illustrate the trends in total profit over multiple years. Create a column chart to compare the total sales and costs for each month within a specific year. This visualization assists in identifying the months with the highest and lowest profits, sales, and costs, allowing for a comprehensive analysis of the overall performance within that particular year.
4. **Funnel Chart**: Use a funnel chart to display the profit distribution by flavour for a specific year. Each segment of the funnel represents a flavour, and the size of the segment reflects its proportionate profit. This visualization helps identify the top-profitable flavour within a particular year.
5. **Donut Chart**: Use a donut chart to display the sum distribution by cookie flavour for a specific year. Each ring of the donut represents a flavour, and the width of the ring reflects its proportionate sum. This visualization helps identify the top-selling flavours within a particular year.
6. **Pie Chart**: Use a pie chart to display the sales distribution by customer for a specific year. Each slice of the pie represents a customer, and the size of the slice reflects its proportionate sales. This visualization helps in the identification of the customers with the highest profit during a specific year.



<img width="613" alt="Screenshot (387)" src="https://github.com/seuwenfei/Power-BI-projects/assets/118715799/6ed9c0bb-eaaa-43fc-8b0f-635af019f99f">

The slicer panel above is built for year and customer, offering several benefits in analyzing and exploring the data.

