# scheduler

Project Name:  Work Day Scheduler

This program is published at the following website:  https://chulopapi.github.io/scheduler/

Github Reposatory:  https://github.com/chulopapi/scheduler


This application create a simple calendar to save events for each hour of the day.  For the purpose of funcionality,
we have limited the time range from 9:00AM to 5:00PM.   This application will run in the browser and will feature dynamic updates of HTML, CSS and jQuery properties.   I am also using Moment.js library to work with date and time wich are essential for the task on hand.  The program has a clean and polished and responsive user interface.

USER STORY: There is a need to create a schedule to be used as a daily planner.

Acceptance Criteria:

1. When I am ready to start planning my day, the first webpage provides a displayed schedule to be used a the daily planner from 9:00AM to 5:00PM.  The current day is displayed at the top of the calendar as requested.

The following image shows the work day scheduler with a grayed color during the business hour times.  It was asked to have a gray color background once the events are in the past.  This is about 6:00PM:

<img width="1100" alt="Screen Shot 2020-06-21 at 6 06 26 PM" src="https://user-images.githubusercontent.com/14985358/85243245-358d4980-b3f6-11ea-8ffb-f94404d6f63b.png">

2.  When a new day starts, 9:00AM or at any time of the day, the current time block will be shown to have a red color as background:

<img width="1268" alt="Screen Shot 2020-06-21 at 9 02 44 AM" src="https://user-images.githubusercontent.com/14985358/85243634-3d012280-b3f7-11ea-8483-0c807a10b2ae.png">

3. We are able to start planning the day with the current activities and being saved to local storage as intended:

<img width="1232" alt="Screen Shot 2020-06-21 at 9 03 27 AM" src="https://user-images.githubusercontent.com/14985358/85243733-7f2a6400-b3f7-11ea-99d9-219b41713373.png">

4.  Once the current time is past 9:00AM.  I can continue to add any new addition to the daily planner if needed.  A gray color will be displayed to be in the past time block, red will be the current time block and green will represent the future time blocks.

<img width="1110" alt="Screen Shot 2020-06-21 at 11 31 10 AM" src="https://user-images.githubusercontent.com/14985358/85244007-42ab3800-b3f8-11ea-851c-de84d0066499.png">

5. At the end of the day, the scheduler will display your calendar as expected.  This time is past 5:00PM.

<img width="1093" alt="Screen Shot 2020-06-21 at 7 31 41 PM" src="https://user-images.githubusercontent.com/14985358/85244116-9e75c100-b3f8-11ea-97e9-cb2d888b1d6f.png">

