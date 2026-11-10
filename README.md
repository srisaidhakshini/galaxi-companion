# Galaxi Companion

The Windows companion for [Galaxi](https://galaxi.dhakshini.studio).

**[Download for Windows x64](https://github.com/srisaidhakshini/galaxi-companion/releases/latest/download/Galaxi-Setup.exe)** · **[Release notes and SHA-256 checksum](https://github.com/srisaidhakshini/galaxi-companion/releases)**

## Getting started

1. Install and open Galaxi. This initial installer is unsigned, so Windows may show an unverified-publisher warning.
2. Install Git if needed. Node.js, npm and Codex are included.
3. Select **Sign in with ChatGPT** and use your own eligible Codex account.
4. Choose an existing Git project and configure its verification checks in the companion.
5. Open the Galaxi website on the same computer and choose **Connect installed companion**.
6. Verify the requesting website address locally and choose view-only access or explicitly allow prompts.

Prompts run on your computer under your own account's usage limits. Galaxi does not provide unlimited AI usage. Repository setup, runtime approvals and applying results stay local. Keep the companion open while using the website.

Use your default browser for installed-app callbacks. The browser-popup connection option also works with an installed companion if using another browser. Connections expire after eight hours and can be revoked from the local app.

This repository distributes installer binaries and checksums. Windows x64 is the initial supported packaging target. Automatic updates and other OS installers are not included in this release.

## Verify the download

Download `SHA256SUMS.txt` from the same release, then compare it with:

```powershell
Get-FileHash .\Galaxi-Setup.exe -Algorithm SHA256
```

Install only releases from this repository. The installer does not include any user's repositories, prompts, credentials or database.
