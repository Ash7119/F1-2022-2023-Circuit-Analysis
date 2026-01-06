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
- This SQL query calculates the average number of points scored from each starting grid position (1–20) during the 2022–2023 Formula 1 seasons. The query joins race results with race and circuit data to analyze how starting position impacts race outcomes across different circuits.

### Team and Driver Points by Circuit

- This SQL query aggregates total points scored by each driver and their constructor at selected circuits during the 2022–2023 Formula 1 seasons. By joining race results with driver, team, race, and circuit data, the query provides a circuit-level breakdown of performance.

## Tableau
### Average Points Earned per Grid Position
- Grid positions are mapped to their physical layout on the starting grid to enable heatmap visualizations in Tableau that highlight performance differences by grid position.

- Purpose: Evaluate the relationship between starting position and points scored.

### Team and Driver Points by Circuit
- The results allow for comparisons of driver and team performance across circuits and are used to create treemap visualizations in Tableau that display point distributions by track.

- Purpose: Analyze driver and team performance by circuit.  
