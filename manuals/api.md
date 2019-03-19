<!-- TITLE: API Documentation -->
<!-- SUBTITLE: For software developers -->

This page describes APIs for developers.

## Uploading competition results
OpenTrack can accept a description of a competition in JSON format.  The format is pretty much the same as the one available for downloading.  This is the preferred way for Federations to submit data form national systems; it will end up published as Open Data, and we will notify IAAF and European Athletics that it is available.

However, we are quite demanding; the data must be correct and complete, will full series of throws or jumps.

To use the upload API, you need to contact OpenTrack and arrange credentials.  We will carefully check the first few uploads; the number of people/federations sending us this day is very small, so we're happy to pro.

### Test Harness
A test harness is available at http://data.opentrack.run/x/create.  This lets you validate JSON packets simply by copying and pasting, and also has basic instructions
![Upload Harness](/uploads/upload-harness.png "Upload Harness")

### API for creation
The actual request should be a POST to [/x/api/create/](https://test-data.opentrack.run/x/api/create].  It can be multipart-form-encoded using parameters *data=<json>*, like the demo web form; or you can send the raw JSON as the POST body.


