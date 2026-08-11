# Privacy Policy for Mirror

**Last updated:** August 11, 2026

Mirror ("the app," "we," "our") is developed by Ian Kiprotich, an individual developer based in Kenya. This Privacy Policy explains what data Mirror accesses, how it's used, and what happens to it.

## The short version

Mirror stores everything on your device. There are no Mirror servers, no analytics, and no third-party data sharing. We never see your Screen Time data, your app usage, or anything else Mirror works with — it stays on your phone.

## What Mirror accesses, and why

**Screen Time / Family Controls data.** With your explicit permission (granted through Apple's system authorization prompt), Mirror uses Apple's Screen Time APIs (DeviceActivity, FamilyControls, ManagedSettings) to:
- Show you patterns in your app usage (peak usage times, pickup counts, session lengths)
- Apply a temporary "pause" screen before opening apps you've chosen
- Enforce daily time limits you set for specific apps

This data is processed entirely on your device, inside Apple's Screen Time framework and Mirror's own app extensions. It is never transmitted anywhere.

**Notifications.** If you enable streak reminders, Mirror requests permission to send local notifications. These are scheduled and delivered entirely on-device through Apple's notification system — Mirror does not use any push notification service or external server to send them.

**History data.** Mirror keeps a local record of your daily limit status and streaks, stored using Apple's SwiftData framework directly on your device. This data is not backed up to iCloud or any other cloud service, is not accessible to us, and is not shared with any third party.

## What Mirror does not do

- We do not operate any servers that receive your data.
- We do not use any analytics, tracking, or advertising SDKs.
- We do not share, sell, or transmit your data to any third party.
- We do not have access to which specific apps you've selected to monitor — Apple's Screen Time framework deliberately keeps this information private even from the app requesting it, using privacy-preserving "opaque tokens" rather than exposing app identities to third-party developers.

## Data export and deletion

You can export your history data at any time from Settings → Export History, which generates a JSON file containing your local records for you to keep or delete as you wish.

You can clear all locally stored history at any time from Settings → Clear History. This permanently deletes your history data from your device.

Uninstalling Mirror removes all app data from your device, including any Screen Time authorizations, shield configurations, and history records.

## Children's privacy

Mirror is not directed at children and we do not knowingly collect data from children. If Mirror is used within Apple's Family Sharing / parental Screen Time setup, please review Apple's own privacy documentation for how that context affects data handling, as it operates under Apple's separate parental controls framework.

## Changes to this policy

If Mirror's data handling changes in a future update (for example, if we introduce optional cloud sync), this policy will be updated to reflect that, and the "Last updated" date above will change accordingly. Material changes will be noted prominently within the app.

## Contact

Questions about this policy or how Mirror handles data can be sent to:

**ikiprotichian@gmail.com**

## Governing law

This policy is governed by the laws of Kenya.
