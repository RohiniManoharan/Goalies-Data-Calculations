# Movella
Step 1: Goalies.csv has some bad data,so skipped the bad lines using "on_bad_lines = 'skip'"
Step 2:Dropped the irrelevant data using drop function.
Step 3:Grouped the data on tmID and year level using groupby function.
Step 4:Then calculated required aggregates using agg(sum),agg(mean),agg(count)
Step 5:Converted datatypes of the fields in the input table for further calculations
Step 6:Used try and except for handling zero division error
Step 7:Created nested dictionary to have the complete details of players with their total goals stopped and found the player who stopped more goals.
Step 8:Created nested dictionary to find the efficiency of players and calculated the most efficient player.
Step 9:Imported the "warning"  package to ignore runtime warnings.
