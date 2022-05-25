# Controls for how to users can check off a task

- Status: In development
- Date: 05/23/2022

## Context and Problem Statement

We do not want users to be allowed to check off any task at any point, instead we want users to work on their current task
and only check it off when they are done. Thus, remove all the individual task check off boxes and create one global
check off box that will check off the current task.

## Decision Drivers

### For:
* Cleans up UI
* Adheres more to the Pomo Theory
* Encourages in order task completion

### Against:
* Users may not like being forced to check off only the current task
* May be confusing to only have 1 checkbox

## Considered Options

* Leave as is
* Remove individual checkboxes and add in a new global checkbox for the current task

## Decision Outcome
Remove individual checkboxes and add in a new global checkbox
