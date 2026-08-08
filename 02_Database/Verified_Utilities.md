# Verified Utility Libraries

---

## Repository 1

### Name
Loguru

### GitHub
https://github.com/Delgan/loguru

### Status
Verified

### Rating
★★★★★

### Purpose
Modern logging library for Python.

### Features
- Structured logging
- Automatic log rotation
- Error tracing
- File logging
- Console logging
- Custom log formats

### Claude Should Study
- Logging
- Exception handling
- Debugging
- Log management

### Why We Chose It
Provides a much simpler and more powerful logging system than Python's built-in logging module.

---

## Repository 2

### Name
Dynaconf

### GitHub
https://github.com/dynaconf/dynaconf

### Status
Verified

### Rating
★★★★★

### Purpose
Configuration management for Python applications.

### Features
- Environment management
- Settings files
- Secret management
- Multiple configuration profiles

### Claude Should Study
- Application settings
- Configuration files
- Environment variables

### Why We Chose It
Keeps application settings organised and makes deployment easier.

---

## Repository 3

### Name
APScheduler

### GitHub
https://github.com/agronholm/apscheduler

### Status
Verified

### Rating
★★★★★

### Purpose
Task scheduling library.

### Features
- Scheduled jobs
- Cron jobs
- Interval execution
- Background scheduling

### Claude Should Study
- Scheduled tasks
- Automatic backups
- Reminder systems
- Maintenance jobs

### Why We Chose It
Perfect for scheduled backups, automatic report generation and routine maintenance.

---

## Repository 4

### Name
watchdog

### GitHub
https://github.com/gorakhargosh/watchdog

### Status
Verified

### Rating
★★★★★

### Purpose
Monitor file system changes.

### Features
- File monitoring
- Folder monitoring
- Automatic refresh
- Event handling

### Claude Should Study
- File watching
- Event-driven programming
- Automatic updates

### Why We Chose It
Useful when applications need to react automatically to file changes.

---

## Repository 5

### Name
platformdirs

### GitHub
https://github.com/tox-dev/platformdirs

### Status
Verified

### Rating
★★★★★

### Purpose
Locate operating system directories correctly.

### Features
- User data folders
- Cache folders
- Configuration folders
- Cross-platform support

### Claude Should Study
- Application data storage
- User settings
- Cache management

### Why We Chose It
Ensures files are stored in the correct Windows, macOS and Linux locations.

---

## Repository 6

### Name
pyperclip

### GitHub
https://github.com/asweigart/pyperclip

### Status
Verified

### Rating
★★★★★

### Purpose
Clipboard management.

### Features
- Copy text
- Paste text
- Clipboard monitoring

### Claude Should Study
- Clipboard operations
- Copy and paste functionality

### Why We Chose It
Useful for copying registration numbers, transcript references and report data.

---

## Repository 7

### Name
desktop-notifier

### GitHub
https://github.com/samschott/desktop-notifier

### Status
Verified

### Rating
★★★★★

### Purpose
Cross-platform desktop notifications.

### Features
- Toast notifications
- Notification actions
- Scheduled notifications
- Cross-platform support

### Claude Should Study
- User notifications
- Background alerts
- Reminder systems

### Why We Chose It
Provides modern desktop notifications for completed tasks, updates and reminders.

---

## Repository 8

### Name
tenacity

### GitHub
https://github.com/jd/tenacity

### Status
Verified

### Rating
★★★★★

### Purpose
Retry failed operations automatically.

### Features
- Automatic retries
- Exponential backoff
- Error handling
- Retry policies

### Claude Should Study
- Fault tolerance
- Network retries
- Database retry logic

### Why We Chose It
Improves application reliability when temporary failures occur.

---

## Repository 9

### Name
python-dotenv

### GitHub
https://github.com/theskumar/python-dotenv

### Status
Verified

### Rating
★★★★★

### Purpose
Load environment variables from .env files.

### Features
- Environment configuration
- Secret management
- API key storage

### Claude Should Study
- Environment variables
- Secure configuration
- Secret handling

### Why We Chose It
Keeps sensitive settings out of the application source code.

---

## Repository 10

### Name
Rich

### GitHub
https://github.com/Textualize/rich

### Status
Verified

### Rating
★★★★★

### Purpose
Rich text formatting and console output.

### Features
- Progress bars
- Tables
- Syntax highlighting
- Status indicators
- Logging support

### Claude Should Study
- Progress indicators
- Diagnostic output
- Development tools

### Why We Chose It
Useful for developer tools, installers and command-line utilities that accompany desktop applications.

---

## Summary

### Primary Recommendation
- Loguru
- Dynaconf
- APScheduler
- watchdog
- platformdirs

### Secondary Recommendation
- desktop-notifier
- pyperclip
- tenacity
- python-dotenv
- Rich

### Best Use Cases
- Logging and diagnostics
- Configuration management
- Scheduled backups
- Automatic report generation
- File monitoring
- Desktop notifications
- Clipboard operations
- Secure environment configuration
- Fault-tolerant operations
- Developer tools

---

# Utilities Development Standards

Claude should use small, reliable utility modules for common tasks instead of repeating the same code throughout the application.

## Common Utility Modules

A professional desktop application may include:

- Date and time utilities
- File utilities
- Folder utilities
- Validation utilities
- String utilities
- Number utilities
- Formatting utilities
- Encryption utilities
- Logging utilities
- Configuration utilities
- Clipboard utilities
- Notification utilities
- Network utilities
- System utilities
- Export utilities

---

## Date and Time

The application should handle dates consistently.

Common requirements include:

- Current date
- Current time
- Date formatting
- Date-range calculations
- Academic sessions
- Semester dates
- Approval dates
- Examination dates
- Report dates

Use a consistent internal date format.

Display dates in a user-friendly format.

Example:

```text
Database:
2026-08-08

Display:
8 August 2026
