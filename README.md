<p align="center">
  <a href="https://valarisai.app"><img src="https://valarisai.app/logo.png" width="96" alt="ValarisAI"></a>
</p>

<h1 align="center">ValarisAI for Windows — releases</h1>

<p align="center">All the world's AI in one chat. Hundreds of models through OpenRouter, voice, photos, PDFs and video.<br>
<a href="https://valarisai.app"><b>valarisai.app</b></a> · <a href="https://valarisai.app/security.html">Security and privacy</a> · <a href="mailto:support@valaris.app">support@valaris.app</a></p>

---

This repository lists **every version of the ValarisAI installer for Windows** with its SHA-256 checksum and
release notes. The program's source code is not published here.

## Download

- The newest installer: **[valarisai.app](https://valarisai.app)** → “Download for Windows”.
- All versions: the **[Releases](https://github.com/ValarisAI/valarisai-releases/releases)** page of this repository.

The installed program updates itself; every update is checked with our signature before it is installed.

## Check the file you downloaded

Every release lists the SHA-256 of its installer. In PowerShell:

```powershell
Get-FileHash .\ValarisAPP-Setup-1.6.0.exe
```

The `Hash` value must be exactly the one in the release notes. If it is different, do not run the file and
write to support@valaris.app.

## Security and privacy in short

- **Your data stays on your device.** The OpenRouter key is kept in Windows Credential Manager; chats, files and
  settings are in the app's data folder. There is no account and no server with your chats.
- **Addresses the app contacts:** `openrouter.ai` (answers, models, balance, sign-in), `valarisai.app` (new version
  check and short notices), web pages only when a model reads a link from your chat (public addresses only), and
  `artificialanalysis.ai` only if you add your own key for model ratings. No analytics, no ads, no telemetry.
- **Signed updates.** Version, file name, size and SHA-256 of every installer are signed with our Ed25519 key; the
  app throws away anything that does not match.
- **Folders.** The app reads only folders you connect; every change to a file asks you first and can be undone.
- **No administrator rights** are needed to install or run ValarisAI.

Details: <https://valarisai.app/security.html>

## Why an antivirus may warn

ValarisAI is a new program and is not yet signed with a paid code-signing certificate. Some antiviruses use machine
learning that is suspicious of new, little-known programs. For example, Microsoft Defender may show
`Trojan:Win32/Wacatac.B!ml` — the `!ml` ending means a guess of the machine-learning model, not a known virus.
We report such false positives to the antivirus makers. Download ValarisAI only from valarisai.app or from this page,
and compare the SHA-256.

## Report a vulnerability

See [SECURITY.md](SECURITY.md).

---

© 2026 ValarisAI · 6 Marjanishvili street, Tbilisi, Georgia ·
[Terms](https://valarisai.app/terms.html) · [Privacy](https://valarisai.app/privacy.html)
