# Discovery and Problem Definition

## The Problem

### What is the current solution.

The current solution is writing all the documentation for a project in a docs folder in the GitHub
repository. This means writing all documentation in Visual Studio Code. This is somewhat efficient 
but lacks professional templates, calendar feature, and visual representation of how the project
is going. You should also be able to at a glace understand what the project is and how the
project is going. 

## The Goal

The ability to start the application, open the repository root folder. 

From there you can edit the documentation in markdown format and preview the current file being 
edited. 

There is also checklist functionality where items that need to be done can be implemented. 

There is deadline functionality where you can set deadlines for yourself. 

Templates are provided for documentation dependent on the pattern of architecture.

Export to website would take the documents from the current project and make sure they are up to
date on my personal website.

## Constraints

- I would like to spend no more than a month on the implementation phase and roughly two weeks on 
  the design phase. 
- I would like to use the Qt6 tech stack.
- It should work offline. But pulling a github repository with the right structure should be able to
  populate the application with all the information needed.

## Scope Boundary

I am not creating an application for public release. Therefore there does not need to be any help
and tutorial sections. (All features will be documented)