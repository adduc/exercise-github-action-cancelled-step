# Exercise: Github Actions: Defining code that runs if a specific step is cancelled

This repository contains an example workflow that shows how a step can
be defined to run only when a specific step is cancelled. It can be a 
useful pattern to implement for deployment workflows, where a rollback
may need to occur if the deploy step was cancelled.
