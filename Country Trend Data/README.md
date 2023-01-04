# Country Trend Data
This folder contains all the data powering the upcoming KFF Global COVID-19 Trackers. These dashboards can be found [here](https://www.kff.org/coronavirus-covid-19/fact-sheet/coronavirus-tracker/). These dashboards will only contain select data, to limit large data files. However, the full data sets can be found here. 

## Cases/Deaths
This dashboard contains information related to COVID-19 cases and deaths globally. Data is sourced from the Johns Hopkins University, World Bank, United Nations, and the World Health Organization. The data for this dashboard can be found under **global_covid_metrics.csv**. Because of GitHub file size limits, this data has been separated into multiple datasets: global_covid_metrics2020.csv (containing 2020 data), global_covid_metrics2021_H1.csv (containing 2021 data from Jan 1-June 30), global_covid_metrics2021_H2.csv (containing 2021 data from Jul 1-Dec 31), gloval_covid_metrics2022H1.csv (containing 2022 data from Jan 1-June 30), global_covid_metrics2022H2.csv (containing 2022 data from Jul 1-Dec 31), and global_covid_metrics2023H1.csv (containing 2023 data).  

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

## Vaccines (forthcoming)
This dashboard contains information related to COVID-19 vaccines procured and administered globally. Data is sourced from Our World in Data, Duke Launch and Scale Speedometer, United Nations, World Bank, and the World Health Organization. The data for this dashboard can be found under **vaccines.csv**. Variables related to doses procured are a snapshot of current estimates, whereas variables related to vaccines administered are time-series. 

### Codebook
#### Global Variables
- Country - Country/area name
- Population - 2020 total population estimate according to the United Nations' World Population Prospects (NOTE: Some country populations have been adjusted to account for protectorates)
- Income - Country income group as defined by the World Bank (NOTE: Not all countries included have a World Bank incomc classification.)
- Region - Country region as defined by the World Health Organization (NOTE: Not all countries included have a WHO region classification.)

#### Doses Procured Variables (snapshot)
- Number of Doses Procured - Total number of doses procured by country
- Number of Poeple Covered by Doses Procured - Total number of people able to be fully vaccinated, based on vaccine products procured by country
- Share of Population Covered by Doses Procured - % of country's total population that can be fully vaccinated, based on vaccine products procured by country
- Share of Population Covered by Doses Procured by Income - % of income-level's total population that can be fully vaccinated
- Share of Population Covered by Doses Procured by Region - % of region's total population that can be fully vaccinated

#### Doses Administered Variables (time-series)
- Date - Date of observation
- Total Vaccinations - Cumulative number of doses administered by country
- Daily Vaccinations - 7-day rolling average of doses administered per day by country
- People With At Least One Dose - Number of people who have received at least one dose by country
- People Fully Vaccinated - Number of people who have are fully vaccinated by country
- Total Vaccinations per Million - Cumulative number of doses administered by country per million people
- Daily Vaccinations per Million - 7-day rolling average of doses administered per day per million people by country
- Share of Population With At Least One Dose - % of country's total population that has received at least one dose
- Share of Population Fully Vaccinated - % of country's total population that are fully vaccinated
- Total Vaccinations per Million by Income - Cumulative number of doses administered by income-level per million people
- Daily Vaccinations per Million by Income - 7-day rolling average of doses administered per day per million people by income-level
- Share of Population With At Least One Dose by Income - % of income-level's total population that has received at least one dose
- Share of Population Fully Vaccinated by Income - % of income-level's total population that are fully vaccinated
- Total Vaccinations per Million by Region - Cumulative number of doses administered by region per million people
- Daily Vaccinations per Million by Region - 7-day rolling average of doses administered per day per million people by region
- Share of Population With At Least One Dose by Region - % of region's total population that has received at least one dose
- Share of Population Fully Vaccinated by Region - % of region's total population that are fully vaccinated


