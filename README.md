# PyBer_Analysis

## Overview of the Analysis

### Background
Pyber is a ride sharing company. Using data from a CSV, I created several analyses using Jupyter Notebook along with matplotlib and pandas libraries to analyze the data.

### Purpose of Analysis
The analysis below showcases the relationships between the types of cities, total rides, total drivers, total fares, average fare per ride, and average fare per driver. The data is aggregated and averaged by the type of city. The city types are rural, suburban, urban. The final intent of the analysis is to identify disparities between city types, and to make recommendations for addressing these disparities.

## Results
This dataframe displays data organized by city type for total rides, total drivers, total fares, average fare per ride, and average fare per driver:
![pyber_summary_df](https://user-images.githubusercontent.com/24308495/138629339-d1910a7f-adb4-4b9f-aaf0-a060885d8802.PNG)

### Total Rides
The rural cities had the fewest number of total rides, and the urban cities had the greatest number of total rides. The urban cities had 1,500 more rides than rural cities, meaning they had 13 times the amount of total rides. The suburban cities had five hundred more rides than rural cities, meaning they had five times the number of total rides. The urban cities had 1,000 more rides than suburban cities, meaning they had 2.6 the number of total rides.

### Total Drivers
The urban cities had the greatest number of drivers, and the rural cities had the fewest number of drivers. The urban cities had 2,327 more drivers than rural cities, meaning they had over 30 times the number of drivers. The suburban cities had 412 more drivers than rural cities, meaning they had over 6 times the number of drivers. The urban cities had 1,915 more drivers than suburban cities, meaning they had nearly five times the number of drivers.

### Total Fares
The urban cities had the most amount of total fares, and the rural cities had the least amount of total fares. The urban cities $35,526.45 more total fares than the rural cities, meaning they had about nine times the amount of total fares. The suburban cities had $15,028.40 more total fares than the rural cities, meaning they had about 4.5 times the amount of total fares. The urban cities had $20,498.05 more total fares than the rural cities, meaning they had about twice the amount of total fares.

### Average Fare per Ride
The urban cities had the lowest average fare per ride, and the rural cities had the greatest average fare per ride. Urban cities had a $10.09 lower average fare than rural cities, meaning their average fare was about 30% lower. The suburban cities had a $3.65 lower average fare than rural cities, meaning their average fare was about 10% lower. The urban cities had a $6.44 lower average fare than suburban cities, meaning their average fare was about 20% lower.

### Average Fare per Driver
The urban cities had the lowest average fare per driver, and the rural cities had the greatest average fare per driver. Urban cities had a $38.92 lower average fare per driver tha nrural cities, meaning their average fare per driver was about 70% lower. Suburban cities had a $15.99 lower average fare per driver, meaning their average fare per driver was about 30% lower. Urban cities had a $22.93 lower average fare per driver, meaning their average fare per driver was about 60% lower.

### Total Fares by City Type Over Time
This graph displays data for total fares by city type from January through April:
![Pyber_fare_summary](https://user-images.githubusercontent.com/24308495/138630005-b6c91af1-ca54-4eff-b7b8-c921efd84a0c.png)

The total dollar amount in fares for city types is consistent relative to each other; none of the city types had an upward or downward trend that stands out in comparison to the other types. <br>
<br>
Urban fares crested in late-February and again in early-March, however by the end of April the total fares were close to where it started in January. <br>
<br>
Suburban fares crested in late February. At the end of April, they were higher than they had started where they had started in January, but that is likely temporary; they had a period in early-March and mid-April that showed no gain from where they started in January. <br>
<br>
Rural fares crested in early-April. They had a jump in total fares in late-February that was similar to the trends of other city types; however, apart from late-February and early-April, the growth is extremely minimal. They ended April in about the same place they started in January.

## Summary

### Advtertise to Potential Riders in Urban Cities
Based on the number of drivers in urban cities, I recommend an advertising push to generate passengers. The supply of drivers assures that passengers will be able to accommodated. The number of drivers is so great in urban cities that it significantly exceeds the the total number of rides provided. Despite the lower average fares in urban cities, the population density and supply of drivers makes them an excellent spot to generate revenue. It will be easier to generate revenue through several smaller transactions in urban cities than trying to scale-up operations in suburban or rural cities (despite a higher dollar amount per transaction).

### Eliminate Rural Operations
The rural cities provide significantly lower total fare amounts than the urban and suburban cities. They tend to have a higher average fare per ride but this is dwarfed by total income amounts from other city types. Their total fares overtime demonstrate nearly no improvement, so it is possible that drivers will lose interest. There's only 78 drivers servicing rural areas; if those few drivers lose interest, it will create service issues. Service issues in rural areas may damage the brand, which may negatively impact urban and suburban markets. I recommend not serving rural areas until there is greater passenger engagement in urban and suburban areas; the return on investment for expanding rural service is too low relative to urban and suburban markets. Expand back into rural areas when there is either higher engagement in urban and suburban areas, or when there are self-driving vehicles are available.

### Engage Drivers to Maximize Retention
Currently there are significantly more drivers than total rides provided in urban areas. Meanwhile, in suburban areas, 625 rides were divided between 490 drivers. Pyber is ripe to scale service in urban and suburban cities by attracting passengers, however drivers need to be engaged so they continue to login to the app even when a passenger may not be available for them to transport. We need to maintain the supply of drivers in order to scale-up operations. Always having a driver available will be key to transforming this service from a novelty to a dependency. Enabling use of push notifications on driver apps may help alert drivers when a passenger is seeking a ride. Additionally, incentives should be created to help sustain drivers to be availability. This can be achieved either through a rewards program or by paying drivers a small amount of money to wait for passengers.
