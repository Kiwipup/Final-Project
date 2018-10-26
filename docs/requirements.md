# Outline for final project

* [homepage_wireframe](https://mail.google.com/mail/u/0?ui=2&ik=8d03360398&attid=0.0&permmsgid=msg-f:1615390001022005014&th=166b04a5b0a26f16&view=fimg&disp=thd&attbid=ANGjdJ9FEBoQEq6_U7ShJvrihNLemBqyzr_U6ZrF4VNQ-31kgPUmZpLAH6Y75fA89uXHrGcik16c_fjQTR5Onc-xIl6fLcnDS_KgZ0r9XQVmRgBUYlWVwptepJ-agv4&ats=2524608000000&sz=w2560-h1380)

* [signup_page_wireframe](https://mail.google.com/mail/u/0?ui=2&ik=8d03360398&attid=0.8&permmsgid=msg-f:1615390001022005014&th=166b04a5b0a26f16&view=fimg&disp=thd&attbid=ANGjdJ8poyMRtV1UKiWNwWz_T-QMnwu9j3-IIoXWcYc73eh2hqd7yiGKrNl1Komtqpi4zjeYvgaoynF4n0lm4X6MgB5CbY9bGlffSHFoawmxSGYEVp2eJ1JaSlzLuP8&ats=2524608000000&sz=w2560-h1380)

* [user_dashboard_wireframe](https://mail.google.com/mail/u/0?ui=2&ik=8d03360398&attid=0.7&permmsgid=msg-f:1615390001022005014&th=166b04a5b0a26f16&view=fimg&disp=thd&attbid=ANGjdJ89K4C8XOfXpNn1H42RyWilIoJqSAVQpt79Hj2rlxp4LNQcGxhcSdAv5r4XJhq5WYYgG-qG8ZBWX1kg6HPUNGsY6C8gi-zRUByyHSb_FIS9_m0NNLHiV7sqM4I&ats=2524608000000&sz=w2560-h1380)

* [reports_page_wireframe](https://mail.google.com/mail/u/0?ui=2&ik=8d03360398&attid=0.6&permmsgid=msg-f:1615390001022005014&th=166b04a5b0a26f16&view=fimg&disp=thd&attbid=ANGjdJ-s1OyiMF7IXI4Jshui522oO8vIyoy3IVaWtHw945MttccGx1PYyWdZSiJEQijsFr_cMBVeRE7WbwARKVNcj4z2mLmiF1UmzeyG1SSxXZI4aEEM3CD0rSdbK1U&ats=2524608000000&sz=w2560-h1380)

* [groups_pages_wireframe](https://mail.google.com/mail/u/0?ui=2&ik=8d03360398&attid=0.4&permmsgid=msg-f:1615390001022005014&th=166b04a5b0a26f16&view=fimg&disp=thd&attbid=ANGjdJ_siFHqQzY0u-8V-toHIQ2U0uF-ejTPhSgUjsl1hfkcZEE92FuoYo6hg5JMjxSAvSWvTy2-NXps2yDjibtxHfxb4DYbBCNjJjebkm45NDsDLwdZdIwiHiwLK-A&ats=2524608000000&sz=w2560-h1380)

* [database_structure_outline](https://mail.google.com/mail/u/0?ui=2&ik=8d03360398&attid=0.2&permmsgid=msg-f:1615390001022005014&th=166b04a5b0a26f16&view=fimg&disp=thd&attbid=ANGjdJ9xgWwK5MXyjHlHkDCDJiewBs3fUiWtzsZlZtXLkCcniwJxaSG4ykz9U-nViANpbYLoKW1M15L2vc0u2Quuw1qMmsmQLR-Z214N2nF2zd7hLcufD563YeXc3x4&ats=2524608000000&sz=w2560-h1380)

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


