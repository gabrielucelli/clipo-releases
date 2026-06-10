# Clipo

The calm clipboard manager — keep every snippet, URL, color, and screenshot you copy, ready to summon with a keystroke. Local-first, no account.

This repository hosts the downloadable installers and the auto-updater manifest for Clipo. **[⬇ Download the latest version](https://github.com/gabrielucelli/clipo-releases/releases/latest)**.

## Download

Grab the right file for your platform from the [latest release](https://github.com/gabrielucelli/clipo-releases/releases/latest):

| Platform | File |
|----------|------|
| macOS (Apple Silicon) | `Clipo_<version>_aarch64.dmg` |
| macOS (Intel) | `Clipo_<version>_x64.dmg` |
| Windows | `Clipo_<version>_x64-setup.exe` |
| Linux | `Clipo_<version>_amd64.AppImage`, `.deb`, or `.rpm` |

## Installing

Clipo currently ships **unsigned** (no paid OS code-signing certificate), so your OS will warn you on first launch. This is expected.

**macOS** — open the `.dmg`, drag Clipo to Applications, then **right-click the app → Open** and confirm. (Double-clicking shows an "unidentified developer" block; right-click → Open bypasses it.) If macOS says the app is "damaged", clear the quarantine flag:
```
xattr -dr com.apple.quarantine /Applications/Clipo.app
```

**Windows** — run the installer; if SmartScreen appears, click **More info → Run anyway**.

## Updates

Once installed, Clipo updates itself — it checks this repository for new releases and offers to download and install them in-app. No need to come back here after the first install.
