---
title: SpareDeck Privacy Policy
permalink: /privacy
---

# SpareDeck Privacy Policy

_Effective: 10 November 2026_ · [Italiano](privacy-it)

SpareDeck turns a spare phone or tablet into a control deck for your own computer. It has two parts: the **SpareDeck app** for Android (and a web page for other devices) and the **SpareDeck server** that you install on your Mac or Windows PC.

**In short:** SpareDeck has no accounts, ads, analytics or tracking. The developer runs no servers and receives none of your data. Your phone talks only to your own computer on your local network.

## 1. What the Android app stores

On your device only:

- the computers you paired: name, network address, port, certificate fingerprint, and the access token your computer issued to this device;
- which computer you used last.

This data is not included in cloud backups (`allowBackup` is off). Tapping **Remove** on a computer, or uninstalling the app, deletes it.

## 2. Where the Android app connects

- **Only to computers on your local network** that run SpareDeck. It finds them with local network discovery (mDNS). Connections use HTTPS with a certificate created on your computer; you approve each new device on the computer.
- The app sends your computer the commands you tap, and your device's **battery level** (shown in the computer's Batteries widget).
- It does not connect to any server run by the developer.

## 3. Permissions

| Permission | Used for | Where the data goes |
|---|---|---|
| Camera | The **Phone** tab, only when you start it: your device's camera becomes a webcam for your computer. | Streamed directly to your paired computer over your local network. Not saved by the app. |
| Microphone | The **Phone** tab, only when you start it: your device becomes a microphone for your computer. | Streamed directly to your paired computer over your local network. Not saved by the app. |
| Network / Wi-Fi state, multicast | Finding your computers on the local network. | Stays on your local network. |
| Vibrate | The timer alarm. | — |

Camera and microphone are requested only when you first use those features, and you can deny or revoke them at any time in Android settings.

## 4. Third-party services used by the Android app

- **QR code scanning:** the **Scan QR** button uses Google Play services' code scanner. The image is processed on your device and the app itself never gets camera access for it. Google Play services may collect diagnostic data under [Google's privacy policy](https://policies.google.com/privacy).

## 5. The SpareDeck server on your computer

It stores its settings, your deck layout, the list of approved devices (tokens stored only as hashes) and a log in the `.sparedeck` folder of your user account. Besides your own devices, it contacts these services:

- **Weather card:** if you don't set a city, it looks up the approximate location of your internet connection with [ipapi.co](https://ipapi.co/privacy/) (or [ipwho.is](https://ipwho.is) as a fallback), which see your public IP address. It then fetches the forecast from [Open-Meteo](https://open-meteo.com/en/terms#privacy) using those coordinates, or the city name you set. Setting a city avoids the IP lookup.
- **Internet speed test:** at start and when you tap the Internet card, it downloads and uploads test data with [Cloudflare's speed test](https://www.cloudflare.com/privacypolicy/), which sees your public IP address.
- **Now playing / app launching / shortcuts** use only the apps on your computer and send nothing out.

## 6. Sharing and selling

The developer receives no personal data and therefore neither sells nor shares any. Data goes to the third parties above only when you use the related feature.

## 7. Children

SpareDeck is not directed at children under 13 and collects no data about them.

## 8. Your choices and deletion

- On Android: remove a computer in the app, revoke permissions in settings, or uninstall the app.
- On the computer: revoke a device from the menu bar / tray menu, or delete the `.sparedeck` folder.

Because the developer holds no data about you, there is nothing to request from us; everything lives on your own devices.

## 9. Changes

If this policy changes, the new version will be published at this address with a new effective date.

## 10. Contact

Questions: **sparedeckpolicy@protonmail.com**
