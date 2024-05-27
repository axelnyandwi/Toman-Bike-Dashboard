# Toman Bike Shop Power BI Dashboard
This repository contains a Power BI dashboard for Toman Bike Shop, a bicycle retailer. The dashboard utilizes sales data and bicycle cost data to provide insights into hourly revenue analysis, profit and revenue trends, seasonal revenue, and rider demographics.

# Data
The data for this project is provided in two CSV files:

sales_data.csv: This file contains sales data with the following columns:

dteday: Date of the sale
season: Season of the year (1: Spring, 2: Summer, 3: Fall, 4: Winter)
yr: Year of the sale
mnth: Month of the sale
hr: Hour of the sale (0-23)
holiday: Whether the day is a holiday (1: Yes, 0: No)
weekday: Day of the week (1: Sunday, 2: Monday, ..., 7: Saturday)
workingday: Whether the day is a working day (1: Yes, 0: No)
weathersit: Weather conditions (1: Clear, 2: Cloudy, 3: Rainy, 4: Windy)
temp: Temperature
atemp: Feels-like temperature
hum: Humidity
windspeed: Wind speed
rider_type: Type of rider (1: Casual, 2: Enthusiast, 3: Professional)
riders: Number of riders
bicycle_cost_data.csv: This file contains bicycle cost data with the following columns:

yr: Year the bicycle was purchased
price: Retail price of the bicycle
COGS: Cost of goods sold for the bicycle

# Dashboard
The Power BI dashboard consists of several pages that provide insights into different aspects of the business:

Hourly Revenue Analysis: This page shows the hourly revenue for each day of the week, as well as the average hourly revenue for each month.
Profit and Revenue Trends: This page shows the profit and revenue trends over time, as well as the profit margin for each year.
Seasonal Revenue: This page shows the seasonal revenue, as well as the most popular bike types for each season.
Rider Demographics: This page shows the demographics of the riders, including the number of riders of each type and the average spending for each type of rider.

# To use the dashboard
Clone this repository to your local machine.
Open Power BI Desktop and connect to the sales_data.csv and bicycle_cost_data.csv files.
Load the PBIX file from this repository into Power BI Desktop.
Explore the dashboard pages and interact with the visualizations.

# Notes
This dashboard is for demonstration purposes only and is not intended for production use.
The data used in this project is synthetic and does not represent real-world data.
