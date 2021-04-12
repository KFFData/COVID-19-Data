# Country Trend Data
This folder contains all the data powering the upcoming KFF Global COVID-19 Trackers. These dashboards will replace the current global COVID-19 tracker which can be found [here](https://www.kff.org/coronavirus-covid-19/fact-sheet/coronavirus-tracker/). These upcoming dashboards will only contain data from the last 200 days, to limit large data files. However, the full data set can be found [here](https://github.com/KFFData/COVID-19-Data/blob/kff_master/Country%20Trend%20Data/country_trend_data.csv). The data compiled here is pulled from Johns Hopkins University, Duke Global Health Innovation Center, Our World in Data, the Oxford Government Response Tracker, the World Bank, and the World Health Organization. 

## Codebook
- Country - Country name
- WHO_region - Region as defined by the World Health Organization. Not all countries listed have a WHO designated region.
- Income - Income classification as defined by the World Bank. Not all countries listed have a World Bank designated income.
- pop - 2020 population estimate
- Date - Date of observation
- Cases - Cumulative cases 
- Deaths - Cumulative deaths 
- Case_Change - New cases 
- Death_Change - New deaths
- cases_per_million - Cumulative cases per 1,000,000 people
- deaths_per_million - Cumulative deaths per 1,000,000 people
- Case_Mean_7 - 7-day rolling average for new cases
- Death_Mean_7 - 7-day rolling average for new deaths
- number_of_people_that_can_be_vaccinated* - Cumulative number of people that could be vaccinated based on purchased doses 
- doses_procured* - Cumulative number of doses purchased
- percentage_of_purchased_doses* - Country's percentage of total doses purchased worlwide 
- percentage_of_people_that_can_be_vaccinated* - Potential coverage of country's population that can be vaccinated based on purchased doses
- total_doses_administered - Cumulative number of doses administered
- total_doses_administered_per_hundred - Cumulative number of doses administered per 100 people
- new_doses_adminstered - Number of new doses administered
- new_doses_administered_per_million - Number of new doses administered per 1,000,000 people
- people_who_have_received_at_least_one_dose - Cumulative number of people who have received at least one dose
- people_who_have_received_at_least_one_dose_per_million - Cumulative number of people who have received at least one dose per 1,000,000 people
- people_fully_vaccinated - Cumulative number of people fully vaccinated
- people_full_vaccinated_per_hundred - Cumulative number of people fully vaccinated per 100 people
- PolicyType - Policy type of government policy response
- PolicyValue - Value of government policy response
- PolicyCategory - Policy category of government policy response
- coding - Description of government policy response
- PolicyDirection - Whether a policy is tightening or loosening in a country

* These variables are not longitudinal and reflect the country's vaccine doses purchased/potential vaccination coverage at present. 
