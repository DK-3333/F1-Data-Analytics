# 🏎️ F1-Data-Analytics
A **data analytics** project delivering high-level insights into **Formula 1 World Championship** trends, constructor success metrics, and driver impact through interactive Tableau visualizations and structured data modeling.

## 📚 Table of Contents

- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [Dataset Description](#-dataset-description)
- [Sample Visuals](#-sample-visuals)
- [Technologies Used](#-technologies-used)
- [Key Takeaways](#-key-takeaways)
- [Reports](#-reports)
- [Contact Information](#-contact-information)

---

## 🔍 Overview
This project centers on performing a **descriptive analysis of the Formula 1 World Championship** to uncover how constructor teams have performed and evolved over time. Using over decades of race data (1950–2024), the analysis focuses on key performance metrics such as constructor points, rankings, driver contributions, and overall team success.

By transforming raw historical data into a clean, structured format and presenting it through interactive Tableau dashboards, the project helps audiences explore trends, comparisons, and patterns with clarity. It aims to provide data-backed insights for F1 fans, analysts, and enthusiasts looking to understand the sport beyond surface-level statistics.

The dashboard highlights:
- Seasonal trends in points and wins for each constructor.
- How individual drivers impact team success.
- Shifts in team rankings across different F1 eras.
- Navigate race outcomes season by season.

---

## ❗ Problem Statement
Despite being one of the most data-rich sports globally, Formula 1's historical data is often fragmented, complex, and difficult to interpret without technical expertise. This project addresses that gap by transforming raw F1 data into clear, interactive visuals—empowering users to uncover trends, evaluate performance, and explore strategic narratives across the sport’s rich history.

The primary objective is to surface meaningful insights across four core dimensions of F1:

  - Driver performance over time and across teams.
  - Constructor success and their dominance across seasons.
  - Circuit-level dynamics, such as race frequency and outcomes.
  - Qualifying metrics and starting grid advantages.

Through comprehensive dashboards, users can answer questions like:

  - How have dominant teams and drivers shifted over decades?
  - Which circuits are most historic or frequently raced?
  - What trends exist in pole positions and qualifying outcomes?
  - What nationalities have led F1 podium finishes?

This unified approach not only streamlines exploration but enhances strategic analysis and fan engagement through visual storytelling.

--- 

## 🧩 Dataset Description
The data for this project was sourced from the Formula 1 World Championship dataset published by Rohan Rao on **[Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020/data)**. This dataset compiles comprehensive historical Formula 1 data from 1950 to 2024, originally extracted and curated from the official Ergast Developer API, a well-known and regularly updated public database of F1 race results and statistics.

---

## 📊 Sample Visuals
**1. Driver Performance over Seasons (2000–2024)**
This dashboard tracks top drivers’ total points, podium finishes, and seasonal consistency over the modern F1 era. Interactive filters allow users to view driver trajectories, compare performance across eras, and understand key contributors to team success.

![dashboard-visual](https://github.com/user-attachments/assets/81b22e7c-51d5-4fbd-b8cb-f5897a6a1dbe)

**2. Constructor (Team) Success**
Focused on team-level performance, this dashboard visualizes total wins, points per season, ranking shifts, and driver contributions. A KPI panel highlights each constructor’s historical stats and identifies the top contributing driver dynamically.

![dashboard-visual](https://github.com/user-attachments/assets/7680d8d3-9d30-4492-a08d-d63976625701)

**3. Race and Circuit Overview**
This visual module highlights Grand Prix events across global circuits. Users can explore the most frequently hosted races, track circuits by location, and view race frequency trends. It reveals insights into circuit popularity and regional race distributions.

![dashboard-visual](https://github.com/user-attachments/assets/0a69d24f-3714-4522-9ad6-7048f5e33492)

**4. F1 Qualifying Insights**
This dashboard provides an analytical view of qualifying outcomes, spotlighting average starting grid positions, pole winners, and nationality trends. It allows fans and strategists to understand how qualifying positions influence race-day outcomes.

![dashboard-visual](https://github.com/user-attachments/assets/86aaab11-0198-4f97-abbe-997c621f1dd5)

---

## 🔍 Technologies Used

| **Technology**         | **Purpose**                                                                 |
|------------------------|------------------------------------------------------------------------------|
| **Python (Pandas, NumPy)** | Data preprocessing, cleaning, transformation, and structured data modeling       |
| **Tableau Desktop**    | Building interactive dashboards and performing visual data analysis         |
| **Tableau Prep Builder** | Visual data preparation and flow-based data integration (initial plan stage) |
| **CSV Files**          | Source data format used for importing race, driver, and constructor data     |
| **Data Joins in Tableau** | Establishing data relationships via primary keys (raceId, constructorId, etc.) |
| **Calculated Fields in Tableau** | Creating KPIs and custom metrics like driver contribution %, seasonal wins |


---

## 💡 Key Takeaways

- **Descriptive Analytics in Action**: This project showcases how descriptive analytics can extract meaningful patterns from large-scale motorsport data, offering performance insights across multiple dimensions—teams, drivers, circuits, and seasons.

- **Constructor-Level Insights**: Analysis of team success over time revealed how dominance shifts between constructors like Ferrari, Mercedes, and Red Bull—helping fans and analysts track performance evolution.

- **Driver Contribution Metrics**: The dashboard quantifies driver impact on team points, highlighting key contributors like Lewis Hamilton and Max Verstappen, and demonstrating how individual excellence drives collective success.

- **Interactive Visualization Power**: With Tableau’s filtering, sorting, and drill-down capabilities, end users can explore the data from different perspectives without needing to write code or SQL.

- **Scalable Data Integration**: By joining multiple datasets through structured keys (e.g., `raceId`, `constructorId`), the project creates a unified model ready for high-quality reporting and KPI generation.

- **Informed Decision-Making**: Whether for a team strategist, journalist, or F1 fan, the dashboards offer a decision support system that combines clarity with depth.



---

## 📚 Reports
[Project Report (PDF)]() – Complete documentation of project steps, discoveries, and methodology.

Includes detailed analysis of KPIs, visual interpretation, and preprocessing approach.

---

## ✨ Contact Information

📬 Contact Author: Dhyey Kasundra <br> 
📧 Email: dhyey.d.kasundra@gmail.com

💡 Data is not just stored, it tells a story. This project is where structure meets insight.

---
