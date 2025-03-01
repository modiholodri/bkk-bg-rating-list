| |Name|Rating|+/-|Exp|
|-|:--:|:----:|:-:|:-:|
|1|Walter|1,938|+4.3|634|
|2|Vinnie|1,925|-6.3|520|
|3|Jay|1,866|+3.9|242|
|4|Ebi|1,824|+3.9|90|
|5|Peter|1,817|+5.2|63|
|6|Armin|1,815|+3.7|50|
|7|Avi|1,805|-3.9|35|
|8|Anders|1,804|-4.1|25|
|9|David|1,803|-5.9|67|
|10|Somchai|1,802|+4.4|80|
|11|Chuck|1,801|-4.4|20|
|12|Ashok|1,800|+4.3|70|
|13|Pradyot|1,796|+3.9|25|
|14|John|1,795|-5.4|396|
|15|Robin|1,794|+4.3|65|
|16|Chris|1,793|-6.7|73|
|17|Majid|1,792|+5.4|28|
|18|Benny|1,791|-4.9|20|
|19|Sandy|1,790|-4.3|85|
|20|Leonard|1,786|+3.9|145|
|21|Gregg|1,784|-4.9|77|
|22|Tony|1,778|-4.4|35|
|23|Graham|1,765|-3.6|150|
|24|Van|1,745|-5|345|
|25|Brian|1,721|+4.7|714|
|26|Modi|1,671|+5|678|


### Rating Formula

If player 1 rated A wins a match up to N points against player 2 rated B, the rating of player 1 increases with W points and then the rating of player 2 drops with W points, where:

W = (1 − P) × S

Here, P is the probability of player 1 winning the match and S is the number of rating points at stake. These are given by:

P = 1 / (1 + 10^(-(A-B) × √N / 2000))

S = 4 × √N

- The winner's rating will increase by a number of points equal to the number of rating points at stake multiplied by the probability that the player involved would have lost the match.
- The loser's rating drops by a number of points equal to the number of rating points multiplied by the probability that the player involved would have won the match.

### Reporting Guidelines

Only the winner reports the result of a match.
A match counts only for the rating if it is a live played match (no money play or chouettes)
with both players agreeing beforehand that it will count for the rating.


### Report Match on GitHub

Frequent players are included in dropdown menus to ease the match reporting.
When a player, who is not included in dropdown menus is involved, the name of the player has to be typed in.

- Report Match:  is used for matches between players that are normally present during the Saturday sessions.
  Matches are reported using dropdown menus for the winner/loser name and the match length.
- Report New Player Match:  is used for matches with a player not in the dropdown menus, for example, when a new player joins.
  Matches are reported using dropdown menus or editing the name manual for the winner/loser name and the match length.

To report any of the two match types go to Actions, select the match type, click on RUN WORKFLOW.
Select or type in the Winner, the Loser and the Match Length.
Click on RUN WORKFLOW again to submit the match report.

The rating list will be updated within 20 seconds.
