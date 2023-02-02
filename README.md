# Run-World-Cup-Simulations
## **A script to simulate a football world cup tournament results**

This code simulates a sports tournament by reading in teams and their ratings from a csv file. The tournament is simulated N (default value is 1000) number of times and the chances of winning for each team are calculated based on the number of wins in the simulations.

The main() function ensures the correct usage of the code, reads the teams from the csv file, converts the teams into a dictionary inside a list, casts the "rating" value to an integer, and runs the simulation N number of times. The result of each simulation is stored in the counts dictionary. Finally, the code prints the chances of winning for each team, sorted by the highest chances of winning.

## **The code has three additional functions:**

**simulate_game()**: takes in two teams and returns True if the first team wins and False otherwise, using the ELO rating system to determine the probability of a team winning.

**simulate_round()**: takes in the remaining teams in the tournament, simulates games between pairs of teams and returns a list of the winning teams.

**simulate_tournament()**: takes in the remaining teams in the tournament and continues to simulate rounds until only one team remains. It returns the name of the winning team.
