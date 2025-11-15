| |Name|Rating|+/-|Exp|
|-|:---|:----:|:-:|--:|
|1|Walter|2,069|-5.3|1818|
|2|Jay|1,946|+3.4|876|
|3|Vinnie|1,942|+5.3|1390|
|4|Ebi|1,912|+2.7|425|
|5|Otto|1,831|+6.4|66|
|6|Chuck|1,819|+5.9|40|
|7|Peter|1,817|+5.2|63|
|8|Armin|1,815|+3.7|50|
|9|Frank|1,808|+4.2|10|
|10|Robin|1,807|+4|251|
|11|Ashok|1,806|+5.3|75|
|12|John|1,805|+4.5|1110|
|13|Avi|1,805|-3.9|35|
|14|Anders|1,804|-4.1|25|
|15|Ben|1,800|-2.9|20|
|16|Bruno|1,798|-6.4|34|
|17|Mark|1,796|+5.5|25|
|18|Gerry|1,796|+4.2|25|
|19|Pradyot|1,796|+3.9|25|
|20|Simon|1,796|-4.5|5|
|21|Sandy|1,795|+2|135|
|22|Shannon|1,795|-4.1|65|
|23|Rene|1,793|-6.8|21|
|24|Bill|1,792|+4.5|20|
|25|Benny|1,791|-4.9|20|
|26|Sebastian|1,791|-5.6|90|
|27|David|1,790|+4.4|169|
|28|Atom|1,788|+3.5|26|
|29|Tom|1,788|-5.6|14|
|30|Kevin|1,788|-4.7|45|
|31|Leonard|1,786|+4.3|225|
|32|Larry|1,785|-3.6|30|
|33|Gregg|1,784|-4.9|77|
|34|Somchai|1,780|-4.6|105|
|35|Tony|1,778|-4.4|35|
|36|Chris|1,776|+5.4|162|
|37|Junior|1,773|-1.7|32|
|38|Brian|1,758|-3.4|3526|
|39|Darryl|1,758|-4.9|60|
|40|Majid|1,753|-4.2|160|
|41|Graham|1,693|-5.1|1350|
|42|Van|1,692|-2.5|850|
|43|Modi|1,607|+5.6|2415|


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
