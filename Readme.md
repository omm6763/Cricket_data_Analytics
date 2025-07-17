### **# Cricket Analytics Project**



#### ***## Project Overview***



This project provides an end-to-end data analytics pipeline focused on the T20 World Cup. It involves web scraping from ESPN Cricinfo using Bright Data, preprocessing and analysis using Python (Pandas), and dashboard creation using Power BI.



The goal is to derive actionable insights from cricket match data, including batting, bowling, match summaries, and player performance.



---



#### ***## Folder Structure***



Cricket\_Analytics\_Project/

├── cricket-project\_data\_preprocessing.ipynb # Data cleaning and analysis using Python

├── world\_Cricket Best\_t20\_11.pbix # Power BI dashboard

├── world\_cricket\_best\_t20\_11.pdf # Exported dashboard in PDF format

├── cricket\_project\_csv\_files/ # Processed CSV datasets

├── cricket\_project\_json\_files/ # Raw scraped JSON files

├── web\_scrapping\_codes/ # Bright Data scraping scripts (JavaScript)

│ ├── t20\_wc\_batting\_summary.js

│ ├── t20\_wc\_bowling\_summary.js

│ ├── t20\_wc\_match\_results.js

│ └── t20\_wc\_player\_info.js

├── README.md # Project documentation





---



#### ***## Key Performance Indicators (KPIs) and Selection Criteria***  



The project aims to select the \*\*Best T20 World Cup 2022 Playing XI\*\* based on a data-driven analysis of player performances.  



##### **## KPIs Used for Selection**  

##### 

###### \- **Batting Metrics**

&nbsp; - Strike Rate (SR)

&nbsp; - Boundary Percentage (% of balls faced resulting in boundaries)

&nbsp; - Batting Average

&nbsp; - Balls Faced

&nbsp; - Total Matches Played  

###### 

###### **- Bowling Metrics**

&nbsp; - Bowling Average

&nbsp; - Economy Rate

&nbsp; - Wickets Taken  



###### \- **Selection Strategy**

&nbsp; - Top-Order Batters selected based on high strike rate, boundary percentage, and consistency.

&nbsp; - Middle-Order Batters and Finishers chosen for their finishing ability, strike rate under pressure, and impact performances.

&nbsp; - Specialist Bowlers picked for their bowling average, economy, and match impact.

&nbsp; - The final XI is balanced to score \*\*180+ runs consistently\*\* and defend \*\*150+ totals\*\*, based on individual and team metrics.  



###### \- **Visual Representation**

&nbsp; - The dashboard showcases selected players, their roles, and key performance metrics.

&nbsp; - Player images and profile-based visuals enhance the understanding of selection logic.

---



#### ***## Technologies Used***



###### **Languages \& Libraries**  

\- Python (Pandas, NumPy, Matplotlib)



###### **Tools**  

\- Bright Data Web Scraper (JavaScript)  

\- Power BI Desktop  

\- Git \& GitHub  



---



## Power BI Dashboard

- **PDF Version of Dashboard:** [View PDF Report](./world_cricket_best_t20_11.pdf)

- **Power BI Report File:** [Download PBIX File](./world_Cricket%20Best_t20_11.pbix)  
  *(Open this file in Power BI Desktop for interactive analysis)*




---





#### ***## Data Source***



All data was scraped from \[ESPN Cricinfo](https://www.espncricinfo.com/) using Bright Data’s Web Scraper. JSON files were transformed into structured CSVs and used for further analysis.



---



#### ***## Author***



Aditya Singh  

GitHub: \[https://github.com/Aditya23303](https://github.com/Aditya23303)



---



#### ***## License***



This project is intended solely for educational and non-commercial purposes.  

All data belongs to its original source: ESPN Cricinfo.









