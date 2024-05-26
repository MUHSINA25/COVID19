# COVID19

# COVID-19 Dashboard

## Overview

This COVID-19 Dashboard provides an interactive view of the COVID-19 pandemic using data from six different sources. The dashboard has three main pages, each providing different insights.

## Data Sources

The dashboard uses data from the following sources:
1. **country_wise_latest.csv**
2. **covid_19_clean_complete.csv**
3. **day_wise.csv**
4. **full_grouped.csv**
5. **usa_county_wise.csv**
6. **worldometer_data.csv**

The data has been cleaned and preprocessed for accuracy and relevance.

## Pages

### 1. Global Overview

**Features:**
- **WHO Region Slicer:** Filter data by WHO regions. Reset button returns to global view.
- **Pie Chart (Total Deaths by Country):** Shows the top 5 countries by total deaths. The US accounts for about 41.04% of total deaths, followed by Brazil, the UK, Mexico, and Italy.
- **Stacked Bar Chart (Total Deaths by WHO Region):** Displays total deaths by WHO region:
  - Americas: 342,732
  - Europe: 211,144
  - South-East Asia: 41,349
  - Eastern Mediterranean: 38,339
  - Africa: 12,223
  - Western Pacific: 8,249
- **Matrix (Total Deaths and Recoveries by Country):** Shows total deaths and recoveries. The US has the highest deaths, Brazil leads in recoveries.
- **Clustered Column Chart (Total Cases by WHO Region):** Illustrates total confirmed cases by WHO region, with the Americas having the most and the Western Pacific the least.
- **Area Chart (Active Cases by Country):** Displays the top 10 countries by active cases. The US has 2.8 million active cases.
- **Map (Total Confirmed Cases by Country):** A map showing total confirmed cases by country. Updates based on selected WHO region.
- **Key Statistics (Cards):** Shows:
  - Total Confirmed Cases: 16 million
  - Total Recoveries: 9 million
  - Total Deaths: 654,000

**Purpose:**
Provides a high-level summary of the pandemic’s impact, showing regional variations and heavily affected areas.

### 2. Monthly Trends

**Features:**
- **Month Selector:** Buttons and a slicer to filter data by month.
- **Line Chart (Total New Cases by Month):** Shows the rise in new cases from January (9,293) to July (5.9 million).
- **Area Chart (Total Confirmed Cases by Country):** Displays the top 5 countries by confirmed cases. The US has about 0.22 billion cases.
- **Tree Map (Total Active Cases by WHO Region):** Highlights active cases by WHO region, with the Americas having the most.
- **Funnel Chart (Total New Deaths by Month):** Shows deaths per month, peaking in April (188,000) and lowest in January (196).
- **Stacked Column Chart (Total Affected Countries by Month):** Indicates the number of countries affected each month, with March having 29 affected countries.
- **Map (Total Active Cases by Country):** Shows active cases by country, updated based on the selected month.

**Purpose:**
Provides insights into how COVID-19 spread over time, showing monthly trends and the increasing impact.

### 3. Testing and Critical Cases

**Features:**
- **Key Metrics (Gauges):** Displays key values:
  - Total Cases per 1M People: 665k
  - Total Deaths per 1M People: 18.45k
  - Total Tests per 1M People: 16M
- **Donut Chart (Total Tests by Continent):** Shows testing by continent:
  - Europe: 96M
  - North America: 70M
  - Asia: 65M
  - South America: 22M
  - Australia: 5M
- **Stacked Column Chart (Total Cases by Continent):** Displays total cases by continent, with North America having the most (5.9M) and Australia the least (21,735).
- **Line Chart (Critical Cases by Total Cases):** Shows total cases (5,032,179) and critical cases (18,296).
- **Area Chart (Total Tests per 1M People by Country):** Filters the top 10 countries with the most tests per million people, including Luxembourg and Monaco.
- **Matrix:** Summarizes total cases, deaths, and recoveries by WHO region and continent.
- **Continent Slicer:** Filter data by continent, updating all visuals.
- **Navigation Button:** "Home Page" button to return to the first page.

**Purpose:**
Provides insights into testing efforts and critical cases, showing the extent and effectiveness of testing across regions.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/covid19-dashboard.git


