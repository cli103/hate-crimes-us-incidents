# Regression Analyses for Hate Crime Incidents in the US 2015-2019
## Background

I used Python on Google Colabatory to conduct data analysis on the reported incidents of hate crimes in the US from 2015 to 2019. I used open data from the FBI Hate Crime Statistics from 2015 – 2019 to generate a regression model and trend line to predict the amount of incidents per year. 

## Business Question
What is the trend of hate crimes in the US from 2015-2019 and can this model be used to make future predictions?

## Data Sources – Open Data
[FBI Hate Crime Statistics](https://www.fbi.gov/services/cjis/ucr/publications#Hate-Crime%20Statistics)

I collated the data from Table 11 of 2015 - 2019. The data from each of the relevant years can be found below:

[2015](https://ucr.fbi.gov/hate-crime/2015)
[2016](https://ucr.fbi.gov/hate-crime/2016)
[2017](https://ucr.fbi.gov/hate-crime/2017)
[2018](https://ucr.fbi.gov/hate-crime/2018)
[2019](https://ucr.fbi.gov/hate-crime/2019)

The file with the collated data can be found [here](https://github.com/cli103/hate-crimes-us-incidents/blob/main/Hate%20Crimes%20Incidents.csv)

## Data Analysis
I generated a simple linear regression model pictured below. 
<img width="1090" alt="Screen Shot 2021-05-07 at 2 13 52 am" src="https://user-images.githubusercontent.com/78471393/117331216-e18a3700-aed9-11eb-8c86-91483c5fd083.png">

The line best fit is y = 392.7* Year -785359.9 and the r squared value is 0.840179. This means that there is a predicted yearly increase of 392 hate crimes. The r squared value is quite high as the model represents around 84% of the variation in the change in hate crimes year over year. Using this model, the predicted number of hate crimes for 2020 and 2021 are 7894 and 8286 respectively.
