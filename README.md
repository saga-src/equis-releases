# Equis

Personal finance for Windows and Android, by Saga.

Track spending, plan budgets and follow your wealth in an encrypted local vault. Cloud synchronization is optional, and you don't need an account to use local features.

All current features are free, with no announced end date or new commercial limits. The app is available in English and Brazilian Portuguese.

[Releases](https://github.com/saga-src/equis-releases/releases) · [Installation](#download-and-installation) · [Updates](#updates) · [FAQ](#faq) · [Report a bug](https://github.com/saga-src/equis-releases/issues)

## What you can do

- Track accounts, income, expenses, transfers, and credit cards.
- Use categories and tags to organize transactions. Set up recurring entries for regular income and expenses.
- Set budgets by month and track savings goals. Review reports for a chosen period, including daily or cumulative cash flow.
- Record investments and follow your wealth over time. Refresh available market quotes or keep manual values.
- Create password-encrypted backups and export records as JSON or CSV.

## Download and installation

Open the **[latest release](https://github.com/saga-src/equis-releases/releases/latest)** and choose a package from its **Assets** section.

| Download | Choose this for |
| --- | --- |
| [Windows installer](https://github.com/saga-src/equis-releases/releases/latest) | A regular Windows installation (`.exe`) |
| [Windows portable](https://github.com/saga-src/equis-releases/releases/latest) | Running Equis from an extracted application folder (`.zip`) |
| [Android APK](https://github.com/saga-src/equis-releases/releases/latest) | Installing or updating Equis on Android (`.apk`) |

See [all releases](https://github.com/saga-src/equis-releases/releases) for version notes and older downloads. The latest release's [SHA-256 checksums](https://github.com/saga-src/equis-releases/releases/latest/download/SHA256SUMS.txt) list the expected hashes of its packages.

### Requirements

| Platform | Supported OS | Architecture | Package |
| --- | --- | --- | --- |
| Windows | Windows 10 or 11 | x64 (64-bit) | Installer (`.exe`) or portable archive (`.zip`) |
| Android | Android 7.0 or newer (API 24+) | ARM64 (`arm64-v8a`), ARMv7 (`armeabi-v7a`), x86-64 (`x86_64`) | Application package (`.apk`) |

### Windows

Run the Windows installer and follow the setup prompts. For a portable package, extract the entire archive into a folder, then run `equis.exe` from that folder.

### Android

Download the Android APK and open it on your device. If Android asks, allow installation from the browser or file manager you used to open the APK, then complete installation. You can turn that permission off afterward.

If you already have Equis installed, follow the [update instructions](#updates).

## Updates

Equis checks this repository for in-app updates. Open **Settings** to check manually or change the automatic-download setting. Installation starts when you choose to install the downloaded update.

On Android, automatic downloads wait for Wi-Fi unless you choose to download immediately. For a manual update, get the package from the [latest release](https://github.com/saga-src/equis-releases/releases/latest).

Before updating, create and validate an encrypted backup when possible. If pending synchronization or conflicts prevent a backup, keep the existing installation while you resolve them.

- **Windows installer:** run the newer installer over your existing installation, preserving its installation folder and mode. Follow any version-specific instructions in the release notes.
- **Windows portable:** close Equis and extract the complete newer archive into a separate folder. Keep your existing copy and backups until you have opened the new version and checked your data.
- **Android:** open the newer APK and choose **Update**. Keep the existing app installed and preserve its storage. If Android rejects the update, report the error before removing anything.

Do not uninstall Equis or clear its data to update.

Updates to the terms may require a new acceptance before normal use.

## Your data

Financial records are stored in an encrypted local vault. Optional cloud synchronization shares encrypted records between your devices. Local planning and reports work offline; synchronization and fresh market data need a connection.

Portable backups and JSON/CSV exports let you keep a separate copy of your records. Exported JSON and CSV files are plaintext; store and share them with care.

### Terms and minimal usage sharing

Equis is intended for adults aged 18 or older. Before normal use, you must accept the terms, make the adult declaration and acknowledge minimal usage sharing in a separate, initially unchecked declaration. The documents can be read and saved before acceptance and remain available offline in Settings.

After the complete acceptance receipt is saved and verified, Equis collects pseudonymous daily feature-use summaries. These contain no financial records or cloud-account associations. Received usage history has no automatic expiration; the Privacy Policy explains retention and applicable rights. Cloud signup remains optional, and failed delivery does not block accepted offline use.

## FAQ

### Do I need an account?

You don't need an account for local features. Sign in if you want to use cloud synchronization.

### Can I use Equis offline?

Yes, after accepting the terms and usage declaration. Local records, planning and reports work offline. Cached market values remain available; synchronization and fresh quotes need a connection.

### Is synchronization the same as a backup?

Synchronization shares records across devices. A portable backup is a separate password-encrypted `.equis` file that you keep and can restore later. Keep backups independently of synchronization.

## Bugs and feedback

Report bugs or suggest improvements in [Issues](https://github.com/saga-src/equis-releases/issues). For bugs, include:

- Equis version and operating-system version.
- Steps to reproduce the problem.
- What you expected and what happened.
- Screenshots or relevant error messages with personal information removed.

Public issues are visible to everyone. Keep financial records, account details, vault files, passwords, and recovery keys out of reports.

For private requests, contact:

- **Support:** [equis@sagasource.com](mailto:equis@sagasource.com)
- **Privacy and data rights:** [privacy@sagasource.com](mailto:privacy@sagasource.com)
- **Confidential security reports:** [security@sagasource.com](mailto:security@sagasource.com)

## About this repository

This repository hosts Equis downloads, release notes, update files, and user feedback. Equis is developed separately.

## License and notices

Equis uses a proprietary EULA. The agreement and Product Notice are included in the app in English and Brazilian Portuguese. Free use does not grant permission to redistribute or modify the proprietary application beyond the EULA and applicable law. Third-party components retain their own licenses; their notices are available in Settings.
