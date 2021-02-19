# Communicate-Data-Findings-Udacity
Communicate Data Findings - Udacity
Relationship of Flight Origin Location with Number of Flights and Average Distance

by Austin Dowd

Dataset
The data used for this analysis covers flight information reported by certified U.S. air carriers that account for at least 1% of domestic scheduled passenger revenues. The data is collected by the Office of Airline Information, Bureau of Transportation Statistics (BTS).

The dataset for exploration includes flight data, with variables specific to individual flights including originating airports and destinations, times of flights, taxi times, delay times, plane and carrier information.

There are also 3 supplemental data sets including airport information, plane data for individual planes, and carrier data for individual U.S Carriers.

The Available flight data spans millions of flights from 1987 to 2008. Due to computation limitations of dataframe sizes only the most recent 10 years where data is complete will be examined, which would be years 1998-2007.

Summary of Analysis and Findings
To conserve computational resources in analysis this data set, a sample was taken from the main flight data for the selected years of 580,000 individual flights.

After initial exploration, key areas of interest were traffic, measured in counts of flights originating and average distance of those flights for both individual airports and geographic locations, available as longitude and latitude coordinates.

A top 10 list of busiest airports as measured by a count of flights originated were compared against each other and the dataframe as a whole.

Several insights were found in relation to the location of the top 10 airports in terms of its geographical location, and the average flight distance in relation to other airports in the dataset, as well as those within close proximity to it as measured by longitude and latitude. 


List of Resources
Data for this Analysis is available at the sources below:

Data Source: http://stat-computing.org/dataexpo/2009/the-data.html

Original Source: The U.S. Department of Transportation's (DOT) Bureau of 
Transportation Statistics
https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp     

Download Source: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7
