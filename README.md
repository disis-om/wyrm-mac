# Wyrm for Mac

Wyrm, the slither game app by OM Rajput, for macOS 12 Monterey and later.
One app runs natively on both Intel and Apple Silicon Macs.

This page holds only the downloads. No source code lives here.

## Download

Open the latest release under **Releases** and pick one:

- **Wyrm-&lt;version&gt;-mac-universal.dmg** (installer): open it and drag Wyrm
  into Applications.
- **Wyrm-&lt;version&gt;-mac-universal-portable.zip** (portable): unzip it and run
  Wyrm.app from any folder you can write to.

## First launch

Wyrm is not notarized by Apple yet. The first time, right-click Wyrm.app and
choose **Open**, or go to System Settings › Privacy & Security and click
**Open Anyway**. After that it opens normally.

## Updates

Wyrm checks for new versions by itself (Settings › Version › Updates, with a
Beta updates switch). **Update now** downloads the new Wyrm, checks it, and
restarts into it. Keep Wyrm in Applications (or another folder you can write
to) so it can update itself; a copy opened straight from the installer or from
Downloads asks you to move it first.

Every update is described by a signed file in `update/` (`latest.json`,
`beta.json`); Wyrm only installs a download whose signature, size and SHA-256
match it.

© 2026 OM Rajput.
