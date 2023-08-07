# MDM Agent for Android

![Flyve MDM banner](https://user-images.githubusercontent.com/663460/26935464-54267e9c-4c6c-11e7-86df-8cfa6658133e.png)

[![License](https://img.shields.io/github/license/flyve-mdm/android-mdm-agent.svg?&label=License)](https://github.com/flyve-mdm/android-mdm-agent/blob/develop/LICENSE.md)
[![Follow twitter](https://img.shields.io/twitter/follow/FlyveMDM.svg?style=social&label=Twitter&style=flat-square)](https://twitter.com/FlyveMDM)
[![Project Status: WIP](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/)
[![Telegram Community](https://img.shields.io/badge/Telegram-Community-blue.svg)](https://t.me/flyvemdm)
[![IRC Chat](https://img.shields.io/badge/IRC-%23flyvemdm-green.svg)](http://webchat.freenode.net/?channels=flyve-mdm)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
[![Greenkeeper badge](https://badges.greenkeeper.io/flyve-mdm/android-mdm-agent.svg)](https://greenkeeper.io/)
[![GitHub release](https://img.shields.io/github/release/flyve-mdm/android-mdm-agent.svg)](https://github.com/flyve-mdm/android-mdm-agent/releases)

The new Ammonitrix MDM Client (code was defunct when I began modifying from Flyve MDM Agent for Android) will auto-enroll devices into the Ammonitrix environment.

Check out the [Ammonitrix Website](https://ammonitrix.com/?from=android-mdm-agent)!

## Table of contents

* [Synopsis](#synopsis)
* [Build Status](#build-status)
* [Compatibility Matrix](#compatibility-matrix)
* [Installation](#installation)
* [Documentation](#documentation)
* [Versioning](#versioning)
* [Contact](#contact)
* [Professional Services](#professional-services)
* [Contribute](#contribute)
* [Copying](#copying)

## Synopsis

The Android Agent will manage all your Android mobile devices from the lowest level, including a range of powerful security features to protect sensitive data stored on mobile devices, allowing you to manage your mobile fleet security policy with accuracy and precision.

The Ammonitrix MDM Agent for Android will help you to:

* Install Ammonitrix configurations on a target Android device
* Configure and deploy your mobile fleet on our web-based console into your secure Ammonitrix account
* Install and uninstall remote applications
* Send files remotely to all devices
* Force the Android device to use our VPN and Proxy services (to monitor device traffic)
* Deploy and control Bluetooth and Wi-Fi connectivity
* Activate real-time geolocation services of your devices
* Delete, partially or totally, your data, in case of loss or theft
* Automatically inventory your entire fleet of Android devices
* Keep control and protect yourself from cyber-attacks:
  * Set the level of complexity of your passwords
  * Activate mobile device encryption
  * Lock the mobile device remotely
  * Control the authorisation for the use of the camera
  * Erase all data from the remote terminal (reset)

For more information visit our [Ammonitrix Official Website](http://ammonitrix.com/features#android/).

## Build Status

|                                                                       **LTS**                                                                       |                                                                   **Bleeding Edge**                                                                   |
|:---------------------------------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------:|
| [![Build Status](https://dev.ammonitrix.com/android-mdm-agent/tree/master.svg?style=svg)](https://dev.ammonitrix.com/android-mdm-agent/tree/master) | [![Build Status](https://dev.ammonitrix.com/android-mdm-agent/tree/develop.svg?style=svg)](https://dev.ammonitrix.com/android-mdm-agent/tree/develop) |

## Compatibility Matrix

### Flyve MDM projects

|MDM Agent|0.99.x|1.0.0|2.0.0|
|:---|---|---|---|
|GLPI|9.1|9.2|9.2|
|Flyve MDM plugin|-|2.0.0|2.0.0|
|Web MDM Dashboard|-|2.0.0|2.0.0|

### MDM Agent & Android

|API|Android|Support|SSL|
|:---:|:---:|:---:|:---:|
| 16 | Android 4.1 | X | - |
| 17 | Android 4.2 | X | - |
| 18 | Android 4.3 | X | - |
| 19 | Android 4.4 | X | - |
| 20 | Android 4.4 | X | - |
| 21 | Android 5.0 | X | X |
| 22 | Android 5.1 | X | X |
| 23 | Android 6.0 | X | X |
| 24 | Android 7.0 | X | X |
| 25 | Android 7.1.1 | X | X |
| 26 | Android 8.0 | - | - |

## Installation

[<img src="https://user-images.githubusercontent.com/663460/26973322-4ddf78a4-4d16-11e7-8b58-4c03b4bc2490.png" alt="Get it on Google Play" height="60">](https://play.google.com/store/apps/details?id=org.flyve.mdm.agent) [<img src="https://f-droid.org/badge/get-it-on.png" alt="Get it on F-Droid" height="60">](https://f-droid.org/packages/org.flyve.mdm.agent.mqtt/) [<img src="https://user-images.githubusercontent.com/663460/26973090-f8fdc986-4d14-11e7-995a-e7c5e79ed925.png" alt="Download APK from GitHub" height="60">](https://github.com/tpowell-at-atoztechco/ammonitrix-mdm-agent/releases/latest)

### As System App

Follow the steps in this article to learn [How to Install from the Google Play Store](http://ammonitrix.com/support/android-installation).

## Documentation

We maintain a detailed documentation of the project on the website, check the [How-tos](http://flyve.org/android-mdm-agent/) and [Development](http://flyve.org/android-mdm-agent/howtos/) section.

## Versioning

In order to provide transparency on our release cycle and to maintain backward compatibility, Flyve MDM is maintained under [the Semantic Versioning guidelines](http://semver.org/). We are committed to following and complying with the rules, the best we can.

See [the tags section of our GitHub project](https://github.com/flyve-mdm/android-mdm-agent/tags) for changelogs for each release version of Flyve MDM. Release announcement posts on [the official Teclib' blog](http://www.teclib-edition.com/en/communities/blog-posts/) contain summaries of the most noteworthy changes made in each release.

## Contact

For notices about major changes and general discussion of Flyve MDM development, subscribe to the [/r/FlyveMDM](http://www.reddit.com/r/FlyveMDM) subreddit.
You can also chat with us via IRC in [#flyve-mdm on freenode](http://webchat.freenode.net/?channels=flyve-mdm) or [@flyvemdm on Telegram](https://t.me/flyvemdm). Ping me @rafaelje if you get stuck.

## Professional Services

[Ammonitrix](https://ammonitrix.com/?from=ammonitrix-mdm-agent) maintains a working platform, and is publishing this app as open source, but has closed it to only work with our services.

## Contribute

Want to file a bug, contribute some code, or improve documentation? Excellent! Read up on our guidelines for [contributing](./CONTRIBUTING.md) and then check out one of our issues in the [Issues Dashboard](https://github.com/flyve-mdm/android-mdm-agent/issues).

## Copying

* **Name**: [Flyve MDM](https://flyve-mdm.com/) is a registered trademark of [Teclib'](http://www.teclib-edition.com/en/).
* **Name**: [Ammonitrix](https://ammonitrix.com/) is a registered trademark of [Ammonitrix, Inc](https://ammonitrix.com/legal/trade#Ammonitrix)
* **Code**: you can redistribute it and/or modify it under the original terms of the Flyve's GNU General Public License ([GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)).
* **Documentation**: released under Attribution 4.0 International ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)).
