# Environmental Impact of COVID-19 Lockdowns on Air Quality in Massachusetts

## Overview

This project investigates the impact of COVID-19 lockdown measures on air quality in Massachusetts, focusing on the relationship between the Air Quality Index (AQI), Social Distancing Index (SDI), COVID-19 cases, and energy demand.

## Project Structure

- `SDI_vs_AQI_vs_COVID_19.ipynb`: Main Jupyter notebook containing the analysis of Social Distancing Index (SDI), Air Quality Index (AQI), and COVID-19 cases. This notebook:
  - Imports and processes COVID-19 data
  - Analyzes and visualizes total and daily COVID-19 cases by county
  - Imports and processes Social Distancing Index (SDI) data
  - Merges COVID-19 and SDI data
  - Calculates correlations between COVID-19 cases and SDI
  - Visualizes SDI trends with key COVID-19 lockdown dates
  - Imports and processes Air Quality Index (AQI) data
  - Analyzes relationships between AQI, SDI, and COVID-19 cases
  - Investigates long-term variations in AQI, including seasonal patterns
- `energyanalysis.ipynb`: Jupyter notebook focusing on energy demand analysis. This notebook:
  - Imports and processes hourly energy demand data from 2011 to 2023
  - Calculates daily and weekly aggregates of energy demand
  - Visualizes energy demand trends over the years, highlighting the impact of COVID-19
  - Analyzes the correlation between energy demand and Air Quality Index (AQI)
- `All_Polutant_analysis_.ipynb`: Jupyter notebook analyzing various pollutants and their impact on AQI. This notebook:
  - Imports and processes AQI data for multiple pollutants across Massachusetts counties
  - Calculates average AQI values and identifies main pollutants for each county
  - Compares AQI values and pollutant trends before and during the pandemic
  - Visualizes yearly and monthly AQI trends across counties
  - Performs correlation analysis between AQI, COVID-19 cases, and SDI for different time periods and seasons
  - Creates choropleth maps showing AQI changes over time
  - Generates animated visualizations of AQI changes across Massachusetts
- `Project_Report.pdf`: Detailed report of the project findings and methodology.
- `Project_Presentation.ppt`: PowerPoint presentation used for showcasing the project results.

## Key Findings

### AQI and COVID-19 Cases
- Weak correlation (0.007) between AQI values and COVID-19 cases
- No significant improvement in air quality directly linked to COVID-19 cases

### Social Distancing and Air Quality
- SDI used as a proxy for lockdown measures
- Varied correlations between SDI and AQI across counties:
  - Some counties showed slight positive correlation
  - Others displayed weak negative correlation
- Overall weak correlations suggest complex relationship between social distancing and air quality

### Energy Demand and AQI
- Weak to moderate correlation (0.38) between energy demand and AQI
- Post-COVID years showed decline in energy demand during initial months
- July peak energy demand remained consistent with previous years

### Seasonal Variations in AQI
- Mean AQI tends to be higher in summer months (June, July, August) for most counties
- Possibly due to increased sunlight and heat contributing to pollutant formation

### Pollutant Analysis
- Ozone identified as the main pollutant in most counties, with Suffolk County showing PM2.5 as the main pollutant
- Slight decrease in average AQI values during the pandemic in most counties
- Fewer instances of high AQI values (>100) during the pandemic period

## Conclusions

- Lockdown measures had some impact on air quality, but changes were not significant
- AQI values remained within good to moderate range throughout the study period
- Relationship between AQI, COVID-19 cases, SDI, and energy demand is complex and varies by location and time

## Implications

- Further research needed to establish causality and identify additional factors influencing air quality
- Future studies should incorporate factors such as population density, healthcare access, and socioeconomic variables

## Data Sources

- COVID-19 data: Massachusetts government and USAFacts websites
- AQI data: Environmental Protection Agency (EPA) Air Data - Multiyear Tile Plot tool
- SDI data: Harvard Dataverse
- Energy demand data: ISO New England website

## Methodology

- Data analysis performed using Python
- Correlation analysis (Pearson, Spearman, and Kendall Tau) conducted for various relationships
- Time series analysis and visualizations created to identify patterns and trends
- Geospatial analysis and mapping of AQI data across Massachusetts counties

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, matplotlib, seaborn, numpy, scipy, geopandas, imageio, cv2

## Setup and Running

1. Clone this repository.
2. Install the required libraries: `pip install -r requirements.txt`
3. Open the Jupyter notebooks to view the analysis.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Raghu Ram Sattanapalle

Project Link: [https://github.com/RaghuRamSatt/Exploring-the-Environmental-Impact--Can-staying-at-home-enhance-Air-Quality](https://github.com/RaghuRamSatt/Exploring-the-Environmental-Impact--Can-staying-at-home-enhance-Air-Quality)