# Verified Database Libraries

---

## SQLModel

Repository:
https://github.com/fastapi/sqlmodel

Purpose:
Modern ORM for Python using SQLAlchemy and Pydantic.

Use:
- Student records
- Senate approvals
- Transcript tracking
- Plagiarism records
- Staff management

Status:
Verified

---

## SQLAlchemy

Repository:
https://github.com/sqlalchemy/sqlalchemy

Purpose:
Industry-standard ORM.

Use:
- Complex databases
- Multi-table relationships
- Large desktop applications

Status:
Verified

---

## Peewee

Repository:
https://github.com/coleifer/peewee

Purpose:
Lightweight ORM.

Use:
- Small and medium desktop apps
- SQLite databases

Status:
Verified

---

## SQLite Browser

Repository:
https://github.com/sqlitebrowser/sqlitebrowser

Purpose:
SQLite database viewer/editor.

Use:
- Inspect databases
- Debug data
- Database maintenance

Status:
Verified

---

## Dataset

Repository:
https://github.com/pudo/dataset

Purpose:
Simple SQL wrapper.

Use:
- Rapid database development
- Quick data access

Status:
Verified

---

# Database Development Standards

Claude should use a reliable database architecture for all desktop applications.

## Primary Database

### SQLite

SQLite should be the default database for applications that need:

- Offline operation
- Local data storage
- Student records
- Staff records
- Senate records
- Transcript records
- Settings
- Audit logs
- Application configuration

### Recommended SQLite Features

Claude should consider:

- Foreign keys
- Transactions
- Indexes
- Views
- Triggers
- WAL mode
- Full-text search
- Database backup
- Database integrity checks

---

## Database Architecture

The application should separate database access from the user interface.

Recommended structure:

```text
UI
 |
ViewModel / Controller
 |
Service Layer
 |
Repository Layer
 |
Database
