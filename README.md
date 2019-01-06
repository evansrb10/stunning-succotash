# Unit 5 | Assignment - The Power of Plots

OBSERVABLE TRENDS
1.  A look into all the rides in all cities and all city types reveals that there is a downward linear trend of the highest fares being in cities with the least amount of rides going to the lowest average fares having the most number of rides in the city.  If you break this into the three city types of Urban, Suburban, and Rural, the data shows what you would expect, with Urban cities having the most drivers, most rides, and lowest average fare price of the three.  

2.  Another noticeable point about the Urban City rides is that they seem to have more consistent ride prices and number of rides.  There are very few outliers in rides by this city type.  In comparison, if you review the rides in Rural cities, there is way less consistency with the data.  For example, there is one city with average fares below $25 and another city with fare prices almost at $45.  

3.  Urban city drivers dominate the percentage of drivers compared to the three with over 80% of the total drivers.  This is a logical find, as you would expect there to be more drivers when there is more demand, or clients needing rides.  This is a dramatic number compared to the rural percentage of drivers being at around 3%.  If you look at the amount of rides by city type though, urban city rides only add up to 68% of the total rides.  So, this would mean that there may be too many drivers for the urban cities, which is why they aren't giving as many rides, and in turn not getting more money for their services.  


## Option 1: Pyber

The ride sharing bonanza continues! Seeing the success of notable players like Uber and Lyft, you've decided to join a fledgling ride sharing company of your own. In your latest capacity, you'll be acting as Chief Data Strategist for the company. In this role, you'll be expected to offer data-backed guidance on new opportunities for market differentiation.

You've since been given access to the company's complete recordset of rides. This contains information about every active driver and historic ride, including details like city, driver count, individual fares, and city type.

Your objective is to build a [Bubble Plot](https://en.wikipedia.org/wiki/Bubble_chart) that showcases the relationship between four key variables:

* Average Fare ($) Per City
* Total Number of Rides Per City
* Total Number of Drivers Per City
* City Type (Urban, Suburban, Rural)

In addition, you will be expected to produce the following three pie charts:

* % of Total Fares by City Type
* % of Total Rides by City Type
* % of Total Drivers by City Type

As final considerations:

* You must use the Pandas Library and the Jupyter Notebook.
* You must use the Matplotlib library.
* You must include a written description of three observable trends based on the data.
* You must use proper labeling of your plots, including aspects like: Plot Titles, Axes Labels, Legend Labels, Wedge Percentages, and Wedge Labels.
* Remember when making your plots to consider aesthetics!
  * You must stick to the Pyber color scheme (Gold, Light Sky Blue, and Light Coral) in producing your plot and pie charts.
  * When making your Bubble Plot, experiment with effects like `alpha`, `edgecolor`, and `linewidths`.
  * When making your Pie Chart, experiment with effects like `shadow`, `startangle`, and `explosion`.
* See [Starter Workbook](Pyber/pyber_starter.ipynb) for a reference on expected format.


