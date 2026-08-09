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

# Verified UI Theme Standards

Application themes should provide a consistent appearance across all screens and controls.

## Theme Types

Common application themes include:

- Light
- Dark
- System

Where appropriate, allow the user to select the preferred theme.

## Consistency

The same theme should apply consistently to:

- Windows
- Dialogues
- Buttons
- Forms
- Tables
- Menus
- Toolbars
- Charts
- Notifications

Avoid mixing unrelated visual styles.

## Colours

Use a defined colour system for:

- Backgrounds
- Text
- Borders
- Buttons
- Links
- Warnings
- Errors
- Success messages
- Disabled controls

Do not use colour as the only way to communicate information.

## Contrast

Text and important controls should have sufficient contrast against their background.

Disabled elements should remain distinguishable without becoming difficult to read.

## Typography

Use a consistent font family and sensible font sizes.

Maintain clear differences between:

- Page titles
- Section headings
- Labels
- Body text
- Table text
- Help text

## Dark Theme

A dark theme should not simply invert every colour.

Check:

- Text readability
- Border visibility
- Button contrast
- Input fields
- Tables
- Charts
- Notifications
- Icons

## User Preference

If theme selection is available, save the user's preference where appropriate.

The application should restore the selected theme when it starts again.

## Theme Testing

Test themes across the major application areas.

Check:

- Main window
- Forms
- Dialogues
- Tables
- Menus
- Charts
- Reports
- Notifications

## Theme Checklist

- [ ] Light theme supported where required
- [ ] Dark theme supported where required
- [ ] System theme supported where useful
- [ ] Colours are consistent
- [ ] Contrast is suitable
- [ ] Typography is consistent
- [ ] Dark theme is fully tested
- [ ] User preference can be saved where required
- [ ] All major UI components support the selected theme
