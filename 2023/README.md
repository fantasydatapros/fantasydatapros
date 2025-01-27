# 2023 Data Summary

## 06-Data Munging
* Projection data from fantasydatapros.com (all positions)
* ADP data from Underdog Fantasy best ball drafts (half-ppr)

## 07-Data Visualizations
* Yearly fantasy data from nfl_data_py for 2022.
* Weekly fantasy data from nfl_data_py for 2022.
* Combine data from 2000 - 2023 (nfl_data_py).

#### Changed from 2022:

* New columns in Fantasy Data: Passing Cmp, 2-Point Conversions
* Data source has been changed to nflfastR / nfl_data_py for weekly stats and also combine data; new columns for each data set.
* New columns for weekly data:

1. PlayerID: nflfastR gsis_id
2. PassingAirYards
3. PassingYAC
4. PassingFirstDown
5. PassingEPA: Passing EPA/week
6. Passing2PC: Passing 2 Point Conversions
7. RushingFirstDown
8. RushingEPA: Rushing EPA/week
9. Rushing2PC
10. Receptions
11. Targets
12. ReceivingYards
13. ReceivingTDs
14. RecevingAirYards
15. ReceivingYAC
15. ReceivingFirstDown
16. ReceivingEPA: Receiving EPA/week
17. Receiving2PC
18. TargetShare
19. AirYardShare
20. WOPR: Weigted Opportunity
21. SpecialTeamsTD

* Combine data now includes the most recent combine results

New columns in combine data:

1. DraftTeam
2. DraftRound
3. PFRPlayerID: Player ID on profootballreference.com
4. CFBPlayerID: Player ID for CFB
5. Vertical: Vertical jump results

Unfortunately, no Age column in this new data source.

## 08-Finding TD Regression Candidates
Removed - now loading data exclusively from `nfl_data_py`. Moved this section to #9.

## 09-Correlation Matrices

Moved section to #8.

* Weekly fantasy data from nfl_data_py for 2022.

#### Changed from 2022:
* Same changes described above as a result of changing the data source
* Changed file name for format on Yearly data to 02-Yearly Fantasy Stats - {year}.csv.

## 10-Machine Learning - Regression
Removed

## 11-Machine Learning - Clustering
Removed
