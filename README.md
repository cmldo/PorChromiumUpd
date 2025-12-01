# PorChromiumUpd

A WinForms application to download and manage the latest Chromium snapshots.

## Features
- Downloads latest official Chromium snapshot for Windows x64
- Extracts directly to `Chromium Stable x64`
- Shows download progress, speed, ETA
- Auto-update check on startup
- Installed/Latest revision display
- Desktop shortcuts:
  - Simple
  - Common profile (shared user data)
  - Single profile (isolated user data)
- Reinstall option
- Error logging

## Build & Run

Clone the repository:

```bash
git clone https://github.com/<yourusername>/PorChromiumUpd.git
cd PorChromiumUpd
dotnet run
