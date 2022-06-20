# surfs_up
Jypter/VSC/ to analyze weather data for new shop on Hawaii island
The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one being for June and the other being December. Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:

In June:
Precipitation
count	1700.000000
mean	74.944118
std	3.257417
min	64.000000
25%	73.000000
50%	75.000000
75%	77.000000
max	85.000000

In December:
Precipitation
count	1700.000000
mean	74.944118
std	3.257417
min	64.000000
25%	73.000000
50%	75.000000
75%	77.000000
max	85.000000

Data is flawed as Dec and June returned same results
