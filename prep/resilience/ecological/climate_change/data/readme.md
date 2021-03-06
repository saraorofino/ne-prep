#Climate Change Resilience Data Details
##Juliette Verstaen
## `data` folder directory

******************************************************************
Data created in the `acee_rankings.Rmd`

`acee_rankings.csv`

Data URL: https://database.aceee.org/state-scorecard-rank

This data was created by taking the ACEE score and dividing it by the maximum score.

******************************************************************

Data created in `carbon_em.Rmd`

`carbon_em.csv`

Data URL: https://www.epa.gov/sites/production/files/2017-09/documents/co2ffc_2015.pdf

This data was created by taking the total annual carbon emissions and dividing it by the target emissions. Carbon emission targets are calculated by performing a linear regression from 2004 to the target year of their emissions goal.

******************************************************************

Data created in `climate_actions.Rmd`

`climate_actions.csv`

Data URL: https://www.bbhub.io/dotorg/sites/28/2017/11/AmericasPledgePhaseOneReportWeb.pdf

This data was created by the converting the scope of each states climate friendly actions into a score.There are 30 different categories of environmental friendly actions, and a state will get a perfect score if they have an action in each of these categories. 

******************************************************************

Data created in `renew_consum.Rmd`

`renew_consum.csv`

Data URL: https://www.eia.gov/beta/states/states/ny/data/dashboard/total-energy

This data was created by taking the EIA energy consumption data, calculating the percent of energy consumed that comes from clean sources, and dividing it by the target emissions. Total annual carbon emissions were pulled from the EIA website. Clean energy consumption targets are calculated by performing a linear regression from 2004 to the target year of their consumption goal. While there is a variety of energy plans and portfolios in the US that differ from state to state, every state in our region of interest has a "renewable energy portfolio standards", so we do not include nuclear energy production as part of the total renewable energy consumption target.

******************************************************************

Data created in `carbon_em.Rmd`

`emissions.csv`

This data was created by calcualting the total carbon emissions by state over time.

******************************************************************

Data created in `res_climate_change.Rmd`

`res_climate_change.csv`

This data was created by pulling in all other data created in this folder, calculating a regulation score, implementation & enforcement score and effectiveness & compliance score and taking the average of all three to calcualte the climate change resilience scores.










