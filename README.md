# T20 Cricket Analysis

This repository contains a Power BI report to identify top 11 players for a T20 cricket team by scraping data from espncricinfo with a
Brightdata website tool, cleaning and transforming the data with pandas, and evaluating various player performance
metrics.

## Dataset

after coillection data in json format This dataset contains four files about match_summary, batting_summary, bowling_summary and players_info.

## Data Processing 

using pandas and python in jupytor notebook we convert this data into pandas dataframe and look for nulkl values , special characters and renaming some column to meaningfull name.
also adding new calculated columns then finally process the data into csv out for further process in powerbi

#Powerbi Dashboard


This Power BI dashboard showcases an in-depth analysis of T20 cricket players based on their real performance data.Using various filters and visual tools, 
we evaluated players on key batting metrics like strike rate, batting average, boundary percentage, and balls faced.We applied role-based filters to divide 
players into categories such as Openers, Middle Overs, Lower Order Finishers, All-Rounders, and Specialist Fast Bowlers. Based on these filters 
and visual comparisons, we selected the best-performing players for the Final Team.

# Openers – Selection Based on:
Batting Average - Average Runs Scored in an innings - More than 30 atleast

Batting Position - order in which batters played - atleast more than 4

Boundary % - % of Runs Scored in boundaries - atleast more thand 50

Strike Rate - No of Runs Scored Per 100 balls - atleast more than 140

Total Innings Batted - Total inning batted - more than 3

👉 We identified openers who consistently provide explosive starts and anchor the innings. Players like Jos Buttler and Alex Hales stood out with high averages and boundary percentages.

# Middle Over Anchors – Selection Based On:
Average Balls Faced

Batting Average

Batting Position

Strike Rate

Total Innings Batted

👉 Middle-over players were selected based on their ability to rotate strike and stabilize innings. We chose players who absorb pressure and guide the game smoothly.

# Finishers / Lower Order – Selection Based On:
Batting Average

Strike Rate

Total Innings Batted

Average Balls Faced

Batting Position

👉 Finishers were evaluated for their explosiveness and efficiency in the last few overs. We focused on high strike rates and ability to make quick runs in limited balls.

# All-Rounders – Selection Based On:
Batting Average

Strike Rate

Economy Rate

Total Innings Bowled

Total Innings Batted

Batting Position

Bowling Strike Rate

👉 All-rounders needed to show balanced contributions with both bat and ball. We selected players who could maintain tight bowling while scoring quick runs.

# Specialist Fast Bowlers – Selection Based On:
Economy Rate

Total Innings Bowled

Bowling Style

Bowling Strike Rate

👉 Specialist fast bowlers were picked for their control, economy, and wicket-taking ability. We looked at fast bowlers who could handle both powerplay and death overs.


# Final Team
The final team was selected after analyzing each player’s performance based on their role-specific KPIs. 
This team combines solid openers, stable middle-order players, aggressive finishers, dependable all-rounders, and economical wicket-taking bowlers.


 
