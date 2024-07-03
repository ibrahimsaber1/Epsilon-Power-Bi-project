# Power BI Sales Dashboard

This project is a comprehensive sales dashboard created using Power BI. It provides an interactive and insightful view of sales data across different regions, products, and years.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Model](#data-model)
- [Dashboard Explanation](#dashboard-explanation)
- [Key Measures](#key-measures)
- [Functions and Clusters](#functions-and-clusters)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This Power BI project visualizes sales data from various dimensions such as region, product, and year. It allows users to interact with the data and derive insights related to total sales, total profit, number of customers, number of orders, and average shipping days.

## Data Model
The data model consists of the following tables:
- **Orders**: Contains information about orders including Order ID, Order Date, Shipping Date, etc.
- **OrderDetails**: Details of each order including Product ID, Quantity, Unit Price, Discount, etc.
- **Products**: Product-related information like Product ID, Product Name, Category ID, Unit Price, etc.
- **Categories**: Categories of products.
- **Suppliers**: Supplier information.
- **Customers**: Customer details.
- **Employees**: Employee information.
- **Calendar**: A calendar table to manage date-related data.

![Data Model](https://raw.githubusercontent.com/ibrahimsaber1/Epsilon-Power-Bi-project/main/image/3.jfif)

## Dashboard Explanation
The dashboard is divided into several sections:

### Overview
- **Total Sales**: The total revenue generated from sales.
- **Total Profit**: The total profit made.
- **Number of Customers**: The total number of customers.
- **Number of Orders**: The total number of orders.
- **Average Shipping Days**: The average number of days taken to ship orders.

### Filters
The dashboard includes filters for different regions (USA, UK, Canada, etc.) to allow users to drill down into specific data.

### Detailed Data
- **Company-wise Sales and Profit**: Shows sales and profit data for different companies from 1996 to 1998.
- **Category-wise Sales and Profit**: Displays sales and profit data for different product categories.
- **Product-wise Sales and Profit**: Provides detailed sales and profit information for individual products.

### Charts
- **Sales and Profit by Category**: A pie chart showing the distribution of sales and profit across different product categories.
- **Order Size Distribution**: A pie chart showing the distribution of orders by size (Small, Normal, Big, Very Big).
- **Sales and Profit Over Time**: A line chart showing the trend of sales and profit over the years.
- **Geographical Distribution**: A map highlighting sales data across different regions.

![Dashboard Image 1](https://raw.githubusercontent.com/ibrahimsaber1/Epsilon-Power-Bi-project/main/image/1.jfif)
![Dashboard Image 2](https://github.com/ibrahimsaber1/Epsilon-Power-Bi-project/blob/main/image/2.jfif)

## Key Measures
Key measures used in this dashboard include:
- **Total Sales**: Sum of sales across all orders.
- **Total Profit**: Sum of profit across all orders.
- **Number of Customers**: Count of distinct customers.
- **Number of Orders**: Count of total orders.
- **Average Shipping Days**: Average of the shipping days for all orders.

## Functions and Clusters
This section explains the functions and clusters used to create the dashboard:

- **Calculated Columns and Measures**: Various DAX (Data Analysis Expressions) functions are used to create calculated columns and measures for accurate data representation.
- **Relationships**: Proper relationships between tables are established to ensure data integrity and accurate calculations.
- **Filters and Slicers**: Interactive filters and slicers are used to allow users to drill down into specific data points and analyze data from different perspectives.
- **Visualizations**: A variety of visualizations such as bar charts, line charts, pie charts, and maps are used to present the data in an intuitive and meaningful way.

## Usage
To use this dashboard, load the data into Power BI Desktop and navigate through the different tabs and filters to interact with the data.

## Installation
1. Clone this repository.
2. Open the Power BI Desktop.
3. Load the data model into Power BI.
4. Configure the data sources and refresh the data.
5. Explore the dashboard.

## Contributing
Contributions are welcome! Please fork this repository and submit pull requests with improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
