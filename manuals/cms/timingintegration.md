<!-- TITLE: Training Manual - Results Recording - Track Events -->

# 1.1 Introduction
There are two methods of recording results are track events - simply put they are automatic and manual results input. However, both are relatively fast and provide minimal work for officials. 
# 1.2 Automatic Results Input - Timing Integration
The purpose of the Timing Integration management screen is to allow the meeting organiser to synchronise OpenTrack's system with the PhotoFinish technology being used for the competition. One of the major benefits of this is that it really limits the work required for the meeting organiser and PhotoFinish engineer and also enables quick-to-view results (unofficial until marked otherwise) for athletes and spectators.

Currently, as of 5th February 2019, integration has been completed for two of the major system's: FinishLynx & MacFinish/TimeTronics. More systems will be added with time and the manual and Competition Management both updated. 

	# 1.22 Set-Up
From the Competition Management screen of the meeting in question, choose *Timing Integration* on the options panel running down the left of the screen. The screen that loads will show you the available options that can currently be synchronised with. Simply click the relevant one. In this instance we are choosing *FinishLynx.* All PhotoFinish technology will synchronise the same way with OpenTrack.

*Timing-Integration Selection*
![Select Tech](/uploads/timing-integration/select-tech.png "Select Tech")

Once you have clicked FinishLynx, you will be shown the following screen. If this is the first time you are following this procedure, you will need to download the synchronisation program. To do this click the button we have highlighted in red labelled *Latest EXE file*. 

*Downloading the Integration software*
![Finishlynx](/uploads/timing-integration/finishlynx.png "Finishlynx")

Some computers will bring up a security alert when attempting to download the software. Please disregard this and download it anyway. Depending on your machine, you may need to click *More Info* followed by *Run anyway*. This error occurs as the software has not yet been used many times and so Windows is not aware of it and creates a warning message. We can assure you it is safe to use. Once it is downloaded, please install and open it.

If you have already been through this process previously, the program will be installed on your PC so simply locate and open it. 

	# 1.23  Synchronisation
Once the software has been downloaded, you can begin to enter the information to synchronise OpenTrack with FinishLynx. 

*System Synchronisation*
![Exe 2](/uploads/timing-integration/exe-2.png "Exe 2")

Follow the instructions on the program to synchronise the Competition Management System with FinishLynx. 

1. **Mode**: Ensure mode is set to the system you are using, in this example *FinishLynx*. 
2. **Folder**: Click browse and navigate to and select the folder that the resulting *.lif* files will be saved when created from the FinishLynx system.
3. **URL**: Set the URL to the competition URL. Simply copy and paste from the URL at the top of page. Ensure you leave out */manage/timing/*
4. **Email**: The email address that you use to log in data.opentrack.run. 
5. **Password**: The password for the above email address.

Once the fields are correct, they will turn green. If anything is incorrect, they will remain red. 

Once everything is green:
6. Click the button that reads *"Click to download lynx.ppl & lynx.evt files"*. This will download the competitor and event files. 
7. Now click the button that reads *"Click to begin uploading"*. 

Once steps 1 to 7 are completed the system now looks to the folder in step 2 every few seconds. Whenever a .lif file is saved into the folder at at the end of each race the program picks this up and automatically uploads it to the front end of the competition, ready for athletes and spectators to view. This means that results are available to view just a few seconds after the event has finished. The results are marked as unofficial until manually changed by the Race Director.

# 1.3 Manual Results Input - Post Race
If your competition does not have PhotoFinish or, for whatever reason, you are unable to synchronise the PhotoFinish system to OpenTrack, then you are still able to input data from your races onto the OpenTrack website to show results. This is still a very quick process but it will not be immediate after the race has finished. The method is similar to the Field results input when not doing live recording. 

As with most recording input screens, from your Competition homepage, click *Start Lists / Results*. From the resulting screen, choose the event in question. In this example we have selected a 200m race. Once you have clicked your event, you will be presented with the screen below. In this race, the competitors have already been seeded, which is why they are showing. If you wish to seed your athletes click here to learn how. Alternatively, if you do not care about the lane order, click the blue *Fetch Start List* button at the top right. 

*Competitor List - Seeded*
![Click Edit](/uploads/track-results/click-edit.png "Click Edit")

Once you have a list of athletes showing in the event, you can click *Edit* or *By Lane*. *By Lane* is often used for track races, from 60m up to 400m where they are lane based. It is easy to edit results if they are given to you in lane order. The other option of *Edit* gives you the option to input results in finishing order. In this example we have clicked *Edit* (ironically with a 100m race). This will give you the following screen. 

*Editing Screen*
![Edit Screen](/uploads/track-results/edit-screen.png "Edit Screen")

This is screen where the results are input. We have highlighted the section that needs to be completed. The grid works the same as an Excel spreadsheet so if your results are in this format then they can be simply copied and pasted in. Alternatively, just type them in.

*Results Input*
![Paste Results](/uploads/track-results/paste-results.png "Paste Results")

The only columns that need to be completed are *"Bib"* and *"Performance"*. From the Competitor list when "managing" the competition, the system knows which bib number matches which athlete so name is not necessary to input. 

Performance must be input in the following format:
9.58
58.5
63.5
1:03.5 - equivalent to 63.5, first digit assumed to be minutes
2:03 - assumed to be an 800m time of 2 minutes, and not a Marathon, because only one colon
2:02:57 - a marathon time, two colons so contains hours
73:15 - a half marathon time, equivalent to 1:03:15

If you are an ultrarunners, you will need to count up the hours!

Once you input the *"Bib"* and *"Performance"*, click *Save* (either bottom left or bottom right). You will see the order autocomplete.

It is possible to view more information from this screen. As you can see below, by checking the box marked *Show Athlete Details* you can view the competitor names, category and club. 

*Results Details*
![Wind Speed](/uploads/track-results/wind-speed.png "Wind Speed")

Furthermore, as seen above, should you be editing an event that warrants it, you can input a wind speed that will show on the *Results* page. 

Clicking the event title at the top of the page (in blue) it will take you to the Results page of the event. The image below shows the screen as someone who has access privileges will view it. 

*Results*
![Results](/uploads/track-results/results.png "Results")
 To make further changes, click the *Edit Results* button on the right. 
