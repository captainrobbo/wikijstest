<!-- TITLE: Relays -->
<!-- SUBTITLE: How to set up Relays and input their results -->

# Setting up relay teams
Relays are complicated.  A Relay Team is not necessarily the same as a team contesting the match.   Sometimes each club has one team, and that's simple.  But sometimes we have, for example, England A and England B.  And sometimes runners just want to practice, and make up teams to fill out the track, so we effectively have guest teams.

The first step is to set up the teams in the match.  Go to Manage Teams.  There should already be an automatically created team for each club that has entered the match through our Team Entry system.  You can also manually create teams, and tell it whether they correspond to real clubs, or countries, or are something temporary.   You can if you wish re-use a guest team across events - e.g. you might have GST1 and GST2 to allow for up to two guest teams in any relay.  click [test](/manuals/cms/events)

## A and B teams

If you just have one team for each club, just make sure the team is declared - leave the A and B fields blank.  If you have A and B relay teams for a team, such as in the example below, you need to choose a bib number to identify them.  This should NOT clash with the id of any human competitor!  You can click on a team and edit this.  In this example, a Wales/England match with guest teams, England has bibs ENG1 and ENG2 assigned, and Wales has WAL1 and WAL2.  This would normally be the number on their chest.  We also have two club with A and B teams, and a club which doesn't.

![Waii Relay Teams](/uploads/track-results/waii-relay-teams.png "Waii Relay Teams")

## Ad-hoc and non-scoring teams
Team Entries have a *match* field.  If left blank, they are non-scoring.   When we plan for joint divisions - *not done yet* - you can add D1 or D2 to show which division they compete in for scoring purposes.
At the Loughborough International, we had proper teams contesting the match, and we also had a number of relay teams thrown together shortly before the match.  The organisers therefore set up some extra match teams, named IND1 to IND9, for individuals.  At club level, you might ask the runners to make up a code and name.  Below we show an example.
![Teams 2](/uploads/track-results/teams-2.png "Teams 2")


It is important to clear or empty the *Match* field, which will remove them from any scores.  Otherwise, you'd end up with the scoring reports showing an extra club doing rather badly, as it scored zero in all other events.  This shows the team-editing dialog:

# Setting up lanes and start lists
Navigate to the event, and look for the *By Lane* button.  This lets you input relay teams.  Pre-race, you will want to input the bib number, and (for track relays) the lane number.  On saving, it will re-order the data so lane one is first, and it will fill in the team name.  The start list will now be displayed to the public.
![Relay Input 1](/uploads/track-results/relay-input-1.png "Relay Input 1")

If you know the runner names at this stage (and often, we do not until after the race), you can input the runners' bib numbers separated by commas, like this:
![Relay Runner Input](/uploads/track-results/relay-runner-input.png "Relay Runner Input")

The names will be filled in for you when you save.  Our system checks that you have four valid bibs (or however many relay legs there are), corresponding to actual competitors; if this is not so, all 4 will disappear.

# Inputting results
There are two web forms for results input. *By Lane* will not necessarily be in time order, but will show all teams set up.  *Edit* looks almost identical, but it only shows relay results with a time assigned to them - it is more useful for inputting the results of road or cross-country relays with many teams, when you always go winner first and might be pasting from a long spreadsheet.  The picture below shows the form after saving once, with all the team and runner names filled in for you.
![Relay Input 3](/uploads/track-results/relay-input-3.png "Relay Input after saving")

## Runner names after the event
Sometimes you don't know who ran until later - especially if athletes swap legs and reserves in the warmup. You can fill in the runners column at any time, with a comma-separated list of bibs.  You MUST have the right number of bibs and they must match competitors - for a four-person relay, it is not possible to input 3 bibs.  See the picture above.

## Splits
Splits are optional and can, again, be added later.  We need *split times*, i.e. *cumulative* - and not *lap times*.  Input one less than the number of legs.  Thus, for a 4x100 where everybody ran 11sec, the input would look like "11.0,22.0,33.0" - we subtract from the final time to get the last leg time.  These will appear to the public on a separate tab.
![Waii Relay Splits](/uploads/track-results/waii-relay-splits.png "Relay Splits example")
# Display of results


