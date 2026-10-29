# Coming Soon

A minimal **ASP.NET Core 8.0 Razor Pages** app that serves a single styled
"Coming Soon" landing page — a lightweight placeholder to put in front of a
domain while the real site is being built.

## Structure

- `Program.cs` — configures Razor Pages, static files and routing.
- `Pages/Index.cshtml` — the landing page (self-contained HTML + CSS, purple
  gradient background).
- `Pages/Index.cshtml.cs` — the page model.

## Run

```
dotnet run
```

Then open https://localhost:51400 (or http://localhost:51401).

## Build & publish

```
dotnet build
dotnet publish -c Release
```
