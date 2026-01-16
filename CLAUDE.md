# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a minimal ASP.NET Core 8.0 Razor Pages web application serving a "Coming Soon" landing page. The application uses the standard ASP.NET Core web application structure with Razor Pages for UI rendering.

## Architecture

- **Program.cs**: Application entry point that configures the web host with Razor Pages support, static files, and routing
- **Pages/**: Contains Razor Pages (.cshtml view files and .cshtml.cs PageModel code-behind files)
  - Index.cshtml: The landing page with embedded CSS styling
  - Index.cshtml.cs: PageModel for the index page (currently minimal with just OnGet handler)
- **Properties/launchSettings.json**: Development launch configuration with URLs https://localhost:51400 and http://localhost:51401

## Development Commands

### Build
```bash
dotnet build
```

### Run
```bash
dotnet run
```
The application will be available at https://localhost:51400 or http://localhost:51401 in development mode.

### Watch Mode (auto-reload on changes)
```bash
dotnet watch run
```

### Clean
```bash
dotnet clean
```

## Technology Stack

- .NET 8.0
- ASP.NET Core Razor Pages
- C# with nullable reference types enabled
- Implicit usings enabled