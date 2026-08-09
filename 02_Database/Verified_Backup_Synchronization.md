# Verified Backup & Synchronization Libraries

---

## Repository 1

### Name
rsync

### GitHub
https://github.com/RsyncProject/rsync

### Status
Verified

### Rating
★★★★★

### Purpose
Industry-standard file synchronisation and backup utility.

### Features
- Incremental backup
- Folder synchronisation
- Delta transfer
- Remote backup
- File comparison

### Claude Should Study
- Backup strategies
- File synchronisation
- Incremental updates
- Disaster recovery

### Why We Chose It
The benchmark for reliable and efficient file synchronisation across platforms.

---

## Repository 2

### Name
rclone

### GitHub
https://github.com/rclone/rclone

### Status
Verified

### Rating
★★★★★

### Purpose
Synchronise files between local storage and cloud providers.

### Features
- OneDrive
- Google Drive
- Dropbox
- Amazon S3
- Encryption
- Scheduled backup

### Claude Should Study
- Cloud synchronisation
- Backup automation
- Remote storage

### Why We Chose It
Supports dozens of cloud providers through one consistent interface.

---

## Repository 3

### Name
borgbackup

### GitHub
https://github.com/borgbackup/borg

### Status
Verified

### Rating
★★★★★

### Purpose
Deduplicating backup system.

### Features
- Compression
- Encryption
- Deduplication
- Version history
- Fast restore

### Claude Should Study
- Versioned backups
- Secure storage
- Backup optimisation

### Why We Chose It
Ideal for enterprise systems that require secure and storage-efficient backups.

---

## Repository 4

### Name
Restic

### GitHub
https://github.com/restic/restic

### Status
Verified

### Rating
★★★★★

### Purpose
Modern encrypted backup solution.

### Features
- Encryption
- Incremental backups
- Snapshot management
- Cloud support
- Cross-platform

### Claude Should Study
- Secure backup
- Snapshot recovery
- Backup scheduling

### Why We Chose It
Provides simple, secure and reliable backups for desktop applications.

---

## Repository 5

### Name
Syncthing

### GitHub
https://github.com/syncthing/syncthing

### Status
Verified

### Rating
★★★★★

### Purpose
Peer-to-peer file synchronisation.

### Features
- Real-time synchronisation
- Local network support
- Encryption
- Version control
- Cross-device sync

### Claude Should Study
- Real-time synchronisation
- Distributed storage
- Device pairing

### Why We Chose It
Excellent for keeping records synchronised across multiple computers without relying on third-party cloud services.

---

## Repository 6

### Name
Duplicati

### GitHub
https://github.com/duplicati/duplicati

### Status
Verified

### Rating
★★★★★

### Purpose
Backup software with cloud support.

### Features
- Scheduled backups
- Compression
- Encryption
- Cloud destinations
- Restore wizard

### Claude Should Study
- Automated backups
- Recovery workflows
- Backup scheduling

### Why We Chose It
Provides a mature backup workflow suitable for enterprise desktop applications.

---

## Repository 7

### Name
watchdog

### GitHub
https://github.com/gorakhargosh/watchdog

### Status
Verified

### Rating
★★★★★

### Purpose
Monitor file system events.

### Features
- Folder monitoring
- File creation detection
- File modification detection
- Automatic triggers

### Claude Should Study
- File monitoring
- Automatic backup triggers
- Synchronisation events

### Why We Chose It
Allows applications to automatically back up files whenever changes occur.

---

## Repository 8

### Name
pyfilesystem2

### GitHub
https://github.com/PyFilesystem/pyfilesystem2

### Status
Verified

### Rating
★★★★★

### Purpose
Unified filesystem abstraction library.

### Features
- Local storage
- FTP
- SFTP
- ZIP files
- Memory filesystem
- Cloud storage support

### Claude Should Study
- Storage abstraction
- File management
- Portable file operations

### Why We Chose It
Simplifies working with multiple storage backends through one API.

---

## Repository 9

### Name
send2trash

### GitHub
https://github.com/arsenetar/send2trash

### Status
Verified

### Rating
★★★★★

### Purpose
Move files safely to the operating system recycle bin.

### Features
- Windows Recycle Bin
- macOS Trash
- Linux Trash
- Safe deletion

### Claude Should Study
- Safe file deletion
- Undo support
- File recovery

### Why We Chose It
Safer than permanently deleting user files.

---

## Repository 10

### Name
portalocker

### GitHub
https://github.com/WoLpH/portalocker

### Status
Verified

### Rating
★★★★★

### Purpose
Cross-platform file locking library.

### Features
- File locking
- Concurrent access protection
- Cross-platform support
- Shared locks

### Claude Should Study
- Concurrent file access
- Data integrity
- Multi-user applications

### Why We Chose It
Prevents database corruption and file conflicts when multiple users or processes access the same files.

---

## Summary

### Primary Recommendation
- rsync
- rclone
- Restic
- watchdog
- portalocker

### Secondary Recommendation
- borgbackup
- Syncthing
- Duplicati
- pyfilesystem2
- send2trash

### Best Use Cases
- Automatic database backups
- Student records protection
- Transcript archive management
- Senate approval backups
- Cloud synchronisation
- Disaster recovery
- File monitoring
- Multi-user desktop systems
- Version history
- Secure enterprise storage

# Verified Backup and Synchronisation Standards

Backup and synchronisation features should protect important application data and reduce the risk of data loss.

## Backup

The application may provide:

- Backup Database
- Restore Database
- Verify Backup
- Automatic Backup
- Backup History

## Manual Backup

Users with the required permission should be able to create a backup manually.

A backup should contain the required application data and preserve database integrity.

## Automatic Backup

Automatic backups may run:

- On application close
- On a scheduled interval
- Before major database changes
- Before migrations

The schedule should be configurable where appropriate.

## Backup Location

Backups should be stored in a controlled location.

Avoid storing backups in temporary folders.

Users should be able to select a suitable backup location where appropriate.

## Backup Naming

Use clear names that help identify the backup.

Example:

```text
database_backup_2026-08-09_0815.db
