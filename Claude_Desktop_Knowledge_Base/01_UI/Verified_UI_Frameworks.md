# Verified UI Frameworks

This document contains verified GitHub repositories that Claude can study when building professional desktop user interfaces.

---

## Repository 1

### Name
PySide6

### GitHub
https://github.com/pyside/pyside-setup

### Purpose
Official Qt for Python project providing PySide6 bindings for Qt.

### Use Cases
- Desktop applications
- Enterprise software
- Multi-window applications
- Data management systems
- Statistical software

### Claude Should Study
- QMainWindow
- QWidget
- QDialog
- Signals and slots
- Layout management
- Model/View architecture
- Qt Designer integration
- Threading
- Menus
- Toolbars
- Dockable panels

### Recommendation
Use PySide6 as the primary GUI framework for our Windows desktop applications.

---

## Repository 2

### Name
Qt

### GitHub
https://github.com/qt/qtbase

### Purpose
Core Qt framework used by PySide6.

### Use Cases
- Application windows
- Layouts
- Events
- File handling
- Networking
- Threading
- Model/View applications

### Claude Should Study
- Qt architecture
- Widgets
- Signals and slots
- Event handling
- Model/View design
- Cross-platform development

### Recommendation
Use Qt concepts and official documentation as the architectural reference for PySide6 development.

---

## Repository 3

### Name
PyQt

### GitHub
https://github.com/baoboa/pyqt5

### Purpose
Python bindings for the Qt framework.

### Use Cases
- Desktop applications
- GUI development
- Data management tools
- Scientific applications

### Claude Should Study
- Qt widget design
- Signals and slots
- Model/View architecture
- Desktop application structure

### Recommendation
Use as a secondary reference when a PySide6 implementation has a useful equivalent in PyQt.

---

## Standard UI Rule

Claude should use **PySide6 as the default GUI framework** unless the project requirements clearly require another framework.

Applications should have:

- Responsive layouts
- Resizable windows
- Clear navigation
- Consistent spacing
- Keyboard shortcuts
- Accessible controls
- Light and dark themes
- High-DPI support
- Professional typography
- Clear error messages
- Consistent icons
- Non-blocking background operations

---

# Dashboard References

This section contains verified GitHub projects that demonstrate dashboard design and implementation with Qt, PySide6, PyQt and QML.

## Repository 1

### Name
prmpsmart/analytics_dashboard

### GitHub
https://github.com/prmpsmart/analytics_dashboard

### Description
A PySide6 implementation of an analytics dashboard based on a Figma design.

### Claude Should Study
- Analytics dashboard structure
- Dashboard cards
- Data presentation
- PySide6 layouts
- Professional dashboard organisation

### Recommendation
Use as a reference for building analytics-focused desktop dashboards.

---

## Repository 2

### Name
MrCl0wnLab/Python_PySide2_DashInfosecGreen

### GitHub
https://github.com/MrCl0wnLab/Python_PySide2_DashInfosecGreen

### Description
A Python and PySide dashboard interface demonstrating a modern desktop dashboard.

### Claude Should Study
- Dashboard navigation
- Information panels
- Modern Qt layouts
- Sidebar design
- Dashboard organisation

### Recommendation
Use as a secondary reference for dashboard layout and navigation.

---

## Repository 3

### Name
KhoaTranProgrammer/QtQml_Dashboard

### GitHub
https://github.com/KhoaTranProgrammer/QtQml_Dashboard

### Description
A Qt Quick/QML dashboard demonstration.

### Claude Should Study
- QML dashboard layouts
- Animated dashboard components
- Data display
- Modern Qt interface design

### Recommendation
Use when a project requires QML-based dashboard concepts.

---

## Repository 4

### Name
cappqtdev/Tesla

### GitHub
https://github.com/cppqtdev/Tesla

### Description
A Qt/QML dashboard project.

### Claude Should Study
- QML interfaces
- Dashboard cards
- Vehicle-style information displays
- Qt Quick layouts

### Recommendation
Use as a visual reference for information-rich dashboards.

---

## Repository 5

### Name
BrnSir/CuteBoard

### GitHub
https://github.com/BrnSir/CuteBoard

### Description
A real-time dashboard built with Qt.

### Claude Should Study
- Real-time data display
- Dashboard widgets
- Charts
- Data visualisation
- Qt dashboard architecture

### Recommendation
Use when developing dashboards that display changing data.

---

## Repository 6

### Name
Serial-Studio/Serial-Studio

### GitHub
https://github.com/Serial-Studio/Serial-Studio

### Description
An open-source telemetry dashboard supporting multiple data sources and communication protocols.

### Claude Should Study
- Real-time dashboards
- Data visualisation
- Instrument panels
- Charts
- Telemetry displays
- Modular dashboard components

### Recommendation
Use as a strong reference for professional real-time data dashboards.

---

# Dashboard Design Standards

Claude should build dashboards with a clear information hierarchy.

A standard dashboard should normally contain:

```text
Sidebar
    |
    ├── Dashboard
    ├── Data
    ├── Analysis
    ├── Reports
    ├── Settings
    └── Help

Main Area
    |
    ├── Page Header
    ├── Summary Cards
    ├── Charts
    ├── Data Tables
    └── Recent Activity
