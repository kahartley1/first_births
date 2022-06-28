# Low Cost Family Activities
Capstone Project - Nashville Software School Data Analytics Cohort DA6

##Table of Contents
* [Motivation](#Motivation)
* [Data Sources & Tools](#Data-Sources-&-Tools)
* [Data Questions](#Data-Questions)
* [Challenges](#Challenges)

## Motivation
While babysitting/nannying and spending time with my nieces and nephews, I always had a hard time finding fun activities that were low cost. While the park can always be fun, playing at a new park or walking around a museum to change things up is mentally stimulating for both the children and adults. I wanted to make a map of sorts for the Nashville area that all families could utilize. I wanted to focus on low income families and where these activities were compared to their location/county. I also wanted to consider the best place for low income housing to be built so they would have easy access to multiple low cost activities.

Back to [contents](#Contents)

## Data Sources & Tools
### Data Sources
* Census Poverty Data for the 10 counties in Nashville
    * [Census Reporter](https://censusreporter.org/data/table/?table=B17026&geo_ids=05000US47189,05000US47021,05000US47037,05000US47043,05000US47119,05000US47125,05000US47147,05000US47149,05000US47165,05000US47187&primary_geo_id=05000US47189 )
* Yelp API
    * [Yelp API Documentation](https://www.yelp.com/developers/documentation/v3/get_started)
    ### Tools
* Python
* Jupyter Notebooks/Geospatial Environment
* Tableau

Back to [contents](#Contents)

## Data Questions
My main data question is: Do low income families have easy access to little to no cost activities?
Following this question, I would like to see the best location for low income housing to be built so families can have easy access to this activities. Also, creating a map that has activities for all families that range in cost.

Back to [contents](#Contents)

## Challenges
Some Challenges I faced with this project mainly revolve around the yelp api. Learning to navigate the yelp api was a task in itself. I soon realized that the yelp api only grabbed 20 rows at a time and thus needed an offset. I ran this offset loop to a large number to ensure it grabbed all of the places I wanted. however this meant it grabbed places outside of the area I wanted. When I would use a search term, it would also bring up places that were not within that search term. For example, if I searched for parks, I would get museums within that list.

I only used the yelp api and there may be other parks or activities that I did not find within yelp.

Finally, getting the folium map to work and run correctly was difficult. I figured out most of it with the help of my teachers, but the tool tip was an issue we did not get to solve.

Back to [contents](#Contents)
