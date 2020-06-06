# Building a Recommendation System for Finding Cities to Live in the United States of America 
## IBM/Coursera Capstone Project- The Battle of the Neighborhoods

### Introduction

*This project is part of the IBM Applied Data Science Capstone Project offered on Coursera.* 

According to Wordometers the United States of America currently has a total population of 330.8 million people . Although cities comprise of just 3.5% of the total land area in the country, 62.7% of the population chooses to live in these metropolitan centers . These cities are most often not just a congregation of people, but culture and services. 

I am currently a graduate student studying in a small college town; however, I am graduating soon and I would like to know which major cities could offer me the best services. Like me, there are many people who are looking to find cities to live in that could offer the services they need. Therefore, this project would be suitable for people who are looking to move to a new city in the United States.

This project will ask people to rate their preferences on what services they prefer and recommend cities that would be the most suitable for them. To achieve this, cities will be clustered on how similar they are based on the services they offer as listed in the Foursquare API, and the entered data will be used to identify the cluster of choice that will be displayed. 

### Data

Based on the problem described above, the following are the factors that will influence the results of the search:

* The type of services that are offered in each city such as coffee shops, restaurants, parks and theaters

* The number of such services within each city which will provide an indication of what are the most popular services in each city

The data I will be using for this project is listed below:
1.    Foursquare API: This API will be used to identify services, restaurants and shops available in each city and how many of each service is present in each city which will give an idea of its popularity. 

2.    U.S. Largest Cities (Source: [Open data for largest cities in the US](https://public.opendatasoft.com/explore/dataset/1000-largest-us-cities-by-population-with-geographic-coordinates/table/?sort=-rank)): This dataset will holds data on the major cities in the U.S. and the location columns will be used for mapping the cities on the map. The cities listed in this database will be the candidates examined for this project. 

### File Directory

1. Capstone-The-Battle-of-the-Neighborhoods.ipynb- File that contains all the python code done for the analysis part of the project

2. Cities.csv- Cities database downloaded from Source: [Open data for largest cities in the US](https://public.opendatasoft.com/explore/dataset/1000-largest-us-cities-by-population-with-geographic-coordinates/table/?sort=-rank)

3. Foursquare_db.csv: File with all services for all the cities used in this analysis, provided for use when API returns NA values.

4. Presentation.pptx: Presentation file detailing the procedure and findings of the project. 

5. Report.dcx: File that contains the detailed report of the project



