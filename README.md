# -Almabetter-Hotel-Booking-EDA-Project-Vishwajeet-Salunkhe

Almabetter Hotel Booking EDA Project Using Python || Vishwajeet Salunkhe's Hotel booking analysis with AlmaBetter EDA This project relates to hotel reservations and includes a variety of city hotels and resort hotels. 
There are 32 columns and a total of 119390 rows in this dataset. 
Data collection, data cleansing and manipulation, and EDA (experimental Data Analysis) are the three categories into which the workflow for data manipulation is divided. 
The names of some of the columns, including hotel, is_canceled, lead_time, arrival_date_year, arrival_date_month, arrival_date_week_number, arrival_date_day_of_month, and stays_in_weekend_nights, have been updated as the data collection process has progressed. 
This is done by coding Head(), Tail(), info(), describe(), columns(), and other methods used for data collection. As we proceed, we identify the distinct value for each column, create a list in tabular format, and also verify the dataset type for every column. 
Identify some columns with inaccurate data types and fix them afterward. As we discover duplicate items totaling 87396, which are later discarded from the dataset, duplicate data items must also be removed during the data cleaning phase.

We must first perform data manipulation before visualizing any data from the data source. To do that, we examined each column's null value. 
After checking, drop the column using the 'drop' method if we find one that has a greater percentage of null values. We are so removed from the "company" column. When there are only a few null values, we fill those null values with the necessary values using the formula.fill().

To achieve greater understanding and business goals, many charts are utilized for data visualization.

