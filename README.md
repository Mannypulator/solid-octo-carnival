# HNG12 Stage 0 Backend API

## Overview
This is a simple public API that returns my information

## Tech Stack
- **C# .NET 8**
- **Deployed with Render with the help of Docker to handle Runtime**

## API Endpoint
- **BASE URL**: `https://solid-octo-carnival.onrender.com/`

## GET `/`
**Response Example:**

```json

  {
    "email": "emeritus93@gmail.com",
    "current_datetime: "2025-02-01T14:04:25.7697333Z",
    "github_url":"https://github.com/mannypulator/solid-octo-carnival"
  }
```

## How To Run Locally
```bash
    git clone https://github.com/mannypulator/solid-octo-carnival.git
    cd HNG12.API
    dotnet run watch
```
