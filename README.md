# **MIST4610 Group 4 Project 2**

## Team Name:
**61608 Group 4**

## Team Members:
1. Devin Davis [@dvndavis](https://github.com/dvndavis)
2. Hadden Peel [@hmpeel](https://github.com/hmpeel)
3. Kate Macken [@katemacken](https://github.com/katemacken)
4. Keira Cullinan [@keiracullinan](https://github.com/keiracullinan)
5. Lleyton Poole [@lleytonpoole10](https://github.com/lleytonpoole10)
6. Luke Burnett [@lukeburnett16](https://github.com/lukeburnett16)

## Description of Dataset
The dataset describes the real estate sales in Connecticut from 2001 to 2021. To obtain this data, we used the website provided, https://catalog.data.gov/dataset/real-estate-sales-2001-2018.  The dimensions of this dataset are 1,048,575 rows and 14 columns. Within this dataset, there are a variety of descriptions to explain each of the sales, such as a town, property address, and date of sale. Seven columns have the dimension type string: town, property address, property type, property assessment, assessor remarks, OPM remarks, residential type, and location. Within location, there are a couple with latitude and longitude coordinates. Within city, the data type was a string, but we edited the geographic role to city. In addition, two columns have the dimension of data: date recorded and list year. Sale amount, sale ratio, and difference are number (decimal). Serial number is number (whole). 

The first column, serial number, describes the serial number of the property listed. Following the serial number, list year describes the year that the property was listed on the market. Connected with this, the date recorded highlights the date, in month, day, and year, that the property was formally sold. Town, represented by a geographic role, lists the town in Connecticut where the property is located. More specifically, the address includes the specific street name and number. The assessed value is the price that the state of Connecticut assigns to the property. Assessed value takes into consideration location and property sales, along with many other factors. On the other hand, sale amount is the price that the property was sold for, which could be higher or lower than the assessed value. The sales ratio is the ratio of assessed value to market value, or sale amount, for the property that has been sold. Property types include many categories, such as residential, commercial, and vacant land. Residential type also includes many different categories of residential properties, such as multi-family homes, condos, and apartments. Non-use codes are used for properties that do not comply with zoning regulations, and it include explanations such as foreclosure, tax, and non-buildable lot. Assessor and OPM remarks include written notes about the properties that are in the market. Lastly, location includes the latitude and longitude of some of the properties. 

## Question 1
Question: How was the housing market affected by the Housing Recession in 2008? Display this using data from 2005 to 2012.

Importance: This question is important as it shows how the devastating recession of 2007 and 2008 affected the property market in the state of Connecticut. This question helps depict how the real estate market looked before, during, and after the recession. This can help the entire financial real estate industry by looking at how their past decisions can affect the housing market. By seeing the downward spiral in property prices as the economy headed into the recession, it is visible that the mistakes made by the banks on Wall Street had external effects on the real estate market. To illustrate this change, we chose to use a line graph that could represent a continuation in the property prices, and the difference in sale amount and assessed value. 

<img width="1440" alt="MISscreenshot" src="https://github.com/katemacken/Group-4-Project-2/assets/163315179/b5c0c2d9-6913-494d-9b78-a405195867c1">

Our first graph illustrates the difference in the average sale amount and the average assessed price. The graph shows that before the recession, there was a wide gap between the assessed value of the home and its final sale amount. However, as the recession came, that gap narrowed and homes began to be sold for a price similar to its assessed value. This trend continued on after the recession.

![MIST Project 2 - Difference Bar Chart](https://github.com/katemacken/Group-4-Project-2/assets/163012888/7ce5d62a-1b79-437e-8a44-d2ed45923687)

This graph shows the average difference between the average sale price and the average assessed value of homes in Connecticut from 2005-2012. This graph shows how the gap between the two started out large in 2005, but as the country headed towards a recession, the gap continually narrowed. This trend continued to happen well after the recession until 2012 when the average assessed value actually became higher than the average sale price for the first time in seven years.



## Question 2
Question: For residential property types, how does proximity to New York City affect the average sale price of homes in 2020 and 2021? List the 10 towns with the highest average residential sale price on a bar graph as well.

Importance: This question is important as it can not only allow customers, but realtors as well to analyze the residential Connecticut real estate market as a whole across 2020 and 2021. This is valuable for realtors because it can show them the towns where they should focus their efforts to maximize their sales. This question is valuable for customers as it allows them to see how far their budget can stretch them in the market and also allows them to see how much they prioritize their distance from New York City. Customers can then have a discussion with their realtor to determine where they can realistically purchase their future home in Connecticut. To illustrate this, we chose to use a symbol map. 

<img width="962" alt="average sale price" src="https://github.com/katemacken/Group-4-Project-2/assets/163315179/28f98e41-f611-4011-9613-343d4dbdb93e">

The first visualization shows each town in Connecticut denoted by a bubble whose size and color is dependent on their average residential sale price in 2020-2021. The larger and darker the bubble is, the greater the average sale price was. The second visualization, shows the 10 towns in Connecticut with the highest average sale price across 2020-2021.

<img width="1440" alt="Screenshot 2024-04-17 at 11 38 09 AM" src="https://github.com/katemacken/Group-4-Project-2/assets/163012542/4665d9b9-aff0-4764-9695-ae098d11a5ab">

Our first visualization showed a clear correlation when it came to how residential sale prices were correlated to their distance to New York City. For reference, New York City is just south west of the border of Connecticut, with the largest and darkest circle on our visualization (Greenwich) being the city that is nearest to NYC. With that being said, it can be confidently said that, on average, the closer the towns are to New York City, the higher their average sale price is. As the towns move further down the coastline and into more rural Connecticut, the average sale prices can be seen dropping drastically, which is shown by the circle size decreasing. This should tell realtors that they should focus more of their business closer to NYC, as they will see much greater sales and use their time much more efficiently, while also seeing a greater number of customers as they are closer to the most populated city in America. The second visualization puts the first visualization into more detail as it provides the names for the top 10 most expensive towns along with their average sale price as well. On the bar graph, you can see that Greenwich, the nearest city to NYC, has an average sale price 40% greater than the next closest city. 

## Manipulations to the Dataset
While the majority of the dataset did not need any manipulations, the "Difference" calculations allowed us to see the true difference between the assessed value and the sale amount. To do this calculation, we added another column to the end of the dataset, and we subtracted the Assessed Value from the Sale Amount. The data format stayed the same as the assessed value and sale amount, which are number (decimals). In addition, we did have to convert the town data type from string to town to be able to visualize the data through a symbol map. 

## Tableau Packaged Workbook
Packaged Workbook: https://outlookuga-my.sharepoint.com/:u:/g/personal/klc15851_uga_edu/EZA_kC-W1tNGt7YIU6No0gMBqx1cDUe7V29bN8bTVT-koA?e=e0JMKT
