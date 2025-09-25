# sales-analytics
📌 Overview

This repository contains a Product Sales Dashboard built using Power Query and Excel. The dashboard processes raw sales data (from Product_Sales.xlsx) to provide insights into agent performance, product sales, and customer interactions.

🛠 Data Processing (Power Query)

The dataset is transformed using Power Query Editor with the following applied steps:

1. Source – Load sales data from Product_Sales.xlsx.


2. Navigation – Select the Product_Sales table.


3. Promoted Headers – Use the first row as column headers.


4. Changed Type – Convert columns to correct data types (AgentID, CallID, CustomerID, Duration, ProductSold).



Columns in Dataset

AgentID – Unique identifier for sales agent.

CallID – Call reference number.

CustomerID – Customer identifier.

PickedUp – Whether the call was picked up.

Duration – Duration of the call.

ProductSold – Number of products sold in a call.

Agent_Name – Name of the sales agent.


📈 Dashboard Insights

Compare Total Products Sold, Duration, and Agent Participation.

Visualize performance through clustered column charts and KPIs.

Identify top-performing agents and areas for improvement.


🎯 Key Benefits

Automates data cleaning and transformation with Power Query.

Provides clear visualizations of sales performance.

Supports decision-making by tracking KPIs.


🚀 Usage

1. Clone or download this repository.


2. Open Product_Sales.xlsx in Excel / Power BI.


3. Refresh data in Power Query to apply transformations.


4. Explore the dashboard to analyze sales trends and agent performance.
