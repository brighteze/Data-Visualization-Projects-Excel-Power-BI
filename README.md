# Project 1. Financial Complaints Dashboard (MS Excel Project)
This is a dashboard project featuring an organizations complaints handling mechanism. The data shows all complaints, for what products, and channels. I built this simple dashboard using Microsoft Excel. The dashboard is a record of complaints by customers of a financial institution.

Data is from data.world, with the title "financial consumer complaints".

Techniques used in this project;

- Power Query to clean the data.
- Power Pivot, for cross tabulations and filtering.
- Excel charts for data visualization.

Here are some insights from this project:

- Web channel was the most frequently used for complaints resolution.
- Most complaints came from customers in California.
- Credit card was the product with the most complaints.
- Over 80% of complaints resolved without monetary compensation.


# Project 2. Visualizing Sales Performance (MS POWER BI Project)
In this project, I have built a dashboard to visualize the sales performance of an online store, using various metrics, such as;
- Aggregate monthly sales performance within the time period of 2015-2019
- Sales, Profit and product returns over the period.
- Sales performance by Product Category & Sales personell.
- Sales Performance by Segment, and
- Sales by customer.

Here are some insights from the analysis and dashboard.
- Total sales came up to $2,300,000 and profit was $286,400 - representing about 12%.
- On aggregate, the highest sales was recorded in September, November & December.
  - This could be down to shopping activities related to festive seasons such as black friday (November) and Christmas.
- Sales appreciates steadily and took a nosedive in 2019, on further investigation, I found that data collection in 2019 was not completed.
- On overall, Anna Andreadi and Chuck Magee were the best performing Sales Personell.
- Consumer segment was the best performing product segment with over 50% of total sales.
- Top customers were Sean Miller, Tamara Chand and Raymond Buch.


 # Project 3. Visualizing Real Estate Analytics in Brazil (MS Excel, Powwer Query and Power)
 
 In this project, I built a dashboard to visualize real estate housing trends in Brazil. The initial data was messy, so, I had to clean it up.
 
 Steps taken are as follows;
 Data augmentation done in Excel.
 -  Out of 97,354 rows, 5019 rows didn't have price information, I fixed this by replacing the null values with the median price.
 -  I also replaced 21,79 null values under the Surface Area Covered column with the mean.

Important Note: I took the option to fill in the null values with median figures because dropping them would have resulted in losing at least 30,000 rows,
or about 40% of the data. These rows had other important information necessary for the analysis.

Data Cleaning in Power Query.
This was the most time consunming part of the project, which is unsurprising as the key to a good analysis is the have clean data. Steps taken include;
- Dropped columns I considered irrelevant to this analysis such as web link, latitude, longitude etc.
- Split a column (by delimeter) containing (Country, State, Municipality and Locality).
- Deleted all empty values in the date column.
- Renamed some columns, and capitalized text data in every column.

Here's screenshot of the process, with data cleaning steps on the right side as recorded by Power Query.
![Screenshot (75)](https://user-images.githubusercontent.com/64503362/157029153-fd4460f6-bad8-44c9-9a13-4d5b844c7f72.png)

After these steps, the data was cleaner and ready for the analysis, which was done using Power BI.

Analysis and Dashboard in Power BI, the following metrics.
- Total Cost of rental properties by State, and Municipaliy.
- Total Cost by property type.
- Relationship between surface area total of property and price.
- Price of property by date (year in review being 2013-2017).

Findings.
- There are 26 States plus 1 Federal Capital Area in Brazil (making 27) and 421 Municipalities.
- A combined total of about $116m was spent on renting houses, stores and apartment between 2013-2107.
- Apartments were the most popular property type accounting for about 48% of all sales.
- Most properties were rented in Sao Paolo.
- Overall, cost of rental was flat from 2013-2014 but after that it witnessed exponential increase.
- There was no relationship between the size of a property and the rental price.
