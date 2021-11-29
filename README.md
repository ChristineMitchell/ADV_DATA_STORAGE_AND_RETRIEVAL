# ADV_DATA_STORAGE_AND_RETRIEVAL

## Overview

While enjoying my pineapple flavored ice cream cone, I fondly recalled my vacation to Oahu where I discovered my passion for the waves. How sweet would it be to surf every day? So, I thought to myself, why not make this a reality? What if I could enjoy both of my indulgences by opening up an ice cream shop in Hawaii? So, I reached out to a fellow surfing enthusiast who could be a potential investor. While he appreciated my excitement, he warned me of how he had a similar idea of opening a surf shop to sustain is surfing lifestyle, however this venture failed due to Hawaii's weather cycle. The rainfall killed his surfing shop dream. So, he suggested that I do a little research to see just how viable it is to have an ice cream shop year round. If he liked the results, he would take that back to his board of directors to sell them on the idea of investing with me. 

So, I put my newfound data analytic skills and tools to work. 

Taking into consideration my audience of potential investors, I discovered a new tool called a *flask app* to showcase the results on my local server. This was done with a python file, app.py, via Visual Studio Code. After connecting to the database file with an engine, I created multiple routes. The first route took me to the welcome page, then I was able to create separate routes showcasing individual result lists such as the precipitation, stations, tobs (temperature observations), and temperature stats (min, ave, and max) for a particular date range. It was my intention to present the data to an audience who was interested in results, not necessarily the code used to capture the results. 

I was able to utilize *SQLalchemy* via Pandas to access a *SQLite database* that stored weather data from nine different weather stations in Hawaii. The SQLite database is basically a flat file stored on my local server. I worked through the original analysis retrieving a year of precipitation data from the most active weather station, then for this challenge I extracted the temperature data for the months of June and December at all of the Hawaii stations.

## Results

As we agreed, I pulled the temperature data statistics for the polar opposite months of June and December where I discovered there really was not a huge difference in the weather temperature for these months, hence the temperature should not signficantly influence by reducing the ice cream sales in the winter months. I was excited to share this information my potential investor.

![Temp Comparisons](https://user-images.githubusercontent.com/82008319/143792697-3894db45-05e5-4f76-91f9-c248da25e9c2.png)

While there were 11% fewer temperation observations recorded in December than June, the average temperature in December is 71&defF, while it is 75&degF in June. That is an approximate 5% decrease, only equating to a 4&deg difference between the two opposite months. The minimum temperature has the greatest difference of 8&deg, equating to a 12.5% reduction from June to December. Overall, this data reflects in my favor that there will be a strong demand for ice cream year round.





