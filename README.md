![banner](Assets/Banner.jpg)

# US-Sales-Data-Analysis-On-Excel
_A client has shared a sales dataset and seeks insights, including sales trends over time, state-wise sales comparison, monthly sales analysis, identifying top-profit customers, and evaluating product category performance._

## Author
- [@saadharoon27](https://github.com/saadharoon27)

## Table of Contents
- [Business Problem](#business-problem)
- [Data Source](#data-source)
- [Data Overview](#data-overview)
- [Method](#method)
- [Quick Glance At The Dashboard](#quick-glance-at-the-dashboard)
- [Data Cleaning and Manipulation](#data-cleaning-and-manipulation)
  
## Business Problem
**Business Problem Statement:** <br>
A client has provided their sales dataset and requested insights from the data, focusing on several factors such as changes in sales orders over the years, a comparison of sales data across different states, monthly sales volume analysis, identification of top-profit-generating customers, and an evaluation of the performance of various product categories

## Data Source
- [US Store Sales Dataset](https://www.kaggle.com/datasets/saadharoon27/us-store-sales-dataset)

## Data Overview
| **Column Name**     	            | **Description**     |
|-------------------	              |------------------	  |
| **Order Date**     	              | Consists the date on which a specific order was created |
| **Customer Name**    	            | Consists the full name of the customer who created an order|
| **State**               	        | Name of the state the customer belonged to|
| **Category**     	                | Which category did the ordered product belong to |
| **Sub-Category**    	            | Name of the sub-category of the ordered product|
| **Product Name**               	  | Name of the ordered product|
| **Sales**     	                  | The price at which the product was sold|
| **Quantity**    	                | Number of quantities the customer ordered of that product|
| **Profit**               	        | How much did the firm make in that transaction|

## Method
- Exploratory data analysis _(EDA)_

## Quick Glance At The Dashboard
![dashboard](Assets/Glance.png)

## Data Cleaning and Manipulation
To create efficient pivot tables and dashboards with the provided data, the initial step involved converting the data into a structured table named _‘SalesData’_ using the **"create table"** option. This transformation enhances data organization, making it more conducive for effective analysis and visualization.<br>

**Column Treatment and Adjustments:**<br>
- 1.	**Sales Column:** The _‘Sales’ column_ was in a general format, which could have potentially cause issues when creating visual representations. To ensure smooth visual plotting, it was necessary to convert the values into a **Number format.**
- 2.	**Quantity Column:** The same goes for the _‘Quantity’ column_, removed the decimal places.
- 3.	**Profit Column:** And the _‘Profit’ column_.
- 4.	**Order Date Column:** The _'Order Date' column_ was converted into a date format and subsequently organized in ascending order, from the oldest dates to the most recent ones. This action ensures that the data is chronologically arranged.
- 5.	**Month Column:** A new column was added, _'Month'_, to enable data visualization in monthly terms. The data underwent a transformation process using the **TEXT() function** to extract the month. Subsequently, this function was further refined to display the month in a more user-friendly manner using **'mmm'**, in format text argument. This adjustment enhances the clarity of the data representation.
- 6.	**Year Column:** A new column was added, _'Year'_, to enable data visualization in yearly terms using the **YEAR() function**.

