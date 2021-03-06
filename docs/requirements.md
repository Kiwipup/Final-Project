# Outline for final project

* [homepage_wireframe](https://drive.google.com/open?id=0B9ZWNfq8o1oJNEhOSlBrck9KYUk4bkRpaWQ0UkxuWDVPSGo4)

* [signup_page_wireframe](https://drive.google.com/open?id=0B9ZWNfq8o1oJbTUtNURNMzktRm5RYUFPSFRUM2FkeXR6bFlF)

* [user_dashboard_wireframe](https://drive.google.com/open?id=0B9ZWNfq8o1oJamxtMDczdUhFeUVIWWFhcXMyY2pNaDBpTkJv)

* [reports_page_wireframe](https://drive.google.com/open?id=0B9ZWNfq8o1oJNlg0QkxmcXdLMXI4YVF0WXY1NG5NSFNUdmRF)

* [groups_pages_wireframe](https://drive.google.com/open?id=0B9ZWNfq8o1oJREd5Nmh2U0paa1hnWnJuSHA4a0pfT3ZZR3k0)

* [database_structure_outline](https://drive.google.com/open?id=0B9ZWNfq8o1oJcjgyRVFFd1V3c1ZMZk1wdkJGYldGeXpJbW84)

## Summary

For my final project, I plan to make an application that is a planner for organizing
any chores or tasks that the user needs to keep track of. Each user will have a calendar,
and on this calendar they can set tasks on the days that they need to be completed and
set up reminders that will light up a notification icon or something similar so they will
not forget. They can invite other users to be in a group for completing said tasks
and the owner of the calendar can assign certain tasks to other users or themselves.
The tasks can be marked complete for that day once they are done by the owner of the calendar
or the user who has been assigned that task.

## User Story

As a busy young adult, I would like an application that brings accountability to chores or other tasks
by letting me track their completion. It needs to be something that allows me to keep track of
the most recent time they were last completed, and also let me set up reminders so I don't forget
when it is time to do them again.

## The problem and the solution

From my experience, it can be very difficult remembering to do small tasks that should be
done on a regular basis such as wiping down the bathroom sink, cleaning doorknobs, windows, etc.
Instead of keeping track of things on a piece of paper (which is what we do at my job) it would be
so much easier to have something where everything is all in one place. We could see
what needed to be done that day, delegate the tasks, and mark them as they get done instead.

## Predicted file structure

For a project such as this, I believe I will need the basic file structure containing at least a few html files, a file for styling (I will probably use scss and import bootstrap), and a JS file. I'm not completely sure what the file structure looks like once we start using php but I do know I will surely need a database
to keep track of all the usernames, passwords, calendars, etc.

## Design structure

For the design I am likely going to want a sign in page, and I would like for each user to have a dashboard that has their calendar, the calendar will correctly show the month we are in and it will highlight the current day. Instead of creating a calendar such as this completely from scratch, I believe I might be able to integrate one from the Google Calendar API or something similar!
From their dashboard they can manage their groups, add tasks to the calendar, and access any
account settings such as changing their password or email. Tasks that have not been completed on the proper day will turn red and a notification will be sent to the owner as well as any assignee. A task that is marked completed will disappear and reappear on the next day it is set to be done. However if an assignee marks it completed, it will simply turn green, only the calendar owner can remove them. I do not want the site to have any distracting photos or flashy decoration. It needs to draw attention to the important areas and make it easy to navigate.

## Data storage

The most obvious information that will need to be stored is each user's personal information. So any login credentials, emails, and phone numbers. If I am going to be creating a system that allows users to set up notifications, I will also need to store that input and send out those reminders at the correct times, to the correct place. If possible I would like to somehow configure push notifications but I have not yet looked into the complexity of creating something like that. I want users to be able to set how often they need a particular task to be done so that it will populate on their calendar again at the correct interval after it has been marked completed. For this I will have to store their preference with each corresponding task.


