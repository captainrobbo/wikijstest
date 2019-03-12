<!-- TITLE: Scoring Tab -->

The scoring tab can be used to set up scoring for points and categories across athletics meets and distance races, such as road and cross country.  These are implemented in two different ways which we call *Athletics* or *Distance* scoring respectively
# 1.1 Athletics Scoring
*Athletics scoring* involves adding up points across many different events in an athletics meeting.  

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

Before any points can be allocated, you need to enter the *Teams* into the competition so the system knows they are to score. Head to the *Teams* tab and enter the relevant teams into the match competition. Click here to learn how.

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

The Scoring Methods that have have been designed and implemented already are listed below.  There are an infinite variety, but most are variations on "points for positions".   A

If you need another system, please contact as well in advance and we will try to add it.

### No team scoring
This is the default for any open meeting or championship.  No scores page will be visible.

###  8-7-6-5-4-3-2-1 based on position in final
###  6-5-4-3-2-1- based on position in final
These are typically for 8-club or 6-club matches.  

###  British Athletic League, A and B string scorers


###  Varsity, two scorers, 5-4-3-2
This was first used for the Welsh Indoor Varsity between Cardiff Metropolitan and Birmingham universities.

###  Kinnaird and Sward Trophy
This is an inter-club meeting held in April each year in South West London.  Six clubs participate, with up to two designated scorers each.  In sprints, there will be designated A and B scorers in different races; in distance races, the first of the pair is the A runner and gets most points.  However, guests may also take part in any race.

###  European Cup 10,000m
This uses the "sum of times" method.   The first 3 finishers from each country have their times totalled.  However, there are A and B races for both men and women, and we have to look at both.

### Loughborough Intl
This is an early-season match in the UK with many years' history, and was the first major delivery of our competition management system.  [Here's the match](https://data.opentrack.run/x/2018/GBR/lia/).  There are 6 teams scoring 6-5-4-3-2-1 according to position, but with double the points for relays.

### Cyprus (6-5-4-3-2-1, all score)
### Balkan (8-7-6... 1, all score)
###  Malta (15-14-13..., one scorer) 
These three competitions are unusual in that we don't limit the number of scorers per team.  So if one club from Cyprus took the first six places in one event, they would get 21 points.

### Cyprus vs Greece (5-3-2-1, 5-2 relays)
This is an annual match held betyeen the two countries.  There are two scorers per team, with special scoring for relays.


### Turkish Super League (8-7-6-5-4-3-2-1)
Turkey has a popular league structure similar to the UK, or to a football league.  The Super League contains the top clubs.  We were honoured to do live tesults in 2019 from the League final which came down to a one-point difference.


###  British / Irish Masters Overall Scores
This is an unusual one.  There is an annual cross-country match for England, Ireland, Scotland and Wales, split into several distance races.  Within this there are matches in every single 5-year age group, scored using *Distance Scoring* below.  However, we also need to know which country was the most successful across all age groups.  This was therefore listed under "athletics scoring", and works by adding up all the *distance scoring* tables.


###  Welsh Indoor Intl (5-3-2-1)**
This was a Wales versus England match held on 3 March 2019 and presented live on OpenTrack.


# 1.2 Distance Scoring
In *Distance Scoring*, we typically have many runners of different categories in one race (or maybe in a few races).  We *filter* the successful finishers, typically extracting one age group or category, then sort them into teams and give points to the teams.  

The system works by defining a number of *scoring tables*.  Each of these can be configured to filter in several ways - by category, or club, or event - and then to total in a certain way.   The UK has a lot of cross-country, and we are cross-country runners, and in our experience this covers most of the scoring systems in common use.

(to be completed)



