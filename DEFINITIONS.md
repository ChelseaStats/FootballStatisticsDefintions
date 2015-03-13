###  Statistical Definitions in Football

#### League Table fields

    PLD - played
    W - Wins
    D - Draws
    L - Losses
    CS - Clean Sheet
    FS - Failed to Score
    BTTS - Both Teams Scored
    F - Goals For
    A - Goals Against
    GD - Goal Difference (Goals For - Goals Against)
    W% - Win Percentage  (Wins / PLD) * 100
    D% - Draw Percentage (Draws / PLD) * 100
    L% - Loss Percentage (Losses / PLD) * 100
    U% - Unbeaten Percentage ((Wins + Draws)/ PLD) * 100
    PPG - Points Per Game (((Wins * 3) + Draws)/ PLD) 
    PTS - Points (Wins * 3) + Draws)

#### Big 7 / Superior 7 

The traditional big 7 premier league teams over recent long term rankings.

    Arsenal
    Chelsea
    Everton
    Liverpool
    Man Utd
    Man City
    Spurs

@ChelseaStats publishes tables on a per <a href="https://www.thechels.co.uk/category/the-big-7-league/">gameweek</a> basis  

For an explanation of these categorisations, Simon Gleave wrote about the concept of the <a href="https://scoreboardjournalism.wordpress.com/2013/12/30/introducing-the-superior-7-and-the-threatened-13/">Superior 7</a> in December 2013.

This concept still exists despite Everton’s performance in the 2014-15 season as it is based on the longer term. However, Southampton are threatening to transform the categories into 'Excellent 8 and Threatened 12' if they repeat their recent performances next season.

#### Threatened 13

All the Premier League teams that are not in the big 7 (superior 7).

For an explanation of these categorisations, Simon Gleave wrote about the concept of the <a href="https://scoreboardjournalism.wordpress.com/2013/12/30/introducing-the-superior-7-and-the-threatened-13/">Threatened 13</a> in December 2013.

@ChelseaStats published an updated table <a href="https://www.thechels.co.uk/threatened-13/">here</a>.

@ChelseaStats also ranks teams against their opposite groups <a href="https://www.thechels.co.uk/big-7-vs-t13/">here</a>

#### Ever 7

The current ever-present Premier League teams 

    Arsenal
    Aston Villa
    Chelsea
    Everton
    Liverpool
    Man Utd
    Spurs

A ranking of teams that have an equal number of games in the premier league. @ChelseaStats publishes this on a per <a href="https://www.thechels.co.uk/category/the-ever-7-league/">gameweek basis</a> 

#### Last38

The Last 38 – This is the ultimate form guide, it refers to the last 38 league games a team has played in the Premier League, during a season this means we take the data from the current season and use the end of the previous season to make up 38 games. There are of course 38 games in a season, so it can be seen as a final table that is updated every gameweek.

The previous season for some sides might in fact be several years ago if they suffered relegation and didn't get promoted again for a number of years.

based on an idea by @OmarChauduri. @ChelseaStats <a href="https://www.thechels.co.uk/last-38-league/">automated the process</a>  of calculating per <a href="https://www.thechels.co.uk/category/the-last-38-league/">gameweek</a>. 

#### Close

Around 85% of results are settled by close scorelines, where the result is +1/0/-1 for example 1-0, 2-1, 2-3, 4-5.

#### Shots

Shots are split into three groups

    Shots on target (thus either saved or scored)
    Shots off target (includes hitting the post/crossbar)
    Shots blocked

#### TSR – Total Shots Ratio
> also known as shots share

A ratio to explain how teams fare against their average competition in the shots battle. Ex: If Manchester City has 20 shots in the match and Newcastle have 10, City’s TSR for that match is .67, Newcastle’s is .33.
James Grayson has written about this frequently on his website <a href="http://jameswgrayson.wordpress.com/2012/12/02/introducing-tsr2-4/">here</a>. We care about TSR for teams because it has a reasonably strong correlation to points and goal difference.
In hockey, this is called Corsi.

    Shots For / ( Shots For + Shots Against )
    
#### ShDom – Shot Dominance 

A different way of expressing TSR. Instead of looking at the shots battle as a ratio, we instead look at it centered around an average of 1. Ex: If Manchester City has 20 shots in the match and Newcastle have 10, City’s ShDom is 2.0 and Newcastle’s is .5.

