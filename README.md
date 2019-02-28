> > Data sourcing and preparation < <

Data has been sourced from https://cricsheet.org/downloads/india.zip. This consists of YAML files with ball by ball record for matches.
Files pertaining to IND-AUS matches have been used. Other files have been removed.

All selected files are parsed, and data from files unrelated to men's ODI or for matches earlier than 2009 are discarded during parsing.

Peculiarities in files are addressed during parsing. e.g.: some matches have no winner.

Composition of India and Australia teams for 2019 ODI series have been sourced from https://www.cricbuzz.com/cricket-series/2773/australia-tour-of-india-2019/squads.


> > Methodology < <

Summary statistics for players in 2019 teams are dervived from data files. Average score ( runs per match | wickets per match ) have been identified only for players who have played more matches than the average number of matches played across all players. This gives weight to long term performance. Average score has been used as indicator to factor in different performance levels of a player. This is a better choice than median score as median score may be biased based on match playing cadence of a player. It is likely that a player's score will improve with experience.

Similarly, the number of 4's and 6's scored by a player are also subject to the same averaging model as above.

To predict the series winner and series outcome, the ratio of wins by both countries has been considered.

To identify wicket taker, fielders are considered wicket takers in case of catches, and bowlers are considered for other forms of wicket taking.


> > Predictions < <

Based on the above, the predictions are:

Series winner: Australia
Series output: India: 2, Australia: 3
Highest run scorer: Virat Kohli
Higher wicket taker: MS Dhoni
Maximum sixes: Glenn Maxwell
Maximum fours: Virat Kohli
