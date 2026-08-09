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


# Verified Email and SMTP Standards

Email features should be reliable, secure and easy to configure.

## SMTP

SMTP should be used when the application needs to send email through an external mail server.

Common SMTP settings include:

- SMTP host
- SMTP port
- Username
- Password
- Encryption method
- Sender email
- Sender name

## Encryption

Use secure SMTP connections where supported.

Prefer:

- TLS
- STARTTLS

Avoid unencrypted authentication where a secure option is available.

## Credentials

Never hard-code SMTP passwords in application source code.

Sensitive credentials should be stored securely.

## Email Configuration

Provide a clear configuration screen where authorised users can enter or update email settings.

Example:

```text
SMTP Host
SMTP Port
Username
Password
Security
Sender Email
Sender Name
