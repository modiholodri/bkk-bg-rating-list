| |Name|Rating|+/-|Exp|
|-|:---|:----:|:-:|--:|
|1|Walter|2,042|-5.9|1934|
|2|Vinnie|1,980|-4.1|1505|
|3|Jay|1,935|+3.5|972|
|4|Ebi|1,930|+2.8|505|
|5|Peter|1,833|+3.6|118|
|6|Otto|1,831|+6.4|66|
|7|John|1,816|+4.4|1162|
|8|Armin|1,815|+3.7|50|
|9|Ashok|1,811|-5.2|100|
|10|Robin|1,807|+4|251|
|11|Aden|1,806|+2|3|
|12|Chuck|1,806|-4.5|65|
|13|Avi|1,805|-3.9|35|
|14|Frank|1,804|+4.4|25|
|15|Anders|1,801|-2.9|30|
|16|Ben|1,800|-2.9|20|
|17|Bruno|1,798|-6.4|34|
|18|Mark|1,796|+5.5|25|
|19|Gerry|1,796|+4.2|25|
|20|Pradyot|1,796|+3.9|25|
|21|Sandy|1,795|+2|135|
|22|Shannon|1,795|-4.1|65|
|23|Aiden|1,794|-5.5|5|
|24|Rene|1,793|-6.8|21|
|25|Atom|1,792|+3.5|44|
|26|Bill|1,792|+4.5|20|
|27|Benny|1,791|-4.9|20|
|28|Brian|1,790|-5.5|3887|
|29|Simon|1,789|-2.9|25|
|30|Tom|1,788|-5.6|14|
|31|Kevin|1,788|-4.7|45|
|32|Chris|1,787|+5.4|182|
|33|Leonard|1,786|+4.3|225|
|34|David|1,785|-5.2|176|
|35|Larry|1,785|-3.6|30|
|36|Gregg|1,784|-4.9|77|
|37|Somchai|1,780|-4.6|105|
|38|Gav|1,779|-3|45|
|39|Tony|1,778|-4.4|35|
|40|Sebastian|1,777|-5.4|145|
|41|Junior|1,766|-2|40|
|42|Darryl|1,758|-4.9|60|
|43|Majid|1,754|-3.5|240|
|44|Van|1,672|-3.6|950|
|45|Graham|1,670|-3.1|1455|
|46|Modi|1,626|+5.5|2646|


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
