# Proposal
## Description
We are building a program to generate a weekly chore schedule for the Management Team. The purpose of the Chore Management System is to automatically create a new chore schedule and scorecard each week. Each user will be assigned to what chore they are doing on that day and it will be in their schedule as well. Each of the managers will be reviewing the chores and sign off on each day of the week. The scorecard is used to measure individual and group performance. 

There are 5 different chores which include; kitchen, floors, bathrooms, lobby, and trash. Two people are assigned one chore per day of the week. One user is only able to work two chores per week. Each chore should be checked off by a manager. A manager can only check off 3 chores a week. Users and Managers should be notified both when a new schedule is uploaded and when a chore is not completed. Managers don't do chores.

Each user should have their own unique sign in and information they need is visibility. Every user will be able to sign in and view the whole chore schedule for that week. They also can view that following week with that certain day and the chores highlighted. If needed, a manager can login and can move people manually on the schedule. 

The Email notifications should be sent to the appropriate party that needs information or takes action. If there is a chore that has not been checked off and the chore of that day passed, it should notify the manager and the users who were assigned the chore. The notification should be visible in the system and it should send them all an email. The Chore Management System should send all users an email that has the next week's schedule as soon as it is created.

The scorecard should be created at the end of each week to calculate these performance measures for the just complete weekly activities. It will be showing these categories of the scorecard which are Overall group performance(% chores completed), Individual Performance(% chores completed by individual), Manager performance(% chores signed off on by manager).

## Prior Art
The Management Team usually creates all schedules by hand which take time especially if one can 
not do a particular chore that day. We are creating a similar way of creating those schedules 
without having to recreate the entire thing. 
## Core User Workflows
- Users can create/ login to an account
- User can sign in and see schedule for this week and following week
- Users can choose a role either Manger or Worker
- Workers can create a schedule with the chores they chose.
- Mangers can edit the schedule
- Mangers can to check off 3 chores
- Both users and managers will receive a scorecard with performance percentage
## Weekly Goals
### Week 1 (July 12-16)
#### Bryce:
- I will be going to work on user authentication where the user can create there account 
  and log in to see the schedules. I will be working on the users table to save login information to database.
  
- I will be going to set up our home page and add minimal styling.

#### Kenia:
- We are also work on our schedule table to save the schedule information. I will also work on the schedule class and
form. I will also met with Bryce to talk about styling.
#### Both:
- Meet with client for updates and what we can change 

### Week 2 (July 19-23)
#### Bryce:
- I will be working on the users schedule. Then work on how they only be assigned two days of chores per week.
#### Kenia: 
- I will continue styling until Bryce finishes the users schedule and then add the manager check off to that schedule.

#### Both:
- Both work on styling the schedule into more of a calendar view.
- Meet with client for updates and what we can change

### Week 3 (July 26-30)

#### Bryce: 
- I will be working on the emailing portion of the project. Where they are notified when there is a new schedule.
#### Kenia: 
- I am going to work on emailing if chores are missed for the day and also marking the schedule as missed.

#### Both:
- Meet with client for updates and what we can change

### Week 4 (August 2-6)
#### Bryce:
- I will be working on the overall group performance on the scorecard.I will work on some styling as well.
#### Kenia: 
- I am going to work on the individual and managers score card and any additional css.
#### Both:
- We are going to dedicate our time to styling and on the appearance of the web page
- We are also going to work on the bread crumb trail to make sure navigation through the 
web app is proficient. 
  
## Team
- Bryce Taylor
- Kenia Sandoval-Lopez

## Technologies
- Spring Boot
- Html/CSS
- Java

## GitHub Repository 
https://github.com/Bryce-Taylor/Capstone-Project
