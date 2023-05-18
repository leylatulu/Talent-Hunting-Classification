<h1 align="center">Talent Hunting Classification</h1> 

<details>
<summary><h2 align="left">Business Problem</h2></summary>
Predicting which class (average, highlighted) players are according to the scores given by the Scouts to the characteristics of the players.
</details>


<details>
<summary><h2 align="left">Data Set Story</h2></summary>
The data set consists of information from Scoutium, which includes the features and scores of the football players evaluated by the scouts according to the characteristics of the footballers observed in the matches. This data set is hidden.
</details>


<details>
<summary><h2 align="left">Description of Features</h2></summary>

<h3 align="left">Scoutium Attributes CSV File</h3>

|**FEATURE**| **DESCRIPTION** |
| --- | --- | 
|task_response_id|The set of a scout's assessments of all players on a team's roster in a match| 
|match_id|The id of the match|
|evaluator_id|The id of the evaluator(scout)|
|player_id|The id of the player|
|position_id|The id of the position played by the relevant player in that match. 1-Goalkeeper, 2-Stopper, 3-Right-back, 4-Left-back, 5-Defensive midfielder, 6-Central midfield, 7-Right wing, 8-Left wing, 9-Attacking midfielder, 10-Striker|
|analysis_id|A set containing a scout's attribute evaluations of a player in a match|
|attribute_id|The id of each attribute the players were evaluated for|
|attribute_value|Value (points) given by a scout to a player's attribute|

<h3 align="left">Scoutium Potential Labels CSV File</h3>

|**FEATURE**| **DESCRIPTION** |
| --- | --- | 
|task_response_id|The set of a scout's assessments of all players on a team's roster in a match| 
|match_id|The id of the match|
|evaluator_id|The id of the evaluator(scout)|
|player_id|The id of the player|
|potential_label|Label showing the final decision of an observer regarding a player in the match. (target)|
</details>