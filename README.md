# COVID-19 Exploratory Data Analysis (EDA)

## Project Description

This project provides an in-depth Exploratory Data Analysis (EDA) on the global COVID-19 dataset. The goal is to analyze the spread of COVID-19, the impact on various countries, and the trends in confirmed, active, and recovered cases over time.

## Dataset

The dataset used in this project is the **COVID-19 clean complete dataset** which includes the following columns:

- `Province/State`: Name of the province or state (if applicable).
- `Country/Region`: Name of the country or region.
- `Lat`: Latitude of the region.
- `Long`: Longitude of the region.
- `Date`: Date of the recorded data.
- `Confirmed`: Number of confirmed COVID-19 cases.
- `Deaths`: Number of deaths due to COVID-19.
- `Recovered`: Number of recovered individuals.
- `Active`: Number of active COVID-19 cases.
- `WHO Region`: The WHO region to which the country belongs.

## Key Findings

- **Confirmed COVID-19 Cases Over Time**: The confirmed cases have risen consistently across the globe.
- **Top 10 Countries by Confirmed Cases**: The United States, India, and Brazil were the countries with the highest number of confirmed COVID-19 cases during the period of analysis.
- **Trends in Confirmed Cases**: Significant peaks in confirmed cases were observed between July and December 2020.

## Visualizations

1. **Confirmed COVID-19 Cases Over Time**: A line plot showing the increase in confirmed COVID-19 cases globally.
2. **Top 10 Countries by Confirmed Cases**: A bar plot highlighting the top 10 countries with the highest confirmed cases.

## Requirements

To run this project, you'll need the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install them using the following command:

```bash
pip install pandas matplotlib seaborn
