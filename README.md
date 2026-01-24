| |Name|Rating|+/-|Exp|
|-|:---|:----:|:-:|--:|
|1|Walter|2,084|-6|2149|
|2|Jay|1,956|+3.7|1012|
|3|Vinnie|1,933|-5.9|1655|
|4|Ebi|1,930|-4.4|570|
|5|Peter|1,855|+5|173|
|6|John|1,835|-4.7|1283|
|7|Otto|1,831|+6.4|66|
|8|Ali|1,819|-3.7|45|
|9|Armin|1,815|+3.6|50|
|10|Johannes|1,808|+4.5|20|
|11|Robin|1,807|+4|251|
|12|Chuck|1,806|-4.5|65|
|13|Bruno|1,805|+3.9|25|
|14|Avi|1,805|-3.9|35|
|15|Frank|1,804|+4.4|25|
|16|Brian|1,802|+4.7|4078|
|17|Ashok|1,802|-4.2|150|
|18|Anders|1,801|-2.9|30|
|19|Ben|1,800|-2.9|20|
|20|Mark|1,796|+5.5|25|
|21|Gerry|1,796|+4.2|25|
|22|Pradyot|1,796|+3.9|25|
|23|Shannon|1,795|-4.1|65|
|24|Mark L|1,795|-2.9|50|
|25|Aden|1,795|-2|23|
|26|Gav|1,794|+4.5|70|
|27|Rene|1,793|-6.9|21|
|28|Benny|1,791|-4.9|20|
|29|Simon|1,789|-2.9|25|
|30|Tom|1,788|-5.6|14|
|31|Kevin|1,788|-4.7|45|
|32|Chris|1,787|+5.4|182|
|33|Leonard|1,786|+4.3|225|
|34|Atom|1,786|+4.5|74|
|35|David|1,785|+6.1|194|
|36|Yost|1,785|-4.7|20|
|37|Larry|1,784|-3.6|30|
|38|Gregg|1,784|-4.9|77|
|39|Amanda|1,782|-4.5|30|
|40|Bill|1,782|-6.1|31|
|41|Somchai|1,780|-4.6|105|
|42|Tony|1,778|-4.4|35|
|43|Sebastian|1,776|-5.4|145|
|44|Sandy|1,766|-4.3|296|
|45|Junior|1,759|-1.6|55|
|46|Darryl|1,758|-4.9|60|
|47|Majid|1,733|-4.1|330|
|48|Van|1,683|+5.9|955|
|49|Graham|1,654|-4.7|1475|
|50|Modi|1,639|+4.7|2885|


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
