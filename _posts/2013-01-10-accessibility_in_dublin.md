---
layout: post
title: [DRAFT] Public Transport and Accessiblity in Dublin
---

{{ page.title }}
================

<p class="meta">January 2013</p>

Summary: Using the location of public transport stops (Bus, Dart, Luas and Train) I explore how where the nearest stop is for the Greater Dublin Area (GDA). I do this my examining the distance need to travel from a 250m grid to the nearest stop, and also provide a user-centered tool to enable you to explore this in your area. Through this approach I generate a surface of accessibility using this basic calculation. This approach does not consider how far you can travel; it only identifies the nearest stops. In the next iteration of this I will explore how far you can travel using public transport modes (and compare this to other transport modes).


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