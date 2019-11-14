**Data**

The city of choice is Toronto. We will be using the same public dataset downloaded from Wikipedia in week 3 peer-graded assignment
in order to map all neighborhoods in the city and their GSP coordinates. Each row in the data set lists a neighborhood, the
borough\post code it belongs to and its coordinates. For example, Rough neighborhood is located in Scarborough under post code
M1B. We will process this data later and use it as our building blocks for clustering, since our problem is that of grouping neighborhoods
according to the services around them.

The complementary data that is missing are the different services offered in every neighborhood. Here, Foursquare free engine will provide
the requirement. It will list every relevant venue, its category and the coordinates. The categories data is crucial to our project since it will not
only determine the value of each sample (neighborhood) but will allow us to study the variety of categories present in the city and determine
which ones are to be considered critical services.
As an example, we see that M1B post has only 1 venue close to it and it belong to the “restaurants” category: Wendy’s at
(43.807448, -79.199056) This is basically the DNA of M1B. Also, since restaurants (all types) are the most popular category in the city,
with more than 500 of them around, it’s clear that this category needs to be considered as a crucial service.
