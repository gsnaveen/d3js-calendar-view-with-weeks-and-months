# d3js-calender-view-with-weeks-and-months

Thanks to Mike Bostock for contributing https://bl.ocks.org/mbostock/4063318 . Have added weeks and months for easy read. I hope this will be helpful for your visualizations. this is an extension to the work of Mike,  Colors by [Cynthia Brewer](http://colorbrewer.org/). Layout inspired by [Rick Wicklin and Robert Allison](http://stat-computing.org/dataexpo/2009/posters/). Dow Jones historical data copyright [Yahoo! Finance](http://finance.yahoo.com/) or independent data provider; fair use for educational purposes.


[Live page](https://bl.ocks.org/gsnaveen/8b3368f3a65228e05d62926aa45a0b53)


![alt text](https://github.com/gsnaveen/d3js-calendar-view-with-weeks-and-months/blob/master/calendar.png "Check Wiki")

###### Input data Format
![alt text](https://github.com/gsnaveen/d3js-calendar-view-with-weeks-and-months/blob/master/calendarInputData.png "Check Wiki")


###### Update the following line of code as per your data attributes
.rollup(function(d) { return (d[0].Close - d[0].Open) / d[0].Open; })

###### For location of the data. Specify the file name if it exist in the same folder in place of the URL
d3.csv("https://bl.ocks.org/mbostock/raw/4063318/dji.csv", function(error, csv)

###### For displaying the number of years
.data(d3.range(1999, 2011))
