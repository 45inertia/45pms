# Repository Standards

## Basic Folder Structure
The following is an example template for a MVC project.

```
project-template/
├── README.md                  ← Placeholder with prompts to fill in
├── CHANGELOG.md               ← Empty, ready to receive first entry
├── docs/
│   ├── discovery/
│   │   └── discovery-and-problem-definition.md  ← Template with headings
│   ├── research/
│   │   ├── competitive-analysis.md              ← Template with headings
│   │   └── technical-spikes/
│   ├── requirements/
│   │   ├── functional-requirements.md         ← What the system must do
│   │   ├── non-functional-requirements.md     ← How well it must do it
│   │   └── user-stories.md
│   ├── design/
│   │   ├── wireframes/
│   │   └── user-flows/
│   ├── architecture/
│   │   ├── system-overview.md
│   │   └── class-diagrams/
│   ├── decisions/             ← Empty, ADRs written as decisions are made
│   └── logbook/               ← Empty, entries written as work progresses
└── src/
```

**Note: Discovery, research, decisions, logbook and most of design folder structure should be
present no matter that project architecture. However a different project architecture and also
a different methodology could change the architecture**

## Further Templates
Further templates to look into for development would be:
- MVC
- Layered Architecture
- Event-Driven Architecture
- Microservices
- Repository Pattern/Clean Architecture
- Pipeline/Data Processing
- Plugin Architecture

