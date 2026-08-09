# Verified Logging Standards

Logging should help developers and administrators understand application activity, errors and security events without exposing sensitive information.

## Log Levels

Use suitable log levels:

- DEBUG
- INFO
- WARNING
- ERROR
- CRITICAL

Use DEBUG for detailed development information and avoid excessive DEBUG logging in production.

## Useful Events

Log important events such as:

- Application startup
- Application shutdown
- Login
- Logout
- Record creation
- Record modification
- Record deletion
- Import
- Export
- Backup
- Restore
- API operations
- Errors

## Sensitive Information

Never log:

- Passwords
- API keys
- Access tokens
- Encryption keys
- SMTP passwords
- Database passwords
- Security tokens

Sensitive personal information should also be excluded unless there is a clear operational need.

## Error Logging

Errors should include enough information to support troubleshooting.

Where appropriate, record:

- Date
- Time
- Operation
- Error type
- Safe error message
- Relevant record or request identifier

Do not expose full technical traces to ordinary users.

## Log Files

Logs should be stored in a controlled location.

Consider:

- File permissions
- File size
- Rotation
- Retention
- Backup requirements

## Log Rotation

Prevent logs from growing without limit.

Use rotation based on:

- File size
- Time
- Number of retained files

## Audit Logs

Where required, maintain audit records for important actions.

An audit record may contain:

```text
User
Action
Date
Time
Record
Result
