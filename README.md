# Data_Analytics_115_Crime_Demographics

![Shooting Map of America (Race) 2019](https://raw.githubusercontent.com/levicollins9/Data_Analytics_115_Crime_Demographics/master/Shooting%20Map%20of%20America%20(Race)%202019.png)
The two images of the United States are my first attempt to process FBI Crime Data that I obtained from: https://fatalencounters.org/view/person-csv/
https://fatalencounters.org/view/person-csv/csv/?
I cut out one death in Alaska and one death in Hawaii to condense the size of the charts and sorted out all races except White and Black. 
* Note: There are a large number of unidentified shootings that may skew actual results.

I then looked up data from the FBI about crime data by race at the following source.
Reference: https://crime-data-explorer.fr.cloud.gov/explorer/national/united-states/crime

This Data came in a very unhelpful format, so I transfered the data manually to my own file to make it compatible with Tableau. 
Reference: Census_FBI_Data_Sorted.xlsx

I made an initial graph and realized that I needed to account for the differences in population between the different races. To accomplish this I went to the census bureau and manually transfered the data about population numbers in WA State in 2019 to my Census_FBI_Data_Sorted.xlsx file.
Reference: https://www.census.gov/quickfacts/WA

![WA % of Crime (Race) 2019](https://raw.githubusercontent.com/levicollins9/Data_Analytics_115_Crime_Demographics/master/WA%20%25%20of%20Crime%20(Race)%202019.png)
This graph shows that most of the crime is committed by the White category in Race. However, this is not true when compared to population percentage. 
*Note: Notice, the swing between the percent of population and percent of crime categories.

![WA Crime by Population (Race) 2019](https://raw.githubusercontent.com/levicollins9/Data_Analytics_115_Crime_Demographics/master/WA%20Crime%20by%20Population%20(Race)%202019.png)
This graph demonstrates distribution of crime adjusted for population.
