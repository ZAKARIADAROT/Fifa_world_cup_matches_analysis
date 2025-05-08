# World Cup Match Data Analysis and Visualization

This project analyzes a dataset of FIFA World Cup matches using Python, with the goal of uncovering insights from match statistics and visualizing key trends.

## 📊 Dataset Overview

The dataset contains detailed statistics for each World Cup match, including:

- Team names
- Possession percentages
- Goals scored
- Shot attempts (on/off target, inside/outside the penalty area)
- Assists, channels of play, line breaks
- Match date and time

The data was loaded and cleaned using `pandas`, and visualized using `matplotlib` and `seaborn`.

## 🧹 Data Cleaning

- Converted the `date` column to proper datetime format.
- Removed or handled missing and non-numeric values.
- Ensured numerical columns were ready for statistical analysis and plotting.

## 🔍 Data Analysis Highlights

- Basic statistics such as mean, median, and standard deviation were computed for numerical fields like possession and goal attempts.
- Identified patterns in goal distribution and shooting behavior by teams.

## 📈 Visualizations

Several plots were created to visualize the data:

1. **Line Chart** – Trend of average goal attempts over time.
2. **Bar Chart** – Comparison of goals scored by team1 vs. team2.
3. **Histogram** – Distribution of possession percentages across matches.
4. **Scatter Plot** – Relationship between total attempts and goals scored.

All plots include titles, labeled axes, and legends where appropriate to improve readability and interpretation.

## 💡 Tools Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Project Structure

- `world_cup_matches.csv` – Raw dataset
- `WorldCup_Analysis.ipynb` – Jupyter notebook containing code, analysis, and visualizations

## 📌 Conclusion

This project demonstrates how to perform end-to-end data analysis on real-world sports data using Python. It showcases how visual insights can be extracted to support data-driven understanding of match performance and strategy.

---

