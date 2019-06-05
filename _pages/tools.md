---
layout: page
title: Digital History
description:
background: '/img/Mapbox-example.png'
---
The project aims at locating in time and place the formation of Catholic sacred spaces in colonial Venezuela from the mid-seventeenth to the eighteenth centuries. The goal is to map these buildings and compare if their frequency in specific moments paralleled  religious and political changes, e.g. the establishment of a town or new church, the visit of a bishop, etc.

For this, it was necessary to create a dataset extracting information from different primary and secondary sources related to the religious history and territorial expansion in the region during the colonial period. For this, [Graziano Gasparini's book *Templos Coloniales de Venezuela*](_pages/gasparini.md) was a major asset along with other resources like the database from the [** Institutional Assets and Monuments of Venezuela**](https://iamvenezuela.com/category/base-de-datos/).

<img src="/mapping-venezuela/img/posts/Sample-dataset.png" style="display: block; width: 700px; margin-right: auto; margin-left: auto;" />
<p class="caption123">Sample of the first dataset created for the project.</p>

I created the map using [Mapbox Studio](https://www.mapbox.com/mapbox-studio), a user-friendly application to edit maps based on datasets. This program is very versatile since it allows to create a base map without modern labels (name of cities, country and state boundaries, etc.) and using a clean canvas for GIS and visualization.

Mapbox also has additional features to show the vector tiles (data) in different formats and selecting specific variables from the dataset, either names and/or dates to show variations in time and space. For this project, I used [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/api/) a [JavaScript](https://www.javascript.com/) library that uses WebGL to transform the original map style to make the vector tiles interactive. Users can click each of the markers on the map to know more about the colonial history of these sacred spaces. Some of these entries also contain additional links to pages with further historical information.

I created the website using [Jekyll](https://jekyllrb.com/), a static site generator, and [Github](https://github.com/)

Special thanks for [Prof. Juan Cobo Betancourt](https://www.history.ucsb.edu/faculty/juan-cobo/) for providing the page templates and his guidance in enhancing the digital features of this project!
