# Access to clean fuels for cooking vs. GDP per capita - Data package

This data package contains the data that powers the chart ["Access to clean fuels for cooking vs. GDP per capita"](https://ourworldindata.org/grapher/access-to-clean-fuels-for-cooking-vs-gdp-per-capita?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For most countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.


## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Access to clean fuels and technologies for cooking
Proportion of population with primary reliance on clean fuels and technology is calculated as the number of people using clean fuels and technologies for cooking, heating and lighting divided by total population reporting that any cooking, heating or lighting, expressed as percentage. “Clean” is defined by the emission rate targets and specific fuel recommendations (i.e. against unprocessed coal and kerosene) included in the normative guidance WHO guidelines for indoor air quality: household fuel combustion.
Last updated: May 19, 2025  
Next update: May 2026  
Date range: 1990–2023  
Unit: %  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
World Health Organization - Global Health Observatory (2025) – processed by Our World in Data

#### Full citation
World Health Organization - Global Health Observatory (2025) – processed by Our World in Data. “Access to clean fuels and technologies for cooking” [dataset]. World Health Organization, “Global Health Observatory” [original data].
Source: World Health Organization - Global Health Observatory (2025) – processed by Our World In Data

### How is this data described by its producer - World Health Organization - Global Health Observatory (2025)?
#### Rationale
The use of solid fuels and kerosene in households is associated with increased mortality from acute lower respiratory, chronic obstructive pulmonary disease, stroke, ischaemic heart disease, and lung cancer.

#### Definition
Proportion of population with primary reliance on clean fuels and technology is calculated as the number of people using clean fuels and technologies for cooking, heating and lighting divided by total population reporting that any cooking, heating or lighting, expressed as percentage. “Clean” is defined by the emission rate targets and specific fuel recommendations (i.e. against unprocessed coal and kerosene) included in the normative guidance WHO guidelines for indoor air quality: household fuel combustion.

#### Method of measurement
The indicator is calculated as the number of people using clean fuels and technologies divided by total population, expressed as a percentage. Based on the recommendations included in the WHO Guidelines for indoor air quality: household fuel combustion, the fuels and technologies that are considered clean include electricity, natural gas, liquified petroleum gas, biogas, ethanol, and solar.

#### Method of estimation
A non-parametrical statistical model based on household survey data and time as inputs is applied to derive estimates. For further information on the model, see Stoner O et al, 2020: Global Household Energy Model: A Multivariate Hierarchical Approach to Estimating Trends in the Use of Polluting and Clean Fuels for Cooking (see link below). Input data for the model is found in the WHO Household Energy Database. This database compiles data from nationally-representative surveys and censuses that provide estimates of primary cooking fuels and technologies. In cases where estimates of the population not cooking at home, with missing data or cooking with "other" fuels are provided, these populations are removed from the denominator for estimation purposes. The population data source is the 2018 Revision of World Urbanization Prospects (see link below).

### Source

#### World Health Organization – Global Health Observatory
Retrieved on: 2025-05-19  
Retrieved from: https://www.who.int/data/gho  


## GDP per capita – In constant international-$ – World Bank
Average economic output per person in a country or region per year. This data is adjusted for inflation and differences in living costs between countries.
Last updated: February 27, 2026  
Next update: February 2027  
Date range: 1990–2024  
Unit: international-$ in 2021 prices  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Eurostat, OECD, IMF, and World Bank (2026) – with minor processing by Our World in Data

#### Full citation
Eurostat, OECD, IMF, and World Bank (2026) – with minor processing by Our World in Data. “GDP per capita – World Bank – In constant international-$” [dataset]. Eurostat, OECD, IMF, and World Bank, “World Development Indicators 125” [original data].
Source: Eurostat, OECD, IMF, and World Bank (2026) – with minor processing by Our World In Data

### What you should know about this data
* GDP per capita is a comprehensive measure of people's average income. It helps compare income levels across countries and track how they change over time. It is especially useful for understanding trends in economic growth and living standards.
* GDP per capita is calculated as the value of all final goods and services produced each year in a country (the [gross domestic product](#dod:gdp)), divided by the population. It represents the average economic output per person.
* This indicator shows the large inequality between people in different countries. In the poorest countries, average incomes are below $1,000 per year; in rich countries, they are more than 50 times higher.
* This data is expressed in constant international dollars to adjust for inflation and differences in living costs between countries. Read more in our article, [What are international dollars?](https://ourworldindata.org/international-dollars)
* This data comes from the World Bank and starts in 1990. For estimates going back several centuries, explore our chart of GDP per capita from the [Maddison Project Database](https://ourworldindata.org/grapher/gdp-per-capita-maddison-project-database).

### How is this data described by its producer - Eurostat, OECD, IMF, and World Bank (2026)?
GDP per capita based on purchasing power parity (PPP). PPP GDP is gross domestic product converted to international dollars using purchasing power parity rates. An international dollar has the same purchasing power over GDP as the U.S. dollar has in the United States. GDP at purchaser's prices is the sum of gross value added by all resident producers in the country plus any product taxes and minus any subsidies not included in the value of the products. It is calculated without making deductions for depreciation of fabricated assets or for depletion and degradation of natural resources. Data are in constant 2017 international dollars.

### Statistical concept and methodology:
For the concept and methodology of 2017 PPP, please refer to the International Comparison Program (ICP)’s website (https://www.worldbank.org/en/programs/icp).

### Source

#### Eurostat, OECD, IMF, and World Bank – World Development Indicators
Retrieved on: 2026-02-27  
Retrieved from: https://data.worldbank.org/indicator/NY.GDP.PCAP.PP.KD  


## Population
Population by country, available from 10,000 BCE to 2023, based on data and estimates from different sources.
Last updated: July 15, 2024  
Next update: July 2026  
Date range: 10000 BCE – 2023 CE  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
HYDE (2023); Gapminder (2022); UN WPP (2024) – with major processing by Our World in Data

#### Full citation
HYDE (2023); Gapminder (2022); UN WPP (2024) – with major processing by Our World in Data. “Population – HYDE, Gapminder, UN – Long-run data” [dataset]. PBL Netherlands Environmental Assessment Agency, “History Database of the Global Environment 3.3”; Gapminder, “Population v7”; United Nations, “World Population Prospects”; United Nations, “World Population Prospects - Interim Update”; Gapminder, “Systema Globalis” [original data].
Source: HYDE (2023); Gapminder (2022); UN WPP (2024) – with major processing by Our World In Data

### What you should know about this data
* Population is the most commonly used metric throughout Our World in Data. It is used directly to understand population growth over time, and indirectly to calculate per-capita indicators, making it easier to compare countries of different sizes.
* We construct this indicator by combining multiple sources covering different periods.
  - HYDE v3.3 (2023): historical estimates from 10,000 BCE to 1799.
  - Gapminder v7 (2022): for 1800-1949.
  - UN World Population Prospects (2024): for 1950 onwards, including 2100 projections.
  - Gapminder Systema Globalis (2023): additional source for former countries (Yugoslavia, USSR, etc.)
* Breaks in the data may occur at the boundaries between sources due to their methodological differences.
* You can read more about the sources and methodology in our [dedicated article](https://ourworldindata.org/population-sources). We also provide a table of sources showing the source we use for each country-year.
* We calculate geographical aggregates (continents, income groups, etc.) by summing individual country populations. For years before 1800, we rely directly on HYDE's values for continents to ensure historical consistency.

### Sources

#### PBL Netherlands Environmental Assessment Agency – History Database of the Global Environment
Retrieved on: 2024-01-02  
Retrieved from: https://doi.org/10.24416/UU01-AEZZIT  

#### Gapminder – Population
Retrieved on: 2023-03-31  
Retrieved from: http://gapm.io/dpop  

#### United Nations – World Population Prospects
Retrieved on: 2024-07-11  
Retrieved from: https://population.un.org/wpp/downloads/  

#### United Nations – World Population Prospects - Interim Update
Retrieved on: 2026-03-31  
Retrieved from: https://population.un.org/wpp/downloads/  

#### Gapminder – Systema Globalis
Retrieved on: 2023-03-31  
Retrieved from: https://github.com/open-numbers/ddf--gapminder--systema_globalis  

#### Notes on our processing step for this indicator
### Combination of different sources
We construct our long-run population data by combining multiple sources:

- 10,000 BCE–1799: historical estimates by HYDE (v3.3).

- 1800–1949: historical estimates by Gapminder (v7).

- 1950–2023: population records from the United Nations World Population Prospects (2024 revision).

**Geographical aggregates**

- For most years, we calculate aggregates by summing the population of member countries.
- We do this based on [our definition of continents](https://ourworldindata.org/world-region-map-definitions#our-world-in-data) and the [World Bank’s income groups](https://ourworldindata.org/grapher/world-bank-income-groups).
- The only exception is before 1800, where we use HYDE's estimates for continents (but not income groups).

For most of the years, we've estimated regional aggregates by summing the population of countries in each region. We've relied on [our continents](https://ourworldindata.org/world-region-map-definitions#our-world-in-data) and [World Bank income group definitions](https://ourworldindata.org/grapher/world-bank-income-groups). The only exception is before 1800, where we've used HYDE's estimates on continents (but not income groups).

**World**
- Before 1800: we use data from HYDE.
- 1800-1950: we estimate the global population by summing all available countries in the dataset.
- After 1950, we rely on estimates from the United Nations World Population Prospects.


## World region according to OWID
Regions defined by Our World in Data, which are used in OWID charts and maps.
Last updated: January 1, 2023  
Date range: 2023–2023  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Our World in Data – processed by Our World in Data

#### Full citation
Our World in Data – processed by Our World in Data. “World region according to OWID” [dataset]. Our World in Data, “Regions” [original data].
Source: Our World in Data

### Source

#### Our World in Data – Regions


    