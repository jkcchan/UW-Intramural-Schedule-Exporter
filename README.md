# UW-Intramural-Schedule-Exporter
Exports intramural schdule to .ics format

First phase:
- Understand the .ics format
- Create Javascript class "CalendarEvent"
- for each row in table, create new CalendarEvent with correct params
- at the end, run through array of CalendarEvents and write to file with title of concatenated strings (sport, team name, term)

Second phase:
- Chrome extension
- Read the webpage
- Download link to .ics (or download straight onto computer)
- Maybe a UI?
