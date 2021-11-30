# Pyber Analysis

## Objective
The objective of the analysis was to transform the raw Pyber ride share data into graphs to gain meaningful insights for the leadership of Pyber.  The analysis looked at three different types of cities - urban, suburban and rural.  Various kpis were calculated such as number of drivers per city type, average fare per city type and summary statistics, among others.  The analysis used python, pandas, matplotlib, NumPy and SciPy to arrange and analyze the data.

## Results
When reviewing the ride share data analysis, we can see that there are differences between urban, suburban and rural city types.  The summary of the below information can be found in this table: https://github.com/julianadvds/pyber_analysis/blob/main/analysis/Pyber%20Ride%20Share%20Summary%20by%20City%20Type.PNG

### Total Rides
•Overall, rural has the smallest number of rides at 125, suburban second at 625 total rides and urban the most at 1,625 total rides.

•Urban cities have 2.6 times the number of total rides than suburban cities

•Urban cities have 13 times more rides than rural cities

•Suburban cities have 5 times more rides than rural cities


### Total Drivers
•Similar to total rides, rural has the fewest drivers at 78, suburban second with 490 drivers and urban has the most drivers at 2,405

•Urban cities have about 5 times more drivers than suburban cities

•Urban cities have about 31 times more drivers than rural cities

•Suburban cities have about 6 times more drivers than rural cities

### Total Fares
•Similar to total rides and drivers, rural has the smallest total fare amount at $4,327.93, suburban second with $19,356.33, and urban has the largest total fare at $39,854.38

•Urban cities have about 2 times the total fare than suburban cities

•Urban cities have about 9 times the total fare than rural cities

•Suburban cities have about 4 times the total fare than rural cities

### Average Fare per Rider
•Contrary to the metrics already reviewed, rural has the highest average fare per rider, at $34.62, suburban second with $30.97 and urban has the smallest average fare per rider at 24.53


### Average Fare per Driver
•The Average fare per driver aligns with the average fare per rider, with rural being the highest at $55.49, suburban being second highest ta $39.50 and again urban being the smallest amount at $16.57

### Total fare by City Type
We can look at the total fare by city type through the time series line graph XXXX Add graph link.  From the graph we can see that while there are some peaks and valleys across all city types, the total fairs for urban tends to fall between about $1750 and $2500 per week.  The suburban total fare per week tends to be around $1000, with the lowest being around $750 and highest being around $1500.  The rural total fare is the lowest per week, coming in between $0 and $500 pr week.  The information can be seen in the line graph.  https://github.com/julianadvds/pyber_analysis/blob/main/analysis/PyBer_fare_summary.png


## Summary
From the analysis and results, there are a number of options that can be explored to address the disparities among the city types.  One option would be to increase the total number of drivers in the rural areas.  The data shows that there are 31x more drivers in the urban areas vs the rural areas.  By increasing the total number of drivers in the rural areas we would reduce the gap between the urban and rural areas. 

Another way to address the disparities would be to increase the total number of rides in the rural areas.  The rural areay is currently lagging behind both urban and suburban in the total number of rides, so increasing that number would bring it more in line with the suburban and urban areas.

A third way to address the disparities would be to increase the average fare per ride in the urban area.  The data shows that it is less than half the average fare when compared to the rural region.  If the average fare per trip increases, it would bring it more in line with the rural area.  
