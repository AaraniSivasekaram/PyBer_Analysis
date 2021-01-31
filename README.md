# PyBer_Analysis

## Overview of the Analysis
The challenge analysis allowed me to look at the PyBer ride and city data from a macro perspective to understand average fares between cities and average fares per driver between cities. I put this this data together in the form of dataframes and a mulitple-line graph. These results will help review overall revenue at the city level and inform strategies to address any disparities between cities.

## Results
There are clear differences in ride-sharing data between the different city types (Urban, Suburban and Rural), when analyzing different indicators the results show:
- Total rides: There were 1625 total rides for urban cities, in comparison there were 625 total rides in suburban areas and 125 total rides in rural regions. Urban areas had 13 times more rides compared to rural cities. 
- Total drivers: There were 2405 total drivers within urban cities, in comparison there were 490 total drivers in suburban areas and 78 total drivers in rural regions. Urban areas had 30 times more drivers compared to rural cities.
- Total fares: The total fares data were similar to the other cumulative indicators, where total fares in urban cities were significantly higher than the other two city types. Urban cities totaled $39,854.38 in fares, suburban areas totaled $19,356.33 in fares and rural regions totaled $4,327.93 in fares. 
- Average fare per ride: Using the totals data, we calculated average fares per city between cities. Rural cities had the highest average fare per ride with $34.62, suburban areas were second highest with $30.97 and urban regions were the lowest with $24.52. 
- Average fare per driver: Using the totals data, we calculated average fares per driver between cities, these results were aligned with the average fare per ride data. Rural cities were the highest with $55.48, suburban areas second highest with $39.50 and urban regions had the lowest average fare per driver with $16.57. 
- These indicators can be viewed in this pyber summary dataframe: https://github.com/AaraniSivasekaram/PyBer_Analysis/blob/main/Analysis/Pyber_summary_dataframe.png
- A summary of the weekly total fares by city can been viewed in this multiple line graph, showing the differences between cities: https://github.com/AaraniSivasekaram/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png

## Summary
The results data indicates there are reduced resources in rural cities, the number of total drivers are very low and consequently total fares are lower in rural cities compared to suburban and urban regions. As well, with limited drivers in rural cities, costs per rides are higher in these areas, which may negatively impact total fares in rural cities overall. Recommendations for PyBer's CEO to address these disparities between cities include:
1. Encourage onboarding new drivers in rural cities through educational campaigns and driver sign-up promotions.
2. Encourage ridership in rural areas by offering reduced fares for clients taking rides in rural areas.
3. Support suburban ridership and encourage new drivers in suburban cities with similar measure as rural areas. 
4. Undertake an analysis of length of rides between city types to understand these differences and how they may impact strategies within different city types. 
