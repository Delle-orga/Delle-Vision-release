# Delle Vision — Downloads

This repository hosts the official releases of **Delle Vision**, a voice-driven memory app for Windows: what you see, think, live or read is captured by speaking, filed into nested boxes, and Claude brings back what echoes.

## Download

Get the latest version:

**[Download Latest Release](https://github.com/Delle-orga/Delle-Vision-release/releases/latest)**

| Platform | File |
|----------|------|
| Windows 10 / 11 (64-bit) | `Delle-Vision-Setup.exe` installer |

Direct link to the latest installer: <https://github.com/Delle-orga/Delle-Vision-release/releases/latest/download/Delle-Vision-Setup.exe>

## Before installing

- A microphone: everything is dictated.
- Local voice (Whisper, whisper.cpp) installs from inside the app on first launch: ≈ 1.3 GB with an NVIDIA GPU, ≈ 200 MB otherwise. Once installed, nothing you say leaves the PC.
- For echoes and the "filigrane": [Claude Code](https://claude.com/claude-code) (the `claude` CLI) installed and signed in to a subscription.
- The installer is not code-signed yet: Windows SmartScreen may show "Windows protected your PC". Click **More info**, then **Run anyway**.

Notes, memos and voice stay in `%APPDATA%\Delle Vision` and survive updates.

## Links

- [Delle Vision on the portfolio](https://myportfolio-production-eb20.up.railway.app/projets?projet=10)

## About

Releases are built locally (`npm run electron:build`) and published with `scripts/release/publish.sh` from the main application repository: the installer is uploaded under a fixed name, so the "latest" link above always points to the newest version.
