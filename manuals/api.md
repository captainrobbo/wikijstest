<!-- TITLE: API Documentation -->
<!-- SUBTITLE: For software developers -->

This page describes APIs for developers.

# Uploading competition results
OpenTrack can accept a description of a competition in JSON format.  The format is pretty much the same as the one available for downloading.  This is the preferred way for Federations to submit data form national systems; it will end up published as Open Data, and we will notify IAAF and European Athletics that it is available.

However, we are quite demanding; the data must be correct and complete, will full series of throws or jumps.

To use the upload API, you need to contact OpenTrack and arrange credentials.  We will carefully check the first few uploads; the number of people/federations sending us this day is very small, so we're happy to pro.

## Test Harness
A test harness is available at http://data.opentrack.run/x/create.  This lets you validate JSON packets simply by copying and pasting, and also has basic instructions
![Upload Harness](/uploads/upload-harness.png "Upload Harness")

## API for creation
The actual request should be a POST to [/x/api/create/](https://test-data.opentrack.run/x/api/create].  It can be multipart-form-encoded using parameters *data=<json>*, like the demo web form; or you can send the raw JSON as the POST body.


# Downloading competition data

OpenTrack believes that, as far as possible, Athletics Data should be open data and freely available. The only exception to this is dates of birth; generally, APIs will give the age of the competitor, unless you are logged in as an authorised director of that competition, a national federation or an approved statistician. 

You can therefore download data from any competition at any stage in its lifecycle:  
* Calendar entries only saying what/where when
* Entries - when people or teams have stated their intent to enter.  The programme of events is usually available at this stage
* Start lists - after seeding and detailed planning
* Results - when the competition is in progress or finished.

The format is always the same, what we call the OpenTrack-Lite competition schema.  The easiest way to understand this is simply by looking at URLs in your browser.  These are made by suffixing 'json' to URLs specific to the competition.  AS an example, we will take the Wales / England Indoor International in March 2019.  You can browse it here:
	https://data.opentrack.run/x/2019/GBR/waii/


The following URLs can be clicked on and browsed:
* [Full Competition Description](https://data.opentrack.run/x/2019/GBR/waii/json/) (this takes a few seconds to generate)	
* [Match Scores](https://data.opentrack.run/x/2019/GBR/waii/scores/json/) - only if there is team scoring)	
* [Single Event](https://data.opentrack.run/x/2019/GBR/waii/event/F01/1/1/json/) - available for all events	

