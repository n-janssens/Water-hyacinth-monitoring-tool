# Water-hyacinth-monitoring-tool
A Google Colab pipeline to be able to classify seasonal dynamics of plastics using Water Hyacinth as a proxy using Sentinel-2 imagery

## Abstract
Water hyacinths are invasive aquatic weeds, present in most freshwater bodies in tropical regions. Due to the ecological and socio-economic damages they can cause, monitoring their spatial coverage and seasonality is crucial to develop timely and efficient mitigation measures. Water hyacinth patches are detectable from space, allowing to build a monitoring tool using freely available remote sensing products such as Sentinel-2. In this study, we present a first method to estimate water hyacinths coverage and their seasonal dynamics over three years (2018-2020) for the Saigon river, Vietnam. We used a Naïve Bayes classifier and successfully classified water hyacinths coverage, with an accuracy of  91%. We show that water hyacinths consistently reaches its maximum extent during the month of February. The dry season (December-May) corresponds to a high water hyacinths abundance period. Rainfall and humidity levels were found to be highly correlated with water hyacinths coverage estimates. In addition to the seasonality patterns, large interannual variations were noticed. Water hyacinth coverage varied by a factor of 5 between the 2018/2019 and 2020 yearly averages and within four orders of magnitude considering daily estimates (from 0.02 to 180 ha – equivalent to 0.001 and 14% of entire study area). Water hyacinths can cover as much as 14% of the entire studied area, thus confirming the severity of water hyacinths invasion in the Saigon river. Our study provides an openly available automated workflow for long-term monitoring of water hyacinths coverage and can be scaled-up and extended to other systems of interest. As such, it provides the first step for building a global monitoring tool of this highly invasive species, which may also be used as an early warning system for operational clean-up. 

Keywords: water hyacinths, remote sensing, invasive plant, eutrophication, hydrology 


![image](https://user-images.githubusercontent.com/48392221/130446716-22147c30-88b0-40f3-869b-f3266ab73d06.png)

## About the data
The detection tool uses Sentinelhub API and the Sentinel-2 Surface Reflectance data.

## How to use the jupyter notebook template
The Jupyter Notebook templates are located in the src folder. Duplicate the Jupyter Notebook template of interest in the Google Colab editor. Using the templates, it is possible to detect water hyacinth in rivers using Sentinel-2 SR imagery, and estimating the area and seasonality of water hyacinth. A Sentinelhub + Google Colab account is required, as well as uploading the shapefile, geometries of the area of interest. A shapefile is provided in the **data/input** folder, corresponding to a large share of the Saigon river, Vietnam. 
