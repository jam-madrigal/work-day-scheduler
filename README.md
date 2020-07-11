# Work Day Scheduler
This app will help you plan a 9-5 workday. 
---
## Features
- Display the current date and time 
- Select an hour of the day and add plans/notes via keyboard input 
- Save your plans on an hourly basis
- See which hours of the day are still incomplete
---
### To get started
1. Have moment.js append the current time and date to the header
2. Create divs that will be timeblocks, 9 AM to 5 PM
- Each div will dynamically change color based on time, red for having past, green for upcoming, and white/pale yellow for the current hour
3. Add events that allow you to type into the timeslot divs
- These keyboard entries will be saved in local storage and persist upon refreshing
- Saving will be finalized by a button click to the side of the div
