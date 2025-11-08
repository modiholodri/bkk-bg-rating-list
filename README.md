| |Name|Rating|+/-|Exp|
|-|:---|:----:|:-:|--:|
|1|Walter|2,086|-5.3|1783|
|2|Vinnie|1,947|+3.6|1375|
|3|Jay|1,942|+5.3|856|
|4|Ebi|1,912|+2.7|425|
|5|Otto|1,831|+6.4|66|
|6|Peter|1,817|+5.2|63|
|7|Armin|1,815|+3.7|50|
|8|Chuck|1,813|+4.1|35|
|9|Robin|1,807|+4|251|
|10|Avi|1,805|-3.9|35|
|11|Anders|1,804|-4.1|25|
|12|Ashok|1,800|+4.3|70|
|13|Ben|1,800|-2.9|20|
|14|Bruno|1,798|-6.4|34|
|15|Mark|1,796|+5.5|25|
|16|Gerry|1,796|+4.2|25|
|17|Pradyot|1,796|+3.9|25|
|18|Sandy|1,795|+2|135|
|19|Shannon|1,795|-4.1|65|
|20|Rene|1,793|-6.8|21|
|21|Sebastian|1,792|+3.9|70|
|22|Bill|1,792|+4.5|20|
|23|Benny|1,791|-4.9|20|
|24|Atom|1,790|-1.7|16|
|25|Tom|1,788|-5.6|14|
|26|Kevin|1,788|-4.7|45|
|27|Leonard|1,786|+4.3|225|
|28|David|1,785|-3.6|164|
|29|Larry|1,785|-3.6|30|
|30|Gregg|1,784|-4.9|77|
|31|John|1,783|+4.6|1085|
|32|Somchai|1,780|-4.6|105|
|33|Tony|1,778|-4.4|35|
|34|Chris|1,776|+5.4|162|
|35|Junior|1,773|-1.7|32|
|36|Majid|1,765|-4.9|145|
|37|Brian|1,759|-5.5|3476|
|38|Darryl|1,758|-4.9|60|
|39|Van|1,706|+4.9|830|
|40|Graham|1,702|-2.4|1340|
|41|Modi|1,590|+5.5|2385|


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
