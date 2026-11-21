# Desktop releases

Installers for the desktop app are published on the
[Releases](https://github.com/Tanjil1-sudo/c1p2i3d4e5/releases) page.

| System | Download |
|---|---|
| Windows 10 / 11, 64-bit | the `.exe` installer |
| macOS 12+, Apple silicon | the `arm64` `.dmg` (or `.zip`) |
| macOS 12+, Intel | the `x64` `.dmg` (or `.zip`) |
| Debian, Ubuntu (x64) | the `.deb` |
| Other Linux (x64) | the `.AppImage` |

## First launch

The app isn't signed with a paid certificate yet, so each system asks once:

- **Windows:** at "Windows protected your PC", click **More info → Run anyway**.
- **macOS:** open the app once, then **System Settings → Privacy & Security → Open Anyway**.
- **Linux:** `sudo apt install ./<file>.deb`, or make the `.AppImage` executable and run it.
  On Ubuntu 24.04+ prefer the `.deb`; the AppImage there needs `--no-sandbox`.

## Updates

Windows and Linux builds update themselves. On macOS the app tells you when a
new version is out.

## Problems

[Open an issue](https://github.com/Tanjil1-sudo/c1p2i3d4e5/issues/new) with your
system, the app version (Help → About), what you did and what happened.
