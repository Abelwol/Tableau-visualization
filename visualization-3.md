## Tableau-visualization 3
## Author :Abel Fereja, 07-Oct-2022
## Data Set Source: 
Tableau projects for practice tutorial by Gronify. Data set link is https://drive.google.com/file/d/1AmpTGttdPZa_bxSdXodFsTIaHsOSP62h/view
## Dataset info:
The dataset is about a sample Walmart stores retail transactions in defferent US cities, states and regions during the period from 2012 to 2015. It contains 8399 records from different store locations and has 25 columns. Below is list and data type of all the columns.
<pre>
Rows: 8399 
Columns: 25 
#   Column                Non-Null Count  Dtype  
---  ------                --------------  -----  
 0   City                  8399 non-null   object 
 1   Customer Age          7496 non-null   float64
 2   Customer Name         8399 non-null   object 
 3   Customer Segment      8399 non-null   object 
 4   Discount              8399 non-null   float64
 5   Number of Records     8399 non-null   int64  
 6   Order Date            8399 non-null   object 
 7   Order ID              8399 non-null   int64  
 8   Order Priority        8399 non-null   object 
 9   Order Quantity        8399 non-null   int64  
 10  Product Base Margin   8336 non-null   float64
 11  Product Category      8399 non-null   object 
 12  Product Container     8399 non-null   object 
 13  Product Name          8399 non-null   object 
 14  Product Sub-Category  8399 non-null   object 
 15  Profit                8399 non-null   float64
 16  Region                8399 non-null   object 
 17  Row ID                8399 non-null   int64  
 18  Sales                 8399 non-null   float64
 19  Ship Date             8399 non-null   object 
 20  Ship Mode             8399 non-null   object 
 21  Shipping Cost         8399 non-null   float64
 22  State                 8399 non-null   object 
 23  Unit Price            8399 non-null   float64
 24  Zip Code              8399 non-null   int64  
dtypes: float64(7), int64(5), object(13)
memory usage: 1.6+ MB
</pre>

## Image 1: Average Measures
This table chart shows Average sales, profits and discount figures during the period.
![Avg Measures](https://user-images.githubusercontent.com/114592689/194573035-1f6fd870-18b6-4018-9441-7064f12f3c03.png)
## Image 2: State vs Profit
This map chart depicts average profit or loss made in each states during the period covered.
![State vs Profit](https://user-images.githubusercontent.com/114592689/194966729-9ff37c5b-97df-4c66-ab36-d8b184a761bf.png)
## Image 3: Age vs Profit
This bar chart shows average proift or loss made based on different age group during the period. Transactions made with customers in age group +90 resulted in losses duing the period.
![Age Vs Profit](https://user-images.githubusercontent.com/114592689/194967032-2fe342c3-6f7a-4a61-a563-6a239e7009b6.png)
## Image 4: Average quarterly profit by regions
This highlight table shows average quarterly proft made in each year by region.
![Regional Profit](https://user-images.githubusercontent.com/114592689/194967292-05263b28-70d8-44f8-9956-c43b6d6b8e96.png)
## Image 5: Walmart retail data analysis dashboard
The dashboard contains all the above four visualizations and one additional visualization(The white diamond shape at the top right of the dashboard) which shows what the data is about and how many records and columns it contains. It is responsive during hovering in the picture in the interactive dashboard. the interactive dashboard is available on below link.
https://public.tableau.com/app/profile/abel5716/viz/WalmartretailDashboard/Dashboard1?publish=yes
![Dashboard 1-5](https://user-images.githubusercontent.com/114592689/194967826-32099939-2768-4a63-bf10-6676230ef921.png)






