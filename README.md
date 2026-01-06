# F1 2022–2023 Circuit Analysis

Performed an in-depth analysis of selected Formula 1 circuits from the 2022–2023 seasons. Used SQL to query and transform race data from a relational database, focusing on team and driver performance trends. Built interactive Tableau dashboards to visualize total points by team and driver and average points scored by grid position.

## Technologies Used
- SQL 
- Tableau

## Key Insights
- Comparison of points earned by teams and drivers across favorite circuits
- Analysis of average points scored by starting grid position
  
## Data Source
- Formula 1 Race Data (Kaggle):  
  https://www.kaggle.com/datasets/jtrotman/formula-1-race-data

## SQL Code
### Average Points Earned per Grid Position
This SQL query calculates the average number of points scored from each starting grid position (1–20) during the 2022–2023 Formula 1 seasons. The query joins race results with race and circuit data to analyze how starting position impacts race outcomes across different circuits.

Grid positions are also mapped to their physical placement on the starting grid (left or right side, and row number) to support visualization of performance differences by grid layout in Tableau.

Purpose: Evaluate the relationship between starting position and points scored 
