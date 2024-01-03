# Country Trend Data
This folder contains all the data powering the KFF Global COVID-19 Tracker. The dashboard can be found [here](https://www.kff.org/coronavirus-covid-19/fact-sheet/coronavirus-tracker/). The dashboard will only contain select data, to limit large data files. However, the full datasets can be found here. 

## Cases/Deaths
This dashboard contains information related to COVID-19 cases and deaths globally. As of March 7, 2023, all data on COVID-19 cases and deaths are drawn from the [World Health Organization’s (WHO) Coronavirus (COVID-19) Dashboard](https://covid19.who.int/data). Prior to March 7, 2023, this tracker relied on data provided by the Johns Hopkins University (JHU) Coronavirus Resource Center’s COVID-19 Map, which ended on March 10, 2023. Population data are obtained from the [United Nations World Population Prospects](https://population.un.org/wpp/Download/Standard/MostUsed/) using 2021 total population estimates. Income-level classifications are obtained from the latest [World Bank Country and Lending Groups](https://datahelpdesk.worldbank.org/knowledgebase/articles/906519-world-bank-country-and-lending-groups). Regional classifications are obtained from the [World Health Organization](https://www.who.int/countries). The data for this dashboard can be found under global_covid_metrics.csv. Because of GitHub file size limits, data are separated into multiple datasets, broken out by quarter. 

### Codebook

- Country - Country/area name
- Date - Date of observation
- Confirmed Cases - Cumulative number of confirmed COVID-19 cases
- Confirmed Deaths - Cumulative number of confirmed COVID-19 deaths
- New Cases - Number of new COVID-19 cases (daily)
- New Deaths - Number of new COVID-19 deaths (daily)
- Income - Country income group as defined by the World Bank (NOTE: Not all countries included have a World Bank incomc classification.)
- Region - Country region as defined by the World Health Organization (NOTE: Not all countries included have a WHO region classification.)
- Population - 2020 total population estimate according to the United Nations' World Population Prospects (NOTE: Some country populations have been adjusted to account for protectorates)
- cpm - Cumulative number of confirmed COVID-19 cases per 1,000,000 people
- dpm - Cumulative number of confirmed COVID-19 deaths per 1,000,000 people
- Case_Change_7_Day_Rolling_Average - 7-day rolling average in new COVID-19 cases
- Death_Change_7_Day_Rolling_Average - 7-day rolling average in new COVID-19 deaths
- cpm_income - Cumulative cases per million by World Bank income-level
- dmp_income - Cumulative deaths per million by WHO region
- cmp_region - Cumulative cases per million by World Bank income-level
- dpm_region - Cumulative deaths per million by WHO region
