## Data Description

| **Column**                   | **Description**                                                                                  |
| --------------------------- | ------------------------------------------------------------------------------------------------ |
| `name`                      | Player's full name                                                                               |
| `position`                  | Player's position: `GK` (goalkeeper), `DEF` (defender), `MID` (midfielder), `FWD` (forward)     |
| `team`                      | Club the player belongs to                                                                       |
| `xP`                        | **Expected Points** – projected FPL points for the player                                        |
| `assists`                   | Actual number of assists in the match                                                            |
| `bonus`                     | Bonus points awarded (FPL's reward system for top 3 performers in a match)                      |
| `bps`                       | **Bonus Point System** – internal scoring metric to determine bonus distribution                 |
| `clean_sheets`              | Number of clean sheets (`GK`/`DEF`/`MID` earn points if no goals conceded)                           |
| `creativity`                | Metric estimating the player's chance-creation ability                                           |
| `element`                   | Internal ID of the player                                                                        |
| `expected_assists`          | Expected assists (xA) – model-based estimation of assist potential                               |
| `expected_goal_involvements`| Sum of xG and xA – overall expected contribution to goals                                         |
| `expected_goals`            | Expected goals (xG) – model-estimated goal-scoring chances                                       |
| `expected_goals_conceded`   | Expected goals conceded by the team when this player was on the pitch                            |
| `fixture`                   | Fixture ID                                                                                       |
| `goals_conceded`            | Actual goals conceded while player was on the pitch                                              |
| `goals_scored`             | Actual goals scored by the player                                                                |
| `ict_index`                 | FPL index combining **Influence**, **Creativity** and **Threat**                                |
| `influence`                 | Player's influence on the match (involvement in key actions)                                     |
| `kickoff_time`              | Match kickoff time (in UTC)                                                                      |
| `minutes`                   | Minutes played in the match                                                                      |
| `modified`                  | Field may indicate modified or synced data                                                       |
| `opponent_team`            | Opponent team's internal ID                                                                      |
| `own_goals`                 | Number of own goals scored by the player                                                         |
| `penalties_missed`          | Number of missed penalty kicks                                                                   |
| `penalties_saved`           | Number of saved penalty kicks (`GK` only)                                                 |
| `red_cards`                 | Number of red cards received                                                                     |
| `round`                     | Gameweek number                                                                                  |
| `saves`                     | Number of saves made (`GK` only)                                                          |
| `selected`                  | Number of FPL managers who selected the player                                                   |
| `starts`                    | Number of starts (i.e. player in starting XI)                                                   |
| `team_a_score`              | Goals scored by `Away` Team                                                    |
| `team_h_score`              | Goals scored by `Home` Team                                                    |
| `threat`                    | Metric estimating the player's attacking threat                                                  |
| `total_points`              | Total FPL points earned in the match                                                             |
| `transfers_balance`         | Net transfers in the gameweek = `transfers_in` – `transfers_out`                                     |
| `transfers_in`              | Number of transfers in for the player during the gameweek                                        |
| `transfers_out`             | Number of transfers out of the player during the gameweek                                        |
| `value`                     | Player's FPL price (in 0.1M units, e.g. `50` = £5.0M)                                           |
| `was_home`                  | Boolean indicating if player played at Home (`True`) or Away (`False`)                          |
| `yellow_cards`              | Number of yellow cards received                                                                  |
