# Verified Desktop Patterns and Best Practices

---

## Pattern 1

### Name
Model-View-ViewModel (MVVM)

### Purpose
Separate the user interface from application logic.

### Benefits
- Easier maintenance
- Better testing
- Cleaner code
- Reusable components
- Better scalability

### Claude Should Apply
- Every PySide6 project
- Enterprise applications
- Multi-window systems

### Why We Chose It
MVVM produces cleaner applications and prevents business logic from being mixed with interface code.

---

## Pattern 2

### Name
Repository Pattern

### Purpose
Separate database operations from business logic.

### Benefits
- Easier testing
- Database independence
- Cleaner architecture

### Claude Should Apply
- SQLite
- PostgreSQL
- MySQL
- SQL Server

### Why We Chose It
Allows databases to change without affecting the rest of the application.

---

## Pattern 3

### Name
Service Layer

### Purpose
Keep business rules separate from the user interface.

### Benefits
- Reusable logic
- Easier maintenance
- Better organisation

### Claude Should Apply
- Authentication
- Transcript generation
- Senate approval
- Reporting

### Why We Chose It
Business rules belong in services, not windows.

---

## Pattern 4

### Name
Command Pattern

### Purpose
Encapsulate user actions.

### Benefits
- Undo/Redo
- Macro support
- Logging

### Claude Should Apply
- Delete
- Save
- Print
- Import
- Export

### Why We Chose It
Provides professional application behaviour.

---

## Pattern 5

### Name
Observer Pattern

### Purpose
Notify different modules when data changes.

### Benefits
- Loose coupling
- Live updates
- Real-time interfaces

### Claude Should Apply
- Dashboard refresh
- Student updates
- Notifications

### Why We Chose It
Essential for responsive desktop software.

---

## Pattern 6

### Name
Singleton Pattern

### Purpose
Ensure one instance of important services.

### Benefits
- Memory efficiency
- Shared resources
- Consistency

### Claude Should Apply
- Configuration
- Database connection
- Logger

### Why We Chose It
Prevents duplicate services from consuming resources.

---

## Pattern 7

### Name
Factory Pattern

### Purpose
Create objects without exposing creation logic.

### Benefits
- Cleaner code
- Flexible object creation
- Easier extension

### Claude Should Apply
- Reports
- Charts
- Documents
- Dialogs

### Why We Chose It
Simplifies complex object creation.

---

## Pattern 8

### Name
Dependency Injection

### Purpose
Provide dependencies externally.

### Benefits
- Testability
- Loose coupling
- Maintainability

### Claude Should Apply
- Services
- Database
- Authentication
- Reporting

### Why We Chose It
A foundation of modern enterprise software.

---

## Pattern 9

### Name
Event Bus

### Purpose
Allow modules to communicate through events.

### Benefits
- Modular applications
- Plugin support
- Better scalability

### Claude Should Apply
- Notifications
- Background tasks
- Live dashboards

### Why We Chose It
Reduces dependencies between modules.

---

## Pattern 10

### Name
Plugin Architecture

### Purpose
Allow applications to load external modules.

### Benefits
- Extensibility
- Modular design
- Easier upgrades

### Claude Should Apply
- Statistical modules
- AI modules
- Reporting modules

### Why We Chose It
Allows features to be added without rebuilding the application.

---

## Pattern 11

### Name
Background Worker Threads

### Purpose
Prevent the interface from freezing.

### Benefits
- Responsive UI
- Better user experience
- Faster workflows

### Claude Should Apply
- Importing files
- Exporting reports
- AI processing
- OCR
- Database backups

### Why We Chose It
Enterprise software should never freeze during long operations.

---

## Pattern 12

### Name
Structured Logging

### Purpose
Record application activity and errors.

### Benefits
- Easier debugging
- Audit trail
- Error diagnosis

### Claude Should Apply
- User login
- Database operations
- Printing
- Import/Export
- AI modules

### Why We Chose It
Essential for maintaining enterprise applications.

---

## Pattern 13

### Name
Centralised Configuration

### Purpose
Store application settings in one place.

### Benefits
- Easier maintenance
- Environment management
- Simpler deployment

### Claude Should Apply
- Database settings
- Themes
- SMTP
- API Keys
- User preferences

### Why We Chose It
Avoids scattered configuration files.

---

## Pattern 14

### Name
Role-Based Access Control (RBAC)

### Purpose
Restrict application features based on user roles.

### Benefits
- Improved security
- Controlled permissions
- Easier administration

### Claude Should Apply
- Administrator
- Registry Staff
- Lecturer
- Examiner
- Student
- Auditor

### Why We Chose It
Critical for university and enterprise management systems.

---

## Pattern 15

### Name
Offline-First Design

### Purpose
Allow applications to operate without internet access.

### Benefits
- Reliability
- Faster performance
- Better availability

### Claude Should Apply
- Student Management
- Statistical Software
- Transcript System
- Senate Tracking
- Examination Processing

### Why We Chose It
Most university administrative work should continue even without internet connectivity.

---

## Standard Folder Structure

```
project/

│

├── assets/

├── config/

├── controllers/

├── database/

├── dialogs/

├── docs/

├── icons/

├── logs/

├── models/

├── reports/

├── resources/

├── services/

├── tests/

├── themes/

├── ui/

├── utils/

├── views/

├── workers/

├── main.py

└── requirements.txt
```

---

## Enterprise Rules Claude Should Always Follow

- Separate UI from business logic.
- Never place SQL directly inside UI code.
- Use worker threads for long-running tasks.
- Validate all user input.
- Log every important operation.
- Encrypt sensitive data.
- Support automatic backups.
- Use parameterised SQL queries.
- Follow PEP 8 coding standards.
- Design modules to be reusable.
- Keep configuration outside the source code.
- Build applications to work offline first.
- Package applications as standalone executables.
- Include comprehensive error handling.
- Design interfaces to scale from small to high-resolution displays.
