# Android KeePassDX Fern

English | [简体中文](README.zh-CN.md)

<img alt="KeePassDX Icon" src="https://cdn.jsdelivr.net/gh/Yezi-Mooyee/KeePassDX-Fern@master/art/icon.png"> **Lightweight password safe and manager for Android**, KeePassDX Fern allows editing encrypted data in a single file in KeePass format and fill in the forms in a secure way.

<img alt="KeePassDX Screenshot" src="https://cdn.jsdelivr.net/gh/Yezi-Mooyee/KeePassDX-Fern@master/art/screen.jpg" width="220">

## Fork notice

KeePassDX Fern is an unofficial fork of [Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX), based on upstream tag 4.5.5 (commit `2db52c5`), and keeps following upstream releases.
Copyright of the modifications belongs to Yezi Mooyee (2026), released under GPLv3 like upstream.
Please do not report the problems of this fork to the upstream KeePassDX project; report the problems and requests of this project to [this repository's issues](https://github.com/Yezi-Mooyee/KeePassDX-Fern/issues).

### Planned features

 - **Configurable fill key sequence**: turn the filling of the Magikeyboard from fixed actions into a user-defined key sequence, for example `{USERNAME}{TAB}{PASSWORD}{KEYBOARD_BACK}`, so that the auto-fill behavior of the Magikeyboard can be customized.
 - **Configurable fill buttons**: the two separate buttons for filling the username and the password can each be configured freely, both what they fill and what they do afterwards.

### Features

 - **Passkeys** for authentication and **local storage of private keys**.
 - **Biometric recognition** for fast unlocking (fingerprint / face unlock / …).
 - **One-Time Password** management (HOTP / TOTP) for two-factor authentication (2FA).
 - **Autofill** for easy form filling with passwords.
 - **Magikeyboard** to efficiently fill in any field.
 - Create **encrypted database files**.
 - Organisation of credentials by **entry** and in **group** trees.
 - Allows opening and **copying URI / URL fields quickly**.
 - Dynamic **templates** for each type of entry.
 - **History** of each entry.
 - Precise management of **settings**.
 - Material design with **themes**.
 - Support for **.kdb** and **.kdbx** files (version 1 to 4) with AES - Twofish - ChaCha20 - Argon2 algorithm.
 - **Compatible** with the majority of alternative programs (KeePass, KeePassXC, KeeWeb, …).
 - Code written in **native languages** (Kotlin / Java / JNI / C).

KeePassDX Fern is **open source** and **ad-free**.

## What is KeePassDX Fern?

An alternative to remembering an endless list of passwords manually. This is made more difficult by **using different passwords for each account**. If you use one password everywhere and security fails only one of those places, it grants access to your e-mail account, website, etc, and you may not know about it or notice, before bad things happen.

KeePassDX Fern is a **local password and passkey manager for Android**, which helps you **manage your passwords in a secure way**. You can put all your passwords in one database, locked with a **master key** and/or a **keyfile**. You **only have to remember one single master password and/or select the keyfile** to unlock the whole database. The databases are encrypted using the best and **most secure encryption algorithms** currently known.

## Small print?

KeePassDX Fern is under **open source GPL3 license**, meaning you can use, study, change and share it at will. Copyleft ensures it stays that way.
From the full source, anyone can build, fork, and check whether for example the encryption algorithms are implemented correctly.
There is **no advertising**.

## Contribution

* **Reporting issues**: this fork only accepts issues about the interface and usability that do not involve the low-level security implementation; upstream problems such as the encryption algorithms and the KDBX parsing should be reported to the [upstream project](https://github.com/Kunzisoft/KeePassDX/issues). If you are unsure where an issue belongs, **report it to [this project](https://github.com/Yezi-Mooyee/KeePassDX-Fern/issues) first**.
* **Contributing code**: add features by making a **[pull request](https://github.com/Yezi-Mooyee/KeePassDX-Fern/pulls)**. The changes of this fork are kept in the outer layers (interface / input method / preferences) whenever possible, avoiding the encryption implementation.
* **Translation**: this fork reuses the upstream translations directly, and the vast majority of the languages in the interface come from the [upstream Weblate project](https://hosted.weblate.org/projects/keepass-dx/) — **if you want to translate the general interface, please contribute upstream**. For the translation of the strings added by this fork, please open an [issue](https://github.com/Yezi-Mooyee/KeePassDX-Fern/issues) for now.
* **Supporting the original author**: almost all the code of this fork comes from upstream. If you want to support the development of this project, please support the upstream author directly: [Kunzisoft/KeePassDX](https://github.com/Kunzisoft/KeePassDX) ([donation page](https://www.keepassdx.com/#donation)).

## Download

Download it from [GitHub releases](https://github.com/Yezi-Mooyee/KeePassDX-Fern/releases/latest).

No release has been published yet, so you have to build it yourself, or wait for the first release.

This fork currently only ships the **libre** build (no Google Play dependency); the upstream free and Pro builds are not provided yet. See the [upstream wiki](https://github.com/Kunzisoft/KeePassDX/wiki/FAQ#why-a-libre-and-free-version) for the difference between the two.

## Frequently Asked Questions

This project has no FAQ yet; you can refer to the upstream [FAQ](https://github.com/Kunzisoft/KeePassDX/wiki/FAQ) for now.

## Other devices

- [KeePass](https://keepass.info/) (https://keepass.info/) is the original and official project for the desktop, with technical documentation for standardized database files. It is updated regularly with active maintenance (written in C#).

- [KeePassXC](https://keepassxc.org/) (https://keepassxc.org/) is an alternative integration of KeePass written in C++.

- [KeeWeb](https://keeweb.info/) (https://keeweb.info/) is a web version that is also compatible with KeePass files.

## License

  Copyright © 2026 Jeremy Jamet / [Kunzisoft](https://www.kunzisoft.com).

  This file is part of KeePassDX.

  [KeePassDX](https://www.keepassdx.com) is free software: you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published by
  the Free Software Foundation, either version 3 of the License, or
  (at your option) any later version.

  KeePassDX is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License
  along with KeePassDX.  If not, see <http://www.gnu.org/licenses/>.

  *This project is a fork of [KeePassDroid](https://github.com/bpellin/keepassdroid) by bpellin.*
