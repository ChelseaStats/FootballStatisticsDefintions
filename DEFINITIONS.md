###  Statistical Definitions in Football

###### Formatting:

Ratios - should be in the format of `x.xxx` to 3 decimal places (dp).

Percentages - should be in the format `xx.xx%` to 2dp.

    

##### League Table fields

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

##### Big 7 / Superior 7 

The traditional big 7 premier league teams over recent long term rankings.

    Arsenal
    Chelsea
    Everton
    Liverpool
    Man Utd
    Man City
    Spurs

##### Threatened 13

All the Premier League teams that are not in the big 7 (superior 7).

##### Ever 7

The current ever-present Premier League teams 

    Arsenal
    Aston Villa
    Chelsea
    Everton
    Liverpool
    Man Utd
    Spurs

##### Last38

The Last 38 – This is the ultimate form guide, it refers to the last 38 league games a team has played in the Premier League, during a season this means we take the data from the current season and use the end of the previous season to make up 38 games. There are of course 38 games in a season, so it can be seen as a final table that is updated every gameweek.

The previous season for some sides might in fact be several years ago if they suffered relegation and didn't get promoted again for a number of years.

##### Close

Around 85% of results are settled by close scorelines, where the result is +1/0/-1 for example 1-0, 2-1, 2-3, 4-5.

##### Shots

Shots are split into three groups

    Shots on target (thus either saved or scored)
    Shots off target (includes hitting the post/crossbar)
    Shots blocked

##### TSR – Total Shots Ratio

A ratio to explain how teams fare against their average competition in the shots battle. Ex: If Manchester City has 20 shots in the match and Newcastle have 10, City’s TSR for that match is .67, Newcastle’s is .33.
James Grayson has written about this frequently on his website here. We care about TSR for teams because it has a reasonably strong correlation to points and goal difference.
In hockey, this is called Corsi.

    Shots For / ( Shots For + Shots Against )
    
##### ShDom – Shot Dominance 

A different way of expressing TSR. Instead of looking at the shots battle as a ratio, we instead look at it centered around an average of 1. Ex: If Manchester City has 20 shots in the match and Newcastle have 10, City’s ShDom is 2.0 and Newcastle’s is .5.

##### SoTR – Shots on Target Ratio

Similar to TSR this focuses on those important shots on target instead.

    Shots on Target For / ( Shots on Target For + Shots on Target Against )
    
##### ExpG – Expected Goals

This is shorthand for either the expected goals from a particular input (shots, shots on target, key passes, whatever) or it is often specifically referring to someone’s model.
In our case, that would be the one developed by Colin Trainor and Constantinos Chappas, but others use it for expectation output from their models as well.

##### SOT – Shots on Target

Used in both player analytics and team stats, it often provides a better layer of accuracy for how effective (or ineffective) a team’s attack is than simple shot numbers.

##### SOTCON or SOTC – Shots on Target Conceded

The defensive side of Shots on Target.

##### ShAcc, Sh% – Shooting Accuracy

Percentage of total shots placed on target.

##### Pass% – Passing Accuracy

Usually given as a percentage.

    (Passes Attempted / Passes Completed ) * 100

or can simply be displayed as the two values `(xx/yy)`  

##### Sv% - Save% – Save Percent

Percentage of total shots that have been saved.

    ((Shots on Target - Goals) / Total Shots on Target ) * 100

##### PDO

“PDO is the sum of a teams shooting percentage (goals/shots on target) and its save percentage (saves/shots on target against). It treats each shot as having an equal chance of being scored – regardless of location, the shooter, or the identity or position of the ‘keeper and any defenders. Despite this obvious shortcoming it regresses heavily towards the mean – meaning that it has a large luck component. In fact, over the course of a Premiership season, the distance a teams PDO is from 1000 is ~60% luck.” - James Grayson

##### ToP%

Time on Pitch percentage. 

    The mins a player plays for their team / total potential minutes.
    
##### Total Potentinal Minutes

    Number of games team has played * 90 

On the assumption you'd only really do this at league level, remember to factor in extra time in some games if you are doing all competitions.

####Player Analytics Section

##### Per90 – p90, /90 or just Foo90

Normalization for time, usually used in player stats. Instead of dividing a player’s rate stat by games or appearances, you take all the minutes played and divide them into 90 minute chunks. Then take THAT number and use it as you would games played.

It’s useful in helping to extrapolate player production into more meaningful units. Ben Pugsley wrote a primer on this here.

##### NPG – Non-penalty Goals

A goal tally for a player after you strip out the penalty goals.

##### G90 – Goals Per90

A player or team goal tally divided into 90 minute chunks. We do this to normalize for actual time played, as it produces far more accurate rates of goal scoring than using appearances, starts, etc.

    goals / ( sum of minutes / 90 )

##### NPG90 – Non-Penalty Goals Per90

A player or team’s goal tally with all the penalties stripped out, divided into 90 minute chunks.

    non-penalty goals / (sum of minutes / 90)

##### A – Assists

Often written that way as part of a quick player stat summary.  Ex: Messi produced 46G/12A in the 2012-13 La Liga season.

##### A90 – Assists Per 90

    assists / (sum of minutes / 90)

##### G+A90 – Goals + Assists per 90

Used interchangeably sometimes with “scoring contribution.”  It’s a more complete way of measuring an individual player’s total offensive contribution than just looking at either G90 or A90 in a vacuum.

    (Goals + Assists) / (sum of minutes / 90)

##### Sh90 – Shots per 90

    Shots / (sum of minutes / 90)

##### SOT90 – Shots on Target per 90

    Shots on Target / (sum of minutes / 90)
    
##### PAdj Defensive Stats – Stands for Possession-Adjusted. 

Essentially, the problem with defensive rate stats is that you can’t make a tackle, interception, etc when your team has the ball. Thus teams that have a lot of the ball will have under-represented defensive output compared to a team with low possession. These types of stats attempt to adjust for opportunity, but as of June 30, 2014 are very new and still in development.

### Concepts Section

##### Defensive Shell

“A defensive shell is a tactical concept that refers when a team largely relinquishes their attacking intent and focuses on protecting the goal. (Also known as turtling.) Teams often do this after taking the lead in a match.”

##### Score Effects and/or Game State 

Benjamin Pugsley wrote a primer on this here and Sander Ijtsma (@11tegen11) has a number of strong pieces about it on his site, including this one on Game State and Conversion.

##### Pace or Shot Pace

Usually referring to the total number of shots taken in an average game, either by team or by league. It’s a proxy for looking at how quickly teams play.

Some teams/leagues exhibit high average paces (like the English Premier League) and some exhibit low ones. Teams also vary within those leagues.

As far as I know, this is the initial article that talked about this concept.

##### Zone Entries

A hockey concept that unfortunately requires infinite work to record manually. It examines how teams put the ball into the final third, and is thought to provide significant insight into team philosophy and attacking style.
