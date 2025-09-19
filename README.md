| |Name|Rating|+/-|Exp|
|-|:---|:----:|:-:|--:|
|1|Walter|2,068|+1.9|1503|
|2|Vinnie|1,965|-3.9|1163|
|3|Jay|1,918|+3.5|690|
|4|Ebi|1,875|+3.7|380|
|5|Peter|1,817|+5.2|63|
|6|Armin|1,815|+3.7|50|
|7|John|1,814|-4.2|950|
|8|Chuck|1,813|+4.1|35|
|9|Robin|1,807|+4|251|
|10|Avi|1,805|-3.9|35|
|11|Anders|1,804|-4.1|25|
|12|Somchai|1,802|+4.4|80|
|13|David|1,801|+4.6|84|
|14|Ashok|1,800|+4.3|70|
|15|Gerry|1,796|+4.2|25|
|16|Pradyot|1,796|+3.9|25|
|17|Sandy|1,795|+2|135|
|18|Shannon|1,795|-4.1|65|
|19|Rene|1,793|-6.8|21|
|20|Benny|1,791|-4.9|20|
|21|Tom|1,788|-5.6|14|
|22|Leonard|1,786|+4.3|225|
|23|Gregg|1,784|-4.9|77|
|24|Junior|1,784|+1.8|22|
|25|Tony|1,778|-4.4|35|
|26|Majid|1,776|-4.4|90|
|27|Chris|1,776|+5.4|162|
|28|Brian|1,760|-5.7|3007|
|29|Darryl|1,758|-4.9|60|
|30|Van|1,702|-5.4|569|
|31|Graham|1,689|-3.1|983|
|32|Modi|1,549|-1.9|2190|


Follow section contains general information and short instructions.

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
