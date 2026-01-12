# Urban Mobility & Traffic Analysis – NYC

## Objective
Analyze traffic, accidents, and weather data to identify mobility patterns in New York City.

## Data Sources
- Traffic data: NYC Open Data
- Accident data: NYC Motor Vehicle Collisions
- Weather data: OpenWeather API

## Architecture
Raw → Transformed → Curated

- Raw: Original CSV / API extracts
- Transformed: Cleaned and normalized datasets
- Curated: Aggregated datasets used in Power BI

## Data Processing
Python (Pandas and Numpy) was used for:
- Data cleaning
- Date normalization
- Null handling
- Daily aggregations

## Orchestration
The pipeline is designed to be orchestrated using Apache Airflow (DAG provided).

## Visualization
Power BI dashboard showing:
- Traffic intensity by borough
- Accident distribution by vehicle type
- Temperature trends
- KPIs

## Key Insights
- Certain boroughs concentrate higher traffic and accident rates
- Temporal patterns suggest potential correlation between weather and accidents