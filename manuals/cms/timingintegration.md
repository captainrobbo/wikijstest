<!-- TITLE: Training Manual - Results Recording - Track Events -->

# 1.1 Timing Integration
The purpose of the Timing Integration management screen is to allow the meeting organiser to synchronise OpenTrack's system with the PhotoFinish technology being used for the competition. One of the major benefits of this is that it really limits the work required for the meeting organiser and PhotoFinish engineer and also enables quick-to-view results (unofficial until marked otherwise) for athletes and spectators.

Currently, as of 5th February 2019, integration has been completed for two of the major system's: FinishLynx & MacFinish/TimeTronics. More systems will be added with time and the manual and Competition Management both updated. 

	# 1.12 Set-Up
From the Competition Management screen of the meeting in question, choose *Timing Integration* on the options panel running down the left of the screen. The screen that loads will show you the available options that can currently be synchronised with. Simply click the relevant one. In this instance we are choosing *FinishLynx.* All PhotoFinish technology will synchronise the same way with OpenTrack.

*Timing-Integration Selection*
![Select Tech](/uploads/timing-integration/select-tech.png "Select Tech")

Once you have clicked FinishLynx, you will be shown the following screen. If this is the first time you are following this procedure, you will need to download the synchronisation program. To do this click the button we have highlighted in red labelled *Latest EXE file*. 

*Downloading the Integration software*
![Finishlynx](/uploads/timing-integration/finishlynx.png "Finishlynx")

Some computers will bring up a security alert when attempting to download the software. Please disregard this and download it anyway. Depending on your machine, you may need to click *More Info* followed by *Run anyway*. This error occurs as the software has not yet been used many times and so Windows is not aware of it and creates a warning message. We can assure you it is safe to use. Once it is downloaded, please install and open it.

If you have already been through this process previously, the program will be installed on your PC so simply locate and open it. 

	# 1.13  Synchronisation
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

# 1.2 Results Input - Post Race
If your competition does not have PhotoFinish or, for whatever reason, you are unable to synchronise the PhotoFinish system to OpenTrack, then you are still able to input data from your races onto the OpenTrack website to show results. This is still a very quick process but it will not be immediate after the race has finished. The method is similar to the Field results input when not doing live recording. 

As with most recording input screens, from your Competition homepage, click *Start Lists / Results*. From the resulting screen, choose the event in question. In this example we have selected a 200m race. Once you have clicked your event, you will be presented with the screen below. In this race, the competitors have already been seeded, which is why they are showing. If you wish to seed your athletes click here to learn how. Alternatively, if you do not care about the lane order, click the blue *Fetch Start List* button at the top right. 

*Competitor List - Seeded*
![Click Edit](/uploads/track-results/click-edit.png "Click Edit")

