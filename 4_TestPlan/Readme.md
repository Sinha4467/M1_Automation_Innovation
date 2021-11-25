# Test Plan

---
## High level Test Plan


| TestID | User I/P | Computer I/P | Actual O/P | Expected O/P|
| ---:   | -------: | -------:     | ----------:| ----------: |
| 01     | Paper    | Rock         |   User Win |  User Wins  |
| 02     |Rock      | Rock         | Tie        | Tie         |
| 03     |Scissors  | Rock         | Computer Wins | Computer Wins |
| 04     |  Rock    |   Paper      |  Computer Wins|  Computer Wins|
|05      | Paper    |  Paper       | Tie           | Tie           |
|06      |  Scissors| Paper        | User Wins     |User Wins      |

## Low level Test Plan

| TestID | User I/P | Computer I/P | Actual O/P | Expected O/P|
| ---:   | -------: | -------:     | ----------:| ----------: |
| 01     | 2 == Paper    |   1 == Rock       |   User Win |  User Wins  |
| 02     |1 == Rock      |1 == Rock         | Tie        | Tie         |
| 03     |3 == Scissors  | 1 == Rock         | Computer Wins | Computer Wins |
| 04     |  1 == Rock      |   2 == Paper      |  Computer Wins|  Computer Wins|
|05      | 2 == Paper  |  2 == Paper     | Tie           | Tie           |
|06      |  3 == Scissors| 2 == Paper       | User Wins     |User Wins      |
