<!-- TITLE: Training Manual - Scoring Tab -->

The scoring tab can be used to set up scoring for points and categories across athletics meets and distance races, such as road and cross country.
# Distance Scoring
The *Distance Scoring* feature is used for running events, usually outside of the track, such as X-Country and road races. 

Once on the *Scoring* tab, choose *Distance Scoring*. If this is the first time you are looking at this screen for the event you are managing, then it will be blank. If you need to add a new scoring method, click *New* in the bottom right corner:

*Distance Scoring*
![Distancescoring](/uploads/scoring/distancescoring.png "Distancescoring")

Once you have clicked *New*, you will be presented with the following screen:

*Distance Scoring Implementation Page*
![Distancescoringpage](/uploads/scoring/distancescoringpage.png "Distancescoringpage")

Fill in the fields as follows:
**Event**: Choose the relevant event within your competition that you want to implement a scoring method for. 
**Name**: Choose the name of your category. For example, if this was a X-Country event with 4 races, this could be Open Race 1 W35-W44. So this would be implementating a scoring system for females in the 35-44 age group category within race 1.
**Subtitle**: This is another user-defined field that appears underneath the **Name** of the event when viewing the results. 
**Filter categories**: Choose the categories (user-defined when loading in *Events* and *Competitors*) that this scoring system will affect. Based on the **Name** of the system above, this would be W35 & W40, meaning any female competitors between age of 35 and 44 (before they hit W45 age group).  
**Filter genders**: Choose from the drop-down which gender you want the scoring to affect. In this example, we would choose Ladies, as it is only for Women (W35-W44).
**Filter teams**: Manually type the teams you want the scoring to affect, separated by a comma (e.g. BEL,THH,HHH). If you want it to affect all teams, just leave it blank.
**Method**: Choose from the available drop-downs:
*Sum of filtered race positions*: Athletes outside a scoring team (non-scorers) are not included in positions/points. For example, if an athlete comes 75th and there are 10 non scorers in front of them, they score  65 points.
*Sum of absolute race positions*: Regardless of whether athletes are scoring or not, they are included in the points calculation. For example, if an athlete comes 295th they score 295 points regardless of whether there are non-scorers in front of them or not.
*Mob match, scorers = smallest team, eliminating non-scorers*:
*Sum of times*: Cumulative times by the number of finishers/scorers per team
*Sum of age grades*: 
*No teams, just filtered individuals*:
**Allow non-scorers**: Tick this if you want non-scorers to impact upon the calculation of places. For example, if you choose a position based scoring method and a non-scorer finished 23rd and scorer is 24th, do you want the scorer to be scored as 23rd or 24th? 
**Scorers**:Type the maximum number of scorers that are to score in a team.
**Allow incomplete teams**:Tick this if incomplete teams (position based scoring methods) are still allowed to score.
**penalty**: Type the position penalty for incomplete teams. It is per competitor. 

Once you have completed the fields, click *Save*. Currently (12th March 2019) you need to complete this input for every race and category you want to implement so if there are multiple categories it could take a while. 

If you have results in already, click *View Table* to see the results. Click *Back* to see your list of saved scoring methods. As you can see below, this example competition had multiple scoring implemented:

*Saved Scoring Systems*
![Distancescoringsaved](/uploads/scoring/distancescoringsaved.png "Distancescoringsaved")

Once you have completed inputting all your scoring methods and your races have finished, you can see the Scores results. Navigate to the homepage of the competition and choose *Scores*. From here you will see the available Category fields:

*Scoring Categories*
![Categoryawards](/uploads/scoring/categoryawards.png "Categoryawards")

Either click on a specific field or scroll down to see them in a long list.

*Scoring Results for M35*
![Categoryawardsm 35](/uploads/scoring/categoryawardsm-35.png "Categoryawardsm 35")

