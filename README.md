# AtlantaBravesAPIxSQLite

Notable Findings and Discrepancies
Comparison of StatsAPI Data and PITCHBYPITCH Data
Player ID:

The player ID 458924 is consistent across both datasets, ensuring that the data being compared corresponds to the same player.
Games Played:

StatsAPI: 28 games played.
PITCHBYPITCH: Not available.
Finding: The absence of games played data in the PITCHBYPITCH table limits the ability to fully assess the player’s performance in context.
Innings Pitched:

StatsAPI: 20.1 innings pitched.
PITCHBYPITCH: 33.0 innings pitched.
Discrepancy: There is a significant difference in innings pitched, with the PITCHBYPITCH data reporting 12.2 more innings. This may indicate discrepancies in the data collection methods or the timeframes of the data being used.
Strikeouts:

StatsAPI: 16 strikeouts.
PITCHBYPITCH: 27 strikeouts.
Discrepancy: The PITCHBYPITCH table reports 11 more strikeouts than the StatsAPI. This discrepancy could suggest either that the StatsAPI data does not account for all strikeouts or that the PITCHBYPITCH data includes additional strikeouts not recorded in the StatsAPI.
Walks:

StatsAPI: 10 walks.
PITCHBYPITCH: 0 walks.
Discrepancy: The PITCHBYPITCH data shows zero walks, indicating a significant inconsistency. This may require further investigation into how walks are recorded in both datasets.
Home Runs:

StatsAPI: 0 home runs allowed.
PITCHBYPITCH: 1 home run allowed.
Discrepancy: The StatsAPI indicates no home runs allowed, while the PITCHBYPITCH data shows one home run. This discrepancy might highlight differences in data accuracy or criteria used for defining a "home run" in each dataset.
