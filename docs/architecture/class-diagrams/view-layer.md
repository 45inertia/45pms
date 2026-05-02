# View Layer

```
---
title: ViewLayer
---
classDiagram
    class MainWindow {

    }
    class ModeNavigator {

    }
    class FileNavigator {

    }
    class Dashboard {

    }
    class EditorPane{

    }
    class MarkdownEditor {

    }
    class MarkdownPreview {

    }
    class Kanban {

    }
    class Calendar {

    }
    class TemplateSelector {

    }
    class ToolBar {

    }
    class StatusBar {

    }
    class QStackedWidget {

    }

    MainWindow *-- ToolBar: owns
    MainWindow *-- StatusBar: owns
    MainWindow *-- ModeNavigator: owns
    MainWindow *-- QStackedWidget: owns
    MainWindow ..> TemplateSelector: creates on new project
    QStackedWidget o-- EditorPane: owns
    QStackedWidget o-- Kanban: owns
    QStackedWidget o-- Calendar: owns
    QStackedWidget o-- Dashboard: owns
    EditorPane *-- MarkdownEditor: owns
    EditorPane *-- MarkdownPreview: owns
    EditorPane *-- FileNavigator: owns
```