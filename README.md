# Correlations With Productivity
In October of 2023, Sondre Solstad at The Economist published an article that showed how productivity has grown faster in Western Europe than in the United States ([found here](https://www.economist.com/graphic-detail/2023/10/04/productivity-has-grown-faster-in-western-europe-than-in-america)). 
This repo contains the data for an exploratory case study aiming to expand upon the Economist's article and explore potential correlations between a country's productivity and its happiness, CO2 emissions, freedom, and homicide rates over the last 15 years. 

The resulting report can be found [here](https://docs.google.com/document/d/10-PzktwLBY5W3-jGo_pqUFPxszGoj1O4qbQdK2_fxKo/edit?usp=sharing)

To replicate the results of this study, please first run 'CleanDataAndExport.ipynb' and 'ProductivityDataCleaning.ipynb', then run the rest of the jupyter notbooks. 

For any questions about this work, please email: <a href="mailto:eoreese@proton.me">eoreese@proton.me</a>

## Notes
This study includes data from countries from 2007-2022. Although not all countries in the study had 15 years of data for all of the datasets used, a minimum of 10 years of data was required to include the country in the study. Productivity data comes from the analysis created by Sondre Solstad found [here](https://github.com/TheEconomist/the-economist-gdp-per-hour-estimates) but originally comes from the OECD, World Bank, UN, and Penn World Table. The happiness data came from the 2023 World Happiness Report, CO2 data came from Our World in Data, the data on homicide rates came from the UNODC's dashboard showing intentional homicide rates, and the human freedom data used came from the CATO institute's Human Freedom Index report. 
All correlations are calculated with Pearsons Correlation Coefficient. 


## Data
Productivity:
[Sondre Solstad "All work and no play"](https://github.com/TheEconomist/the-economist-gdp-per-hour-estimates), [OECD](https://data.oecd.org/), [World Bank](https://data.worldbank.org/), [UN](https://population.un.org/dataportal/), and [Penn World Table](https://www.rug.nl/ggdc/productivity/pwt/?lang=en).<br>  
Happiness: [WHR](https://worldhappiness.report/data/)<br>  
CO2 Emissions: [OWID](https://ourworldindata.org/) - [Specific Page](https://github.com/owid/co2-data](https://ourworldindata.org/co2-and-greenhouse-gas-emissions#explore-data-on-co2-and-greenhouse-gas-emissions)<br>  
Homicide Rates: [UNODC](https://dataunodc.un.org) - [Specific Page](https://dataunodc.un.org/dp-intentional-homicide-victims)<br>  
Human Freedom: [CATO](https://www.cato.org/human-freedom-index/2021) - [Specific Page](https://www.cato.org/human-freedom-index/2021)



## Citations
The Economist and Solstad, Sondre (corresponding author), 2023. "All work and no play", The Economist, October 4th issue, 2023.

## Suggested Citation
Reese, Ethan (Corresponding Author), 2024. 
