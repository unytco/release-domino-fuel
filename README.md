# Domino-Holofuel Releases
![GitHub release (latest by date)](https://img.shields.io/github/v/release/unytco/release-domino-holofuel?style=for-the-badge)
![GitHub All Releases](https://img.shields.io/github/downloads/unytco/release-domino-holofuel/total?style=for-the-badge)


## Installation

Download the appropriate version for your system.

| Releases                 |
|--------------------------|
| [macOS x64 (Intel)](https://github.com/unytco/release-domino-holofuel/releases)            |
| [macOS arm64 (Silicon)](https://github.com/unytco/release-domino-holofuel/releases)      |
| [Linux Debian](https://github.com/unytco/release-domino-holofuel/releases) (recommended)    |
| [Linux AppImage](https://github.com/unytco/release-domino-holofuel/releases) (read note below) |
| [Windows](https://downloads.unyt.co/windows)                         |
| [Android](#) (no release available)                                  |
| [iOS](#) (no release available)                                      |


> [!IMPORTANT]
> If you encounter sandbox-related issues, you can try running the AppImage with:
> ```bash
> ELECTRON_DISABLE_SANDBOX=1 ./domino.AppImage
> ```
> This is automatically configured in the latest version, but might be needed for manual execution in some cases.


All available versions can be found in the [Releases](
https://github.com/unytco/release-domino-holofuel/releases)

Once installed, set up Domino either with a password or without a password. In either case, the software will run locally on your device and your password will not leave your device. 

NOTE: If you set up with a password and later lose your password, we will NOT be able to help you regain access to your account. You will need to delete the software and reinstall to create a fresh account to continue testing. See below section on **Starting Fresh**.

## Setup
Note: The release for your operating system may not be code signed yet, so you may need to right click to open the file. In Mac, because you downloaded the software directly and not through Apple's App Store, you may need to open the System Settings and go to Privacy and Security, scroll down to Security and give Domino permission to run.

When you open Domino on your operating system for the first time, it will create a set of public and private keys for you that you can use to interact with others. These are stored in a private keystore (Lair) on your own machine and are used during future uses. 

To get started, you can try sending, executing, and receiving transactions either with friends that have also downloaded Domino, or with team members from the Development Team.

## Starting Fresh
Details on removal and reinstallation.

If you want to start fresh (whether because you lost a password or for another reason), uninstall the old version and then reinstall again. On Mac, you will also need to delete your local data:

Here are the steps for Uninstalling, Deleting Local Data and Reinstalling the app:

1. Close the app.

2. Delete the domino file from your applications folder.

3. Open the Terminal application
4. In Terminal, type the following two commands and hit enter after each:

```
cd ~/Library/Application\ Support
```

```
rm -rf co.unyt.domino.holofuel
```

That co.unyt.domino.holofuel file had your local data in it.

Now that it is deleted, you can again install domino and start fresh with a new account.

## License

[![License: CAL 1.0](https://img.shields.io/badge/License-CAL%201.0-blue.svg)](https://github.com/holochain/cryptographic-autonomy-license)

Copyright (C) 2024 - 2025, unyt.co

