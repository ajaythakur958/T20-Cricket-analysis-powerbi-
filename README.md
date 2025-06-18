# T20 Cricket Analysis – Power BI Dashboard

This repository contains a Power BI report to identify the top 11 T20 cricket players by analyzing real match data. The data was processed using Python (Pandas) and visualized in Power BI using key performance metrics and role-based filters.

---

## Dataset

The dataset was structured into the following files:

- `match_summary`
- `batting_summary`
- `bowling_summary`
- `players_info`

---

## Data Processing

Using Python and Pandas in Jupyter Notebook:
- Converted raw JSON data to Pandas DataFrames
- Handled null values and special characters
- Renamed columns to meaningful names
- Exported cleaned data to CSV for use in Power BI

---

## Power BI Dashboard

The Power BI dashboard provides interactive visuals and filters to evaluate player performance. It identifies top players for specific roles based on key metrics such as batting average, strike rate, economy rate, and more.

---

## Player Role Analysis

### Openers – Selection Based On:
- Batting Average - Average runs scored in an innings  
- Batting Position - Order in which batter played  
- Boundary % - Percentage of runs scored in boundaries  
- Strike Rate - Number of runs scored per 100 balls  
- Total Innings Batted - Total number of innings batted  

![Screenshot 2025-06-16 000306](https://github.com/user-attachments/assets/f2c02091-db87-4c58-8193-74a4e680267d)

We identified openers who consistently provide explosive starts and anchor the innings.

---

### Middle Over Anchors – Selection Based On:
- Average Balls Faced - Average balls faced by batter in an inning  
- Batting Average - Average runs scored in an innings  
- Batting Position - Order in which batter played  
- Strike Rate - Number of runs scored per 100 balls  
- Total Innings Batted - Total number of innings batted  

![Screenshot 2025-06-16 000315](https://github.com/user-attachments/assets/e0365dbd-5243-4728-aa83-33063d7d2eb0)

These players were selected for their ability to rotate strike and absorb pressure during middle overs.

---

### Finishers / Lower Order – Selection Based On:
- Batting Average - Average runs scored in an innings  
- Strike Rate - Number of runs scored per 100 balls  
- Average Balls Faced - Average balls faced per inning  
- Total Innings Batted - Total number of innings batted  
- Batting Position - Order in which batter played  

![Screenshot 2025-06-16 000322](https://github.com/user-attachments/assets/5f89d9e2-2cdd-4b99-bc52-b0028c416e1c)

Finishers were picked for their ability to make quick, impactful runs in the final overs.

---

### All-Rounders – Selection Based On:
- Batting Average - Average runs scored in an innings  
- Strike Rate - Number of runs scored per 100 balls  
- Economy Rate - Runs conceded per over while bowling  
- Bowling Strike Rate - Balls bowled per wicket taken  
- Total Innings Batted - Total number of innings batted  
- Total Innings Bowled - Total number of innings bowled  
- Batting Position - Order in which batter played  

![Screenshot 2025-06-16 000328](https://github.com/user-attachments/assets/0997c0a8-bf6d-42e2-9fc1-6067cbd807f5)

All-rounders were selected for balanced contributions with both bat and ball.

---

### Specialist Fast Bowlers – Selection Based On:
- Economy Rate - Runs conceded per over  
- Total Innings Bowled - Total number of innings bowled  
- Bowling Style - Type of bowling (e.g., fast, medium-fast)  
- Bowling Strike Rate - Balls bowled per wicket taken  

![Screenshot 2025-06-16 000334](https://github.com/user-attachments/assets/e8895c03-9acf-411a-9868-8129835bf749)

Specialist fast bowlers were picked based on their control, economy, and wicket-taking ability.

---

## Final Team

The final team was selected after evaluating all players across their respective roles using defined KPIs. It includes:

- Strong Openers  
- Reliable Middle Order Anchors  
- Explosive Finishers  
- Versatile All-Rounders  
- Disciplined Fast Bowlers
 
- ![Screenshot 2025-06-16 000340](https://github.com/user-attachments/assets/c2258e93-628f-49b7-9700-53083e3feeed)


---

## Repository Contents

- `t20_cricket.pbix` – Final Power BI report  
- `data_processing.ipynb` – Data cleaning and transformation script 
- `data/*.csv` – Cleaned CSV files used in the dashboard

---

## Tools Used

- Python (Pandas) – For data transformation and feature engineering  
- Power BI – For dashboard creation and performance analysis


# Final Team
The final team was selected after analyzing each player’s performance based on their role-specific KPIs. 
This team combines solid openers, stable middle-order players, aggressive finishers, dependable all-rounders, and economical wicket-taking bowlers.


 
