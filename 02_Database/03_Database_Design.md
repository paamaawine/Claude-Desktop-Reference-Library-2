# Database Design

Search GitHub

Database Design

ER Diagram

Entity Relationship

Database Normalization

Study

One-to-One

One-to-Many

Many-to-Many

Indexes

Constraints

Primary Keys

Foreign Keys

Unique Constraints

Composite Keys

Database naming conventions

# Verified Database Design Standards

Database design should provide clear relationships, reliable data storage and efficient access.

## Database Structure

Design tables around clear business entities.

Examples include:

- Users
- Students
- Applications
- Payments
- Courses
- Departments
- Reports

Avoid storing unrelated data in one large table.

## Normalisation

Use normalisation where it improves data quality and reduces duplication.

Common levels include:

- First Normal Form
- Second Normal Form
- Third Normal Form

Do not over-normalise a simple desktop application when it creates unnecessary complexity.

## Primary Keys

Each major table should have a primary key.

The key should uniquely identify each record.

## Foreign Keys

Use foreign keys to maintain relationships between related tables.

Example:

```text
Students
   ↓
Applications
   ↓
Payments
