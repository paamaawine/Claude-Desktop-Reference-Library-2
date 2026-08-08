# Verified Email and SMTP Standards

Claude should build email functions as a separate service so that email settings and sending logic are not scattered throughout the application.

---

## Email Architecture

Use a dedicated email service:

```text
User Interface
      ↓
Email Service
      ↓
SMTP Provider
      ↓
Recipient
