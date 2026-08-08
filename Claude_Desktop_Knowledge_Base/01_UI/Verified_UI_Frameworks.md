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
