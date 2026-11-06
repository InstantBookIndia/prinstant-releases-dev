# Prinstant Releases (dev)

> **Internal test builds. Not for shops.**
> These builds connect to the Prinstant **test** servers and only work with test accounts.
> To install Prinstant in a shop, use the official releases:
> **[github.com/InstantBookIndia/prinstant-releases](https://github.com/InstantBookIndia/prinstant-releases)**

This repository contains **only signed test installers and update manifests**; the source code is private.

## Download (test PCs only)

**Prinstant Desktop (Windows), latest test build:**
[Prinstant-Desktop-Setup.exe](https://github.com/InstantBookIndia/prinstant-releases-dev/releases/download/desktop-dev-channel/Prinstant-Desktop-Setup.exe)

## How updates work

Test builds of the desktop app check this repository for updates when they open. Every installer is signed, and the
app verifies the signature before installing, so an unsigned or modified file is never installed.

| Release | Purpose |
|---|---|
| `desktop-vX.Y.Z-dev.N` | A desktop test build |
| `desktop-dev-channel` | What test PCs update to. Do not delete. |

## Notes

- Releases are published automatically by CI. Do not upload or edit files here by hand.
- Test builds can be unstable and are replaced often.
