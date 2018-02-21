# d3js-calender-view-with-weeks-and-months

Thanks to Mike Bostock for contributing https://bl.ocks.org/mbostock/4063318 to D3js. Though this is a very elegent way of presenting timeseriese data, I felt additon of weeks and months will make it intutitive. I looked on the web and found different variations. I liked the simplicity and compactness of this so added Months and Weeks markers to it. I hope this will he helpful for your visualizations.


![alt text](https://github.com/gsnaveen/d3js-calendar-view-with-weeks-and-months/blob/master/calendar.png "Check Wiki")

###### Input data Format
![alt text](https://github.com/gsnaveen/d3js-calendar-view-with-weeks-and-months/blob/master/calendarInputData.png "Check Wiki")


###### Update the following line of code as per your data attributes
.rollup(function(d) { return (d[0].Close - d[0].Open) / d[0].Open; })

###### For location of the data. Specify the file name if it exist in the same folder in place of the URL
d3.csv("https://bl.ocks.org/mbostock/raw/4063318/dji.csv", function(error, csv)
