# Equis

Personal finance for Windows and Android, by Saga.

Equis helps you track spending and plan your finances. Your records live in a local vault, with optional cloud synchronization between devices.

[Releases](https://github.com/saga-src/equis-releases/releases) · [Installation](#download-and-installation) · [Updates](#updates) · [FAQ](#faq) · [Report a bug](https://github.com/saga-src/equis-releases/issues)

## What you can do

- Track accounts, income, expenses, transfers, and credit cards.
- Use categories and tags to organize transactions. Set up recurring entries for regular income and expenses.
- Set budgets and goals. Review cash flow and reports.
- Record investments and follow your wealth over time.
- Create portable backups and export records as JSON or CSV.

## Download and installation

Downloads are listed on the [Releases page](https://github.com/saga-src/equis-releases/releases), alongside release notes and known issues.

Open a release's **Assets** section and choose the package for your platform.

### Requirements

| Platform | Supported OS | Architecture | Package |
| --- | --- | --- | --- |
| Windows | Windows 10 or 11 | x64 (64-bit) | Installer (`.exe`) or portable archive (`.zip`) |
| Android | Android 7.0 or newer (API 24+) | ARM64 (`arm64-v8a`), ARMv7 (`armeabi-v7a`), x86-64 (`x86_64`) | Application package (`.apk`) |

Check the release notes for available packages and any additional requirements.

### Windows

Run the Windows installer and follow the setup prompts. For a portable package, extract the entire archive into a folder, then run `equis.exe` from that folder.

### Android

Download the Android APK and open it on your device. If Android asks, allow installation from the browser or file manager you used to open the APK, then complete installation. You can turn that permission off afterward.

If you already have Equis installed, follow the [update instructions](#updates).

## Updates

Equis checks this repository for in-app updates. Open **Settings** to check manually or change the automatic-download setting. Installation starts when you choose to install the downloaded update.

On Android, automatic downloads wait for Wi-Fi unless you choose to download immediately. For a manual update, get the package from the [Releases page](https://github.com/saga-src/equis-releases/releases).

Before updating, create and validate an encrypted backup when possible. If pending synchronization or conflicts prevent a backup, keep the existing installation while you resolve them.

- **Windows installer:** run the newer installer over your existing installation, preserving its installation folder and mode. Follow any version-specific instructions in the release notes.
- **Windows portable:** close Equis and follow the release's portable-update instructions. Keep a validated backup and your existing copy until the update is verified.
- **Android:** open the newer APK and choose **Update**. Keep the existing app installed and preserve its storage. If Android rejects the update, report the error before removing anything.

## Your data

Financial records are stored locally. Cloud synchronization is optional; synchronization and market-data requests need a network connection.

Portable backups and JSON/CSV exports let you keep a separate copy of your records. Exported JSON and CSV files are plaintext; store and share them with care.

## FAQ

### Do I need an account?

You don't need an account for local features. Sign in if you want to use cloud synchronization.

### Can I use Equis offline?

Local records, planning, and reports work offline. Synchronization and fresh market data need a network connection. Cached market values are still available offline.

### Is synchronization the same as a backup?

Synchronization shares records across devices. A portable backup is a separate password-encrypted `.equis` file that you keep and can restore later. Keep backups independently of synchronization.

### Can I export my records?

Export a vault as JSON or transactions as CSV. You can also create an encrypted portable backup.

### Which languages are available?

English and Brazilian Portuguese.

## Bugs and feedback

Report bugs or suggest improvements in [Issues](https://github.com/saga-src/equis-releases/issues). For bugs, include:

- Equis version and operating-system version.
- Steps to reproduce the problem.
- What you expected and what happened.
- Screenshots or relevant error messages with personal information removed.

Public issues are visible to everyone. Keep financial records, account details, vault files, passwords, and recovery keys out of reports.

## About this repository

This repository hosts Equis downloads, release notes, update files, and user feedback. Equis is developed separately.

## License and notices

For applicable license terms and third-party notices, refer to the files accompanying the release you download.
