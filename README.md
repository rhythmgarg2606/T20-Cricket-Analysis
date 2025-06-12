# 🏏 T20 Cricket Analysis & Team Selection Dashboard

A dynamic Power BI dashboard that transforms raw cricket data into powerful insights to assist in player evaluation and optimal team selection for T20 matches. Built with a strong focus on data modeling, DAX calculations, and interactive visualization, this project enables data-driven decision-making for cricket analysts, coaches, and selectors.

---

## 📌 Project Overview

Traditional team selection in cricket often involves subjective judgment and limited statistics. This project solves that by:

- Collecting and cleaning player performance data
- Modeling it in Power BI using advanced DAX
- Visualizing player profiles, trends, and team composition
- Allowing dynamic filtering, comparison, and team simulation

> This solution bridges the gap between raw statistics and strategic insights for cricket teams.

---

## 📊 Key Features

- **Role-Based Filtering**: View players grouped by roles like Hitters, Anchors, All-Rounders, Bowlers
- **Trend Analysis**: See player performance trends over time (batting avg, strike rate, economy, etc.)
- **Player Comparison**: Interactive scatter plots and performance metrics side-by-side
- **Final 11 Selector**: Choose your team and instantly view combined strength stats
- **Tooltips & Profiles**: Hover for key stats or drill into detailed per-match analysis

---

## 🧰 Tech Stack

| Feature               | Tool/Platform             |
|----------------------|---------------------------|
| Data Collection       | Bright Data (Web Scraper API, Browser API) |
| Data Transformation   | Power Query Editor        |
| Data Modeling         | Power BI (Star Schema, DAX) |
| Visualization         | Power BI Dashboard        |
| File Format           | CSV                       |

---

## 📂 Project Structure

cricket-analysis-dashboard/
├── README.md
├── T20 Cricket Analysis.docx # Detailed project report
├── data/
│ ├── metrics_list.csv
│ └── match_stats.csv
├── pbix/
│ └── cricket_dashboard.pbix # Power BI dashboard file
├── assets/
│ └── screenshots/ # Dashboard preview images (optional)


---

## 📁 Data Sources

Player and match statistics were collected via Bright Data from:
- Public cricket websites
- Match archives and player profiles

Scraped data includes:
- Batting: Runs, Balls Faced, Strike Rate, Boundaries, Averages
- Bowling: Overs, Wickets, Economy, Bowling Avg
- Match Context: Opponent, Date, Venue

---

## 📐 Data Model & DAX Examples

- **Star Schema**: Fact table + Player, Match, and Date dimensions
- **Key DAX Measures**:
  - `Batting Average = Total Runs / Dismissals`
  - `Strike Rate = (Runs / Balls Faced) * 100`
  - `Bowling Economy = Runs Conceded / Overs`
  - `Player Form (Last 5 Matches)` via `TOPN()` and `AVERAGEX()`

---

## 🚀 How to Use

1. Clone this repository
2. Open the `.pbix` file in Power BI Desktop
3. Load the `data/*.csv` files into Power BI if not preloaded
4. Interact with the dashboard to explore player insights and form a Final 11


---

## 📈 Future Improvements

- 🧠 Predictive modeling with machine learning
- 🏥 Fitness and injury tracking integration
- 📊 Opponent-specific performance analysis
- 📺 Live match data integration
- 🌍 Geospatial venue-based insights

---

## 🙋‍♂️ Author

**Rhythm Garg**  
📧 rhythmcgarg@gmail.com  
🌐 [Portfolio](https://rhythm-portfolio-woad.vercel.app/)

---

## 📝 License

This project is released under the MIT License. Feel free to use or adapt for personal and non-commercial analytical purposes.


