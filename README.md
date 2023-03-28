# Premier_League_2018-2019_Player_Analyses: A mathematical data analysis of this season's players

## Getting started
To run this notebook, you will need to have Python installed, as well as the following libraries:

- numpy
- pandas
- matplotlib

You can install them using pip:

```
pip install numpy pandas matplotlib
```

## Loading the data
The data used in this notebook is available in the file england-premier-league-players-2018-to-2019-stats.csv. We will load it using pandas:

```python
import pandas as pd

players = pd.read_csv('england-premier-league-players-2018-to-2019-stats.csv')
```

## Analyses
The notebook contains the following analyses:
- Age of the players
- Relationship between the columns
- Names of the big six players

### Age of the players
We analyzed the age of the players and created some visualizations to better understand the data. We calculated the maximum, minimum, average, and median age of the players, and created a density graph and a pie graph categorizing the age of the players through the creation of a new column.

### Relationship between the columns
We related some variables from the database, creating a figure that graphically shows the correlation between the variables. Furthermore, with the creation of graphs with points, we realized that there is no direct linear relationship between the minutes played by the player and his total goals, as there are many defenders who play many games and do not score goals; and also, an inverse linear relationship between the number of goals and the player's position in the ranking of the best strikers was noticed, since the more goals he scores, the closer he is to the top positions.

### Names of the big six players
Finally, we looked at the names of the big six players from the season. We displayed the names of the Arsenal, Chelsea, Liverpool, Manchester City, Manchester United, and Tottenham Hotspur players.
