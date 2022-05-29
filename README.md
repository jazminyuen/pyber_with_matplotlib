# Overview
## Pyber Analysis
Analyze and visualize ride-sharing data using Python, Pandas, and Matplotlib. With the ride-sharing data organized by city type, a summary DataFrame and a multiple-line graph will help to provide business recommendations for addressing disparities among the city types.

## Resources
- Python 3.9.7, Pandas and Matplotlib libraries
- Data source: city_data.csv, ride_data.csv

# Results
## Differences in the ride-sharing data among the different city types


Urban cities show 13 times more **total rides** than rural cities, and over 2 times more than suburban cities.
![total rides](/analysis/fig6.png)

Urban cities show 30 times more **total drivers** than rural cities, and almost 5 times more than suburban cities.
![total drivers](/analysis/fig7.png)

Urban cities show 9 times more **total fares** than rural cities, and 2 times more than suburban cities.
![total fares](/analysis/fig5.png)

Rural cities show the highest **average fares per ride and per driver**:

![summary df](/analysis/summary_df.jpg)

**Total fares** by city type show **weekly trends** from January to April 2019: 

![line chart](/analysis/pyber_fare_summary.png)



# Summary
## Business Recommendations 

- Encourage an increase in rural and suburban drivers with an incentive initiative for new drivers based in those areas.
- Schedule rider savings promotions during an expected lull in total fares (i.e., beginning of January in urban cities, beginning of March in suburban cities). 
- Plan an overall increase in urban city fares to make up for the disproportionate amount of total fares to total drivers in urban cities.