Ted Knutson (@Mixedknuts) looked at league shot dominance for previous Champions League Qualifiers <a href="http://statsbomb.com/2013/10/what-does-it-take-to-qualify-for-the-champions-league/">here</a>.

#### SoTR – Shots on Target Ratio

Similar to TSR this focuses on those important shots on target instead.

    Shots on Target For / ( Shots on Target For + Shots on Target Against )
    
#### ExpG – Expected Goals

This is shorthand for either the expected goals from a particular input (shots, shots on target, key passes, whatever) or it is often specifically referring to someone’s model.

for example one developer by <a href="http://statsbomb.com/2013/08/goal-expectation-and-efficiency/">Colin Trainor and Constantinos Chappas</a>.

#### SOT – Shots on Target

Used in both player analytics and team stats, it often provides a better layer of accuracy for how effective (or ineffective) a team’s attack is than simple shot numbers.

#### SOTCON or SOTC – Shots on Target Conceded

The defensive side of Shots on Target.

#### ShAcc, Sh% – Shooting Accuracy

Percentage of total shots placed on target.

#### Shots Conversion %

The number of goals from shots on target expressed as a percentage. 

#### Chance conversion %

The number of goals from all shots expressed as a percentage. 

#### Chances Created

passes, crosses or set pieces that lead to a shot. 

#### Pass% – Passing Accuracy

Usually given as a percentage.

    (Passes Attempted / Passes Completed ) * 100

or can simply be displayed as the two values `(xx/yy)`  

#### Sv% - Save% – Save Percent

Percentage of total shots that have been saved.

    ((Shots on Target - Goals) / Total Shots on Target ) * 100

#### PDO

“PDO is the sum of a teams shooting percentage (goals/shots on target) and its save percentage (saves/shots on target against). It treats each shot as having an equal chance of being scored – regardless of location, the shooter, or the identity or position of the ‘keeper and any defenders. Despite this obvious shortcoming it regresses <a href="http://jameswgrayson.wordpress.com/2011/05/14/sh-sv-pdo-part-n/">heavily towards the mean</a> – meaning that it has a large luck component. In fact, over the course of a Premiership season, the distance a teams PDO is from 1000 is <a href="http://jameswgrayson.wordpress.com/2011/04/15/pdo-part-ii/">~60% luck</a>.” - <a href="http://jameswgrayson.wordpress.com/2013/12/23/on-the-spread-of-pdo-throughout-a-premiership-season/">James Grayson</a>

In other articles about PDO, it has often been used around the 100 marker rather than 1000, perhaps this is because it's more familiar to english users and percentages etc.

#### ToP%

Time on Pitch percentage. 

    The mins a player plays for their team / total potential minutes.
    
#### Total Potentinal Minutes

    Number of games team has played * 90 

On the assumption you'd only really do this at league level, remember to factor in extra time in some games if you are doing all competitions.

#### Per90 – p90, /90 or just Foo90

Normalization for time, usually used in player stats. Instead of dividing a player’s rate stat by games or appearances, you take all the minutes played and divide them into 90 minute chunks. Then take THAT number and use it as you would games played.

It’s useful in helping to extrapolate player production into more meaningful units. 
Ben Pugsley wrote a primer <a href="http://statsbomb.com/2013/08/an-introduction-to-the-per-90-metric/">here</a>.

    player value / ( sum of minutes / 90 )

#### NPG – Non-penalty Goals

A goal tally for a player after you strip out the penalty goals.

    goals - pens

#### G90 – Goals Per90

A player or team goal tally divided into 90 minute chunks. We do this to normalize for actual time played, as it produces far more accurate rates of goal scoring than using appearances, starts, etc.

    goals / ( sum of minutes / 90 )

#### NPG90 – Non-Penalty Goals Per90

A player or team’s goal tally with all the penalties stripped out, divided into 90 minute chunks.

    non-penalty goals / (sum of minutes / 90)

#### A – Assists

Often written that way as part of a quick player stat summary.  Ex: Messi produced 46G/12A in the 2012-13 La Liga season.

Assists can be subjective and they differ from stats providers to a club's own statisticians generally penalties won do not count, yet they tend to do so in fantasy leagues.

#### A90 – Assists Per 90

    assists / (sum of minutes / 90)

#### G+A90 – Goals + Assists per 90
> Also known as Points Per 90

