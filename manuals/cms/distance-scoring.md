<!-- TITLE: Training Manual - Scoring Tab -->

The scoring tab can be used to set up scoring for points and categories across athletics meets and distance races, such as road and cross country.
# Distance Scoring
## Concepts
The *Distance Scoring* feature is used for *team scoring* in running events, usually outside of the track, such as X-Country and road races. The basic concept is to filter a (possibly large) race and apply a scoring system to a sub-group of the runners. 
You do this by defining the *Scoring Tables* you wish to display.  Each of these becomes a web page you can link to.  So, for example, within a race of several hundred athletes, you can have multiple matches going on such as...
* Men's or women's team of N runners
* Mob matches where almost every runner counts
* Age group competitions (e.g. M40/M45 team prize)
* Age graded virtual team competitions, which engage everybody
* A two-club match within a much larger race

Scoring happens instantly - it's just a report on the data, calculated as people look at it.

We make available a number of reports including a web page on each scoring table, and a PDF awards summary which can be read out by commentators, or pinned up or circulated.  We also try hard to 'show the working' so those who wish can check.

We believe this covers most common scoring systems in current use.

There are three broad steps:  
1. You define who it applies to  (filter by age, gender, team)
2. You choose a *summation (totaling) method* - one of *scoring position*, *absolute position*, *sum of times* (popular in big road races and Euro 10k), or *age graded* (first place is the highest age grade, not the actual winner) 
3. You set various options such as number of scorers, and whether to allow (and penalize) incomplete teams

The system takes account of people running outside their natural age category, if the meeting organiser allows this and sets the team age group.  So, we can handle veterans' down-aging, and talented juniors moving up an age-group.

We hope that this handle most popular needs, but if you need a custom situation, please do let us know about it.  We're happy to implement anything of reasomably general use.




## How to use it
Once on the *Scoring* tab, choose *Distance Scoring*. If this is the first time you are looking at this screen for the event you are managing, then it will be blank. If you need to add a new scoring method, click *New* in the bottom right corner:

*Distance Scoring*
![Distancescoring](/uploads/scoring/distancescoring.png "Distancescoring")

Once you have clicked *New*, you will be presented with the following screen:

*Distance Scoring Implementation Page*
![Newdistancescoring](/uploads/scoring/newdistancescoring.png "Newdistancescoring")

Fill in the fields as follows:
**Event**: Choose the relevant event within your competition that you want to implement a scoring method for. 

**Name**: Choose the name of your category. For example, if this was a X-Country event with 4 races, this could be Open Race 1 W35-W44. So this would be implementating a scoring system for females in the 35-44 age group category within race 1.  The name is used to calculate a friendly *slug* or URL component, so the page for this scoring table would be *<competition>/scores/open-race-1-w35-w45*

**Subtitle**: This is another user-defined field that appears underneath the **Name** of the event when viewing the results. It is purely descriptive.

**Filter categories**: Choose the categories (user-defined when loading in *Events* and *Competitors*) that this scoring system will affect. Based on the **Name** of the system above, this would be W35 & W40, meaning any female competitors between age of 35 and 44 (before they hit W45 age group).   If you want a category for 'men over 50', you'll have to enter a list like **M50,M55,M60,M65,M70** up to the oldest age you expect

**Filter genders**: Choose from the drop-down which gender you want the scoring to affect. In this example, we would choose Ladies, as it is only for Women (W35-W44).  It is not necessary to complete this box if you have a category filter, as categories usually specify male or female.

**Filter teams**: Manually type the teams you want the scoring to affect, separated by a comma (e.g. BEL,THH,HHH). If you want it to affect all teams, just leave it blank.  This lets you do an internal club championship report, or a dual match within a bigger road race.   Note that if you have guests within an inter-club match, but not enough to make a scoring team, you can leave it blank.  For example, in a six-to-score match with two guests from another club, the guests would not count as a team.  

**Method**: Choose from the available drop-downs:

*Sum of filtered race positions*: Athletes outside a scoring team (non-scorers) are not included in positions/points. For example, if an athlete comes 75th and there are 10 non scorers in front of them, they score  65 points.  This is commonly called the *university method* in the UK

*Sum of absolute race positions*: Regardless of whether athletes are scoring or not, they are included in the points calculation. For example, if an athlete comes 295th they score 295 points regardless of whether there are non-scorers in front of them or not.  This is common in schools races (do you remember the old brass numbered tokens the teacher used to add up), and the English Southern and National, as it was too complex to eliminate non-scorers in the old days.

*Sum of times*: Cumulative times by the number of finishers/scorers per team.   For example, best 3 times is used for the inter-club prize at the London Marathon; and also at the European Championships 10,000

*Sum of age grades*: This is a new one, which we think may appeal to add interest to club races.  We produce a listing by best age grade, NOT by time, and then we apply scores by position to this.  So you can have a 'best age graded team' where every club member counts, without the hassle of having lots of possibly-incomplete teams in different age groups. If someone does not have a date of birth then they ignored in the results for this scoring method.


**Teams per club**: Choose from the available drop-downs:
*One team per club*: Choose this if you are only going to have one competing team for each club. 
*A and B teams only*: Choose this if you are going to have two teams in each club. For example, if you have a XC race and it is 4 to score per team, you could have an A & B team per club. This will impact scoring further down the field if you choose *Sum of filtered race positions* as your method.   Teams get suffixes A, B on the results.
*Any number of teams*:As above but you can have any number of teams per club until you run out of athletes so no-one would be a non-scorer, unless there are incomplete teams (that are not allowed).

**Allow non-scorers**: Tick this if you want non-scorers to impact upon the calculation of places. For example, if you choose a position based scoring method and a non-scorer finished 23rd and scorer is 24th, do you want the scorer to be scored as 23rd or 24th? 

**Scorers**:Type the maximum number of scorers that are to score in a team.

**Allow incomplete teams**:Tick this if incomplete teams (position based scoring methods) are still allowed to score.  You may then end up with teams "padded" with Penalty Score.  By default, we give a score one greater than the number of runners; so if the last scorer got 90 points, any incomplete team gets 91 points per missing runner.  It is not applicable to age-graded or sum-of-times scoring.


Once you have completed the fields, click *Save*. Currently (12th March 2019) you need to complete this input for every race and category you want to implement so if there are multiple categories it could take a while. If you want to edit a field then just click on the specific Scoring field and it will bring up the above options to edit.

If you have results in already, click *View Table* to see the results. Click *Back* to see your list of saved scoring methods. As you can see below, this example competition had multiple scoring implemented:

*Saved Scoring Systems*
![Distancescoringsaved](/uploads/scoring/distancescoringsaved.png "Distancescoringsaved")

Once you have completed inputting all your scoring methods and your races have finished, you can see the Scores results. Navigate to the homepage of the competition and choose *Scores*. From here you will see the available Category fields:

*Scoring Categories*
![Categoryawards](/uploads/scoring/categoryawards.png "Categoryawards")

Below you can see examples of different scoring method outputs. These are all calculated from same competition - British & Irish Masters Cross Country International - with the same age group of M50 to easily compare the scoring methods.

*Sum of filtered race positions*
![Filteredpositions](/uploads/scoring/filteredpositions.png "Filteredpositions")

*Sum of absolute race positions*
![Absolutepositions](/uploads/scoring/absolutepositions.png "Absolutepositions")

*Sum of times*
![Sumoftimes](/uploads/scoring/sumoftimes.png "Sumoftimes")

*Sum of age grades*

Finally, this is the PDF showing the Awards Summary Output created from all the implemented scoring methods.
