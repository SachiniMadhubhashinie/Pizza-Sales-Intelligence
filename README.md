# Pizza-Sales-Intelligence
A comprehensive Pizza Sales Report project analyzing key performance metrics using interactive dashboards. Includes insights on best and worst selling pizzas by revenue, quantity, and orders, sales performance by category and size, and identification of peak sales periods across days and months using BI visualizations.

<h2 style="font-size: 1.2em;">Project Overview</h2>
This project is an end-to-end data analysis portfolio piece focused on a pizza sales dataset. The primary goal was to leverage SQL for data extraction and calculation of key business metrics (KPIs) and Power BI/Excel for creating interactive dashboards to visualize key sales trends and performance indicators.

<h2 style="font-size: 1.2em;">Problem Statement</h2>
<p>The business objective was to visualize various aspects of the pizza sales data to gain insights and understand key trends. Specifically, we needed to analyze business performance through key indicators and visualize order patterns, customer preferences, and sales distribution.</p>


<h2 style="font-size: 1.2em;">Technology Stack</h2>
<ul>
  <li><strong>Database & ETL:</strong> SQL (used for querying, calculating KPIs, and aggregating data for visualizations).</li>
  <li><strong>Visualization:</strong> Power BI / Excel (used for data modeling, DAX/formulas, and dashboard design).</li>
</ul>


<h2 style="font-size: 1.2em;">Key Performance Indicators (KPIs) Required</h2>
<p>We calculated the following essential business metrics:</p>
<ol>
  <li><strong>Total Revenue:</strong> The sum of the total price of all pizza orders.</li>
  <li><strong>Average Order Value:</strong> The average amount spent per order (Total Revenue / Total Orders).</li>
  <li><strong>Total Pizzas Sold:</strong> The sum of the quantities of all pizzas sold.</li>
  <li><strong>Total Orders:</strong> The total number of orders placed.</li>
  <li><strong>Average Pizzas Per Order:</strong> The average number of pizzas sold per order (Total Pizzas Sold / Total Orders).</li>
</ol>


<h2 style="font-size: 1.2em;">Chart Requirements & Analysis</h2>
<p>The dashboard was structured to meet the following visualization requirements:</p>
<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th>#</th>
      <th>Requirement</th>
      <th>Chart Type Used</th>
      <th>Insight Gained</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Daily Trend for Total Orders</td>
      <td>Bar Chart</td>
      <td>Helped identify patterns or fluctuations in order volumes on a daily basis.</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Monthly Trend for Total Orders</td>
      <td>Line Chart</td>
      <td>Illustrated the trend of total orders throughout the year to identify peak periods.</td>
    </tr>
    <tr>
      <td>3</td>
      <td>Percentage of Sales by Pizza Category</td>
      <td>Pie Chart</td>
      <td>Showed the distribution of sales across different categories and their popularity.</td>
    </tr>
    <tr>
      <td>4</td>
      <td>Percentage of Sales by Pizza Size</td>
      <td>Pie Chart</td>
      <td>Represented the percentage of sales attributed to different pizza sizes to understand customer preferences.</td>
    </tr>
    <tr>
      <td>5</td>
      <td>Total Pizzas Sold by Pizza Category</td>
      <td>Funnel Chart</td>
      <td>Presented the total number of pizzas sold for each category to compare sales performance.</td>
    </tr>
    <tr>
      <td>6</td>
      <td>Top 5 Best Sellers</td>
      <td>Bar Chart</td>
      <td>Highlighted the most popular pizzas based on Revenue, Total Quantity, and Total Orders.</td>
    </tr>
    <tr>
      <td>7</td>
      <td>Bottom 5 Best Sellers</td>
      <td>Bar Chart</td>
      <td>Showcased the least popular/underperforming pizzas based on Revenue, Total Quantity, and Total Orders.</td>
    </tr>
  </tbody>
</table>


## Key Insights & Recommendations

Based on the analysis of the pizza sales data, several key business drivers and performance indicators were identified:

### Business Performance (KPIs)
- **Total Revenue:** Approximately $817,860 generated from 21,350 total orders.  
- **Average Order Value (AOV):** ~$38.31, indicating customers typically purchase around 2.32 pizzas per order.

### Product & Sales Performance
- **Top Performers:** The top-selling pizzas by revenue are dominated by chicken options, led by *The Thai Chicken Pizza* and *The Barbecue Chicken Pizza*.  
- **Worst Performers:** The least popular item by revenue is *The Brie Carre Pizza*.  
- **Category Dominance:** The Classic pizza category contributes most to total sales and pizzas sold, followed by Supreme and Veggie.  
- **Size Preference:** Large (L) size is overwhelmingly preferred, accounting for 46.37% of sales.

### Order Trends (Time Series)
- **Peak Days:** Friday and Saturday see the highest order volumes, followed by Thursday, indicating strong weekend demand.  
- **Peak Months:** July and May have the highest total orders, suggesting seasonal trends or successful summer campaigns.

### Data-Driven Recommendations
1. **Optimize Marketing & Staffing:** Increase staffing and targeted marketing (e.g., weekend deals) on Fridays and Saturdays to maximize service efficiency.  
2. **Inventory Focus:** Prioritize inventory and preparation for Large-size pizzas to prevent stockouts.  
3. **Menu Review:** Investigate low-sales items like *The Brie Carre Pizza*. Consider targeted promotions or menu simplification.  
4. **Promote Chicken Pizzas:** Prioritize chicken-based pizzas in visual merchandising and promotional bundles as they are top revenue generators.













