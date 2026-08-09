# Database Development

This folder contains references and best practices for building robust desktop application databases.

Topics include:

- SQLite
- SQLAlchemy
- CRUD architecture
- Search
- Filtering
- Data validation
- Backup
- Recovery
- Import and export
- Example projects

# Verified Database Knowledge Base

This section provides standards for database design, development, testing, backup and recovery in desktop applications.

## Core Areas

The database knowledge base covers:

- SQLite
- SQLAlchemy
- Database design
- CRUD architecture
- Search and filtering
- Backup and recovery
- Import and export
- Data validation
- Example database projects
- Database APIs
- Database libraries

## Recommended Architecture

Use a clear separation between the interface, application logic and database.

```text
User Interface
      ↓
Service Layer
      ↓
Repository Layer
      ↓
Database Library
      ↓
Database
