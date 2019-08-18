# best-nfl-matchups
This project parses a complete CSV of games to identify the best matchups of the
2019-2020 NFL season.


## How to customize

Customize this repo by changing the team names and "scores" in `goodteams.csv`. 
A team with a higher score is considered to have more interesting games; use any
 positive number for a team's score. From this file, each matchup is a given a 
 score, and the matchups are sorted into tiers by how interesting you decided 
 each should be.

After customizing `goodteams.csv`, run the project as follows

```
python3 process.py
```

You can then find your custom schedule written to `result.md`.

## Thanks

The CSV file `nfl_2020_game.csv` was copied from Pro Football Reference 
[at this URL](https://www.pro-football-reference.com/years/2019/games.htm), many
 thanks to Pro Football Reference!

Cloned repo from @dnoursi's [best-nba-matchups]([https://www.pro-football-reference.com/years/2019/games.htm])
