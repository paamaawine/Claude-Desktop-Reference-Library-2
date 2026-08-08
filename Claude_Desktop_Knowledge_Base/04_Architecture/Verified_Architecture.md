# Verified Desktop Application Architecture Standards

Claude should build desktop applications using a clear, modular architecture.

The architecture should keep the user interface, business rules, database access and external services separate.

---

## Recommended Architecture

Use:

```text
Presentation Layer
        ↓
Application / Service Layer
        ↓
Repository Layer
        ↓
Database / External Services
