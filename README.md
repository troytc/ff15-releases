# ff@15 — Releases

This repository publishes **installers and auto-update manifests only** for **ff@15**, a League of Legends companion overlay.

Application source, issues, and development live in the private main repository. Nothing here is built from this tree — CI uploads release assets when a version tag is cut upstream.

## Download latest

**[Releases → latest](https://github.com/troytc/ff15-releases/releases/latest)**

| Platform | Artifacts |
|----------|-----------|
| Windows | `.msi` or `.exe` (NSIS) installer |
| macOS | `.dmg`, or `.app.zip` (`aarch64` = Apple Silicon, `x64` = Intel) |
| Linux | `.AppImage` or `.deb` |

### First launch

- **macOS** (unsigned builds): right-click the app → **Open**.
- **Windows** (SmartScreen): choose **More info → Run anyway**.

## Auto-updates

Installed builds check `latest.json` on each published release in this repository.

---

Questions and feedback: contact the maintainer or see project docs linked from your install channel.
