# TimeTracker_spreadsheet
A simple MS Excel based time tracker. It's a simple productivity tool. The idea of the time tracker sheet is to analyse how I spend my entire day and how much active time is contributed to office work. The days are broken down in 30 minutes slots. It can be adjusted based on an individuals requirtements.

## How to use
### TODO sheet:
- TODO Sheet is meant only for office works - TODO: update it to include personal works as well
- Update the TODO Sheet to add all the TODO tasks.
- If provided a deadline(date) and the status is not `DONE`, it would track the days left for the task to finish

### Month's time tracker sheet(s):
- Create a new sheet for each month (the sheet contains all the days in the month)
- All pending (status is not `DONE`) tasks from the TODO sheet should be available in the month's time tracker cells as dropdown with a `Work: ` tag
- In the month's time tracker sheet, all activities with tag `Work` contributes to time contributed towards active professional/office work (personal times are excluded from the total column)
- Any freeform text can be added in the task slots. Make sure to add a `Work: ` tag for office related tasks
- The total column in the end tracks active time spent of office work
