# Bike Sharing Data Analysis 

This project involves the analysis of a bike-sharing dataset, focusing on understanding customer behavior, system performance, and resource optimization. The dataset includes details about trips, costs, energy consumption, and more.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Description](#data-description)
3. [Key Analyses](#key-analyses)
4. [Methodology](#methodology)
5. [Insights](#insights)
6. [Future Work](#future-work)
7. [Dependencies](#dependencies)
8. [Usage](#usage)

---

## Project Overview
The goal of this project is to gain insights into bike-sharing usage patterns, identify optimization opportunities, and explore customer behaviors. The analysis spans data exploration, statistical testing, and visualization.

---

## Data Description
The dataset includes the following key features:
- **Ticket Type**: Categorical variable (Single, Season, Savonia).
- **Cost**: Fee paid (in euros).
- **Month**: Month of the trip (April–October).
- **Locations**: Start and end locations of trips.
- **Duration**: Travel time (in seconds).
- **Distance**: Travel distance (in meters).
- **Assistance**: Electric assistance status (0 = disabled, 1 = enabled).
- **Energy Used**: Energy consumed during the trip (in watt-hours).
- **Energy Collected**: Energy recovered during the trip (in watt-hours).

---

## Key Analyses
### 1. Data Exploration
- Examined the distribution and validity of key variables.
- Resolved data inconsistencies (e.g., negative distances, energy consumption mismatches).

### 2. Customer Insights
- Analyzed usage patterns by ticket type.
- Calculated total trips, distance, and fees for different customer segments.

### 3. Station Analysis
- Identified stations with the highest surplus and deficit of bikes.
- Suggested relocation strategies to optimize resource distribution.

### 4. Energy Trends
- Examined net energy gain trends for trips with and without electric assistance.

### 5. Hypothesis Testing
- Compared travel times across ticket types using t-tests and Mann-Whitney U tests.
- Analyzed the correlation between energy consumption rates and travel distance.

---

## Methodology
- **Data Cleaning**: Addressed invalid entries and missing values.
- **Visualization**: Used bar plots, scatter plots, and line plots to present findings.
- **Statistical Analysis**: Applied hypothesis testing to validate observed trends.
- **Optimization Recommendations**: Proposed strategies for improving system efficiency.

---

## Insights
1. **Customer Behavior**:
   - Single ticket holders contribute the highest revenue and usage.
   - Seasonal variations strongly influence rental activity.

2. **Station Imbalances**:
   - Surplus stations: KAUPPAKATU, PUIJONLAAKSO.
   - Deficit stations: SATAMA, KYS, TORI.

3. **Energy Trends**:
   - Longer trips with electric assistance result in higher energy consumption.
   - Non-assisted trips often result in net energy recovery.

4. **Travel Times**:
   - Single ticket holders tend to have longer travel durations than seasonal users.

---

## Future Work
1. Refine customer value analysis by incorporating profitability metrics.
2. Explore the impact of pricing changes on customer behavior.
3. Conduct deeper analysis of energy patterns to optimize battery usage.

---

## Dependencies
This project uses the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `sklearn`
