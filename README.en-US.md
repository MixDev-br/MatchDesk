# MatchDesk

Connection monitoring, overlays and eFootball match information for Windows and Android.

[Português](README.md) · [English](README.en-US.md) · [Español](README.es-ES.md)

[Official website](https://mixdev-br.github.io/MatchDesk/) · [Downloads](DOWNLOADS.md#english) · [Support](SUPPORT.md#english)

## Preparing something new

MatchDesk is moving to its new identity. The new app builds are still in preparation. The full website will launch alongside the updated apps; until then, the official address displays a preview.

**No MatchDesk packages are available in this repository yet.** Releases and downloads carrying the previous brands have been withdrawn. See [Downloads and availability](DOWNLOADS.md#english) for the official distribution status.

## Applications

| Application | Platform | Purpose |
| --- | --- | --- |
| **MatchDesk Pro** | Windows 10/11, 64-bit | Connection monitor, overlay, server center, regions and match history. |
| **MatchDesk Scout** | Windows 10/11, 64-bit | Available opponent and match information, as a standalone app or integrated into Pro. |
| **MatchDesk Mobile** | Android with a compatible OpenWrt router | Monitor a PC, PlayStation or Xbox on the local network, using your phone as a dashboard. |
| **MatchDesk Trial** | Windows 10/11, 64-bit | Evaluation edition of the main app. Availability and conditions will be announced with its release. |

PC support covers eFootball on Steam and Xbox PC. Check the notes for each build for features, requirements and compatibility. Scout runs on Windows only; console monitoring requires Mobile and a compatible router.

## Before installing

- Direct network capture on Windows with Pro uses [Npcap](https://npcap.com/#download), installed from the official source. Scout does not require Npcap.
- Mobile requires a router running OpenWrt. The manufacturer's original firmware is not sufficient. See the [setup guide in Portuguese](OPENWRT_MOBILE_GUIDE.md).
- Commercial editions require the corresponding license. A license for one application does not automatically grant access to the others.
- Follow the published package instructions and extract the entire contents of ZIP archives.

The app displays the data made available by the session and platform. Latency measurements, location estimates and opponent identification have limitations; region selection does not guarantee a matchmaking result.

## Downloads and updates

Future builds will be published through the official channels listed in [DOWNLOADS.md](DOWNLOADS.md#english), with a version, platform, release notes and integrity information. Do not use third-party copies or files renamed to appear to be a new release.

During this transition, the update manifest for withdrawn builds is no longer published. A missing manifest does not indicate that a new version is available.

## Help and security

- [Support and troubleshooting](SUPPORT.md#english)
- [Mobile and OpenWrt guide in Portuguese](OPENWRT_MOBILE_GUIDE.md)
- [Report an issue](https://github.com/MixDev-br/MatchDesk/issues/new/choose)
- [Report a vulnerability privately](SECURITY.md)
- [Public changelog](CHANGELOG.md)

Do not publish license keys, passwords, tokens, complete device codes or screenshots containing personal data. Existing support channels remain available during the transition.

## About this repository

This is the public documentation and distribution repository for MatchDesk, maintained by MixDev. The application source code is proprietary and is not provided here. Application use is governed by the terms supplied with each product; public access to this repository does not grant an open-source license.

MatchDesk is an independent project, not affiliated with, sponsored by or endorsed by KONAMI. eFootball and other referenced trademarks belong to their respective owners.
