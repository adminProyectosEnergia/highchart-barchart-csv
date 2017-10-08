# highchart-barchart-csv

This is a simple example to show how to use the highcharts code using a csv file. The data is represented in a Bar Chart.

This code is based on the  highcharts general documentation available at:
[highcharts.com](https://www.highcharts.com/docs/working-with-data/data-module)

The data used come from the website [**World Population Growth**](https://ourworldindata.org/world-population-growth/)

An **asynchronous HTTP (Ajax)** request is used to read the contents of the CSV file. 

Then, the bar chart is loaded and displayed in the div tag _container_.

The following files should be stored in the same folder:

* index.html
* bars.js
* data.csv