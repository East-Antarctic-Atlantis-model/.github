# EastAnt-Atlantis :penguin:
## An East Antarctic implementation for Atlantis, an end-to-end ecosystem model

![model](https://github.com/East-Antarctic-Atlantis-model/EADocumentation/blob/main/figures/img.png)

Welcome to the **EastAnt-Atlantis** model page. Here you will find information on the model's nature, function, and structure.

This page is being built as part of a PhD project by Ilaria Stollberg, under the supervision of Dr.s Sophie Bestley, Jess Melbourne-Thomas, Javier Porobic Garate, and David Green at the Institute for Marine and Antarctic Studies (IMAS-UTAS) and the Commonwealth Scientific and Industrial Research Organisation (CSIRO). The model is still under development; the calibrated version will be available in 2024. 
The project aims to follow the FAIR (Findable, Accessible, Interoperable, Reusable) principles, as set out by Wilkinson et al., 2016.

## Page structure
The page contains all elements required for running the EastAnt implementation of Atlantis. The model itself is under licence and needs to be installed separately.


## What is Atlantis?
Atlantis is an end-to-end ecosystem model that represents interactions between all levels and spheres (i.e., physical, chemical, biological, economic, social, and more) of an ecosystem; it was developed by Dr. Beth Fulton at CSIRO (for more information, see [https://research.csiro.au/atlantis/] and Fulton et al., 2004). Atlantis' strength lies in its ability to simulate long-term scenarios, such as the impact of human activities and climate change, to aid management and decision-making; due to its complexity, it requires the input of several experts and careful calibration.

# Atlantis for East Antarctica
## Why East Antarctica?
East Antarctica, specifically the Prydz Bay area, is a region that encompasses several habitats and rich ecosystems which rely on the seasonal ice cover and availability of krill and fish. Prydz Bay has been identified as an important habitat for commercially important species such as toothfish (*Dissostichus spp.*) and Antarctic krill (*Euphausia superba*); it is also breeding and feeding grounds for several charismatic species, such as the iconic emperor penguin (*Aptenodytes forsteri*) and elephant seal (*Mirounga leonina*). 

## Model domain
The domain consists of 29 polygons, each representing a different biological and physical regime; each box may be divided into up to 10 depth layers which capture biologically and physically important processes such as primary production, foraging, remineralisation at surface and in deeper waters, and iceberg scouring. Physical drivers (i.e., currents, temperature, salinity) are obtained from the output of ACCESS-OM2, a physical model described by Kiss et al. 2020; ecologically important variables, such as sea ice seasonality and mixed layer depth, were validated by Fierro-Arcos et al. 2023.

## References
1. Wilkinson, M. D. et al. The FAIR Guiding Principles for scientific data management and stewardship. Sci Data 3, 160018 (2016).
2. Fulton, E. A., Smith, A. D. M. & Johnson, C. R. Biogeochemical marine ecosystem models I: IGBEM—a model of marine bay ecosystems. Ecol. 174, 267–307 (2004).
3. Kiss, A. E. et al. ACCESS-OM2 v1.0: a global ocean–sea ice model at three resolutions. Geosci. Model Dev. 13, 401–442 (2020). Available at: [https://gmd.copernicus.org/articles/13/401/2020/]
4. Fierro-Arcos, D. et al. Analysis of ecologically relevant sea ice and ocean variables for the Southern Ocean using a high-resolution model to inform ecosystem studies. Progress in Oceanography 215, 103049 (2023). Available at: [https://linkinghub.elsevier.com/retrieve/pii/S0079661123000927]



