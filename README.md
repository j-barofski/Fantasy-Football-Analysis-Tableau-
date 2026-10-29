# Fantasy-Football-Analysis-Tableau-
I analyzed the first six weeks of my fantasy football league using Tableau to find out in more detail just how well each team is doing. Thanks to Claude, I was able to use a Python script to pull the data I wanted from Sleeper's API. Sleeper is the app that my fantasy football league is using. 

# Standings
<img width="1133" height="116" alt="image" src="https://github.com/user-attachments/assets/629f6ecf-2203-45fc-a875-d00158197db7" />

<img width="565" height="540" alt="image" src="https://github.com/user-attachments/assets/053bbf01-df41-4f5f-9b4d-682b9fdf5cd4" />

# Points Overview
<img width="760" height="108" alt="image" src="https://github.com/user-attachments/assets/5ebb3637-94dc-4e53-90d4-d49b440306e5" />

<img width="565" height="540" alt="image" src="https://github.com/user-attachments/assets/665a90bf-bfe3-439b-976d-7c63f287549c" />

# Best Performers
<img width="748" height="174" alt="image" src="https://github.com/user-attachments/assets/76687537-a60c-4516-9777-bb38d9ef375d" />

<img width="565" height="540" alt="image" src="https://github.com/user-attachments/assets/d3cc7fb9-22c3-40d2-aea0-8560a1e219ad" />

# Player Performances
<img width="520" height="125" alt="image" src="https://github.com/user-attachments/assets/46af22e0-1847-4ba4-90ee-96a9c7287412" />

<img width="565" height="540" alt="image" src="https://github.com/user-attachments/assets/c196e831-139c-49ca-b6d9-e292723d8f5e" />

# Positional Strength
<img width="543" height="132" alt="image" src="https://github.com/user-attachments/assets/c566ca20-c3ca-4e50-a92d-1498dce1d3ac" />

<img width="565" height="540" alt="image" src="https://github.com/user-attachments/assets/41dd26c0-ec06-422d-b8f1-553d6f000d8b" />

# My change-log
- Asked Claude to write a Python script using the Sleeper app’s API 
- Using the first 5 weeks of the season
- Script able to make an Excel spreadsheet of the data
- Updated team names and usernames for privacy purposes
- Redid the Python script to use week 6 data and add projected points
- Changed blanks in projected points column to 0s
- Again, updated names
- Created points overview graph that visualizes the weekly points scored for each team and if they won or not. 
- Weekly points comparison graph that compares:
  - Points for the team
  - Points against the team
  - League average points scored for each week
- All-play records graph
  - Record if they played every team each week
- Positional Strength
  - What position performs the best for each team
- Team Rankings
  - Ranks the teams by record and total points scored
- Player Performance
  - Tracks the performance of each player from each week
- Player Rankings
  - Added a new data source to find the all-play records. Otherwise, it messes with the other data because I joined a matchup to matchup
- Created dashboards and a story
- Calculated fields added
  - Points - Projected points
  - Points for - Points against
  - Points/Projected points
    - Shows both the points scored and what the projected points were
  - Win (1 if true, 0 if false)
  - Loss (1 if true, 0 if false)
  - Tie (1 if true, 0 if false)
  - Record (Adds number of wins, losses and ties)
  - Running Record (calculates by week)
  - League Avg
  - All-Play Win
  - All-Play Loss
  - All-Play Tie
  - All-Play Record
  - Running All-play Wins (calculates by week)
  - Running All-Play Losses
  - Running All-Play Ties
  - Running All-Play Record
  - Standings Score (Creates a calculation score to help determine the rankings)
  - Standings Rank (Ranks the scores)
  - Player Rank (rank by total points)
  - Player Avg (Player’s average points)
  - Position Avg (The position’s average points)
