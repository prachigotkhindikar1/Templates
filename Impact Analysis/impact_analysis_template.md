### Impact Analysis Process
Skip to end of metadata
Last modified on Dec 20, 2016
Go to start of metadata
Overview
This document outlines the high-level overview of the Impact analysis process the Kiosk team has come up with. The Impact Analysis meeting involves gathering all the key stake holders and discussing the impacted workflows, passivity concerns, regression testing. The engineer setting up the meeting shall update the Impact Analysis JIRA with the provided template.

### Required Attendees
* Solution Owners
* Engineers and Architects
* Test Analysts

### Topics Discussed
* Workflows around the Enhancement
* Passivity concerns
* Dependent Modules
* Functional and Regression test sets created/ approved

### Template

* Attendees Invited to review
* Areas this change is impacting
  **  Functional Areas
  ** Feature Flag
  ** UI
  ** Administration (Build Tool)
* Technical
  ** iOS
  ** Server
  ** Write back
* Regression test plan to run

### Questionnaire -

* Detail the current behavior and how it will be altered with your changes.
  ** Current Behavior:
  ** Changes:
* Detail how previous functionality is being maintained.
* Detail any assumptions the code is making as far as parameter values, system state, etc.
* Detail all consumers of this code and what behavior outlined above is being leveraged by that location.
* For each consumer, detail how the code will be affected by your changes. Any special cases among the consumers?
* Detail any conversations you had with subject matter experts to determine how the code functions, assumptions made, etc.
* Are there any passivity concerns cause by workflow changes?
* Are there any passivity concerns cause by UI changes?
* Are there any significant performance concerns?
* What are our new maintainability requirements going forward?
* What changes need to be made to support processes or documentation?
* Are there any significant scalability concerns?
* Are there any special considerations requiring additional test coverage?
