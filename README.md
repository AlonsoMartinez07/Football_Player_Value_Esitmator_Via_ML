# Football_Player_Value_Esitmator_Via_ML
This Machine Learning tool helps estimate football/soccer player values. It is trained on over 17,000 players and uses SciKit Learn with 95% accuracy. 

# Instructions
1. Make sure to have SciKit Learn installed (pip install scikit-learn)
2. Paste/download the code in main_code
3. Download the fifa_players.csv linked in this repo
4. Make sure to change code to include your path to fifa_players.csv
5. Go to https://fifaindex.com and search your player or search up [your player] fifa stats to get your players statistics
6. Then plug those in to player_stats near the bottom of the code in order
   
The order in which you plug in your players stats will be the following:

'age', 'height_cm', 'overall_rating', 'potential', 'skill_moves(1-5)',
       'national_rating', 'crossing', 'finishing', 'heading_accuracy',
       'short_passing', 'volleys', 'dribbling', 'curve', 'freekick_accuracy',
       'long_passing', 'ball_control', 'acceleration', 'sprint_speed',
       'agility', 'reactions', 'balance', 'shot_power', 'jumping', 'stamina',
       'strength', 'long_shots', 'aggression', 'interceptions', 'positioning',
       'vision', 'penalties', 'composure', 'marking', 'standing_tackle',
       'sliding_tackle'
If you feel any of these are useless and dont accuratly represent a players value go to player_list = player_list.drop(columns=['name'... and add the stat that you would like to remove
