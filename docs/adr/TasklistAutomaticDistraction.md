# How to allow users to use the task list during an active pomo

- Status: In development
- Date: 05/23/2022

## Context and Problem Statement

We were torn between allowing users to use the task list during an active pomo session and not, as it is distracting and 
does not follow the pomodoro technique. Thus we found a middleground with allowing users to use the tasklist and check off tasks
(for instance if a user finishes a task early), but it will be logged as an automatic distraction
## Decision Drivers

### For:
* Follows Pomo Theory, but still gives user the power
* A good middleground for the problem at hand
* Gives the user more power, including checking off tasks during a pomo

### Against:
* User may be confused as to why they get a distraction
* Does not exactly follow the pomo theory, as they should not be allowed to mess with task list at all during a pomo session

## Considered Options

* Leave as is, which is giving the user free reign of tasklist during pomo session
* Automatically log a distraction when the user checks off a task or moves/deletes a task during a pomo session

## Decision Outcome
Automatically log a distraction
