# Public Transport Efficiency Analysis: Understanding City Bus Delay Patterns

## Overview
This Jupyter Notebook analyzes the efficiency of public transport buses by examining delay patterns in city bus routes. It provides insights into where, when, and why buses are delayed, aiming to help improve transit reliability and operational planning.

## Objective
The main objective is to perform Exploratory Data Analysis (EDA) to identify patterns and causes of delays in public transport buses. The analysis focuses on:
- Which bus routes experience the most delays
- Timing of delays: morning vs evening rush hours
- Impact of conditions such as weekdays vs weekends, and route distances
- Regional variation in delay patterns

## Dataset
The dataset used contains 5,000 entries with the following key fields:
- `routeid`: Bus route identifier
- `busnumber`: Bus identification number
- `scheduledarrival`: Scheduled arrival time
- `actualarrival`: Actual arrival time
- `delayminutes`: Delay in minutes (negative values indicate early arrivals)
- `distancekm`: Route distance in kilometers
- `weekday`: Day of the week
- `weather`: Weather conditions during the trip
- `region`: City region of the bus route

## Analysis Highlights
- **Delay Distribution**: Most buses experience varying delays, ranging from early arrivals to significant late arrivals.
- **Route Insights**: Certain routes consistently show higher average delays, identifying potential hotspots for operational focus.
- **Time Patterns**: Delay characteristics differ during morning and evening rush hours.
- **Regional Trends**: Some city regions have slightly higher average delays, but variations are generally moderate.
- **Distance vs Delay**: Route distance is not strongly correlated with delays, suggesting other factors impact efficiency more.

## Tools and Libraries
The notebook leverages popular Python libraries for data analysis and visualization:
- `pandas` and `numpy` for data manipulation
- `matplotlib`, `seaborn`, and `plotly` for plotting and interactive visualizations

## How to Use
1. Load the dataset into the notebook.
2. Run the cells step-by-step to follow the data cleaning, transformation, and exploratory analysis.
3. Review the visualizations and summarized insights for understanding delay patterns.
4. Use the insights to guide decisions for improving public transport timeliness.

## Conclusion
This analysis provides a comprehensive view of city bus delays, highlighting critical routes, times, and conditions contributing to inefficiency. It serves as a foundation for transit authorities or researchers aiming to optimize public transport services.

---

_For detailed code and stepwise analysis, please refer to the notebook itself._

