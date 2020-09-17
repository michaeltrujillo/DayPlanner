GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist

COMPLETED:
1. current day is displayed at the top of the calendar
2. presented with timeblocks for standard business hours
4. click into a timeblock I can enter an event


IN PROGRESS:
5. click the save button for that timeblock the text for that event is saved in local storage
6. refresh the page the saved events persist

HARDEST PART:
3. each timeblock is color coded to indicate whether it is in the past, present, or future


moment().format("dddd MMM Do");     

when a button is clicked, then all content typed into the text area will replace the inner html of the text area and be saved in the users local storage
