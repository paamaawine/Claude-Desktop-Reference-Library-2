# Verified Configuration Standards

Application configuration should be separate from application source code.

## Configuration Types

Configuration may include:

- Database location
- Application name
- Theme
- Language
- Email settings
- SMTP server
- Backup location
- Logging level
- API endpoints
- Feature settings

## Sensitive Configuration

Never store sensitive credentials directly in source code.

Protect:

- Passwords
- API keys
- Access tokens
- Encryption keys
- SMTP credentials
- Database credentials

## Environment Variables

Environment variables may be used for sensitive or deployment-specific configuration.

Examples include:

```text
DATABASE_URL
SMTP_HOST
SMTP_USERNAME
SMTP_PASSWORD
API_KEY
