# Astra Companion for Android

Astra Companion lets you view and control the accounts running in your Astra desktop account manager. Each phone needs approval on the PC, and you choose which accounts it can access.

[Download the latest Android APK](https://github.com/s1mpledelacraiova-spec/Astra-Compapp/releases/latest)

Version **0.2.2**, build **2004**. Requires **Android 7.0 or newer**. The universal APK supports ARMv7, ARM64 and x86_64 devices.

## Install and pair

1. Open the download link on your Android phone and download the APK from the release assets.
2. Open the downloaded file. If Android asks, allow your browser or file app to install apps from this source, then tap **Install**.
3. Open **Astra Companion** and tap **Sign in with Discord**. Authorize in the browser, then return to Astra Companion.
4. On the PC, open Astra and start the accounts you want to access. Open **Phone (P)**, check **Enable phone dashboard**, then click **Create pairing code**.
5. On the phone, tap **Pair PC**, then **Scan QR code**. Allow camera access and scan the code displayed in Astra. You can also enter the pairing code manually. Tap **Request pairing**.
6. On the PC, click **Approve selected accounts…** and select the accounts this phone may view.
7. To allow changes, open **Paired phones**, select this phone, then click **Change control permission…** and confirm **Allow phone controls**.

Use Astra desktop 1.8.0.56 or newer, and keep it running and connected on the PC. The phone controls those PC sessions; the PC must be available for changes to apply.

## Account controls

Select one account, several accounts, or **Select all approved accounts**, then tap **Edit selected**. You can change:

- Pause or Resume.
- Configuration preset.
- Module, ammunition, working map and formation.
- Supported settings for the selected module.
- NPC targets to attack and their priority.

Review the change and its selected accounts before applying it. Astra reports a result for each account. If a result is unconfirmed or expires, check the PC before sending the change again. Available choices depend on the accounts and modules running on the PC.

Phones are initially approved for viewing. The PC controls account access and can remove a phone's access at any time.

## Updating from the local test APK

If you installed the earlier **local test/debug APK**, uninstall it once before installing this public release. The release uses a different signing certificate, so Android cannot install it over that test APK. After installation, sign in and pair the phone again; approve its accounts and controls on the PC again.

Keep using APKs from this repository for later releases. Updates signed with the same release certificate can be installed over the public app. Download and install the new APK when you want to update.

## Beta status and iPhone

This is a public beta. Testing on physical Android phones is still pending.

iPhone users can use the [Astra web app](https://astra-companion.s1mpledelacraiova.workers.dev). Open it in Safari, then choose **Share → Add to Home Screen**.

This repository distributes the Android APK and installation instructions.
