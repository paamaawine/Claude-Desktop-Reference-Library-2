# Verified File Management Standards

File operations should be safe, predictable and easy for users to understand.

## Supported Operations

Where required, applications may support:

- Create
- Open
- Read
- Copy
- Move
- Rename
- Delete
- Import
- Export

## File Validation

Before processing a file, check:

- File exists
- File type
- File size
- File path
- File permissions
- File contents where required

## File Paths

Do not trust user-supplied file paths.

Prevent access to unauthorised directories and path traversal.

## Temporary Files

Temporary files should be stored in an appropriate temporary location.

Remove temporary files when they are no longer required.

## File Naming

Use clear and predictable file names.

Avoid characters that are invalid on supported operating systems.

## Delete Operations

Destructive file operations should require confirmation where appropriate.

Example:

```text
Are you sure you want to delete this file?
