# Country Trend Data
This folder contains all the data powering the upcoming KFF Global COVID-19 Trackers. These dashboards will replace the current global COVID-19 tracker which can be found [here](https://www.kff.org/coronavirus-covid-19/fact-sheet/coronavirus-tracker/). These upcoming dashboards will only contain select data, to limit large data files. However, the full data sets can be found here. 

## Global COVID-19 Dashboard
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

## Global COVID-19 Vaccine Dashboard
This dashboard contains information related to COVID-19 vaccines procured and administered globally. Data is sourced from Our World in Data, Duke Launch and Scale Speedometer, United Nations, World Bank, and the World Health Organization. The data for this dashboard can be found under **vaccines.csv**. Variables related to doses procured are a snapshot of current estimates, whereas variables related to vaccines administered are time-series.

### Codebook

- Global Variables
  - Country - Country/area name
  - Population - 2020 total population estimate according to the United Nations' World Population Prospects (NOTE: Some country populations have been adjusted to account for protectorates)
  - Income - Country income group as defined by the World Bank
  - Region - Country region as defined by the World Health Organization
- Doses Procured Variables
  - Number of Doses Procured - Total number of secured doses procured by Country
  - Share of Population Covered by Doses Procured - Estimated share of total country population able to be vaccinated based on number of doses procured and vaccine type
  - Share of Population Covered by Doses Procured by Income - Estimated share of total income-level population able to be vaccinated based on number of doses procured and vaccine type
  - Share of Population Covered by Doses Procured by Region - Estimated share of total region-level population able to be vaccinated based on number of doses procured and vaccine type
- Doses Administered Variables
  - Date - Date of observation
  - Total Vaccinations - Total number of doses administered
  - Daily Vaccinations - Total number of doses administered per day (using OWID's 7-day smoothed calculation)
  - People With At Least One Dose - Total number of people who have received at least one dose
  - People Fully Vaccinated - Total number of people who have received the full round of doses required, according to vaccine type
  - Total Vaccinations per Million - Total number of doses administered per 1 million people
  - Daily Vaccinations per Million - Total number of doses administered per day per 1 million people
  - Share of Population With At Least One Dose - Share of country population that has received at least one dose
  - Share of Population Fully Vaccinated - Share of country population that is fully vaccinated
  - Total Vaccinations per Million by Income - Total number of doses administered per 1 million people by income-level
  - Daily Vaccinations per Million by Income - Total number of doses administered per day per 1 million people by income-level
  - Share of Population With At Least One Dose by Income - Share of income-level population that has received at least one dose
  - Share of Population Fully Vaccinated by Income - Share of income-level population that is fully vaccinated
  - Total Vaccinations per Million by Region - Total number of doses administered per 1 million people by region-level
  - Daily Vaccinations per Million by Region - Total number of doses administered per day per 1 million people by region-level
  - Share of Population With At Least One Dose by Region - Share of region-level population that has received at least one dose
  - Share of Population Fully Vaccinated by Region - Share of region-level population that is fully vaccinated

## Global COVID-19 Policy Actions Table
This tracker contains information related to COVID-19 policy responses globally. Data is sourced from the Oxford Covid-19 Government Response Tracker, World Bank, and the World Health Organization. The data for this dashboard can be found under **policy_actions.csv**. 

### Codebook

- Country - Country/area name
- Date - Date of observation
- Policy Category - Whether a policy is considered a closure response, economic response, or health-related response.
- Policy Value - Range of values based on Oxford Covid-19 Government Response Tracker's [codebook](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md)
- Policy Value Description - Description of policy action based on Oxford Covid-19 Government Response Tracker's [codebook](https://github.com/OxCGRT/covid-policy-tracker/blob/master/documentation/codebook.md)
- Income - Country income group as defined by the World Bank
- Region - Country region as defined by the World Health Organization
