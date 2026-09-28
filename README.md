# OffCourse

A study planner for university students. It turns your classes and assignments into a balanced weekly study plan, and helps you study with friends.

## The Problem

We've all been guilty of last-minute cramming. Many students sit down to study, but end up wasting time because they do not know what to work on first. Trying to track every deadline while managing a heavy workload causes stress, burnout, and unproductive study time.

## Inspiration

This project was inspired by Timeshifter. Timeshifter is an app for long flights across different time zones. It tells you exactly when to sleep, see light, or drink coffee so your body clock adjusts before you land. 

I liked how Timeshifter uses your personal schedule to plan the best times for energy and sleep. I wanted to use this same idea for studying: spacing out your work so you stay productive without burning out.

## Intention

OffCourse connects your tasks to your schedule so you never have to guess what to study next. It reads your calendar, knows your deadlines, and automatically spaces out your work over time. For example, it can schedule one subject today and a different subject tomorrow. You can focus on learning without stressing about when to study.

OffCourse is meant to connect to Google Calendar, Apple Calendar, Web Learning, and Rain Classroom to read your classes and assignments automatically.

**This prototype does not have those connections.** You type in your classes and assignments yourself, or press "Load sample week". Friends and their calendars are sample data.

## What it does

- Weekly calendar with your classes, study blocks, and group sessions
- Assignment list with deadlines, hours needed, and priority
- "Generate my plan" places study blocks in your free time
  - Earlier deadlines and higher priority go first
  - Work is split into short sessions and spread over several days
  - Never goes over your daily study limit
  - Warns you if something cannot fit before its deadline
- Workload bars that show busy days
- Friends tab
  - Suggested for you: shared courses, shared deadlines, shared free time
  - Open sessions: join a session a friend posted
  - Find a time: pick friends and see when you are all free
  - Privacy: friends show as busy or free unless they share course names
- Settings for daily limit, study hours, session length, and breaks

## How to run it

Open `index.html` in a browser. No install needed.

## How to deploy on GitHub Pages

1. Create a new public repository on GitHub.
2. Upload `index.html` and `README.md` to it.
3. Go to Settings, then Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch".
5. Choose the `main` branch and the `/ (root)` folder. Click Save.
6. Wait about a minute. Your link will be `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Limits of the prototype

- Data is saved in your browser only (localStorage). Clearing browser data deletes it.
- Only one week is shown, and deadlines are set by day of the week.
- Friends, their schedules, and their sessions are sample data.
- Invites are not really sent.

## Next steps

- Real Google and Apple Calendar sync
- Real Web Learning and Rain Classroom connection
- Accounts and real friends (needs a server)
- Notifications
- Week navigation and dates