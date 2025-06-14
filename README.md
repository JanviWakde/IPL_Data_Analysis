# IPL Data Analysis
### Project Overview
This project analyzes the IPL (Indian Premier League) dataset using Python and popular data analysis libraries such as pandas, matplotlib, and seaborn. The objective is to uncover hidden patterns, performance metrics, and trends at both player and team levels. The project includes data cleaning, exploratory data analysis (EDA), and insightful visualizations.


### Files and Folders
IPL Data Analysis.ipynb — The main Jupyter Notebook containing the complete analysis and code.
matches.csv — Match-level data including match ID, teams, winner, toss details, venue, and Player of the Match.
deliveries.csv — Ball-by-ball level data covering runs, players involved, and dismissals.


### Project Structure
🔹 Importing Libraries and Loading Data
Imported essential Python libraries such as pandas, numpy, matplotlib.pyplot, and seaborn.
Loaded and previewed both datasets (matches.csv and deliveries.csv) into pandas DataFrames.

🔹 Data Exploration
Displayed the first and last few rows of both datasets.
Explored dataset shapes, column names, data types, and missing values.
Checked for unique values, duplicates, and data inconsistencies.

🔹 Data Cleaning
Handled missing values and ensured data consistency (e.g., corrected column names, verified date formats).
Merged datasets where required (e.g., combining match and delivery data for season-wise analysis).

🔹 Data Visualization
Visualized player and team performance using bar plots, line graphs, stacked bars, and heatmaps.
Analyzed metrics such as top run-scorers, wicket-takers, dismissal types, and winning patterns.


### Key Insights
- Most Man of the Match Awards: Chris Gayle has received the most Player of the Match awards.
- Most Runs in a Season: Virat Kohli scored a record-breaking 973 runs in the 2016 season.
- Consistency: Suresh Raina has consistently scored 300+ runs in every IPL season.
- Top Scorers: Players like Virat Kohli, Suresh Raina, and Rohit Sharma dominate the all-time run charts.
- Highest Team Total: RCB recorded the highest-ever IPL total with 263 runs in a single match.
- Most Common Dismissal: "Caught" is the most frequent mode of dismissal.
- Performance Trends: Decline in form of some players (e.g., Kohli post-2016) observed season-wise.
- Toss and Win: Preliminary data shows that winning the toss doesn't always guarantee match victory.

### Conclusion
This project offers a detailed analysis of IPL data through the lens of Python and data visualization. The insights are valuable for understanding player consistency, team strategies, and match outcomes. This project demonstrates the power of data analytics in sports and how actionable insights can be derived through structured analysis and visualization.

