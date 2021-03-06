<!-- TITLE: Test Plan -->
<!-- SUBTITLE: Tyres we need to kick -->

Here's a list of experiments we should carry out...

Authentication:
* can we create users? *yes - https://wiki.opentrack.run/admin/users Click top right button - Create / Authorize / Users. Also, we could programmatically access the Mongo DB to create/sync them with, say, users in a specific group*
* can we allow login through Facebook etc? Yes, https://wiki.opentrack.run/admin/users Do the above and click select facebook from the list
* can we authenticate through extra external systems? *Seems to support Microsoft, google, Slack, Github and Facebook etc.  we will need to register an app and add a suitable client id and secret for each of them to turn them on, though*

Authorisation:
* can we restrict access (view and edit) to specific subdirectories for specific groups of users? *Yes, easy - you can define access for the Guest user to deny everything under a URL> . Example:  [Staff Directory](staff/home)*


Styling
* can we tweak the style - e.g. to match https://opentrack.run/  *In the UI, we can only select from colors.  But since all code is in Git, presumably we can modify it easily enough*

Code samples and docs
* are they easy to edit?  *Yes, nice editor and highlighters...*

```python
if stage.startswith('proposal'):
    decision = summary.proposal_decision()
    if stage.startswith('development'):
        decS = summary.standard_decision()
        decA = summary.assessment_decision()
        decision = decS or decA
```


Image gallery
* how does it work?  Is it pleasant? *Seems easy*

Github:
* How does it look at the GitHub end?  *URLs define a directory structure, every page is an md file - so this is /test-plan.md.  So it would be easy to, for example, grab all the content and transform the md files into a manual; or to generate other stuff offline.*
* Can we clone that, write content offline, push back and update without causing total chaos? *Yes, it works.  I did not attempt to force a merge conflict though*