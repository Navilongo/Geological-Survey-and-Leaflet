# Geological Surveys with Leaflet

## The USGS needs you!

The United States Geological Survey is responsible for providing scientific data about natural hazards, and today, I have been
elected to participate in their survey of earthquakes around the world. 

To begin, we want to better visualize the earthquakes that occur around the world, and obtain a good representation of their
magnitude and depth within the earth's core. This will help the USGS to better understand the changes that our planet is 
experiencing and hopefully be able to better predict major disasters before they negatively influence our society. 

## The task

Using the USGS JSON information on their site, I have pulled the earthquakes in the past week (7 days) and placed it into
a map of the earth using leaflet and javascript. 

We used this data to pull relevant information for our visualization and show within their actual coordinates (Lattitude and Longitude), 
where these earthquakes have occurred. 

To better represent the data, and to avoid all merging together, we have used their magnitude to influence the radius of the marker within
our map. We have also taken the depth of the earthquake and assigned it one out of 6 colors to indicate the depth of the earthquake
occurrence. 

![Image of Map](Visualization of Earthquakes Map.jpeg)