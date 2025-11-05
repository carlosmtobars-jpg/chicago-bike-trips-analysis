# Chicago Bike Trips Analysis

## Overview
This project explores bike share trip data from Chicago to understand how different types of users (subscribers vs. casual riders) use the service.  
The analysis looks at trip duration, day-of-week and time-of-day patterns, as well as seasonality.

## Dataset
The dataset contains bike trips made in Chicago and includes:

- Trip start and end timestamps
- Trip duration
- User type (subscriber vs. casual)
- Additional fields such as station and bike identifiers (depending on the dataset version)

> Note: The raw data is not included in this repository.  
> The notebook assumes you store the CSV files locally in a `data/` folder.

## Tech stack
- Python: `pandas`, `numpy`
- Visualization: `matplotlib`, `seaborn`
- Statistics: `scipy.stats`
- Environment: Jupyter Notebook

## Key questions
1. Do subscribers and casual users behave differently in terms of trip duration?
2. How does usage vary by hour of the day and day of the week?
3. Is there seasonality in the number of trips throughout the year?

## Methodology
1. Data cleaning (handling missing values, parsing dates).
2. Feature engineering (extracting hour, day of week, month).
3. Exploratory data analysis and visualizations.
4. Statistical hypothesis testing to compare groups.

## Example insights
- Casual riders usually take longer trips, particularly during weekends and afternoons.
- Subscribers show strong commuting patterns during weekday mornings and evenings.
- Trip volume increases significantly in warmer months, highlighting weather dependency.

## How to run
1. Clone this repository.
2. Place the CSV files into a `data/` folder.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
