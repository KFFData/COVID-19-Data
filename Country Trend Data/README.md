# Country Trend Data
This folder contains all the data powering the upcoming KFF Global COVID-19 Trackers. These dashboards will replace the current global COVID-19 tracker which can be found [here](https://www.kff.org/coronavirus-covid-19/fact-sheet/coronavirus-tracker/). These upcoming dashboards will only contain select data, to limit large data files. However, the full data sets can be found here. 

## Cases/Deaths
This dashboard contains information related to COVID-19 cases and deaths globally. Data is sourced from the Johns Hopkins University, World Bank, United Nations, and the World Health Organization. The data for this dashboard can be found under **global_covid_metrics.csv**. 

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




