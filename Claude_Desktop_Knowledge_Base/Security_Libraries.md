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
