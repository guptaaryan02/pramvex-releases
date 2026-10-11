# Pramvex by B2R: downloads

Installers for **Pramvex**, private offline document intelligence. Every answer, backed by evidence.

This repository holds release files only. Get the latest version from
[Releases](https://github.com/guptaaryan02/pramvex-releases/releases).

| Platform | File |
|---|---|
| macOS, Apple Silicon (M1 or later) | `Pramvex_<version>_aarch64.dmg` |
| macOS, Intel | `Pramvex_<version>_x64.dmg` |
| Windows 11, x64 | `Pramvex_<version>_x64-setup.exe` (or `.msi`) |
| Linux, x86_64 | `.AppImage`, `.deb` or `.rpm` |

## These builds are not code-signed

- **macOS:** open Pramvex once; when macOS blocks it, go to **System Settings › Privacy & Security**, scroll down and click
  **Open Anyway**, then confirm (on macOS 14 and earlier, right-click → Open also works). If macOS says the app is damaged,
  run `xattr -dr com.apple.quarantine /Applications/Pramvex.app` once.
- **Windows:** on the blue SmartScreen screen choose **More info**, then **Run anyway**.
- **Linux:** `chmod +x Pramvex_<version>_amd64.AppImage`, or install the `.deb` / `.rpm`.

Check every download against `SHA256SUMS.txt` in the release:

```bash
shasum -a 256 -c SHA256SUMS.txt --ignore-missing
```

Support: support@b2r.it.com
