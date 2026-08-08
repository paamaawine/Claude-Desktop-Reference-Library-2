# Verified Packaging & Deployment Libraries

---

## Repository 1

### Name
PyInstaller

### GitHub
https://github.com/pyinstaller/pyinstaller

### Status
Verified

### Rating
★★★★★

### Purpose
Convert Python applications into standalone Windows executables.

### Features
- Generate .exe files
- One-file packaging
- One-folder packaging
- Bundle dependencies
- Cross-platform support

### Claude Should Study
- Executable creation
- Resource bundling
- Application packaging
- Build configuration

### Why We Chose It
PyInstaller is the most widely used packaging tool for Python desktop applications and is ideal for distributing applications without requiring users to install Python.

---

## Repository 2

### Name
Nuitka

### GitHub
https://github.com/Nuitka/Nuitka

### Status
Verified

### Rating
★★★★★

### Purpose
Compile Python applications into high-performance executables.

### Features
- Native compilation
- Performance optimisation
- Executable generation
- Code protection
- Standalone builds

### Claude Should Study
- Python compilation
- Performance optimisation
- Executable generation

### Why We Chose It
Produces faster executables and offers better source code protection than traditional packaging tools.

---

## Repository 3

### Name
auto-py-to-exe

### GitHub
https://github.com/brentvollebregt/auto-py-to-exe

### Status
Verified

### Rating
★★★★★

### Purpose
Graphical interface for PyInstaller.

### Features
- GUI packaging
- Build configuration
- Icon selection
- Hidden imports
- Resource inclusion

### Claude Should Study
- Packaging options
- Build settings
- Resource management

### Why We Chose It
Makes executable creation much easier and helps visualise PyInstaller options.

---

## Repository 4

### Name
cx_Freeze

### GitHub
https://github.com/marcelotduarte/cx_Freeze

### Status
Verified

### Rating
★★★★★

### Purpose
Create standalone executables from Python applications.

### Features
- Windows executables
- MSI installer support
- Dependency packaging
- Cross-platform builds

### Claude Should Study
- Executable generation
- Installer creation
- Deployment

### Why We Chose It
Provides an excellent alternative to PyInstaller with strong Windows support.

---

## Repository 5

### Name
Briefcase

### GitHub
https://github.com/beeware/briefcase

### Status
Verified

### Rating
★★★★★

### Purpose
Package Python applications for Windows, macOS and Linux.

### Features
- Native installers
- Cross-platform deployment
- Desktop integration
- Application templates

### Claude Should Study
- Cross-platform packaging
- Native installers
- Application deployment

### Why We Chose It
Useful when the application needs to run on multiple desktop operating systems.

---

## Repository 6

### Name
Inno Setup

### GitHub
https://github.com/jrsoftware/issrc

### Status
Verified

### Rating
★★★★★

### Purpose
Professional Windows installer creator.

### Features
- Installation wizard
- Desktop shortcuts
- Start Menu entries
- Registry configuration
- Uninstaller

### Claude Should Study
- Installer creation
- Installation scripts
- Application deployment

### Why We Chose It
Creates polished installation packages similar to commercial Windows software.

---

## Repository 7

### Name
WinSparkle

### GitHub
https://github.com/vslavik/winsparkle

### Status
Verified

### Rating
★★★★★

### Purpose
Automatic update framework for Windows applications.

### Features
- Update checking
- Automatic downloads
- Version management
- Secure updates

### Claude Should Study
- Auto-update systems
- Version control
- Update notifications

### Why We Chose It
Allows deployed desktop applications to check for and install updates automatically.

---

## Summary

### Primary Recommendation
- PyInstaller
- Nuitka
- Inno Setup

### Secondary Recommendation
- auto-py-to-exe
- cx_Freeze
- Briefcase
- WinSparkle

### Best Use Cases
- Build standalone .exe applications
- Create professional Windows installers
- Deploy commercial desktop software
- Enable automatic updates
- Protect application source code

---

# Packaging and Deployment Standards

Claude should build desktop applications that can be packaged and installed easily on Windows computers without requiring the user to install Python.

## Primary Packaging Tool

### PyInstaller

### GitHub
https://github.com/pyinstaller/pyinstaller

### Purpose
Packages Python applications and their dependencies into distributable applications.

### Claude Should Study
- Application bundling
- Executable creation
- Hidden imports
- Resource files
- Application icons
- One-folder builds
- One-file builds
- Spec files

### Recommendation
Use PyInstaller as the default packaging tool for Python desktop applications unless project requirements require another solution.

---

## Windows Executable

The final application should be capable of producing:

```text
Application.exe
