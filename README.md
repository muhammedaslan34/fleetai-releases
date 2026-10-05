# FleetAI downloads

Official builds of **FleetAI** — a native desktop workspace for Claude Code, Codex, Antigravity, OpenCode and every other CLI coding agent — and its Android companion app.

| Platform | Download |
| --- | --- |
| Windows 10/11 (x64) | [FleetAI-Setup-x64.exe](https://github.com/muhammedaslan34/fleetai-releases/releases/latest/download/FleetAI-Setup-x64.exe) |
| Android 7+ | [FleetAI-Android.apk](https://github.com/muhammedaslan34/fleetai-releases/releases/latest/download/FleetAI-Android.apk) |

These links always point to the newest release. Older versions are on the [Releases](https://github.com/muhammedaslan34/fleetai-releases/releases) page.

## Installing

**Windows** — run `FleetAI-Setup-x64.exe`. The installer isn't code-signed yet, so Windows SmartScreen may show "Windows protected your PC": choose **More info → Run anyway**.

**Android** — open `FleetAI-Android.apk` on your phone and allow installing from your browser or file manager when Android asks. Pair it with the desktop app from **Settings → Mobile**.

## Verify your download

Every release includes `SHA256SUMS.txt`. On Windows:

```powershell
Get-FileHash .\FleetAI-Setup-x64.exe -Algorithm SHA256
```

On macOS/Linux: `sha256sum FleetAI-Android.apk`. The hash must match the line in `SHA256SUMS.txt`.

## Account

FleetAI needs a subscription — sign up at [fleetai.pixeloud.com](https://fleetai.pixeloud.com).

This repository only hosts release files; the source code is private.
