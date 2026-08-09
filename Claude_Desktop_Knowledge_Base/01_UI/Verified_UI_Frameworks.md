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


---

# Animation References

This section contains verified Qt and PySide6 projects that demonstrate animation techniques for desktop applications.

## Repository 1

### Name
Rev-RoastedDuck/Qt-RoastedDuck-Widgets

### GitHub
https://github.com/Rev-RoastedDuck/Qt-RoastedDuck-Widgets

### Description
A Python Qt widget library based on animated Material Design components.

### Claude Should Study
- Animated widgets
- Material Design effects
- Button animations
- Widget transitions
- Qt animation techniques

### Recommendation
Use as a reference when building polished animated Qt widgets.

---

## Repository 2

### Name
niklashenning/pyqtcountup

### GitHub
https://github.com/niklashenning/pyqtcountup

### Description
A numerical data animation library for PyQt and PySide labels.

### Claude Should Study
- Animated numerical values
- Counter animations
- Dashboard statistics
- Label transitions

### Recommendation
Use for animated dashboard statistics and KPI counters.

---

## Repository 3

### Name
Video-Nomad/qt-css-engine

### GitHub
https://github.com/Video-Nomad/qt-css-engine

### Description
A CSS transition system for PyQt6 and PySide6.

### Claude Should Study
- CSS-like transitions
- Widget state changes
- Smooth property transitions
- Interface effects

### Recommendation
Use when smooth transitions are needed between widget states.

---

## Repository 4

### Name
majuch/PySide6-Shadcn-Widgets

### GitHub
https://github.com/majuch/PySide6-Shadcn-Widgets

### Description
A modern PySide6 UI library inspired by shadcn/ui components and animations.

### Claude Should Study
- Modern component design
- Animated UI components
- Cards
- Buttons
- Dialogs
- Modern desktop styling

### Recommendation
Use as a reference for modern PySide6 component design.

---

## Repository 5

### Name
marconhenning/pyqt-loading-button

### GitHub
https://github.com/marconhenning/pyqt-loading-button

### Description
A QPushButton with built-in loading animations for PyQt and PySide.

### Claude Should Study
- Loading states
- Progress feedback
- Button animations
- Asynchronous task feedback

### Recommendation
Use for buttons that perform operations requiring visible progress feedback.

---

## Repository 6

### Name
dimkanovikov/WidgetAnimationFramework

### GitHub
https://github.com/dimkanovikov/WidgetAnimationFramework

### Description
A Qt library for animating widgets.

### Claude Should Study
- Widget animation
- Animation timing
- UI transitions
- Animated interface components

### Recommendation
Use as a reference for reusable widget animation systems.

---

## Repository 7

### Name
iwxyi/Qt-InteractiveButtons

### GitHub
https://github.com/iwxyi/Qt-InteractiveButtons

### Description
Qt widgets with interactive animations and custom button behaviour.

### Claude Should Study
- Interactive buttons
- Hover effects
- Button transitions
- Custom widget behaviour

### Recommendation
Use for interactive button design.

---

## Repository 8

### Name
iwxyi/Qt-FacileMenu

### GitHub
https://github.com/iwxyi/Qt-FacileMenu

### Description
An animated Qt menu widget.

### Claude Should Study
- Animated menus
- Menu transitions
- Sidebar interactions
- Navigation effects

### Recommendation
Use when implementing animated navigation menus.

---

## Repository 9

### Name
Furkanzmc/QML-loaders

### GitHub
https://github.com/Furkanzmc/QML-loaders

### Description
Loading animation implementations using QML.

### Claude Should Study
- Loading indicators
- QML animation
- Progress feedback
- Application startup states

### Recommendation
Use as a reference when QML is used for animated loading interfaces.

---

## Repository 10

### Name
iwxyi/Qt-DraggableTabWidget

### GitHub
https://github.com/iwxyi/Qt-DraggableTabWidget

### Description
A Qt tab widget supporting draggable tabs and tab merging.

### Claude Should Study
- Draggable tabs
- Tab interactions
- Animated tab behaviour
- Advanced navigation

### Recommendation
Use when applications require flexible multi-document tab interfaces.

---

## Repository 11

### Name
Wanderson-Magalhaes/QPropertyAnimation_PySide2_PyQt5_Widgets_Animation

### GitHub
https://github.com/Wanderson-Magalhaes/QPropertyAnimation_PySide2_PyQt5_Widgets_Animation

### Description
Examples of widget animation using Qt's QPropertyAnimation system.

### Claude Should Study
- QPropertyAnimation
- Widget movement
- Widget resizing
- Opacity effects
- Sidebar animation
- Sequential animations

### Recommendation
Use QPropertyAnimation as the preferred Qt-native approach for simple widget animations.

---

## Repository 12

### Name
Tuhin-thinks/PySide2-Side-Menu

### GitHub
https://github.com/Tuhin-thinks/PySide2-Side-Menu

### Description
An implementation of a side menu using PySide and QPropertyAnimation.

### Claude Should Study
- Collapsible sidebars
- Navigation animation
- QPropertyAnimation
- Sidebar transitions

### Recommendation
Use as a reference for animated collapsible navigation.

---

## Repository 13

### Name
janbodnar/pyqt-qpropertyanimation

### GitHub
https://github.com/janbodnar/pyqt-qpropertyanimation

### Description
Examples based on Qt QPropertyAnimation.

### Claude Should Study
- Property animation
- Widget movement
- Widget geometry
- Animation control

### Recommendation
Use as a basic reference for Qt property animation.

---

# Animation Standards

Claude should use animation to improve usability, not merely decoration.

Preferred uses include:

- Sidebar expansion
- Sidebar collapse
- Page transitions
- Button feedback
- Loading indicators
- Progress feedback
- Dashboard counters
- Dialog appearance
- Notification appearance
- Tab transitions
- Expandable panels

Animations should be short and purposeful.

Avoid excessive animation in data-heavy applications.

## Preferred Qt Animation Tools

Use Qt-native animation classes where appropriate:

```text
QPropertyAnimation
QSequentialAnimationGroup
QParallelAnimationGroup
QPauseAnimation
QVariantAnimation


# Verified UI Framework Standards

The UI framework should provide a consistent, responsive and maintainable desktop interface.

## Framework Selection

Choose a framework based on:

- Platform support
- Stability
- Documentation
- Accessibility
- Performance
- Available widgets
- Project requirements

## Qt

Qt is suitable for professional Python desktop applications.

Common Python options include:

- PySide6
- PyQt

Use one Qt binding consistently within a project.

## UI Structure

Separate the interface from application logic.

A suitable structure is:

```text
UI
 ↓
Controller / ViewModel
 ↓
Service Layer
 ↓
Repository
 ↓
Database
