# Verified API Libraries Standards

Claude should select API libraries based on the actual needs of the application.

API integrations should be isolated from the user interface and business logic.

## API Architecture

Use a structure similar to:

```text
User Interface
      ↓
API Service
      ↓
API Client
      ↓
External API
