# Thuisbezorgd-menu-scraper
### Scraping restaurant data and their menu items data from Thuisbezorgd

This was a project for the course Solving Societal Health Challenges with Data Science (CHL60309) at Wageningen University. 

## Goal of the project
This project was about understanding online food availability in the Netherlands via socioeconomic mapping. There is limited knowledge about how food is distributed and accessed via delivery platforms in the Netherlands, particularly in relation to regional socioeconomic factors. This gap limits the development of informed public health interventions and effective food policies. However, international studies have revealed a disproportionate availability of unhealthy food in lower socioeconomic areas. Therefore, it's important that the availability is mapped for the Netherlands as well. 

## Approach 
The project consisted of three important parts:
1. Scraping the restaurant data and their individual menu items data from Thuisbezorgd for each delivery postal code.
2. Normalizing food categories by standardizing the food names to existing ontology.
3. Geospatial mapping of the food availability against the socioeconomic status(SES) for healhty and unhealty foods.

## Dependencies
This project was done in Python and used Undetected Chromedriver to scrape the data automatically. Make sure to download Selenium first:
- run `pip install undetected-chromedriver`

