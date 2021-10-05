# PRA_C2_CodeCamp
## Team Members
* Floris Van Bezooijen
* Jurgen Van Kanenburg
* Rick Bruijs
* Jordy De Ron

# Conventions
## Backlog (project kanban board)
Issues derived from the user stories are all placed in `To Do`. 
The title of the issue is short, simple and have a issue number, for example: 
* [Issue_1] - Example title. 
* [Issue_15] - Example title. 

an issue can be closed and merged, and delivers a working part of the website without breaking anything.
In the issue's description there is a detailed discription of what has to be implemented or fixed. The issue is also nicely divided in sub tasks with checkboxes if necessary like this:
- [x] this task is done.
- [ ] this task is jet to be finished.

Every issue has to be assigned some assignee('s), label(s) and a milestone (sprint). Espacially before an issue is moved to `In Progress`. These are the following:
* The issue has to be assigned to a minimum of 1 team member.
* It has to have a label for the amount of work the issue is. You can choose between the folowing:
  * ![XS](https://img.shields.io/badge/-XS-00ff00) The issue is almost no work.
  * ![S](https://img.shields.io/badge/-S-ffff00) The issue is a small amount of work.
  * ![M](https://img.shields.io/badge/-M-ff8c00) The issue is a normal amount of work.
  * ![L](https://img.shields.io/badge/-L-ff4d00) The issue is a lot of work.
  * ![XL](https://img.shields.io/badge/-XL-ff0000) The issue is a massive amount of work.
* It has to have a label for the priority of the issue. You can choose between the following:
  * ![High Priority](https://img.shields.io/badge/-High%20Priority-ff0000) This issue has a high priority, is very important and has to be done as soon as possible.
  * ![Medium Priority](https://img.shields.io/badge/-Medium%20Priority-ff8c00) This issue has a medium priority, is important and has to be done after high priority.
  * ![Low Priority](https://img.shields.io/badge/-Low%20Priority-00ff00) This issue has a low priority. It is not a primary requirement and can be done last if time allows it.
* The issue has to be assigned to a sprint with the help of the milestones feature in github.

When you finish your issue and you comitted (merged) with the main branch the issue can be placed in `In Review`, and given a label ![Approved by your name](https://img.shields.io/badge/-Approved%20by%20Your%20Name-0080ff).
The rest of the team will pull the code and test out if everything is still working. When a team-member confirmed that everything is working as it supposed to he has to assign his approval label. for example: ![Approved by Jurgen](https://img.shields.io/badge/-Approved%20by%20Jurgen-0080ff). When every team-member approved the issue it can be moved to `Done`.

When a team member notices that the issue is not working as it is supposed to then he can move the issue back to `In Progress` and has to be assigned a label of ![Bug](https://img.shields.io/badge/-Bug-6900c4).
Later on when issues are already closed or an unrelated bug pops up, an new issue has to be made. it has to be assigned a label of ![Bug](https://img.shields.io/badge/-Bug-6900c4) and it has to be placed in `To Do`.

If new issues (user stories) are provided by the product owner after the initial issues (user stories), then these have to be placed in `New`.
When the product owner doesn't want a feature anymore, the issue is closed and placed in `Depricated`.

## Code conventions
The project is made with bootstrap and laravel. The styling has to be mostly done with bootstrap unless there is no other way. The php and sql part is mostly done with laravel unless there is no other way. The project is build with the conventions of laravel and bootstrap and every team-member acts on this fact. All of the code, variables, etc. is written in English.

## Commit conventions
Commits are made like this:

title:

[Issue_x] - Added/Fixed example feature/example bug.

discription:

a short discription of what you did.

Every time you finish a task (so not a whole issue) you have to check the checkbox at the end of the day. This way all team-member can see how everyones progress is going.

## Other conventions
If a team-member is havig trouble he/she will ask for help. Every team-member will be happy to help, but he will not take over his or her work. If a team-member is stuck and asking for help is not working, the issue can be assigned to someone else. but the team-member will have to pick up another issue of the one that is taking over the issue to keep the tasks divided equally.

## Usefull Tips
In the kanban you can easily filter the issues by filtering the cards on the top right. By clicking on the search bar it gives you a few options to filter the issues. You can chain these filter options together to easily pick your issues you have to work on. For example if i want the issues assigned to me that has high priority and isnt a bug you can type this:

`assignee:<your github name> label:high priority -label:bug`

You will get the hang of it. Good luck.
