# Super Store Sales Dashboard using Power BI

### Software & Tools Required
1. [Power BI] (https://www.microsoft.com/en-us/download/details.aspx?id=58494)
 
### Objective:
To contribute to the success of a business by utilizing data analysis techniques, specifically focussing on time series analysis, to provide valuable insights and accurate sales forecasting.

### Description:
The objective can be broken down into the following detailed components:

#### 1. Dashboard Creation: 
Identify the KPIs, design an intuitive and visually appealing dashboard, and add interactive visualizations & filtering capabilities to allow users to explore the data at various levels of granularity.

#### 2. Data Analysis: 
Provide valuable insights to business entities regarding the effectiveness of their sales through visualizations and charts.

#### 3. Sales Forecasting:
Leverage historical data and apply time series analysis to generate sales forecasting for the next 15 days.

#### 4. Actionable Insights and Recommendations:
The end goal is to share valuable insights and actionable information that can drive strategic decision-making and support the supermarket's goals for growth, efficiency, and customer satisfaction goals.

### Imported & Cleaned Data (Data Cleaning):
1. For this analysis project, a comma-separated file (.csv) file was utilized.
2. Power query was used to impart necessary changes in the dataset before analysis was conducted.
3. The dataset contained some blank/empty columns which were removed.
4. The 'Returns' column contained 2 kinds of values '#N/A' and '1'. The '#N/A' value was replaced with '0'.

### Dashboard Creation and Dax Calculations:
1. Clustered bar charts were used to display Sales by Category, Sales by Subcategory, and Sales by Ship Mode respectively.
2. Area Charts were used to represent Monthly Sales YoY and Monthly Profit YoY respectively.
3. Map was created to showcase profit and sales by state.
4. A new column 'AvgDelivery' was created using dax query to calculate and show the average delivery time between the order date & ship date.
5. Cards were used to show the sum of orders, sum of sales, sum of profits, and ship Days (i.e. average delivery time).
6. A slicer was used to make the dashboard interactive and slice down the analysis on the basis of region.
7. Donut charts were utilized to analyze the proportion of contribution to the total sales by each element of payment mode, region, and segment respectively.
8. Another clustered bar chart was created to exhibit sales by state & analyze the top 10 best-performing states in terms of sales.

### Sales Forecasting:
1. A line chart was created for forecasting.
2. Time series analysis was conducted using this line chart. For this, sales record was paired with order date.
3. In the visualization pane, there is an 'Analytics' feature, which was used to add further analysis. In 'Analytics', there is a tool called 'Forecast' which was utilized to forecast sales for the next 15 days.
4. A copy of this line chart was created and a zoom slider was added for clear visualization of forecasted value.
5. A new table was created and in it, using dax query, a new column 'SalesForecast' was created. 'Summarize' method was used to group the sales according to date as the data contained duplicate date records.

### Insights:
1. Sales on the basis of 'Cash On Delivery' mode of payment were highest (43%), followed by 'Online' (35%) and 'Cards' (22%).
2. 'West' region had the highest proportion of contribution to the total sales of the store (33%) followed by the 'East' region (29%), 'Central' (22%), and 'South' (16%).
3. 'Consumer' segment contributed the most to the total sales by 48% margin followed by 'Corporate' (33%) and 'Home Office' (19%).
4. In 2019, the month of November recorded the highest sales (78399.04) whereas in the year 2020, the month of December captured the highest sales (166185.85) in comparison to other months in both years. 
5. In 2019, the month of December documented the highest profit (17885.31) whereas in 2020, the month of November registered the highest profit (9275.28) in comparison to other months in both years.
6. 'Standard class' ship mode tabulated for the highest sales (9,12,401.04) in comparison to other shipping modes {(Second Class - 3,14,508.06), (First Class - 2,42,936,72),  (Same Day - 95,958.50).
7. When analyzing Sales by Category, 'Office Supplies' showcased the highest proportion of total sales of the stores (6,43,707.69) as compared to 'Technology' (4,70,587.99) and 'Furniture' (4,51,508.65).
8. While analyzing Sales by Sub-Category, 'Phones' logged the highest sales (1,96,563.55) as compared to 'Chairs' (1,81,946.00), 'Binders' (1,74,978.39) and 'Storage' (1,50,351.32).
9. The forecasted sales for the next 15 days (from 31 December 2020 to 14 January 2021) is 5,304.19.
10. The state of California chronicled the highest sales (3,35,190.26) as compared to other states.
11. In both years, the total orders placed to the store amounted to 22,000 with 1.6 Million sales and 1,75,00 profit. Also, the average ship days turn out to be 4 days.

### Learning:

Incorporated data analysis techniques, specializing in time series analysis to deliver valuable insights, accurate sales forecasting, and interactive dashboard creation, driving business success.

