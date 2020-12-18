# Capstone

Introduction
In this project we will help people who are looking for renting an apartment in Vienna. If they are looking to move to Vienna they can see:

Which district has cheaper rent or,
They can choose to live in residential or commercial areas and can see for example which residential districts is best
Or, if they already live in one of the 23 districts in Vienna they will be able to see:

If they are paying more than the average price for their apartment
If there are similar districts to theirs with lower rents
Data
The data on apartments (size, number of rooms, address, and price) is collected by scraping a local website with apartment listings (willhaben.at). Using geopy we find the coordinates for each district and then using Foursquare we collect the closest venues (supermarket, restaurant, park, etc.). After the data collection we can run k-means clustering to cluster the districts into residential and commercial areas and visualize all the data on a single choropleth map.
