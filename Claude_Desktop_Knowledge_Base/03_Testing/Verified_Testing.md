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
