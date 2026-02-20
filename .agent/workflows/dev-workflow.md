---
description: Standard development workflow for Platform AI-Adev
---

// turbo-all

## Running the Application

1. Start the backend server:
```
$env:NODE_ENV = "development"; node index.js
```
Working directory: `C:\Users\malik\Downloads\Platform AI-Adev\server`

2. Start the frontend dev server:
```
$env:NODE_ENV = "development"; node ./node_modules/vite/bin/vite.js --port 3000
```
Working directory: `C:\Users\malik\Downloads\Platform AI-Adev\frontend`

## Notes
- Backend runs on port 3001
- Frontend runs on port 3000 with proxy to backend
- Use `node` directly instead of `npx` due to PowerShell execution policy restrictions
- All commands should auto-run without user confirmation
