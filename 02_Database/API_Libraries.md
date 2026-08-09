# Verified API Libraries Standards

Claude should select API libraries based on the actual needs of the application.

API integrations should be isolated from the user interface and business logic.

## API Architecture

Use a structure similar to:

```text
User Interface
      ↓
API Service
      ↓
API Client
      ↓
External API

# Verified Database API Library Standards

Database APIs and libraries should provide safe and maintainable access to application data.

## SQLAlchemy

SQLAlchemy is suitable for Python applications that require an ORM or structured database access layer.

Use it for:

- Models
- Queries
- Relationships
- Transactions
- Database connections

## SQLite

SQLite is suitable for many local desktop applications.

Use it for:

- Offline applications
- Local storage
- Lightweight deployments
- Single-user applications
- Small desktop systems

## PostgreSQL

PostgreSQL is suitable for applications requiring a robust server-based relational database.

Consider it when the application requires:

- Multiple users
- Centralised data
- Advanced database features
- Larger datasets
- Strong concurrent access

## MySQL

MySQL may be used where the project already depends on the MySQL ecosystem or requires a server-based relational database.

## Microsoft SQL Server

Microsoft SQL Server may be appropriate for organisations already using Microsoft database infrastructure.

## Oracle Database

Oracle may be considered for enterprise environments that already depend on Oracle infrastructure and tooling.

## Database Drivers

Use the official or well-maintained database driver appropriate for the selected database engine.

Examples include:

```text
SQLite
PostgreSQL
MySQL
SQL Server
Oracle
