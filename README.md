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
- **WHO Region Slicer:**
  - **Purpose:** Allows users to filter data by WHO regions (Americas, Europe, South-East Asia, Eastern Mediterranean, Africa, Western Pacific).
  - **Insight:** Users can see how the pandemic affects different regions, providing a comparative analysis.

- **Pie Chart (Total Deaths by Country):**
  - **Purpose:** Displays the top 5 countries by total deaths.
  - **Insight:** Highlights that the US accounts for about 148,011 (41.04%) of total deaths, followed by Brazil (24.3%), the UK (12.71%), Mexico (12.21%), and Italy (9.74%). This underscores the severe impact on these countries.

- **Stacked Bar Chart (Total Deaths by WHO Region):**
  - **Purpose:** Shows total deaths by WHO region.
  - **Insight:** 
    - **Americas:** 342,732 deaths.
    - **Europe:** 211,144 deaths.
    - **South-East Asia:** 41,349 deaths.
    - **Eastern Mediterranean:** 38,339 deaths.
    - **Africa:** 12,223 deaths.
    - **Western Pacific:** 8,249 deaths.
  - **Insight:** The Americas and Europe are the most affected regions in terms of deaths, indicating higher mortality rates or larger populations.

- **Matrix (Total Deaths and Recoveries by Country):**
  - **Purpose:** Displays total deaths and recoveries by country.
  - **Insight:** The US has the highest deaths, while Brazil leads in recoveries. This shows the varying capacity of countries to manage recoveries.

- **Clustered Column Chart (Total Cases by WHO Region):**
  - **Purpose:** Illustrates total confirmed cases by WHO region.
  - **Insight:** The Americas (129,531) have the most cases, while the Western Pacific has the least (3,289). This might reflect differences in population density, healthcare systems, and government responses.

- **Area Chart (Active Cases by Country):**
  - **Purpose:** Displays the top 10 countries by active cases.
  - **Insight:** The US has 2.8 million active cases, indicating ongoing widespread transmission. Brazil and India both have 0.5 million active cases, showing significant ongoing transmission in these countries as well.

- **Map (Total Confirmed Cases by Country):**
  - **Purpose:** A map showing total confirmed cases by country.
  - **Insight:** Provides a geographical representation of the pandemic’s spread, with the ability to see country-specific data. North America, specifically the US, shows the highest number of confirmed cases at 4,290,259. In South America, Brazil shows 2,442,375 confirmed cases.

- **Key Statistics (Cards):**
  - **Purpose:** Summarizes key metrics.
  - **Insight:** 
    - **Total Confirmed Cases:** 16 million.
    - **Total Recoveries:** 9 million.
    - **Total Deaths:** 654,000.
  - **Insight:** These figures give a snapshot of the global scale of the pandemic.

**Purpose:**
Provides a high-level summary of the pandemic’s impact, showing regional variations and heavily affected areas.

**Key Insights:**
- The Americas and Europe are the most affected regions in terms of total deaths and confirmed cases.
- The US stands out with the highest number of deaths and active cases, indicating a severe impact.
- The data reveals significant differences in the pandemic's impact across WHO regions.
- Brazil and India also show significant ongoing transmission with high numbers of active cases.
- Geographical representation highlights the US and Brazil as major hotspots with the highest number of confirmed cases in their respective continents.

### 2. Monthly Trends

**Features:**
- **Month Selector:**
  - **Purpose:** Allows users to filter data by month.
  - **Insight:** Users can see how the pandemic evolved over time on a month-by-month basis.

- **Line Chart (Total New Cases by Month):**
  - **Purpose:** Shows the rise in new cases from January to July.
  - **Insight:** 
    - **January:** 9,293 new cases.
    - **July:** 5.9 million new cases.
  - **Insight:** The exponential increase in new cases shows the rapid spread of the virus.

- **Area Chart (Total Confirmed Cases by Country):**
  - **Purpose:** Displays the top 5 countries by confirmed cases.
  - **Insight:** The US has about 0.22 billion cases, indicating it is the hardest-hit country.

- **Tree Map (Total Active Cases by WHO Region):**
  - **Purpose:** Highlights active cases by WHO region.
  - **Insight:** The Americas have the most active cases, reflecting ongoing transmission and possibly limited control measures.

- **Funnel Chart (Total New Deaths by Month):**
  - **Purpose:** Shows deaths per month.
  - **Insight:** 
    - **April:** 188,000 deaths.
    - **January:** 196 deaths.
  - **Insight:** The peak in April indicates a high mortality rate during this period, possibly due to overwhelmed healthcare systems.

- **Stacked Column Chart (Total Affected Countries by Month):**
  - **Purpose:** Indicates the number of countries affected each month.
  - **Insight:** 
    - **March:** 29 affected countries.
    - **February:** 12 affected countries.
  - **Insight:** The increase in affected countries shows the global spread of the virus.

- **Map (Total Active Cases by Country):**
  - **Purpose:** Shows active cases by country, updated based on the selected month.
  - **Insight:** Provides a month-by-month geographical spread of active cases.

**Purpose:**
Provides insights into how COVID-19 spread over time, showing monthly trends and the increasing impact.

**Key Insights:**
- There is an exponential increase in new cases from January to July, indicating rapid spread.
- The US consistently leads in total confirmed cases each month.
- Active cases are predominantly in the Americas, showing regional hotspots.
- Deaths peaked in April, suggesting the highest mortality rate during this period.

### 3. Testing and Critical Cases

**Features:**
- **Key Metrics (Gauges):**
  - **Purpose:** Displays key values.
  - **Insight:** 
    - **Total Cases per 1M People:** 665k.
    - **Total Deaths per 1M People:** 18.45k.
    - **Total Tests per 1M People:** 16M.
  - **Insight:** These metrics provide a per capita perspective, showing the extent of the pandemic relative to population size.

- **Donut Chart (Total Tests by Continent):**
  - **Purpose:** Shows testing by continent.
  - **Insight:** 
    - **Europe:** 80M tests.
    - **North America:** 70M tests.
    - **Asia:** 60M tests.
  - **Insight:** Reflects testing capacity and efforts by continent.

- **Bar Chart (Critical Cases by Country):**
  - **Purpose:** Displays the number of critical cases by country.
  - **Insight:** Countries with the highest number of critical cases can be identified, indicating where healthcare systems may be under the most strain.

**Purpose:**
Provides a detailed view of testing efforts and critical cases, highlighting healthcare system capacity and stress.

**Key Insights:**
- Per capita metrics show the significant impact of the pandemic relative to population size.
- Testing efforts vary by continent, with Europe leading in total tests conducted.
- Identifying countries with the highest number of critical cases helps understand where healthcare systems are most burdened.








