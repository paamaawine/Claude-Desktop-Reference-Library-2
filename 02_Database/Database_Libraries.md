# Verified Database Libraries Standards

Claude should select database libraries based on the needs of the application.

The database layer should remain separate from the user interface.

## SQLAlchemy

SQLAlchemy is a widely used Python database toolkit and ORM.

It is suitable for applications that require:

- Structured database models
- Database queries
- Relationships
- Transactions
- Database abstraction
- Support for multiple database engines

GitHub Repository: https://github.com/sqlalchemy/sqlalchemy

Status: APPROVED

SQLAlchemy should be the preferred ORM when the project needs a structured and portable database layer.

## SQLite

SQLite is suitable for many offline desktop applications.

Use SQLite when the application needs:

- Local storage
- Offline operation
- A simple database
- Low administration needs
- A single-user or small-user environment

SQLite is a good default for many standalone desktop applications.

## SQLModel

SQLModel may be used when a simple combination of Python type models and database models is useful.

It can be suitable for applications using:

- Python
- SQL databases
- Type hints
- ORM-based data access

Choose SQLModel only when its features provide a clear benefit to the project.

## Peewee

Peewee is a lightweight Python ORM suitable for smaller applications.

It may be considered when:

- The application is small
- Simple database models are required
- A lightweight ORM is preferred

Do not introduce Peewee into a project that already uses another ORM without a clear reason.

## Database Driver Selection

Use the appropriate driver for the selected database.

Examples include:

- SQLite
- PostgreSQL
- MySQL

The database driver should match the database engine and application requirements.

## Database Abstraction

Applications should avoid spreading raw database operations throughout the UI.

Recommended structure:

UI  
↓  
Service  
↓  
Repository  
↓  
Database

Example:

StudentForm  
↓  
StudentService  
↓  
StudentRepository  
↓  
SQLite

## Repository Pattern

A repository should contain database access operations where the project benefits from such separation.

Example:

```text
StudentRepository
├── create()
├── get_by_id()
├── get_all()
├── update()
└── delete()
