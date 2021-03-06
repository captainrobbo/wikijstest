<!-- TITLE: Training Manual - Events Tab-->

The events tab is, as you would expect, the place to create all the events that your competition is going to host.
# 1.1 Entering Events
The entry method is set up as a simple grid table meaning you can create a spreadsheet and simply copy and paste it in. Simply head to the Events tab and either paste in your events or type them in.

*Events Table*
![Event Tab](/uploads/events/event-tab.png "Event Tab")

The columns are defined and must be completed as follows:
**Num**: Each event must be given an Event ID. It can be numeric, text or a combination of both but it **must** be unique. Most simple is to just label them in ascending order.
**Event Code**: Events must be input in a standardised format, i.e. they must comply to the OpenTrack/EA data standard. 
**Age Groups**: Here you enter the age group(s) the event is available for. If it is available to everyone then “ALL” is written. If there are limitations then use codes such as U15,U17,V40,V50, etc. If there are multiple age groups, then they are separated by a comma without spaces.
**Gender**: The standard codes of M or F denote male or female, regardless of age (i.e. B & G do not exist). MF is for both.
**Category**: This is user-defined and can whatever the you want. For example, an event can be listed as “Junior”, “JM”, “Wheelchair”, etc. It will default to a combination of *Age Groups* and *Gender* if left blank.
**Limit**: This field limits the number of participants that can be in each event. It denotes the number of entries per event.
**Name**: This field is user-defined. It will usually just be the name of the event. For example, HJ becomes High Jump. However, it can also be whatever the organiser wants it to be displayed as in their competition event list, i.e. High Jump – Female, or perhaps to denote an age group.

**PLEASE NOTE: If using PhotoFinish then ensure that there are no overlaps in your start times. If you have multiple rounds then the system will automatically generate a sensible gap between them. So, for example, 1500m races are given a 7 minute gap - if you have five 1500m races and the first is at 17:00 then the following races will be at 17:07, 17:14 etc. (Obviously once the race happens then PhotoFinish will update this with the actual time). The important thing to bear in mind is that the final heat (i.e. 17:28) is not before the scheduled start of the next event - this will create errors with PhotoFinish. The next track event must have a scheduled start of after 17:28.**

**Rounds**: This column dictates the structure of the event and denotes whether there will be just one race or heats and finals. The example given in the screenshot above shows that most events have one round but the male 100m has 4 heats, 2 semi-finals and 1 final. They are separated by commas (no spaces). The example in the above screenshot would suggest 4 heats (8 competitors in each), 2 semi-finals (8 again), 1 final (8 again). When your event has rounds, you edit the *Advanced Configuration* to specify further details. 
**Day**: This field dictates what day of the competition the event takes place in. If the competition is just one day, then “1” is put for all events. If your event takes place over multiple days (e.g. 100m in the example screenshot) put the day of the first event/discipline. 
**Time**: This follows the structure of the timetable of your competition. Times are entered in 24hour format, i.e. 13:15. As with the day, if your event takes place over multiple days (e.g. 100m in the example screenshot) put the day of the first event/discipline. 
**Parent**: This final column is for multi-eventers, i.e. heptathletes pentathletes and decathletes. For these, enter all events within the decathlon as the same number, as with the example below.

**Currently (16th April 2019) we do not have a re-number event button so please do not do this once events and competitors have been loaded in. It is fine to edit Start Times but not Event Numbers!**

*Multi-Event Competitions*
![Multievent](/uploads/events/multievent.png "Multievent")
# 1.2 Advanced Configuration
When your event has rounds, you edit the *Advanced Configuration* to specify further details. 

If you scroll to the bottom of the *Events Grid* then you will find the *Advanced Configuration* options available. This is for for events with multiple rounds or heats. Click on the event that you wish to edit. In the example below we have chosen Male 100m.

*Events - Advanced Configuration*
![Event Adv](/uploads/events/event-adv.png "Event Adv")

Complete the fields as follows:
**name**: This will be auto-filled with whatever you called the competition in the grid above.
**rounds**: This will be autofilled with however you defined the rounds in the grid above.
**day**: This will be autofilled with whichever day of the competition you listed as the first day of this event in the grid above. 
**r1_time**: This will be autofilled with whatever time you stipulated as the first round taking place in the grid above. 
**r2_day**: Type which day round two will take place on.
**r2_time**: Type which time round two will start. Use a 24 hour format. For example, 13:25. 
**r3_day**: Type which day round three will take place on.
**r3_time**: Type which time round three will start. Use a 24 hour format. For example, 13:25. 
*N.B.*: the *"r_day"* and *"r_time"* options will repeat as necessary accoring to **rounds**.
**max_per_heat**: Type the maximum number of athletes allowed/possible in each heat.
**Seeding method**: Choose which method of seeding (from the options available) you want for this event. **This is for track events.**
**cut_after_round**: Input after which round competitors will be cut. **This is for field events only. For example, typically in Long Jump, competitors will cut cut after 3 jumps (i.e. 3 rounds).**
**cut_survivors**: Input how many athletes continue after the cut. **This is for field events only.** 
**Team Types**:  Select from one of the three options available. Ad-hoc teams means teams that will be created purely for your event on a one-off occasion. For example, a pub or work colleagues team.
**Record text**: Type the details of the record - i.e. Name, Location, Year, Natinality - it is up to you. This will appear on the homepage of the event - you also need to complete the *Record performance* box for it to appear.
**Record performance**: Type the details of the record - i.e. 18.02m. This will appear on the homepage of the event - you also need to complete the *Record text* box for it to appear.
**Minimum performance**:
**Maximum performance**:


***N.B. Currently, progression from heats to finals must be done manually.***

When finished, click the blue *Save* button at the bottom right of the page. 

# 1.3 Practice
If you want to have a practice at inputting events then use our Demo competition that can be found at the following link:

https://data.opentrack.run/x/2018/GBR/ot_demo/

Email *support@opentrack.run* for access.
