# 🏏 IPL CRUNCH '26 — Data Analytics Hackathon Project

## 📌 Overview

This project was built for the **IPL CRUNCH ’26 Data Analytics Hackathon** organized by Wooble.

The objective was to analyze **5 seasons of IPL ball-by-ball data** and uncover insights about:
- Toss impact on match outcomes
- Match phase intelligence
- Batter and bowler dominance
- Winning patterns across venues and seasons
- Hidden insights that influence IPL victories

The project combines:
- Python-based data cleaning & preprocessing
- Exploratory Data Analysis (EDA)
- Power BI dashboard storytelling
- Cricket analytics & strategic insights

---

# 🚀 Problem Statement

The competition required participants to answer the following key questions:

### 1️⃣ Do teams that win the toss actually win more matches?

### 2️⃣ Which phase impacts victory the most?
- Powerplay
- Middle Overs
- Death Overs

### 3️⃣ Who are the top batters and bowlers across 5 seasons?

### 4️⃣ Find one genuinely surprising insight from the data.

---

# 🧠 Key Business Insights

## ✅ Toss Winning Does NOT Guarantee Match Victory
- Toss-winning teams won only **49.12%** of matches.
- Chasing teams had a slight edge with **50.88% success rate**.
- Toss impact was far lower than expected.

---

## ✅ Death Overs Have Maximum Match Impact
Death overs generated:
- Highest scoring acceleration
- Highest run rate
- Strongest impact on final outcomes

Death over execution proved more important than toss advantage.

---

## ✅ Middle Overs Control the Game
Teams dominating middle overs consistently outperformed opponents.

Middle overs showed:
- Highest total runs contribution
- Highest wicket involvement
- Strong momentum swing impact

---

## ✅ Bowling Pressure > Wicket Taking
Dot-ball pressure had stronger correlation with winning than wickets alone.

Economical bowling and disciplined death-over execution created match-winning advantages.

---

# 📊 Dashboard Sections

The Power BI dashboard contains 6 analytical pages:

| Page | Focus Area |
|------|-------------|
| 1 | Tournament Overview |
| 2 | Toss Impact Analysis |
| 3 | Match Phase Intelligence |
| 4 | Batter Intelligence Hub |
| 5 | Bowler Intelligence Hub |
| 6 | Hidden Insights & Final Conclusion |

---

# 📈 Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| Python | Data Cleaning & Feature Engineering |
| Pandas | Data Manipulation |
| NumPy | Numerical Processing |
| Power BI | Dashboard Development |
| DAX | KPI & Measure Creation |
| Excel/CSV | Raw Dataset Handling |

---

# 🧹 Data Cleaning & Processing Workflow

## Raw Data Source
- IPL Ball-by-Ball Dataset
- 5 IPL Seasons
- Match-level + delivery-level data

---

## Cleaning Steps Performed

### ✔ Removed Missing Values
Handled null values and inconsistent entries.

### ✔ Standardized Team Names
Unified franchise naming across seasons.

### ✔ Created Match Phases
Overs categorized into:
- Powerplay (1–6)
- Middle Overs (7–15)
- Death Overs (16–20)

### ✔ Feature Engineering
Created:
- Dot Ball %
- Boundary %
- Economy Rate
- Strike Rate
- Chase Success %
- Toss Win %
- Phase Run Rate
- Match Result Indicators

### ✔ KPI Creation
Custom DAX measures for:
- Total Runs
- Total Wickets
- Win Percentages
- Run Rate Analysis
- Batter/Bowler Rankings

---

# 📊 Power BI Dashboard Highlights

## 🔹 Interactive Navigation
- Multi-page storytelling dashboard
- Dynamic slicers
- Cross-filtering enabled

## 🔹 Advanced Analytics
- Toss Success Matrix
- Match Phase Momentum Flow
- Batter Efficiency Analysis
- Bowler Pressure Analysis
- Venue Intelligence

## 🔹 Executive Storytelling
Designed using consulting-style visual storytelling inspired by:
- McKinsey
- BCG
- Bain

---

# 🎯 Surprising Finding

> “Winning the toss has far less impact on IPL victories than death-over execution and bowling pressure.”

This insight challenged one of cricket’s most common assumptions.

---
