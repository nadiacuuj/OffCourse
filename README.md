# OffCourse

A study planner for university students. It turns your classes and assignments into a balanced weekly study plan, and helps you study with friends.

**Live demo:** https://nadiacuuj.github.io/OffCourse/

## The Problem

We've all been guilty of last-minute cramming. Many students sit down to study, but end up wasting time because we don't know what to work on first. Trying to track every deadline while managing a heavy workload causes stress, burnout, and unproductive study time.

## Inspiration

This project was inspired by Timeshifter. Timeshifter is an app for long flights across different time zones. It tells you exactly when to sleep, see light, or drink coffee so your body clock adjusts before you land. 

I liked how Timeshifter uses your personal schedule to plan the best times for energy and sleep. I wanted to use this same idea for studying: spacing out your work so you stay productive without burning out.

## Intention

OffCourse connects your tasks to your schedule so you never have to guess what to study next. It reads your calendar, knows your deadlines, and automatically spaces out your work over time. For example, it can schedule one subject today and a different subject tomorrow. You can focus on learning without stressing about when to study.

OffCourse is meant to connect to Google Calendar, Apple Calendar, Web Learning, and Rain Classroom to read your classes and assignments automatically.

**This prototype does not have those connections.** All data in the app is made-up sample data. You can type in your own classes and assignments, or use "Reset to demo data" in Settings. Friends and their calendars are sample data.

## Try it

1. Open the live demo link above. No install or login needed.
2. The app opens with a demo week and a study plan already made. The demo clock is fixed at Wednesday 11:00am.
3. Things to try:
   - **Week tab:** click a purple study block to see why OffCourse put it there.
   - **Settings:** change "When do you focus best?" and watch the plan move.
   - **Assignments:** add an assignment and the plan updates.
   - **Friends tab:** schedule a suggestion or join an open session. Your solo study blocks re-plan around it.
   - **Find a time:** pick friends and book a shared free slot.

## What it does

- Weekly calendar with classes, planned study blocks and group sessions
- Assignment list with deadlines, hours needed and priority
- "Generate my plan" places study blocks in your free time
  - Earlier deadlines and higher priority go first
  - Work is split into short sessions and spread over several days
  - Study goes in your best focus time first (morning, afternoon or evening)
  - Never goes over your daily study limit
  - Warns you if something cannot fit before its deadline
- Nudges: sample reminders and heads-ups, like what is up next and which assignments are on track
- Workload bars that show busy days
- Friends tab
  - Suggested for you: shared courses, shared deadlines, shared free time
  - Open sessions: join a session a friend posted
  - Find a time: pick friends and see when you are all free
  - Privacy: friends show as busy or free unless they share course names

## Run it on your computer

You do not need to install anything.

1. Download or clone this repository.
2. Double-click `index.html`. It opens in your browser.

To clone with the terminal:

```bash
git clone https://github.com/nadiacuuj/OffCourse.git
cd OffCourse
open index.html
```

(`open` works on Mac. On Windows use `start index.html`.)

## Files

- `index.html`: the whole app (HTML, CSS and JavaScript in one file)
- `README.md`: this file

## Reset the demo

Go to Settings, then Data, then "Reset to demo data". Your changes are saved in your browser only, so clearing browser data also resets the app.

## Limits of the prototype

- Only one week is shown, and deadlines are set by day of the week.
- The demo clock is fixed, so the app does not use the real date or time.
- Friends, their schedules and their sessions are sample data.
- Invites and reminders are not really sent.
- Data is stored in your browser (localStorage), not on a server.

## Next steps

- Real Google and Apple Calendar sync
- Real Web Learning and Rain Classroom connection
- Accounts and real friends (needs a server)
- Real phone notifications
- Week navigation and real dates