Used interchangeably sometimes with “scoring contribution.”  It’s a more complete way of measuring an individual player’s total offensive contribution than just looking at either G90 or A90 in a vacuum.

    (Goals + Assists) / (sum of minutes / 90)

#### Sh90 – Shots per 90

    Shots / (sum of minutes / 90)

#### SOT90 – Shots on Target per 90

    Shots on Target / (sum of minutes / 90)
    
#### Expected Points

Calculating Expected Points from bookmarkers' decimal odds.

    a = (1 / odds home) / ( (1 / odds home win) + (1 / odds draw) + (1 / odds away win) )
    b = (1 / odds draw) / ( (1 / odds home win) + (1 / odds draw) + (1 / odds away win) )
    c = (1 / odds away) / ( (1 / odds home win) + (1 / odds draw) + (1 / odds away win) )
    home expected points = ( 3 * a ) + b
    away expected points = b + ( c * 3 )
    
@SimonGleave wrote about it <a href="https://scoreboardjournalism.wordpress.com/2012/09/01/how-to-avoid-rank-journalism-a-simple-expected-points-model/">here</a>

Bookmarkers odds can be taken from each of their websites, but football-data.co.uk does an excellent job of combining these for each game on a weekly basis.
    
#### PAdj Defensive Stats – Stands for Possession-Adjusted. 

Essentially, the problem with defensive rate stats is that you can’t make a tackle, interception, etc when your team has the ball. Thus teams that have a lot of the ball will have under-represented defensive output compared to a team with low possession. These types of stats attempt to adjust for opportunity, but as of June 30, 2014 are very new and still in development.

statsbomb wrote about it <a href="http://statsbomb.com/2014/06/introducing-possession-adjusted-player-stats/">here</a>.

#### YAPSS

Young Attacking Player Statistical Scout. It’s a model developed by Ted Knutson that attempts to use statistics on players that are age 23 or under to find future stars. The introductory piece can be found <a href="http://statsbomb.com/2014/06/statistical-scouting-young-super-stars/">here</a> and more can be found by searching site articles for YAPSS.

#### Defensive Shell

“A defensive shell is a tactical concept that refers when a team largely relinquishes their attacking intent and focuses on protecting the goal. (Also known as turtling.) Teams often do this after taking the lead in a match.”

statsbomb wrote about it <a href="http://statsbomb.com/2013/08/introduction-to-defensive-shells/">here</a>

    Example: Premier League 2013-14 Liverpool 0-2 Chelsea.

#### Score Effects / Game State 

Game state is essentially the current score but marked as -1, 0, +1, +2, +3, a team leading 1-0 is likely to go into a defensive shell and hit on the counter attack, thus it is likely the losing team would see an increase in possession metrics, shots, final third entries these are known as <a href="http://statsbomb.com/2013/12/score-effects/">score effects</a>.

This might explain why it's a common punditry term that 2-0 is a dangerous scoreline. Benjamin Pugsley is the main driver for this terminology and metrics. see @ObjectiveFooty for more info.

<a href="http://11tegen11.net/2013/04/06/game-states-and-conversion/">Game states and conversion</a>.

#### Pace or Shot Pace

Usually referring to the total number of shots taken in an average game, either by team or by league. It’s a proxy for looking at how quickly teams play.

    total shots / total games

Some teams/leagues exhibit high average paces (like the English Premier League) and some exhibit low ones. Teams also vary within those leagues.

bitterandblue wrote about it <a href="http://bitterandblue.sbnation.com/2013/1/24/3908816/football-soccer-analytics-pace">here</a> and statsbomb <a href="http://statsbomb.com/2013/11/pace-and-margin-for-error/">here</a>.

Shot pace might be best expressed as an average x.xx minutes per shot for/against at a team level. One could then map whether pace was changing over the course of the season.

#### Zone Entries

A hockey concept that unfortunately requires infinite work to record manually. It examines how teams put the ball into the final third, and is thought to provide significant insight into team philosophy and attacking style.

Would require better camera angles for self-recording, overhead or behind the goal.

Statsbomb wrote about it <a href="http://statsbomb.com/2013/08/an-introduction-to-zone-entries/">here</a>.


## Links

+ http://www.squawka.com/football-stats-definitions
+ http://statsbomb.com/stat-definitions/
+ http://www.cbssports.com/help/glossary/stats/soccer
+ http://web.mit.edu/~csvoss/Public/usabo/stats_handout.pdf
