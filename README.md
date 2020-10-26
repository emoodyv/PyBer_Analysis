# PyBer Analysis
## Overview of the analysis
The goal of this project is to analyze data for the ride sharing company PyBer. After the analysis was complete, a
compelling visualization was made in order to present to CEO V. Isualize. Jupyter notebook, Python, and the libraries 
matplotlib and pandas were used to assist with the analysis.

## Results
In order to garner proper results and analysis this project first took the raw data that included the city, date, fare, 
ride ID, driver count, and city type for each ride in the year 2019. From there the data was first sorted into the city
types: urban, suburban, and rural. After that, the results were able to be populated for those categories for the 
following columns: Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver.
The resultant dataframe looked like this:

![DataFrame1](https://user-images.githubusercontent.com/71234992/97136061-4e449d80-170f-11eb-82a1-5b258e1bd587.PNG)

As can be seen the relationship of more drivers to rides in the urban setting becomes inverted as the city type changes 
to rural. Another data point of note is that there a lot more rides in the urban setting. This rapidly decreases in the
suburban and rural settings. Finally, it is important to notice that the fares are a lot cheaper in the urban cities.

All in all, the urban cities resulted in a lot more revenue for PyBer. That can be seen in the chart below:

![PyBer_fare_summary](https://user-images.githubusercontent.com/71234992/97136774-48e85280-1711-11eb-8464-36590645c071.png)

## Summary
In summary the differences in fares and drivers can assist the CEO to make business changes. One, the CEO can focus on
adjusting fares upward in the urban cities. It is clear that the demand is there. Two, it might be beneficial to
decrease fares in the rural cities. These fares are very high per ride. This might be decreasing demand. Third, the CEO
could try to recruit more drivers in the rural areas. Conclusively this data can assist V. Isulize to improve revenue.
