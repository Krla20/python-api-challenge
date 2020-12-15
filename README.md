***
# Python API Challenge
***
# WeatherPy Analysis(☞ﾟヮﾟ)☞☜(ﾟヮﾟ☜)¯\_(ツ)_/¯
***
👍Create a series of scatter plots to showcase the following relationships: Temperature (F) vs. Latitude, Humidity (%) vs. Latitude, Cloudiness (%) vs. Latitude, Wind Speed (mph) vs. Latitude. (After each plot, add a sentence or two explaining what the code is analyzing).

👍The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude): Northern Hemisphere - Temperature (F) vs. Latitude, Southern Hemisphere - Temperature (F) vs. Latitude, Northern Hemisphere - Humidity (%) vs. Latitude, Southern Hemisphere - Humidity (%) vs. Latitude, Northern Hemisphere - Cloudiness (%) vs. Latitude, Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude, Southern Hemisphere - Wind Speed (mph) vs. Latitude (After each pair of plots, take the time to explain what the linear regression is modeling.)

👍Your final notebook must: Randomly select at least 500 unique (non-repeat) cities based on latitude and longitude, perform a weather check on each of the cities using a series of successive API calls, include a print log of each city as it's being processed with the city number and city name.
            ***Save a CSV of all retrieved data and a PNG image for each scatter plot.***
            
--Latitude vs. Temperature

*The closer to the equator the hotter it is.

*Between latitudes -20 and 20 are the hottest temperature in the cities.

*The far a city is from the equator the colder it is.

--Latitude vs. Humidity

*The data seems to be spread and hard to define where.

*The cities with the highest humidity are located between latitudes 40-75

--Latitude vs. Cloudiness

* The cloudiness is everywhere depending of the weather changes

--Latitude vs. Wind Speed

*The colder the temperature is the more wind that blows

-- Linear Regression:

           Max Temp vs. Latitude Linear Regression: The high r value indicates a strong positive correlation between latitude and max temperature.
           Humidity (%) vs. Latitude Linear Regression: The low r values indicate a weak to no relationship between humidity and latitude.
           Cloudiness (%) vs. Latitude Linear Regression: The low r values indicate a weak positive relationship between latitude and cloudiness.     
           Wind Speed (mph) vs. Latitude Linear Regression: The low r values indicate that there is no real relationship between wind speed and latitude. The difference between the hemispheres doesn't seem to be significant enough to comment upon.



***
# VacationPy Analysis🎉👓🥽🧤🩱🩳👚⚽⚾🏈♥
***
👍Create a heat map that displays the humidity for every city from Part I.

✔Narrow down the DataFrame to find your ideal weather condition. Criteria for "Ideal Weather": A max temperature lower than 80 degrees but higher than 70, wind speed less than 10 mph, zero cloudiness, drop any rows that don't contain all three conditions.


👀These are the cities and hotel randomely chose for my project regarding the temperatures requested 

City: Mandera - Country: Kenya - Hotel Name: M-Pesa Olkitira Communications Agency Ltd

City: Betioky - Country: Madagascar - Hotel Name: RadioFeon'nyOnilahy

City: Kodār - Country: India - Hotel Name: RadioFeon'nyOnilahy

City: Jizan - Country: Saudi Arabia - Hotel Name: Missing field/result... skipping

City: Ampanihy - Country: Madagascar - Hotel Name: Hotel Restaurant ANGORA

City: Sur - Country: Saudi Oman - Hotel Name: Pizza Hut

City: Bara - Country: Nigeria - Hotel Name: Missing field/result... skipping

City: Belmonte - Country: Brazil - Hotel Name: CEPLAC Comissão Executiva Plano Lavoura Cacaueira

City: Mandera - Country: Kenya - Hotel Name: M-Pesa Olkitira Communications Agency Ltd
