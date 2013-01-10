---
layout: post
title: Public Transport and Accessiblity in Dublin
---

{{ page.title }}
================

<p class="meta">January 2013</p>

[DRAFT] 
Using the location of public transport stops (Bus, Dart, Luas and Train) I explore how where the nearest stop to your house is for the Greater Dublin Area (GDA). I do this by splitting Dubiln into a grid with squares of 250m and calculating the distance from this grid to the nearest stop. I also provide a tool which enables you to identify the nearest stop in your area. Using these calculations I make a map showing how far away you are from Public Transport for the GDA. This approach does not (yet) consider how far you can travel; it only identifies the nearest stops. In the next article on this site, I will show measures of how far you can travel using public transport. All the data used in this analysis is free to download at the end of this article.


# Average Distances to Public Transport #

Using a 250m grid, the distance from every grid-cell to the nearest modes of transport were calculated. This treats Dublin Bus, LUAS, DART and Irish Rail all equally. Each mode does have a very different _reach_ so this is a preliminary assessment of accesbility.


# Explore the Nearest Public Transport to your House #

Using a custom built tool you can enter your address into the search bar and the route to the closest station is shown.

# How many people can access Public Transport by foot? #

Using the assumption, that people are prepared to walk up to 500m to public transport, we can start to examine how many people are served by the network. Any 250m grid-cell where the centroid of the grid fell within a 500m road network distance was considered. In the worst case, the total distance would be 500m. From this we cann assess how much of Dublin is well served using this approach.

<!---
# test iframe #
<iframe src="http://crime.mappingdemocracy.ie/1"style="width:610px;height:1285px;" frameborder="0" ></iframe>
--->

<!---
![test image](http://zooooooooooooooot.com/beastifier/ecce_homo.png)
--->