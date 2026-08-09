# Verified Testing Standards

Testing should be part of the development process, not something done only before release.

Claude should create tests for the application's business logic, database, user interface, security and major workflows.

---

## Testing Structure

Use a clear testing structure:

```text
tests/
├── unit/
├── integration/
├── database/
├── ui/
├── security/
└── fixtures/

# Verified Testing Standards

Testing should be part of the development process, not something done only before release.

Claude should create tests for business logic, database operations, user interfaces, security and major application workflows.

## Unit Testing

Unit tests should verify individual functions and classes.

Test:

- Normal input
- Invalid input
- Boundary values
- Expected errors
- Business rules

## Integration Testing

Integration tests should verify that application components work correctly together.

Examples include:

- Service and repository
- Repository and database
- Authentication and database
- Import and database
- Reporting and database

## Database Testing

Database tests should verify:

- Record creation
- Record retrieval
- Record updates
- Record deletion
- Constraints
- Transactions
- Relationships
- Search and filtering
- Backup and restore

## UI Testing

Important user workflows should be tested.

Examples:

- Login
- Add record
- Edit record
- Delete record
- Search
- Filter
- Import
- Export
- Print
- Logout

## Security Testing

Test:

- Invalid login
- Incorrect passwords
- Permission restrictions
- Session expiry
- Password reset
- Input validation
- Access control
- Protected operations

Never use real production credentials in tests.

## Regression Testing

When an existing feature is changed, related tests should be run again.

A change to one part of the application should not silently break another part.

## Test Data

Use controlled test data.

Do not use sensitive real-world user data unless there is a clear and authorised reason.

## Test Isolation

Tests should avoid depending on the order in which other tests run.

Each test should create or use the data it needs.

## Fixtures

Reusable test data and setup should be kept in fixtures where appropriate.

Example:

```text
tests/
├── unit/
├── integration/
├── database/
├── ui/
├── security/
└── fixtures/
