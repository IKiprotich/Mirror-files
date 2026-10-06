# Privacy Policy for Mirror

**Last updated:** October 6, 2026

Mirror ("the app," "we," "our") is developed by Ian Kiprotich, an individual developer based in Kenya. This Privacy Policy explains what data Mirror accesses, how it's used, and what happens to it.

## The short version

Mirror stores your Screen Time insights, history, settings and answers on your device. There are no Mirror servers and no analytics. We never see your Screen Time data, your app usage, or anything else Mirror works with — it stays on your phone.

The one thing that leaves your phone is a record of any purchase you make. If you buy Mirror Premium, Apple processes the payment and RevenueCat, the service Mirror uses to record purchases, keeps a record of it. That record isn't linked to your name or email. See [Purchases](#purchases) below.

## What Mirror accesses, and why

**Screen Time / Family Controls data.** With your explicit permission (granted through Apple's system authorization prompt), Mirror uses Apple's Screen Time APIs (DeviceActivity, FamilyControls, ManagedSettings) to:
- Show you patterns in your app usage (peak usage times, pickup counts, session lengths)
- Apply a temporary "pause" screen before opening apps you've chosen
- Enforce the rules you set: daily limits, blocks, schedules, a daily goal and Quick Block

This data is processed entirely on your device, inside Apple's Screen Time framework and Mirror's own app extensions. It is never transmitted anywhere.

**Notifications.** If you turn on reminders, a daily goal or the Sunday recap, Mirror asks permission to send local notifications. These are scheduled and delivered entirely on-device through Apple's notification system — Mirror does not use any push notification service or external server to send them.

**Your answers.** When you set Mirror up, it asks a few questions, such as your first name (optional), what you'd like more time for, and when your days start and end. Mirror uses your answers to suggest rules and to word things for you, for example on the screen shown when an app is held. They are stored only on your device and are never sent anywhere.

**History data.** Mirror keeps a local record of each day, such as whether your rules held, stored using Apple's SwiftData framework directly on your device. This data is not backed up to iCloud or any other cloud service, is not accessible to us, and is not shared with any third party.

### Purchases

If you buy Mirror Premium, Apple processes the payment; Mirror never sees your payment details. Mirror uses RevenueCat, a subscription service, to record purchases, so we can see how many people subscribe. RevenueCat receives the purchase details (the plan, when it was bought, the price and currency), your device model and iOS version, your country, and a random ID created on your phone. It never receives your name, email, Screen Time data, history or answers, and we can't link a purchase to you. RevenueCat's privacy policy is at [revenuecat.com/privacy](https://www.revenuecat.com/privacy), and Apple's at [apple.com/legal/privacy](https://www.apple.com/legal/privacy/).

### Things you choose to send

**Feedback.** If you use Send Feedback, Mirror opens an email to us with your app version, iOS version and device model filled in. You can read and change all of it before sending, and nothing is sent unless you send it.

### A friend's key

If you ask someone you trust to hold a key to your rules, they type a four-digit code on your phone. Mirror keeps only a scrambled (hashed) copy of it on your device and sends it nowhere.

## What Mirror does not do

- We do not operate any servers that receive your data.
- We do not use any advertising or tracking SDKs, and nothing measures how you use the app. The one third-party SDK in Mirror is RevenueCat, which records purchases only.
- We do not sell your data. Apart from the purchase records described under Purchases, we do not share or transmit your data to any third party.
- We do not have access to which specific apps you've selected to monitor — Apple's Screen Time framework deliberately keeps this information private even from the app requesting it, using privacy-preserving "opaque tokens" rather than exposing app identities to third-party developers.

## Data export and deletion

You can export your history data at any time from Settings → Your Data → Export History, which generates a JSON file containing your local records for you to keep or delete as you wish.

You can clear all locally stored history at any time from Settings → Your Data → Clear History. This permanently deletes your history data from your device.

Settings → Your Data → Delete All Data removes your apps, rules, history and answers from your device.

Purchase records are kept by Apple and RevenueCat, not on your device, so deleting data in Mirror doesn't remove them. The RevenueCat record isn't linked to you; if you'd like it removed, email us and we'll help.

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
