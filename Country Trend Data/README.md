# Country Trend Data
This folder contains all the data powering the KFF Global COVID-19 Tracker. The dashboard can be found [here](https://www.kff.org/coronavirus-covid-19/fact-sheet/coronavirus-tracker/). The dashboard will only contain select data, to limit large data files. However, the full datasets can be found here. 

## Cases/Deaths
This dashboard contains information related to COVID-19 cases and deaths globally. Data is sourced from the Johns Hopkins University, World Bank, United Nations, and the World Health Organization. The data for this dashboard can be found under **global_covid_metrics.csv**. Because of GitHub file size limits, this data has been separated into multiple datasets: global_covid_metrics2020.csv (containing 2020 data), global_covid_metrics2021_H1.csv (containing 2021 data from Jan 1-June 30), global_covid_metrics2021_H2.csv (containing 2021 data from Jul 1-Dec 31), gloval_covid_metrics2022H1.csv (containing 2022 data from Jan 1-June 30), global_covid_metrics2022H2.csv (containing 2022 data from Jul 1-Dec 31), and global_covid_metrics2023H1.csv (containing 2023 data to date).  

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
