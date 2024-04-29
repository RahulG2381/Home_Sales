# Home_Sales
## Introduction
This Challenge is for using the knowledge of SparkSQL to determine key metrics about home sales data.
## Data Preparation
To answer the  follwing questions dataset have been prepared by using following steps:
<br>•	converted the datatypes for the columns to appropriate datatypes.  E.g date columns to date, other numerical columns has been converted form string to integers. 
<br>•	Extracted and added new year column from date columns

## Answer the following questions using SparkSQL:
1.	What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
 ![image](https://github.com/RahulG2381/Home_Sales/assets/148564779/742b55c6-2156-40ed-b292-c469a354f7d1)

2.	What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
 <br>![image](https://github.com/RahulG2381/Home_Sales/assets/148564779/0caf6d36-3b08-4421-9a4b-75866b4579de)

3.	What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
<br> ![image](https://github.com/RahulG2381/Home_Sales/assets/148564779/7f384260-1d73-4d27-b70b-232a088ac2f7)

4.	What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
<br> ![image](https://github.com/RahulG2381/Home_Sales/assets/148564779/87e713ef-72a8-4c70-aaab-13db8a5deb93)

5.	Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
 <br>![image](https://github.com/RahulG2381/Home_Sales/assets/148564779/7931c82b-00b7-46a9-a05a-97d5a7c7db29)

<br>•	Partition by the "date_built" field on the formatted parquet home sales data.
<br>•	Create a temporary table for the parquet data.
<br>6.	Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
<br> ![image](https://github.com/RahulG2381/Home_Sales/assets/148564779/c0338367-a690-4c85-9c7e-cbe09f49cf95)

## conclusion: 
using the caching the data performance of the query is incresed  and the query run time reduced from 0.65 to 0.49 sec. howeven after doing theperformance were reduced and the time to run the query increses to 2.18 sec.
