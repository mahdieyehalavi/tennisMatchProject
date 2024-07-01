# Tennis Data Analysis Project

## Introduction
This project is a comprehensive analysis of tennis player data, focusing on various aspects such as player profiles, match durations, tournament dynamics, and performance insights. The analysis is based on the data provided in the attached files.

## Data
1. `match_home_team_df`: Contains information about the home team players, including their names, profiles, and performance statistics.
2. `match_away_team_df`: Contains information about the away team players, including their names, profiles, and performance statistics.
3. `event_df`: Provides details about the matches, such as the winner, seeding, and other event-related information.
4. `match_time_df`: Includes the duration of each period in the matches.
5. `game_df`: Holds the scoring information for each point in the matches.
6. `period_df`: Provides statistics about the matches, such as aces, winners, and other performance metrics.
7. `power_df`: Includes data related to the power dynamics during the matches.
8. `tournament_df`: Holds information about the tournament, such as the category, ground type, and other details.
9. `home_score_df`: Contains the home team's scores for each period of the matches.
10. `away_score_df`: Contains the away team's scores for each period of the matches.
There are other data frames extracted from the provided data. But, we did not use them as that's not necessary.
## Analysis
The analysis of the tennis player data covers the following aspects:

1. **Player Profiles**: Explore the player profiles, including their heights, weights, playing styles, and their rank.
2. **Match Durations**: Analyze the duration of the matches, identifying the longest and average match.
3. **Tournament Dynamics**: Investigate the relationship between the seeding of the players and the ground type of the tournament.
4. **Scoreboard Insights**: Uncover insights from the scoreboard data, such as the performance of the home and away teams.
5. **Power Dynamics**: Analyze the relationship between the power values and the occurrence of breaks during the matches.
6. **Odds and Betting Markets**: Explore the changes in the odds for various betting markets over time.

## Results
The analysis of the tennis player data has revealed several interesting insights, including:
1. The matches contain 2352 total number of players.
2. The tournament featured a diverse mix of players, with an average height of 1.82 meters and a range of playing styles.
3. The longest match in the tournament lasted over 172 minutes, while the mean duration of the match lasted just 100 minutes.
4. The player with the most winnings in matches was Uchijima M. with 15 winnings.
5. Most games typically had 3 in a tennis match.
6. The average number of winners per match is higher in Red clay compared with hard court surfaces
7. The player who wins the most tournaments was Paquet C.
8. According to the scatter plot and height_rank_correlation value, it cannot be claimed that there is a correlation between players height and their rank.
9. The average number of games per set in men's matches is 9.18, while the average number of games per set in women's matches is 8.92.
10. The right-handed players are 8217 persons, more than the left-handed players, 1210 persons. The ambidextrous players are 11 persons.
11. By plotting a bar plot for Tournament Surface Types' we can get the most common surface which is 'Red clay'.

   

## Conclusion
This data analysis project has provided valuable insights into professional tennis matches. The findings can be used by players, coaches, and fans to understand better the factors that contribute to success on the ATP Tour.

## Usage
To run the analysis, you will need to have the following dependencies installed:

- Python 3.0
- Pandas
- Numpy
- Matplotlib
- Scipy
- Seaborn


You can clone the repository and run the analysis scripts to reproduce the results.

## Contributing
If you have any suggestions or feedback, please feel free to open an issue or submit a pull request.
