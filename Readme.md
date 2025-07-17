## **Cricket Analytics Project**

---

#### **Project Overview**

This project provides an end-to-end data analytics pipeline focused on the T20 World Cup. It involves web scraping from ESPN Cricinfo using Bright Data, preprocessing and analysis using Python (Pandas), and dashboard creation using Power BI.

The goal is to derive actionable insights from cricket match data, including batting, bowling, match summaries, and player performance.

---

#### **Folder Structure**

**Cricket_Analytics_Project/**

├── cricket-project_data_preprocessing.ipynb   — Data cleaning and analysis using Python  
├── world_Cricket Best_t20_11.pbix             — Power BI dashboard  
├── world_cricket_best_t20_11.pdf              — Exported dashboard in PDF format  
├── cricket_project_csv_files/                 — Processed CSV datasets  
├── cricket_project_json_files/                — Raw scraped JSON files  
├── web_scrapping_codes/                       — Bright Data scraping scripts (JavaScript)  
│   ├── t20_wc_batting_summary.js  
│   ├── t20_wc_bowling_summary.js  
│   ├── t20_wc_match_results.js  
│   └── t20_wc_player_info.js  
├── README.md                                  — Project documentation  

---

#### **Key Performance Indicators (KPIs) and Selection Criteria**

The project aims to select the Best T20 World Cup 2022 Playing XI based on a data-driven analysis of player performances.

**Batting Metrics:**
- Strike Rate (SR)
- Boundary Percentage (% of balls faced resulting in boundaries)
- Batting Average
- Balls Faced
- Total Matches Played

**Bowling Metrics:**
- Bowling Average
- Economy Rate
- Wickets Taken

**Selection Strategy:**
- Top-Order Batters selected based on high strike rate, boundary percentage, and consistency.
- Middle-Order Batters and Finishers chosen for their finishing ability, strike rate under pressure, and impact performances.
- Specialist Bowlers picked for their bowling average, economy, and match impact.
- The final XI is balanced to score 180+ runs consistently and defend 150+ totals, based on individual and team metrics.

**Visual Representation:**
- The dashboard showcases selected players, their roles, and key performance metrics.
- Player images and profile-based visuals enhance the understanding of selection logic.

---

#### **Technologies Used**

**Languages & Libraries:**
- Python (Pandas, NumPy, Matplotlib)

**Tools:**
- Bright Data Web Scraper (JavaScript)
- Power BI Desktop
- Git & GitHub

---

#### **Power BI Dashboard**

- **PDF Version of Dashboard:** [View PDF Report](./world_cricket_best_t20_11.pdf)  
- **Power BI Report File:** [Download PBIX File](./world_Cricket%20Best_t20_11.pbix)  
  *(Open this file in Power BI Desktop for interactive analysis)*  

---

#### **Data Source**

All data was scraped from [ESPN Cricinfo](https://www.espncricinfo.com/) using Bright Data’s Web Scraper.  
JSON files were transformed into structured CSVs and used for further analysis.

---

#### **Author**

**Aditya Singh**  
**GitHub:** [View Profile](https://github.com/Aditya23303)


---








