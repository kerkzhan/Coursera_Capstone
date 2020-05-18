# A data science project to analyze the best location in Petaling Jaya to open a fitness center

### Introduction
Petaling Jaya is one of the cities in Malaysia with a bigger population of approximately 613,977 people. It consists of 3 malls on a single highway, with many amneties and facilities in every neighborhood. With that said, you can expect many gyms and fitness centers that have been already established. However, as Petaling Jaya grows at a rapid pace and new neighborhoods are being developed by the minute, there is a need for amneties to built alongside those neighborhoods. Fitness centers are especially important as most citizens choose to go to the nearest one to their homes, as it is convenient. Therefore, the goal of this project is to determine neighborhoods that have lack in fitness facilities and to find insights on which location is best to open a new fitness center.

### Data
- Neighborhood sections can be webscraped from Wikipedia. 
- Neighborhood coordinates can be acquired through Google Maps
- Category of businesses nearby can be acquired through Foursquare API

The concept of the project is as follows. We first list out every neighborhood in the city. Then, we use their coordinates to explore businesses in that neighborhood and retrieve the type of business they are. Then we will cluster those results by observing the density of those business in a given neighborhood to determine which which has least competitors in a less dense area.
