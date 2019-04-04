<!-- TITLE: Training Manual - Scoring Tab -->
The scoring tab can be used to set up scoring for points and categories across athletics meets and distance races, such as road and cross country.
# 1.1 Athletics Scoring
This is for athletics (Track & Field) meets so covers all disciplines of athletics. 

Firstly, choose the *Scoring* tab on the left hand side of the Manage screen. From here, click the *Scoring System* drop down and this will provide the options available. All of these have been prepared ad-hoc upon request. If the system you require is not listed here then please enquire to *support@opentrack.run* to see if we can implement the system you need.

*Track & Field Scoring Options*
![Athleticsscoring](/uploads/scoring/athleticsscoring.png "Athleticsscoring")

In this example, we have chosen *Welsh Indoor Intl (5-3-2-1)*, which was first used on 3rd March 2019 for the annual Wales V England U20s Indoor International event: 
https://data.opentrack.run/x/2019/GBR/waii/

*Welsh Indoor Intl*
![Welshscoring](/uploads/scoring/welshscoring.png "Welshscoring")

Once you have selected the Scoring system you want to use, click *Save*. 

With the Wales V England U20s Indoor International event, there are 2 teams competing with 2 athletes (per team) in each event. *Welsh Indoor Intl (5-3-2-1)* scoring system is defined as follows:
**Points**
5 = Winner
3 = Second
2 = Third
1 = Fourth
Bonus Point = Meeting Record Performance

Before any points can be allocated, you need to enter the *Teams* into the competition so the system knows they are to score. Head to the [Teams](/manuals/cms/teams-tab) tab and enter the relevant teams into the match competition.

In this example, we have a few guest clubs for will not be competing for points and England & Wales who will be - they have been entered into the match, as you can see by the code *WAII*.

*Teams Entered into a Match*
![Selectingteams](/uploads/scoring/selectingteams.png "Selectingteams")

The *A String* & *B String* relates to relays - England entered 2 teams into a relay event, whilst Wales only entered 1 - this field denotes what A & B String runners will wear on their vests. For all other events, competitors wear normal bib numbers (i.e. 1, 2, 3) and their club (England or Wales) is specified when the competitors enter. 

Below is an example of how this point scoring system works in the men's Shot Put. As you can see from the results below, England came 1st & 2nd, scoring them 5 & 3 points. Wales came 4th & 6th but the competitors in 3rd & 5th were not competing for clubs involved in the match, which means that Wales still come 3rd & 4th, scoring 2 & 1 points.

*Shot Put Results*
![Points](/uploads/scoring/points.png "Points")

However, as you can see from Lewis Byng's final throw, he beat the meeting record, which, in this scoring system, gains another point. This has to be done manually. Once looking at the results of the competition, click *Edit* or *Edit Results*. From the resulting screen, you will see a field named *Scoring overrides*. 

From here, you override the scoring for this event. In this example, England had 8 points. With the meeting record bonus points, they should have 9. In the *Scoring overrides* field, enter the club code and the new points, in the format as shown below:

*Scoring Override*
![Scoreoverride](/uploads/scoring/scoreoverride.png "Scoreoverride")

As you can see, this updates the Scores (as navigated to from the event homepage) to the override, giving England 9 & Wales 3 for this event:

*Scores Results*
![Athletics Scoring](/uploads/scoring/athletics-scoring.png "Athletics Scoring")

	# 1.1.2 Currently Implemented Scoring Methods & Explanations

The Scoring Methods that have have been designed and implemented already are as follows:

*  **No team scoring**
	* *Explanation*: This is the default option on this page and means there is no team scoring method within the competition.
	* *Example*: https://data.opentrack.run/x/2019/GBR/sx-sy-indoor/
*  **DNA: 12-10-8-6-4-2, one scorer per team**
	* *Explanation*: 
	* *Example*: https://data.opentrack.run/x/2018/BLR/dna3/
*  **8-7-6-5-4-3-2-1 based on position in final**
	* *Explanation*: 
	* *Example*:
*  **6-5-4-3-2-1 based on position in final**
	* *Explanation*: 
	* *Example*:
*  **British Athletic League, A and B string scorers**
	* *Explanation*: 
	* *Example*:
*  **Varsity, two scorers, 5-4-3-2**
	* *Explanation*: 
	* *Example*:
*  **Kinnard and Sward Trophy**
	* *Explanation*: 
	* *Example*:https://data.opentrack.run/x/2018/GBR/ks/
*  **European Cup 10,000m**
	* *Explanation*: 
	* *Example*: https://data.opentrack.run/x/2018/GBR/not/
*  **Loughborough Intl**
	* *Explanation*: 
	* *Example*: https://data.opentrack.run/x/2018/GBR/lia/
*  **Cyprus (6-5-4-3-2-1, all score)**
	* *Explanation*: 
	* *Example*:
*  **Balkan (8-7-6... 1, all score)**
	* *Explanation*: 
	* *Example*:
*  **Malta (15-14-13..., one scorer)**
	* *Explanation*: 
	* *Example*:
*  **Cyprus vs Greece (5-3-2-1, 5-2 relays)**
	* *Explanation*: 
	* *Example*:
*  **Turkish Super League (8-7-6-5-4-3-2-1)**
	* *Explanation*: 
	* *Example*: https://data.opentrack.run/x/2018/TUR/turkcell/
*  **British / Irish Masters Overall Scores**
	* *Explanation*: 
	* *Example*:
*  **Welsh Indoor Intl (5-3-2-1)**
	* *Explanation*: Four points scorers within each event. Awarded 5 for 1st, 3 for 2nd, 2 for 3rd and 1 for 4th. Meeting records secure bonus points which are input manually. See above for explanation on how.
	* *Example*: https://data.opentrack.run/x/2019/GBR/waii/

# 1.2 Distance Scoring
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

