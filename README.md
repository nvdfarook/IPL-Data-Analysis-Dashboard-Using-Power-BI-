# 🏏 IPL Analysis Dashboard (Power BI & DAX)

This project is an **interactive IPL (Indian Premier League) Analysis Dashboard** built using **Power BI** and **DAX**, covering multiple seasons of IPL data from **2008 to 2022**.

The dashboard provides **team-level, player-level, and match-level insights** with dynamic slicers and advanced DAX calculations.

---

## 📸 Dashboard Preview

> <img width="1193" height="698" alt="Screenshot (155)" src="https://github.com/user-attachments/assets/ca858139-b292-43c9-ad18-fa9a273453cf" />


---

## 📊 Dashboard Overview

The dashboard includes the following key sections:

### 🏆 Tournament Insights
- **Title Winner** (Season-wise)
- **Orange Cap Winner** (Most Runs)
- **Purple Cap Winner** (Most Wickets)
- **Total Tournament Sixes**
- **Total Tournament Fours**

---

### 🏏 Batting Analysis
- Select **Batsman** using slicer
- Metrics:
  - Total Runs
  - Total Sixes
  - Total Fours
  - Strike Rate

---

### 🎯 Bowling Analysis
- Select **Bowler** using slicer
- Metrics:
  - Total Wickets
  - Economy Rate
  - Bowling Average
  - Strike Rate

---

### 📍 Match & Venue Insights
- Matches won by **Runs vs Wickets** across venues
- Matches won based on **Toss Decision**
- Team-wise **Total Matches Won in a Season**

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- **Power Query**
- **IPL Ball-by-Ball & Match Datasets**
- **Calendar Table for Time Intelligence**

---

## 🧠 Key DAX Concepts Implemented

- Filter Context & Row Context
- `CALCULATE()`
- `ALLSELECTED()`
- `VALUES()`
- `SELECTEDVALUE()`
- Aggregations for:
  - Runs
  - Wickets
  - Strike Rate
  - Economy
  - Averages
- Dynamic calculations based on slicer selections

---

## 📁 Data Model

- **Fact Tables**
  - Ball-by-ball data
  - Match-level data
- **Dimension Tables**
  - Calendar table
  - Teams
  - Players
- Proper relationships established for accurate filtering

---

## 🎯 Features

- Fully **interactive slicers** (Season, Batsman, Bowler)
- Dynamic KPI cards
- Clean and visually rich dashboard layout
- Handles complex filter interactions correctly
- Optimized DAX for performance

---

## 🚀 How to Use

1. Download or clone this repository
2. Open the `.pbix` file using **Power BI Desktop**
3. Refresh data if required
4. Interact with slicers to explore insights

---



## 📌 Future Enhancements

- Player comparison visuals
- Team performance trends over years
- Playoff & finals analysis
- Advanced tooltips

---

## 👤 Author

**Naveed Farook**  
Power BI & Data Analytics Enthusiast  

---

## ⭐ If you like this project

Give this repository a ⭐ and feel free to fork or contribute!
