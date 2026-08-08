# Verified UI Libraries

---

## Repository 001

Name

PyQt-Fluent-Widgets

Author

zhiyiYo

GitHub

https://github.com/zhiyiYo/PyQt-Fluent-Widgets

Status

Verified

Stars

8000+

Maintenance

Excellent

Documentation

Excellent

Difficulty

Intermediate

Purpose

Provides Windows 11 Fluent Design controls for Python desktop applications.

Features

- Navigation Interface
- Cards
- Tree Views
- Data Tables
- Dialogs
- Settings Pages
- Info Bars
- Progress Rings
- Modern Buttons
- Responsive Layouts

Why Include

This is one of the highest quality Fluent UI libraries available for Qt.

Useful For

- Student Management Systems
- Senate Approval Systems
- Hospital Systems
- Banking Applications
- Inventory Systems
- ERP Systems

Claude Notes

Study

- Navigation
- Window Layout
- Table Views
- Dialog Design
- Theme Switching
- Settings Pages

# Verified UI Libraries Standards

Claude should select UI libraries based on the application requirements, platform support, maintainability and existing project architecture.

The UI layer should remain separate from business logic, database operations and external services.

## PySide6

PySide6 is an approved choice for professional Python desktop applications.

It provides access to the Qt framework and supports:

- Windows
- macOS
- Linux
- Forms
- Tables
- Dialogues
- Menus
- Toolbars
- Charts
- Animations
- Model-view interfaces

GitHub Repository:

https://github.com/pyside/pyside-setup

Status: APPROVED

PySide6 should be preferred when the project requires a modern, feature-rich Python desktop interface.

## PyQt6

PyQt6 is another Qt-based Python GUI framework.

It may be used when:

- The project already uses PyQt6.
- Existing components depend on PyQt6.
- The project's licensing requirements are compatible with PyQt6.

Do not mix PyQt6 and PySide6 in the same application without a clear technical reason.

## Tkinter

Tkinter is included with standard Python installations and can be suitable for small desktop tools.

Use it when:

- The application is small.
- Simple forms are required.
- Advanced UI features are not needed.

For large professional applications, prefer a more capable framework when appropriate.

## CustomTkinter

CustomTkinter may be considered for applications that need a simpler modern interface while remaining close to the Tkinter programming model.

Use it only when its feature set matches the project requirements.

## Qt Designer

Qt Designer can be used to design Qt-based interfaces visually.

It may help create:

- Forms
- Dialogues
- Layouts
- Buttons
- Tables
- Input controls

Generated UI code should remain separate from application logic.

## UI Architecture

Use a clear separation between interface and application logic.

Recommended structure:

```text
UI
 ↓
Controller / ViewModel
 ↓
Service
 ↓
Repository
 ↓
Database
