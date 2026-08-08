# Verified UI Themes

This document contains verified resources for creating professional light and dark themes in PySide6 applications.

---

## Repository 1

### Name
QDarkStyleSheet

### GitHub
https://github.com/5yutan5/PyQtDarkTheme

### Purpose
Provides dark and light themes for Qt applications.

### Claude Should Study
- Dark themes
- Light themes
- Qt stylesheets
- Colour palettes
- Widget styling

### Recommendation
Use established Qt styling approaches rather than creating inconsistent colours for individual widgets.

---

## Repository 2

### Name
QtAwesome

### GitHub
https://github.com/spyder-ide/qtawesome

### Purpose
Provides an icon system for Qt applications using Font Awesome and Material Design icons.

### Claude Should Study
- Application icons
- Toolbar icons
- Sidebar icons
- Menu icons
- Consistent icon usage

### Recommendation
Use QtAwesome when an application needs a broad collection of professional interface icons.

---

## Theme Standards

Claude should design applications with:

- Light mode
- Dark mode
- Consistent colours
- Consistent spacing
- Clear visual hierarchy
- Readable text
- Accessible contrast
- Consistent button styles
- Consistent input-field styles
- Consistent table styles
- Consistent navigation styles

### Important Rule

Do not hard-code colours throughout the application.

Create a central theme system so the application can change between light and dark modes without rewriting individual screens.

### Theme Architecture

Use a central theme manager such as:

```text
ThemeManager
    |
    ├── Light Theme
    ├── Dark Theme
    └── Application Stylesheet
