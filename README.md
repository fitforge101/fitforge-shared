🔗 **Central Documentation:** [https://github.com/fitforge101/fitforge-app-docs](https://github.com/fitforge101/fitforge-app-docs)

# Shared Module

## Overview
The `fitforge-shared` repository is designated for common utilities, custom Express middleware, type definitions, and unified error handling across the FitForge ecosystem.

## Features
*   *Note: Currently serving as an architectural placeholder.*
*   Designed to prevent DRY violations across Node.js microservices.

## Tech Stack
*   Node.js (Library package)

## Reusable Utilities (Future Scope)
*   Unified `verifyToken` middleware.
*   Centralized `errorHandler`.
*   Standardized Redis event payload types.
*   Logging wrappers (Winston/Pino).

## How Other Services Use It
Other microservices include this repository in their `package.json` as a Git dependency:
```json
{
  "dependencies": {
    "fitforge-shared": "git+https://github.com/fitforge101/fitforge-shared.git#main"
  }
}
```

## Folder Structure
```text
.
└── README.md
```
