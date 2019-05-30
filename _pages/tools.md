---
layout: page
title: Digital History
description:
background: '/img/Mapbox-example.png'
---
This project started with the goal of locating in time and place the formation of Catholic spaces in the colonial Venezuela from the mid-seventeenth to the eighteenth centuries. The goal was to map these buildings and compare if their frequency in specific moments paralleled  religious and political changes, e.g. the establishment of a town or new church, the visit of a bishop.

For this, it was necessary to create a dataset extracting information from different primary and secondary sources related to the religious history and the territorial expansion in the region during the colonial period. For this, Graziano Gasparini's book *Templos Coloniales de Venezuela* was a major [resource](link sources).

![First Dataset](/posts/Sample-dataset.png)

The map was created using [Mapbox Studio](https://www.mapbox.com/mapbox-studio), a user-friendly application to edit maps and work with the datasets. The program was very versatile since it allows to create a base map without modern labels (name of cities, country and state boundaries, etc.) and using a clean canvas.

The features of the program show the vector tiles (data) in different formats and selecting specific variables from the dataset, either names and/or dates to show variations in time and space. We used Mapbox GL JS [link] a JavaScript library that uses WebGL to transform the original map style to make the vector tiles interactive.
