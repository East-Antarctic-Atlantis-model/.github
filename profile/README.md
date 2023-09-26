# EastAnt-Atlantis :penguin:
## An East Antarctic implementation for Atlantis, an end-to-end ecosystem model

![model](https://github.com/East-Antarctic-Atlantis-model/EADocumentation/blob/main/figures/img.png)

Welcome to the **EastAnt-Atlantis** model page. Here you will find information on the model's nature, function, and structure.

## Introduction
This organisation is being built as part of a PhD project by Ilaria Stollberg (supported by the [AAPP Program](https://aappartnership.org.au/)), under the supervision of Dr.s Sophie Bestley, Jess Melbourne-Thomas, Javier Porobic Garate, and David Green at the Institute for Marine and Antarctic Studies (IMAS-UTAS) and the Commonwealth Scientific and Industrial Research Organisation (CSIRO). The model is still under development; the calibrated version will be available in 2024.

The project aims to follow the [FAIR data principles](https://www.nature.com/articles/sdata201618) (Findable, Accessible, Interoperable, Reusable) to ensure reproducibility and long-term usefulness of the model.

The organisation page contains all elements required for running the EastAnt implementation of Atlantis. The model itself is under licence and needs to be installed separately; you can find instructions on becoming part of the Atlantis community [here](https://research.csiro.au/atlantis/home/links/).

## What is Atlantis?
Atlantis is an end-to-end ecosystem model that represents interactions between all levels and spheres (i.e., physical, chemical, biological, economic, social, and more) of an ecosystem; it was developed by Dr. Beth Fulton at [CSIRO](https://research.csiro.au/atlantis/) (for more information on the model, see [Fulton et al., 2004](https://linkinghub.elsevier.com/retrieve/pii/S0304380003004290)). Atlantis' strength lies in its ability to simulate long-term scenarios, such as the impact of human activities and climate change, to aid management and decision-making; due to its complexity, it requires the input of several experts and careful calibration.

# Atlantis for East Antarctica
## Why East Antarctica?
East Antarctica, specifically the Prydz Bay area, is a region that encompasses several habitats and rich ecosystems which rely on the seasonal ice cover and availability of krill and fish. Prydz Bay has been identified as an important habitat for commercially important species such as toothfish (*Dissostichus spp.*) and Antarctic krill (*Euphausia superba*); it is also breeding and feeding grounds for several charismatic species, such as the iconic emperor penguin (*Aptenodytes forsteri*) and elephant seal (*Mirounga leonina*). 
## Model domain
The domain consists of 29 polygons, each representing a different biological and physical regime; each box may be divided into up to 10 depth layers which capture biologically and physically important processes such as primary production, foraging, remineralisation at surface and in deeper waters, and iceberg scouring. Physical drivers (i.e., currents, temperature, salinity) are obtained from the output of ACCESS-OM2, a physical model described by [Kiss et al., (2020)](https://gmd.copernicus.org/articles/13/401/2020/); ecologically important variables, such as sea ice seasonality and mixed layer depth, were validated by [Fierro-Arcos et al., 2023](https://linkinghub.elsevier.com/retrieve/pii/S0079661123000927).
## Functional groups
EastAnt-Atlantis contains 29 functional groups, 8 of which are resolved to the species level. Functional groups are collections of species that share similar life histories, feeding habits, and/or role within an ecosystem; generally, Atlantis models reserve species-level distinction only when the species has a particular importance, for example it is a keystone for its habitat, or is commercially/culturally important.
The selection of species and functional groups is based on information and input from experts on Antarctic biology, which can be found on [SOKI (Southern Ocean Knowledge and Information wiki)](https://sokiaq.atlassian.net/wiki/spaces/ABOUT/overview?mode=global).

## References
1. [Wilkinson, M. D. et al.](https://www.nature.com/articles/sdata201618) The FAIR Guiding Principles for scientific data management and stewardship. Sci Data 3, 160018 (2016).
2. [Fulton, E. A., Smith, A. D. M. & Johnson, C. R.](https://linkinghub.elsevier.com/retrieve/pii/S0304380003004290). Biogeochemical marine ecosystem models I: IGBEM—a model of marine bay ecosystems. Ecol. 174, 267–307 (2004).
3. [Kiss, A. E. et al.](https://gmd.copernicus.org/articles/13/401/2020/). ACCESS-OM2 v1.0: a global ocean–sea ice model at three resolutions. Geosci. Model Dev. 13, 401–442 (2020). 
4. [Fierro-Arcos, D. et al](https://linkinghub.elsevier.com/retrieve/pii/S0079661123000927) Analysis of ecologically relevant sea ice and ocean variables for the Southern Ocean using a high-resolution model to inform ecosystem studies. Progress in Oceanography 215, 103049 (2023). 



