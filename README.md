# Power-Consumption-analysis-across-various-sectors

Understand and analyze the power consumption behavior across the different sectors in the following six states of US – Maryland, Massachusetts, Florida, Colorado, California and Washington.

Data Source:

Temperature data: 
https://www.ncdc.noaa.gov/cag/statewide/time-series
Process to obtain the data: 
Navigate to the above provided URL and select parameter as Average temperature, Time Scale as 1 month, month, Start year – 1995, End year – 2020 and the state.
(I downloaded each month data for all the six states)

Power consumption/retail sales of power: https://www.eia.gov/electricity/data/browser/#/topic/5?agg=0,1&geo=vvvvvvvvvvvvo&endsec=vg&linechart=ELEC.SALES.TX-ALL.M~ELEC.SALES.TX-RES.M~ELEC.SALES.TX-COM.M~ELEC.SALES.TX-IND.M&columnchart=ELEC.SALES.TX-ALL.M~ELEC.SALES.TX-RES.M~ELEC.SALES.TX-COM.M~ELEC.SALES.TX-IND.M&map=ELEC.SALES.US-ALL.M&freq=M&start=200101&end=202009&ctype=linechart&ltype=pin&rtype=s&maptype=0&rse=0&pin=
Process to obtain the data: 
Click on the above URL and choose “5.4 Retail sales of electricity to ultimate customers by end-user sector”. Then select monthly button and click on Download button. 

Overview of the data:
Data consists of the power consumption by the Residential, Commercial, transportation etc. sectors over the last 20 years. I plan to merge this data with the average statewide temperature data over the last 20-year time period.

I propose the combined data to consist of the following 12 columns:
•	Year: The year of the observation
•	Month: Month value of the observation
•	All: All the sectors power consumption value
•	Residential: Power consumption by the residential sector
•	Commercial: Power consumption by the commercial sector
•	Industrial: Power consumption by the industrial sector
•	Transportation: Power consumption by the transportation sector
•	Other: Power consumption by the other miscellaneous sectors
•	State: State value of the observation
•	Source key: Source of the observation
•	Units: Units of the power consumption
•	Temperature: Average temperature of the state

Total size of the data is 3 MB. It consists of 1400 records.
