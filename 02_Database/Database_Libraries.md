---

# Repository 1: SQLAlchemy

**GitHub Repository**
https://github.com/sqlalchemy/sqlalchemy

**Verified:** ✅ Yes

**Stars:** 12k+

**Last Updated:** Active

**Purpose**
- Industry-standard Python ORM.
- Supports SQLite, MySQL, PostgreSQL, SQL Server and Oracle.
- Ideal for professional desktop applications.
- Recommended as the primary database engine for Claude projects.

**Why we are keeping it**
Claude can use SQLAlchemy to build a clean data layer that can easily switch from SQLite to PostgreSQL or MySQL in future without rewriting the application.

**Status:** APPROVED ✅

---

# Repository 2: Alembic

**GitHub Repository**
https://github.com/sqlalchemy/alembic

**Verified:** ✅ Yes

**Stars:** 4k+

**Last Updated:** Active

**Purpose**
- Official database migration tool for SQLAlchemy.
- Tracks database schema changes.
- Creates migration scripts automatically.
- Upgrades or rolls back database versions safely.

**Why we are keeping it**
Claude can use Alembic to update the application's database structure without deleting existing student records. It is essential for maintaining production databases as new features are added.

**Status:** APPROVED ✅

---

# Repository 3: SQLModel

**GitHub Repository**
https://github.com/fastapi/sqlmodel

**Verified:** ✅ Yes

**Stars:** 18k+

**Last Updated:** Active

**Purpose**
- Built on SQLAlchemy and Pydantic.
- Simplifies database model creation.
- Reduces boilerplate code.
- Fully compatible with SQLite.

**Why we are keeping it**
Claude can use SQLModel when a cleaner and simpler ORM is preferred while still benefiting from SQLAlchemy's reliability and performance.

**Status:** APPROVED ✅

---

# Repository 4: Peewee

**GitHub Repository**
https://github.com/coleifer/peewee

**Verified:** ✅ Yes

**Stars:** 12k+

**Last Updated:** Active

**Purpose**
- Lightweight Python ORM.
- Excellent support for SQLite.
- Simple API with fast performance.
- Suitable for small and medium desktop applications.

**Why we are keeping it**
Although SQLAlchemy will remain our primary ORM, Peewee provides Claude with an excellent alternative for lightweight projects or prototypes.

**Status:** APPROVED ✅
