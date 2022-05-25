# Create a new checklist for completed tasks

- Status: In development
- Date: 05/23/2022

## Context and Problem Statement

Currently when the user checks a task off, it can be confusing when that task gets moved to the bottom of the checklist. Instead
we want to make a separate completed checklist to make it easier for the user to see what they have accomplished.

## Decision Drivers

### For:
* Cleans up UI of current task list
* Makes checking off tasks less disorientating 

### Against:
* May be a lot of hidden complexity with the way the task list and stats are set up currently
* Might be confusing to have two task lists instead of just one

## Considered Options

* Leave as is with one task list
* Create a separate completed task list where checked off tasks go to

## Decision Outcome
Create separate task list for completed tasks
