# Data Model Interaction with ViewModel

```
---
title: Data Model Interaction with View Model
---
classDiagram
    class Task {
        -int id
        -QString name
        -optQString description
        -optStatus status 
        -optPriority priority
        -optint Sprint
        -optQDate startDate
        -optQDate endDate

        +getters()
        +setters()
    }
    class Sprint {
        -int id
        -QString name
        -optQDate startDate
        -optQDate endDate

        +getters()
        +setters()
    }

    class taskManager {
        -vector tasks
        -vector sprints

        +addTask()
        +removeTask()
        +addSprint()
        +removeSprint()
    }

    class Status {
        <<enumeration>>
        TODO
        IN_PROGRESS
        DONE
        BLOCKED
    }

    class Priority {
        <<enumeration>>
        LOW
        MEDIUM
        HIGH
    }

    Sprint <|-- Status
    Task <|-- Status
    Task <|-- Priority
    taskManager <|-- Task
    taskManager <|-- Sprint
    Task <|-- Sprint
```