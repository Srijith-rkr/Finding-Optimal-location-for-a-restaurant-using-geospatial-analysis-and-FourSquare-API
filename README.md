# Finding-the-optimal-location-for-a-restaurant-franchise-using-geospatial-analysis-and-FourSquare-API
Project to find the optimal location for a restaurant using clustering and geolocational data

## Introduction

Madurai Idly shop is a successful chain of quick service restaurants serving traditional South-Indian vegetarian food in Bangalore. It currently has fifteen branches in Bangalore.
Bangalore is the capital of India's southern Karnataka state. The centre of India's high-tech industry, the city is also known for its parks and nightlife.

In this project we will try to find an optimal location for the franchise of the restaurant chain using Geolocational data

## Objective 

Madurai Idly shop is looking to open new branches throughout Bangalore as a part of its successful expansion. Since it is a south-Indian vegetarian restaurant, it plans on setting up shop near its vegetarian competitors.
In addition to that, Madurai Idly shop also wants to take advantage of the online food delivery services (Swiggy, Zomato etc). These services only offer to deliver foods for a 4KM radius, as covering a distance more than that in city traffic would make the food cold. 
Hence in addition to finding areas of veg restaurants, Madurai Idly shop should also ensure that the shops are spread out to cover maximum area possible, to ensure more online delivery.
Hence by finding the areas with more number of vegetarian restaurants, we will be able to find ares where the owners of Madurai Idly Shop can set up shop to compete.

## Data

I have manually collected the Latitude and Longitude of the fifteen branches of the restaurant chain form their website. Moreover, we use the data of the top 50 Indian Vegetarian restaurants from Foursquare. We use the latitude and Longitude of these restaurants to map cluster of Indian Veg restaurants

Then we use the cluster centres to find the cluster that is farthest from the existing branches. This would indicate a potential place to set up a Madurai Idly shop.

## Methodology

To solve this problem we begin by plotting the existing location of Madurai Idly Shop in a map. And make note of the locations covered by the shops. We also check to see if any of the existing shops have a disadvantage in their current locations. 

After that we select the top 50 south India restaurants and plot them, and cluster them. We do this to find location in Bangalore with high density of South Indian restaurants as this would indicate that many south Indian people prefer this place to dine in their native cuisine

Once we cluster them, we use the cluster centroids to find good locations that are not covered by the existing outlets. 

The process has been thoroughly explained as part of the code notebook. 

The findings from the projects has been documented in the report notebook
