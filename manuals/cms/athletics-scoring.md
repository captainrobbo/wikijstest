<!-- TITLE: Training Manual - Scoring Tab -->
The scoring tab can be used to set up scoring for points and categories across athletics meets and distance races, such as road and cross country.
# Athletics Scoring
This is for athletics (Track & Field) meets so covers all disciplines of athletics. 

Firstly, choose the *Scoring* tab on the left hand side of the Manage screen. From here, click the *Scoring System* drop down and this will provide the options available. All of these have been prepared ad-hoc upon request. If the system you require is not listed here then please enquire to *support@opentrack.run* to see if we can implement the system you need.

*Track & Field Scoring Options*
![T Fscoring](/uploads/scoring/t-fscoring.png "T Fscoring")

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
*  **Welsh League (winner points = 2 x Num teams, B string = 1x)**
	* *Explanation*: Points are scored per age group and then all are added up at the end of the event to provide an overall score as well as per age group. Age groups include U17, U20 and SEN (Masters age groups are included with the seniors). Points scored are defined by the number of teams in the event. Each team can have an A & B string scorer. The A string scorer receives double points per position based on number of teams, whilst B scorer gets 1 times. For example if you have 10 teams and your A String winner comes 3rd they will receive 16 points (1st gets 20, 2nd gets 18, etc etc). A 3rd place B string would get 8 (4th gets 7, 5th gets 6). 
	* *Example*:
*  **Bosnian (winner points = number of teams**
	* *Explanation*: Points are defined by the number of teams in the event. If you have 16 teams, 1st place in an event would get 16 points, with 16th place receiving 1 point and everything inbetween.
	* *Example*: 