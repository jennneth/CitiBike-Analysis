# CitiBike-Analysis
Analysis of NYC's CitiBike usage during COVID (March 2020 - March 2021)

This project explores how the lock down situation in NYC during the last 12 months influenced CitiBike usage.
![Citi-Bikes](citi-bike-station-bikes.jpg)

Data was downloaded from [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

This analysis focused on the activity during Year 1 of the COVID-19 lockdown compared to the previous 12 months.
    Corona Year: March 2020 - February 2021
    Pre-Corona Year: March 2019 - February 2020

Data was downloaded, manipulated to include month and year data, and then merged into a single dataset. The ETL activity was performed in a Jupyter Notebook using Python.

The data was then loaded into Tableau for analysis and visualization. The final Story can be found here at [Impact of Corona Virus Lockdowns on CitiBike Program](https://public.tableau.com/profile/jen7431#!/vizhome/NYCCitiBikeAnalysis_16168911035980/COVIDStory).

The lockdown had a significant impact on the total number of rides taken during the indicated year. Other than a spike in September 2020, the number of rides taken was consistently fewer than previous period. This is in alignment with the public health emergency mandating people to stay home to stop the spread of the virus.
![# of Rides](image1.png)

The average duration of the trip during the Corona Year was higher than previous year across all months.  People who were brave enough to be out in public were looking for opportunities to get some relief from being shut in without jeopardinzing their health by being exposed to germs on the subway or buses.
![Avg Duration of Rides](image3.png)

Due to people staying home, along with the increase in the unemployment rate, there was a decrease in subscribership during the Corona Year.  While rides were still taken, these were most commonly purchased on a one or three day pass.
![Subscribership](image4.png)

The full story with analysis is available on Tableau Public and in the workbook in GitHub.
