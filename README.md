# cricket-betting-model

**Project Objective:**
The project would provide suggestions for cricket betting and generate revenues for the bettors by providing the winning recommendations for money line, spread, over/under, and player metrics using various prediction models.

**Betting Terms:**
1. Moneyline:
   - A straightforward bet on which team will win the match.
   - The odds are displayed next to each team, indicating the potential payout for a $100 bet.
   - A positive (+) number indicates the underdog, while a negative (-) number indicates the favourite.
2. Spread:
   - A bet on the margin of victory for the winning team.
   - The odds are displayed with a point spread, such as "+10.5" or "-10.5".
   - For a winning bet on "+10.5", the underdog must win or lose by less than 10.5 runs.
   - For a winning bet on "-10.5", the favourite must win by more than 10.5 runs.
3. Over/Under:
   - A bet on the total number of runs scored in the match.
   - The odds are displayed with a target run total, such as "Over 250" or "Under 250".
   - For a winning bet on "Over 250", the combined runs of both teams must exceed 250.
   - For a winning bet on "Under 250", the combined runs must fall below 250.
4. Player Performance:
   - A bet on the individual performance of a specific player.
   - This includes prediction on the run-scored, wickets taken, etc.
   - The odds for these bets vary depending on the player's form and the perceived difficulty of the achievement.

**Data**
- **Folder:** Main_Data_Source
- **Source File related to Models:**
  1. Moneyline and Spred: cricket_datasource_prednov10.xlsx, cricket_predict_datas.xlsx
  2. Over/Under: pldata.xlsx
  3. Player Statistics: .csv file with player names
  4. Visualisations: Weather.csv, Team.csv
- **Technologies Used:** Excel, Google Sheets, Python
- Python for Web Scraping Data and Data Transformation/Pre-processing, Excel/Google Sheets for Data Transformation/Pre-processing.

**Models**
- Folder: Prediction_Models
- **Source File related to Models:**
  1. Moneyline and Spred: team.ipynb
  2. Over/Under: player_ou.ipynb
  3. Player Statistics: Prediction_Models/Player_Performance
- Models Used:
  1. Moneyline/Spread/Over-Under: Random Forest, Gradient Boost, and XG Boost
  2. Player Statistics: Random Forest, Regressor

**Project Flowchart:**
![image](https://github.com/snehbrews/cricket-betting-model/assets/58567775/88ebad73-b4fc-4627-bfca-4694e3404305)






