# Final Machine Learning Project: Regression Comparisons

This project utilizes Linear Regression, Support Vector Regression, Random Forest Regression, ARIMA (Auto Regressive Integrated Moving Average), SARIMA (Seasonal ARIMA) and Holt Winters Exponential Smoothing to forecast hourly weather data out one weeks time.
We display a map of Wisconsin, allowing the user to select anywhere in the state, then take in one month of hourly data as train data as a weighted average from triangulating the selected locations information based on the three closest weather stations. We then run each model and test on a seperate validation set, and finally compare results using root mean squared error.

Below is the link to a google slidshow going through what this project is. 
https://docs.google.com/presentation/d/1K0o1jeUx8h5qf2DxzTMDn3KgiUY_LKQwvq-sRd3KZPI/edit?slide=id.p#slide=id.p 

Here is a link to the dataset we used
https://www.ncei.noaa.gov/access/search/data-search/normals-hourly-2006-2020?dataTypes=HLY-HTDH-NORMAL&dataTypes=HLY-DEWP-NORMAL&dataTypes=HLY-HIDX-NORMAL&dataTypes=HLY-PRES-NORMAL&dataTypes=HLY-PRES-10PCTL&dataTypes=HLY-PRES-90PCTL&dataTypes=HLY-TEMP-NORMAL&dataTypes=HLY-TEMP-10PCTL&dataTypes=HLY-TEMP-90PCTL&dataTypes=HLY-WCHL-NORMAL&dataTypes=HLY-WIND-AVGSPD&dataTypes=HLY-WIND-VCTDIR&dataTypes=HLY-WIND-VCTSPD&dataTypes=HLY-WIND-1STDIR&dataTypes=HLY-WIND-1STPCT&pageSize=100&pageNum=1&startDate=2025-04-09T00:00:00&endDate=2025-04-16T00:00:59&bbox=47.232,-95.645,41.820,-87.426 
