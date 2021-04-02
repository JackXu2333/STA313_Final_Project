README
================

# Toronto Fire Incidents (2011-2019)

The purpose of this visualization is to inform the city planners and the
fire department about details of fire incidents in the City of Toronto.
More specifically, this visualization is designed to help city planners
and the fire department to decide where additional fire stations should
be built within the city, to reduce the number of fire incidents or
minimize loss from such. The data that are used in the visualization is
from The City of Toronto’s Open Data Portal. The datasets that we used
included fire incidents data, fire station locations, and neighborhood
profiles (Toronto Census 2016). There are two parts in the
visualization: 1) a map on the left side and 3) a scatterplot on the
right side. When the website is first opened, an info (information) box
will pop up and hover over the scatterplot, in which highlights in the
visualization will be stated, and readers can close it whenever so the
scatterplot would be visible again. If the readers are interested in
reading it again, the reader can click on a small button on the top
right corner of the website to open the info box again.

Our main audiences are the city planners and the fire department in the
city of Toronto, the map with a general overview and the map with
specific details regarding neighborhoods would provide insights to the
audience, so that they can see which neighborhood or which area within a
specific neighborhood would require more fire stations. Also, with the
scatterplot, our audience would be able to see if there is a trend
between the number of incidents and time in each neighborhood, so that
they can make a plan on the order of building fire stations. This means
that they can first build more stations in more urgent neighborhoods,
which are the neighborhoods with a strong positive trend on the
scatterplot. Then they can follow the order (trend) and build in other
neighborhoods.

## Development plan

Technology/Libraries to Be Used: In our development, we will be building
a shiny app in R. The project will be deployed on Github as R projects
for easy collaborations. The final product will be a shiny web app if
time permits. The main libraries we will be using include “shiny” for
creating interactive web applications; “tidyr”, “dylpr”, “lubridate” for
data manipulations; “sf”, “leaflet” and “opendatatoronto” for handling
geographical data. Lastly, we will use “ggplot2” for plotting
everything.

## Installation

For now, the easiest way to run the **fire incidents shiny app** is
pulling the [github
repo](https://github.com/JackXu2333/STA313_Final_Project), or you could
do it in the command line via:

    $ git clone https://github.com/JackXu2333/STA313_Final_Project.git

## About Us <img src="app/www/logo.png" width="25" height="auto">

Hi there, it’s the “Fancy Thoughts Squad”, students from the University
of Toronto teaming up for the STA313 final assignment. Hope anyone who
read this will have a “fancy” day (?)… I guess?
