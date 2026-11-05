<p align="center">
  <img src=".github/lockup.png" alt="QAzinho, by Salve Software" width="520">
</p>

<p align="center">
  <strong>A desktop QA assistant that tests your web and mobile apps on your own machine.</strong>
</p>

---

QAzinho plans tests with you, walks them on a real browser, emulator or simulator, and reports what
it saw against what you expected. It works with the coding agent you already use, so there is no
account to create and no run quota.

This repository hosts the installers and the update feed. The app itself is closed source.

## Download

Get the installer for your system from the [**latest release**](https://github.com/Salve-Software/qazinho-releases/releases/latest).

| System  | File                            | Notes                                     |
| ------- | ------------------------------- | ----------------------------------------- |
| macOS   | `QAzinho-<version>-arm64.dmg`   | Apple silicon. Signed and notarized.      |
| macOS   | `QAzinho-<version>-x64.dmg`     | Intel. Signed and notarized.              |
| Windows | `QAzinho-Setup-<version>.exe`   | 64-bit.                                   |
| Linux   | `QAzinho-<version>.AppImage`    | 64-bit.                                   |

The `.zip`, `.blockmap` and `latest*.yml` files are what installed apps read to update. You don't
need to download them.

## Install

**macOS:** open the `.dmg` and drag QAzinho to Applications.

**Windows:** run the installer. Until the app is code-signed, SmartScreen may warn you once: click
**More info**, then **Run anyway**.

**Linux:** make the AppImage executable, then open it.

```bash
chmod +x QAzinho-*.AppImage
./QAzinho-*.AppImage
```

## Updates

QAzinho keeps itself up to date. It downloads new versions in the background and installs them the
next time you quit. When an update is ready, a quiet **Update** button appears in the title bar. On
Linux this works when you run the AppImage.

## What it tests

| Target  | You provide                         |
| ------- | ----------------------------------- |
| Web     | the URL of your environment         |
| Android | an `.apk`                           |
| iOS     | a simulator `.app` build (Mac only) |

Everything runs on your computer: browsers, emulators, simulators and test runs.

---

<p align="center">
  <sub>© Salve Software. All rights reserved.</sub>
</p>
