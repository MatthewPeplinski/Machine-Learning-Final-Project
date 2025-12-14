# Final Machine Learning Project: Regression Comparisons

This was a 2 month project which utilized Linear Regression, Support Vector Regression, Random Forest Regression, ARIMA (Auto Regressive Integrated Moving Average), SARIMA (Seasonal ARIMA) and Holt Winters Exponential Smoothing to forecast hourly weather data out one weeks time. In order to do this, we gathered hourly data going back 2 months from 41 weather stations in and around Wisconsin. 
We display a map of Wisconsin, along with a Voronoi Graph around each weather station. The map is and interactive plot which allows the user to select anywhere in the state, then the program will take in 2 months worth of hourly data as train data calculated triangulating the selected locations weather information based on the three closest weather stations and taking a weighted average of those stations' weather data using inverse distance weighting. We then run each model and test on a seperate validation set, and finally compare results using root mean squared error and a GUI visualization.

## In class Presentation
Below is the link to a google slidshow going through what this project is.
https://docs.google.com/presentation/d/1K0o1jeUx8h5qf2DxzTMDn3KgiUY_LKQwvq-sRd3KZPI/edit?slide=id.p#slide=id.p 

## Data
We collected data from 41 different weather stations across Wisconsin and its surrounding states. This information was provided for free by NOAA and a detailed look at our data is available at this link:
https://www.ncei.noaa.gov/access/search/data-search/normals-hourly-2006-2020?dataTypes=HLY-HTDH-NORMAL&dataTypes=HLY-DEWP-NORMAL&dataTypes=HLY-HIDX-NORMAL&dataTypes=HLY-PRES-NORMAL&dataTypes=HLY-PRES-10PCTL&dataTypes=HLY-PRES-90PCTL&dataTypes=HLY-TEMP-NORMAL&dataTypes=HLY-TEMP-10PCTL&dataTypes=HLY-TEMP-90PCTL&dataTypes=HLY-WCHL-NORMAL&dataTypes=HLY-WIND-AVGSPD&dataTypes=HLY-WIND-VCTDIR&dataTypes=HLY-WIND-VCTSPD&dataTypes=HLY-WIND-1STDIR&dataTypes=HLY-WIND-1STPCT&pageSize=100&pageNum=1&startDate=2025-04-09T00:00:00&endDate=2025-04-16T00:00:59&bbox=47.232,-95.645,41.820,-87.426 

The stations and Voronoi graph are arranged as follows:
![Wisconsin Weather Station Map](https://github.com/MatthewPeplinski/Machine-Learning-Final-Project/blob/main/images/wisonsin_vorinoi_graph.png)
