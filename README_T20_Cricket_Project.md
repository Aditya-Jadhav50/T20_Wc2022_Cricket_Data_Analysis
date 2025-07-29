
# 🏏 Earth XI vs Aliens: T20 World Cup 2022 Analytics Dashboard

An engaging end-to-end **data analytics project** using real T20 World Cup 2022 data to assemble the **Best XI players from Earth**—our planet's finest cricket team to take on an alien challenge! 🛸

This project leverages pre-scraped data provided by Codebasics, with **data preprocessing in Python** and **Power BI dashboarding** to extract actionable insights.

---

## 🚀 Project Overview

- 📁 Used **JSON files** provided by [Codebasics.io](https://codebasics.io) as raw data.
- 🔄 Transformed JSON to structured **CSV format** using a **Python Jupyter Notebook** (`t20_data_preprocessing.ipynb`).
- 📊 Created a rich, multi-tabbed **Power BI dashboard** (`Visualisation.pbix`) to:
  - Filter and rank players based on KPIs
  - Analyze performance by role (e.g., openers, finishers, all-rounders, bowlers)
  - Select the ultimate **Earth XI team**

---

## 📁 Project Structure

```
📂 T20-Earth-vs-Aliens/
├── t20_data_preprocessing.ipynb       # Data cleaning and transformation in Python
├── dim_players_no_images.csv          # Cleaned player data without images
├── DAX Measures and Calculated columns.xlsx  # All DAX logic used in Power BI
├── Visualisation.pbix                 # Final Power BI dashboard
└── README.md                          # Project documentation
```

---

## 🧰 Tools & Technologies

| Tool             | Purpose                                   |
|------------------|--------------------------------------------|
| Python (Pandas)  | Data cleaning and CSV generation           |
| Power BI         | Dashboard development & DAX analysis       |
| Excel            | DAX measure documentation & planning       |
| JSON / CSV       | Data format                                |

---

## 🔎 Key Features

- Role-specific insights (Power Hitters, Anchors, Finishers, Bowlers)
- Filtering with parameters like:
  - Batting Average, Strike Rate, Boundary %, Balls Faced
  - Bowling Economy, Strike Rate, Average, Dot Ball %
- Advanced KPIs via **DAX Measures** and **Calculated Columns**
- **Interactive visualizations** for player comparisons
- Scenario-based final XI selection (Earth vs Aliens)

---

## 🧠 Final 11 Players (Team Earth)

| Player              | Role            | Country     |
|---------------------|-----------------|-------------|
| Jos Buttler (WK)    | Opener          | England     |
| Rilee Rossouw       | Opener          | South Africa|
| Virat Kohli         | Anchor          | India       |
| Suryakumar Yadav    | Anchor          | India       |
| Glenn Phillips      | Anchor          | New Zealand |
| Marcus Stoinis      | Finisher/All-Rounder | Australia |
| Sikandar Raza       | All-Rounder     | Zimbabwe    |
| Shadab Khan         | All-Rounder     | Pakistan    |
| Shaheen Afridi      | Fast Bowler     | Pakistan    |
| Sam Curran          | Fast Bowler     | England     |
| Anrich Nortje       | Fast Bowler     | South Africa|

---

## 📊 Dashboard Preview

> 📁 Open `Visualisation.pbix` in Power BI Desktop to explore:
- Multi-tabbed layout for different player roles
- KPIs for performance filtering
- Final XI page with summary stats
- Chart types: Cards, Tables, Bar Charts, Scatter Plots, KPI Tiles

---

## 🧠 DAX Measures & Calculated Columns

All DAX expressions used in the Power BI file are documented in:
📄 `DAX Measures and Calculated columns.xlsx`

This includes:
- Total Runs, Strike Rate, Batting Average
- Boundary %, Bowling Economy, Bowling Strike Rate
- Custom calculated columns like Boundary Runs, Match Impact, etc.

---

## ✅ How to Run

1. Launch Power BI Desktop
2. Open `Visualisation.pbix`
3. Interact with filters and visuals
4. Explore role-based players and finalize your Earth XI team!

---

## 📮 Let’s Connect!

Have questions or feedback?  
Feel free to reach out via [LinkedIn](https://linkedin.com/in/adityajadhav) or connect on GitHub!

---

## 🏷️ Tags

`#DataAnalytics` `#PowerBI` `#T20WorldCup2022` `#CricketAnalytics` `#ResumeProject` `#PythonPandas` `#DAX`
