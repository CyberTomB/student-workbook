## What is a Github action and how do they work?

Actions are basically subroutines that execute when certain conditions are triggered. They work by creating listener-type events that wait for conditions to be met and then execute attached actions.

## What benefits do Github actions provide?

They can automate the processes of your workflow so that you don't have to manually process every aspect of your code's production.

## What types of trigger actions can a workflow use? What do they do?

Workflow, Scheduled, Webhooks, and External. Workflow triggers are push, pull or fork requests. Scheduled can run on timers, webhooks can run on other github actions (like starring a repository), and external would be if something from outside the github environment needs to communicate with your repo.