| |Name|Rating|+/-|Exp|
|-|:---|:----:|:-:|--:|
|1|Walter|2,075|+3|1828|
|2|Jay|1,956|+3.5|891|
|3|Vinnie|1,952|+3.6|1405|
|4|Ebi|1,912|+2.7|425|
|5|Otto|1,831|+6.4|66|
|6|Peter|1,817|+5.2|63|
|7|Armin|1,815|+3.7|50|
|8|Ashok|1,812|-3|90|
|9|Robin|1,807|+4|251|
|10|Chuck|1,806|-4.6|55|
|11|John|1,806|+3.8|1120|
|12|Avi|1,805|-3.9|35|
|13|Anders|1,804|-4.1|25|
|14|Frank|1,804|+4.4|25|
|15|Ben|1,800|-2.9|20|
|16|Bruno|1,798|-6.4|34|
|17|Mark|1,796|+5.5|25|
|18|Gerry|1,796|+4.2|25|
|19|Pradyot|1,796|+3.9|25|
|20|Sandy|1,795|+2|135|
|21|Shannon|1,795|-4.1|65|
|22|Rene|1,793|-6.8|21|
|23|Simon|1,792|-3.6|20|
|24|Bill|1,792|+4.5|20|
|25|Benny|1,791|-4.9|20|
|26|David|1,790|+4.4|169|
|27|Atom|1,788|+3.5|26|
|28|Tom|1,788|-5.6|14|
|29|Kevin|1,788|-4.7|45|
|30|Leonard|1,786|+4.3|225|
|31|Larry|1,785|-3.6|30|
|32|Gregg|1,784|-4.9|77|
|33|Somchai|1,780|-4.6|105|
|34|Tony|1,778|-4.4|35|
|35|Chris|1,776|+5.4|162|
|36|Sebastian|1,773|-3.5|110|
|37|Junior|1,773|-1.7|32|
|38|Brian|1,762|-5.4|3541|
|39|Darryl|1,758|-4.9|60|
|40|Majid|1,757|-4.5|175|
|41|Graham|1,693|-5.1|1350|
|42|Van|1,685|-3.8|860|
|43|Modi|1,612|+5.4|2435|


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
