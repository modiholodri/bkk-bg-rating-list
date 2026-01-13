| |Name|Rating|+/-|Exp|
|-|:---|:----:|:-:|--:|
|1|Walter|2,088|+3.2|2085|
|2|Vinnie|1,965|-5.5|1595|
|3|Jay|1,948|+3.7|992|
|4|Ebi|1,932|-6.2|530|
|5|Peter|1,854|-3.2|153|
|6|Otto|1,831|+6.4|66|
|7|John|1,828|-5.7|1223|
|8|Armin|1,815|+3.6|50|
|9|Johannes|1,808|+4.5|20|
|10|Robin|1,807|+4|251|
|11|Chuck|1,806|-4.5|65|
|12|Bruno|1,805|+3.9|25|
|13|Avi|1,805|-3.9|35|
|14|Frank|1,804|+4.4|25|
|15|Ashok|1,802|-4.2|150|
|16|Anders|1,801|-2.9|30|
|17|Ben|1,800|-2.9|20|
|18|Mark|1,796|+5.5|25|
|19|Gerry|1,796|+4.2|25|
|20|Pradyot|1,796|+3.9|25|
|21|Shannon|1,795|-4.1|65|
|22|Aden|1,795|-2|23|
|23|Rene|1,793|-6.9|21|
|24|Benny|1,791|-4.9|20|
|25|Brian|1,790|+4.4|4028|
|26|Simon|1,789|-2.9|25|
|27|Tom|1,788|-5.6|14|
|28|Kevin|1,788|-4.7|45|
|29|Chris|1,787|+5.4|182|
|30|Leonard|1,786|+4.3|225|
|31|David|1,785|+6.1|194|
|32|Yost|1,785|-4.7|20|
|33|Larry|1,784|-3.6|30|
|34|Gregg|1,784|-4.9|77|
|35|Bill|1,782|-6.1|31|
|36|Atom|1,781|-2.9|69|
|37|Somchai|1,780|-4.6|105|
|38|Gav|1,779|-3|45|
|39|Tony|1,778|-4.4|35|
|40|Sebastian|1,776|-5.4|145|
|41|Sandy|1,776|-4.4|236|
|42|Junior|1,763|-2.5|51|
|43|Darryl|1,758|-4.9|60|
|44|Majid|1,738|-4.2|310|
|45|Van|1,671|-3.6|920|
|46|Graham|1,654|-4.7|1475|
|47|Modi|1,637|+5.3|2825|


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
