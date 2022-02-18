# surfs_up

## Overview of the Analysis
The Surf and Shake Shop, which sells surfing gear and ice cream, is currently in the process of finding locations for its first shop in Oahu. Due to concerns about weather conditions and its impact on sales, the business's investors would like an analysis of weather datasets from the island, particularly temperature trends during the months of June and December.  Data from the two months over the years 2010-2017 were extracted and analyzed to determine the summary statistics (count of values, standard deviation, and mean, minimum, maximum temperatures as well as 25th, 50th and 75th percentile temperature statistics). Tools used for this analysis include Jupyter Notebook, SQLite, and SQAlchemy. 

## Results

![image](https://user-images.githubusercontent.com/90944163/154608490-a1f7cc8e-a25c-425e-9efe-a96fba180208.png)

![image](https://user-images.githubusercontent.com/90944163/154608466-34728f31-15d9-4e13-8721-ea5c33e6285b.png)

- The mean temperature for June is 74.9 degrees, compared to a mean temperature of 71.0 degrees in December.  This represents an approximately 4 degree difference in mean temperatures between December and June.  
- The minimum temperature recorded in June is 64 degrees, compared to a minimum temperature recorded in December of 56 degrees.  This represents an approximately 8 degree variance in minimum temperatures between December and June. 
- The maximum temperature recorded in June is 85 degrees, with a maximum temperature recorded in December of 83 degrees.  This represents an approximately 2 degree variance in maximum temperature between December and June.  

## Summary
Overall, temperatures in both June and December are similar, with most values (25%, 50%, 75% and max temp) within 3 to 4 degrees Fahrenheit when comparing months.  The widest variance is between minimum temperatures, with June minimum temps being approximately 8 degrees higher than minimum temps in December. The mean and other values would suggest steady, warm temperatures that could support demand for both ice cream and surf/water sport gear. However, it should be noted that there were nearly 200 fewer temperature recordings in December than in June, and this could potentially skew the preceding results. To gain further insight on the weather in Oahu, additional queries on precipitation specifically in the months of June and December (shown below) may also be helpful in addressing weather trends when comparing them with temperature results during those months. Similarly, queries on specific weather stations closest to potential store locations, for the months of June and December, could be particularly useful.   

![image](https://user-images.githubusercontent.com/90944163/154610022-d3e4341e-c7c7-443e-97ab-8363bf65497b.png)

![image](https://user-images.githubusercontent.com/90944163/154610054-9b6103c1-7941-4d66-98e0-5e6fc57059ec.png)


