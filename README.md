# TECHIN510

## Project Objectives 

This project will center around creating a Real Estate oriented dashboard that allows users to visualize which aspects of a local market affected the value of the home, and then understand the future outlook of these variables.  

## Target Users & Needs 

This product would primarily be for the following user groups: 
* Developers and investors looking to see the future efficacy and potential value of a home, without having to infer or assume localization 
  * Users need quick and responsive tools 
  * UI needs to be simple and straight to the point, as it is purely a financial decision to them 
  * They care more about the bottom-line growth of the home, and how much money they will get out of it 
  * Having ways to see the most disruptive market factors can help direct future investment within regions 
* Brokers and their consumers looking for homes 
  * Similar needs as before 
  * More information and details are needed however, as it is much more of an emotional experience 
  * Future value still matters for when the consumers decide to sell in the future, but it should be more focused on which aspects impact the price the most 

## Key Deliverables 

This product will need the following: 
* Map integration 
* PCA analysis on an individual home 
* PCA analysis on a zip code 
* PCA on a drawn area (if time allows) 
* AI-based outlooks on how that aspect of the home may fare in the future 

## Special Constraints 

As this deals with Real Estate data, there are some regulatory and data-oriented limitations: 
* RE data is limited to some public data sources such as county or city based valuations
  * https://api-developer-dev.kingcounty.gov/signin?returnUrl=%2F 
  * https://gis-kingcounty.opendata.arcgis.com/ 
  * https://data.kingcounty.gov/ 
* Or, you will need to access MLS APIs. These are blocked out from consumers however, and you need to be a part of the MLS in some capacity to access it (RE broker, firm, etc.) 
  * https://www.nwmls.com/#/m/North%20King 
  * But, zillow has a MLS API that I requested access to, with a description of this project! So there may be access to the MLS soon: 
    * https://www.zillowgroup.com/developers/api/mls-broker-data/mls-listings/ 

With each of those resources, there are specific constraints that may apply that the ecosystems will provide more information on  them.  

## Expected Outcome 

The expected outcome of this project is that a user will be able to do the following when they open the app: 
* Users open the app and end up on a landing page that is the macro view of king county (or Bellevue depending on API constraints) 
* Users can search for a specific property, zip code, or other general region that is represented by data 
* Users will be able to see high-level details of a home as well, kinda like a MLS system 
* For the selected unit/area, users will be able to see the overall PCA analysis, with a visualization on which aspects have impacted that selection the most 
* Users can then see insights into the future outlook for each of those aspects to better influence their decisions about that property 
* Potentially some financial prediction and analysis if time permits 
