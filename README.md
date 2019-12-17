# Coursera_Capstone
IBM Data Science Capstone Project

1.

Clearly define a problem or an idea of your choice, where you would need to leverage the Foursquare location data to solve or execute. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem.

Problem Description:
Food wastage is a serious issue in United States, approximately 125 to 150 billion pounds of food or $220 billion is being wasted every year. Meanwhile,
12% of american households are food insecure according to https://foodprint.org/issues/the-problem-of-food-waste/. A major step to reduce food insecurity would be to divert or minimize this food wastage. Most of the food
that is being wasted is edible and nutritious, this food majorly comes from restaurant chains, coffee houses, and bakeries. 

Our aim here is to build a food bank that collects edible food from the above food hubs and keep it distribution ready for people who visit the food bank.
Some of the major challenges to this food bank would be;
1. Proximity to reastaurants
2. How densely are the restaurants located?
3. How famous or popular are these restaurants
4. How easy is it to commute to this food bank for consumers using public transportation

We have chosen Boston city as high level location of the food bank, as Boston has lot of food chains and has a higher amount of food waste, so we could
act upon this and divert the food to the needy. Now, we need to identify the correct neighborhood in which we need to start the food bank so that the 
consumers would be able to visit the food bank with less cost of transportation. Our end goal from this project is to leverage data obtained using 
foursquare API, clustering methods, and identify the best neighborhood to start the food bank.


2. 
Data Section:
Describe the data that you will be using to solve the problem or execute your idea. Remember that you will need to use the Foursquare location data to solve the problem or execute your idea. You can absolutely use other datasets in combination with the Foursquare location data. So make sure that you provide adequate explanation and discussion, with examples, of the data that you will be using, even if it is only Foursquare location data.

1. As we have already chosen Boston in United States, we would need latitude, longitude, zipcode, and neighborhood associated with Boston.
2. We would require data associated with the food chains located in these neighborhoods.
3. Data required for each food chain would be place name, place summary, place category, distance in meters
4. We need to identify top venue categories for each neighborhood, and if top venues are associated with food in that neighborhood.
5. These neighborhoods are potential places to setup this food bank as higher number of food places in the vicinity would result in obtaining more food
for the food bank
6. Using foursquare API by making a basic data pull call we get the following data, 

[Postal Code] [Distance (meter)] [Neighborhood(s)] [Venue Summary] [Venue Category] [Neighborhood Latitude] [Neighborhood Longitude] [Venue] 

[02115] [170] [Seaport] [Popular eatery] [Chinese restaurant] [Restaurnt] [143.711112] [-79.284577] [wagamama]

Using the data in the above format, we can obtain the most suitable neighborhood for starting the food bank
