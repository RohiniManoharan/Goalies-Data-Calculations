Computed these aggregates at the tmID and year level and print the output.
1.	tmID: string
2.	year: Year
3.	Wins_agg: total wins / total players
4.	Losses_agg: total losses / total players
5.	GP_agg: total games played / total players
6.	Mins_over_GA_agg: total minutes played / total goals against
7.	GA_over_SA_agg: total goals against / total shots against
8.	avg_percentage_wins: calculate the percentage of games won for each player, then take the mean at team level
9.	most_goals_stopped: {‘playerID’: playerID, ‘goals_stopped’: goals_stopped}
10.	most_efficient_player: {‘playerID’: playerID, ‘efficiency’: goals_stopped / minutes played}
 

Step 1: Goalies.csv has some bad data,so skipped the bad lines using "on_bad_lines = 'skip'"
Step 2:Dropped the irrelevant data using drop function.
Step 3:Grouped the data on tmID and year level using groupby function.
Step 4:Then calculated required aggregates using agg(sum),agg(mean),agg(count)
Step 5:Converted datatypes of the fields in the input table for further calculations
Step 6:Used try and except for handling zero division error
Step 7:Created nested dictionary to have the complete details of players with their total goals stopped and found the player who stopped more goals.
Step 8:Created nested dictionary to find the efficiency of players and calculated the most efficient player.
Step 9:Imported the "warning"  package to ignore runtime warnings.
