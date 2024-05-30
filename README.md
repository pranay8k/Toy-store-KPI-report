# Toy-store-KPI-report
Interactive KPI report to track key metrics and explore high-level trends 🤖 



Review table columns, check for blank or null values, confirm that datatypes are accurately defined, and identify any primary and foreign keys



Take a moment to profile the data. How many transactions were recorded? 



How many stores does Maven Toys operate? What are the lowest and highest priced products?



Add calculated columns in the calendar table for ‘start of month’ and ‘start of week’



Load the tables to the data model and create relationships from the sales table to the products, stores, and calendar tables



Confirm that you are following data modeling best practices. Your model should take the form of a star schema, with 1: many relationships between fact and dimension tables



Create a date hierarchy containing the ‘start of month’, ‘start of week’, and ‘date’ fields



Hide all foreign keys in the sales table from the report view



Create calculated columns in the sales table to pull in ‘cost’ and ‘price’ from the products table, then use those fields to calculate revenue and profit for each transaction



Create measures to calculate the count of orders (‘total orders’), sum of revenue (‘total revenue’) and sum of profit (‘total profit’)



BONUS: Define new measures to calculate total revenue and profit without referencing the calculated columns in the sales table



Add KPI card visuals showing ‘total orders’, ‘total revenue’ and ‘total profit’ for the current month, along with monthly trends for each metric

Total Order by Month = 41830

Revenue by Month = 658.19K

Total Profit by Month = 180.45K



Add a slicer to filter the report page by store location



Add a bar chart showing ‘total Profit’ by product category, store location and a line chart showing ‘total revenue’ with the date hierarchy on the x-axis 

with drill up and down 



Assemble the charts into a logical layout and adjust formatting, alignment and polish to finalize the report as you see fit
