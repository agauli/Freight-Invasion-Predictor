# SRE_simulation

Models to create projections of invasive species spread are critical in identifying high priority shipping centers and pathways of bioinvasion, essential information for the prevention of environmental and economic harm caused by invasive species. In this work, we developed an interactive web-based simulation system called ComFlo to project the movement of invasive species across the United States. We utilized Freight Analysis Framework (FAF) commodity shipping data from 1997-2012, provided by the Federal Highway Administration to produce our model. Specifically, to generate the transition matrix at the core of a stochastic matrix model that projects terrestrial invasive species spread in the United States via the domestic commodity flow network. In addition, we use environmental predictors, including precipitation and temperature, found on the noaa.gov website, to restrict the movement of the invasive population to regions that have a suitable habitat for the species. The resulting model is unique in its reliance on FAF shipping data in conjunction with the environmental data, and can be used for a variety of species that may be transported within commodity shipments.

The invasive model can be found here: https://ryancyan.shinyapps.io/invasion_simulation/

