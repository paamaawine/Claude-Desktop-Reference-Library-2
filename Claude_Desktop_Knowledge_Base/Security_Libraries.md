# Verified Security Libraries Standards

Claude should use established and well-tested Python security libraries rather than creating security functions from scratch.

Security controls should be kept separate from the user interface.

## Password Hashing

Use a recognised password-hashing library.

Recommended options include:

- Argon2
- bcrypt
- PBKDF2

Passwords must never be stored as plain text.

The application should store a secure password hash instead.

## Argon2

Argon2 is a modern password-hashing method.

GitHub Repository:

https://github.com/hynek/argon2_cffi

Use Argon2 when a strong password-hashing method is required.

Status: APPROVED

## bcrypt

bcrypt is an established password-hashing method.

GitHub Repository:

https://github.com/pyca/bcrypt

It may be used where the project already relies on bcrypt or requires compatibility with an existing password system.

Status: APPROVED

## Cryptography

The Python Cryptography package provides cryptographic tools for secure applications.

GitHub Repository:

https://github.com/pyca/cryptography

It may be used for:

- Encryption
- Decryption
- Digital signatures
- Key management
- Secure tokens
- Certificate-related operations

Status: APPROVED

Do not create custom cryptographic algorithms.

## Secrets

Use Python's standard `secrets` module for security-sensitive random values.

Suitable uses include:

- Password-reset tokens
- Session tokens
- Verification tokens
- Temporary security codes

Do not use ordinary random-number functions for security tokens.

## API Keys and Credentials

API keys, passwords and other secrets must not be hard-coded.

Avoid:

```python
API_KEY = "real-secret-key"


# Verified Security Library Standards

Security libraries should be selected based on the application's actual security requirements.

## General Rule

Use established, maintained libraries rather than writing cryptographic or security functions from scratch.

Security-sensitive code should be kept simple and tested carefully.

## Password Security

Use recognised password-hashing libraries and algorithms.

Approved approaches may include:

- Argon2
- bcrypt
- PBKDF2

Never store passwords as plain text.

## Cryptography

Use established cryptographic libraries for:

- Encryption
- Decryption
- Secure hashing
- Digital signatures
- Key management

Do not implement cryptographic algorithms manually.

## Secrets

Do not place secrets directly in source code.

Protect:

- Passwords
- API keys
- Access tokens
- Encryption keys
- SMTP credentials
- Database credentials

## Input Validation

Validate user input before processing it.

Check:

- Required fields
- Data types
- Length
- Allowed values
- File types
- File sizes

## File Security

Files uploaded or imported by users should be checked before processing.

Consider:

- File extension
- MIME type
- File size
- File contents
- Storage location

## Database Security

Use:

- Parameterised queries
- Access controls
- Secure credentials
- Transactions
- Input validation

Never build SQL queries by directly joining untrusted user input.

## Authentication

Authentication should include:

- Secure password storage
- Failed-login protection
- Session management
- Logout
- Password reset
- Role-based access where required

## Authorisation

Authentication confirms who the user is.

Authorisation determines what the user is allowed to do.

Protected operations should check permissions on the server or application service layer, not only in the UI.

## Security Logging

Record useful security events such as:

- Login
- Logout
- Failed login
- Password change
- Permission changes
- Account lockout
- Security errors

Never log:

- Passwords
- Access tokens
- API keys
- Encryption keys

## Dependency Security

Keep security-related dependencies updated.

Review dependencies for:

- Known vulnerabilities
- Maintenance status
- Supported versions
- Licence requirements

## Security Checklist

- [ ] Established security libraries used
- [ ] Passwords securely hashed
- [ ] Secrets protected
- [ ] User input validated
- [ ] Files validated
- [ ] Database queries parameterised
- [ ] Authentication protected
- [ ] Authorisation enforced
- [ ] Security events logged safely
- [ ] Dependencies reviewed
