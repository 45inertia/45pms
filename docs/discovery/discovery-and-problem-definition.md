# Discovery and Problem Definition

## The Problem

### What is the current solution.

The current solution is writing all the documentation for a project in a docs folder in the GitHub
repository. This means writing all documentation in Visual Studio Code. This is somewhat efficient 
but lacks professional templates, calendar feature, and visual representation of how the project
is going. You should also be able to at a glace understand what the project is and how the
project is going.

In project managment there are multiple different apps/webapps used for gantt charts, github kanban,
etc. Having one point of contact would be more efficient.

## The Goal

The goal is to replace a fragmented collection of tools currently used for project management and
documentation with a single desktop application that gives an at-a-glance understanding of any
project's state, keeps everything version controlled via Git, and enables easy publication to a
personal website. 

## Core Features 

- Opening the Project root folder (repository root)
  - WHY: For ease of use when importing projects and keeping them in the right state.
- Markdown Editing and Preview
  - WHY: Editing project documentation is the highest priority.
- File Navigation
  - WHY: Organising project files and documentation.
- Checklist/Kanban Functionality
  - WHY: Managing tasks for the project.
- Deadline/Calendar Scheduling
  - WHY: Project timeline information should be included in the one point of contact. Deadlines can
    be task specific, sprint/phase specific or project wide.
- Documentation Templates
  - WHY: Projects should have a baseline similarity for documentation but can differ in regards to 
    type of architecture and type of project.
- Export Markdown to Personal Website.
  - WHY: Easy publication of logbook demonstrating the project state and other project files.


## Constraints

- I would like to spend no more than a month on the implementation phase and roughly two weeks on 
  the design phase. 
- I would like to use the Qt6 tech stack.
- It should work offline. But pulling a github repository with the right structure should be able to
  populate the application with all the information needed.

## Scope Boundary

I am not creating an application for public release. Therefore there does not need to be any help
and tutorial sections. (All features will be documented)

Multi user/collaboration features are out of scope as well as cloud storage or sync beyond git.

A full mobile or web version of app is out of scope.

A plug or extension system is out of scope

Themes or UI beyond dark mode and light mode are out of scope.

## Open Questions

- What architectures will templates be provided for?
- What does "export to personal website" mean specifically?
- What does the Kanban board store its state in?
- How does deadline/calendar data persist?
- What constitues right structure for a GitHub repository to be importable?
