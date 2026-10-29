# Privacy Policy

**Last updated: October 29, 2026**

This policy applies to HIITime 1.2 and later.

## Overview

HIITime ("the App") is a workout timer and tracker for HIIT, strength and cardio on iPhone and Apple Watch. "We" and "us" in this policy mean the developer of HIITime. Your privacy is important to us. This policy explains what data the App uses, where it is kept, and how you can remove it.

## Data Collection

**HIITime does not collect your personal data. Everything the App uses stays on your devices.**

- We do not run servers or backend infrastructure, and the App does not send your data to us or anyone else.
- We do not use analytics, advertising, tracking or any third-party SDKs.
- We do not track you across apps or websites, and the App does not show ads.
- The App's diagnostic logging (Apple's OSLog) stays on your device. If you have chosen to share analytics with app developers in Settings › Privacy & Security › Analytics & Improvements, Apple may send us anonymous crash reports; you can turn that off at any time.

## Data Stored on Your Device

HIITime stores your data **locally on your device** using Apple's SwiftData framework. This includes:

- Your routines, strength templates and exercise library.
- Your workout history: durations, sets, reps and weights, heart-rate readings, calories, distances, effort scores, and the GPS route of outdoor sessions.
- Your settings.

The App does not sync this data through iCloud. Like other app data, it may be included in your iPhone's backups (iCloud Backup or a computer backup) if you have turned those on.

HIITime keeps its data in a shared container on your device (an "App Group") that its extensions can also use. The App's database is stored there; the Home Screen widgets and Controls read a short list of your workouts' names and icons from it; and the share extension drops text you share into HIITime there for the App to pick up. This container never leaves your device, apart from the device backups described above.

## Apple Health

If you give permission, HIITime uses Apple Health as follows. You choose which types to allow, and you can change this at any time.

**Read:**

- Heart rate and active energy, to show live heart rate and calories during workouts.
- Resting heart rate and date of birth, to set your heart-rate zones.
- Body weight, to work out loads for bodyweight exercises.
- Workouts.

**Write:**

- Your HIIT, strength and cardio workouts.
- Heart rate and active energy (calories) recorded during those workouts.
- Walking/running and cycling distance.
- The GPS route of outdoor sessions.

**Health data is never used for advertising or marketing, never sold, and never shared with third parties.** It is used only to provide the App's fitness features. Health data stays on your devices, except where Apple itself syncs or backs it up according to your own Apple settings — for example, Apple Health syncing through iCloud, or your device backups, which include the heart-rate and calorie readings HIITime copies into its workout history. We never have access to it.

## Location

HIITime uses your location only during outdoor runs, rides and interval workouts, to track your route, distance and pace. It asks for "While Using the App" permission only, and location is used only while a session is running; tracking that starts in the App continues while your screen is locked and stops when the session ends.

The route is saved in your on-device workout history and, if you allow it, to Apple Health as a workout route. It is never sent to us or any third party. Route maps in the App are shown with Apple Maps, which loads map images for that area from Apple. You can turn off location access at any time in Settings › Privacy & Security › Location Services › HIITime; the App's indoor and timer workouts work without it.

## Apple Watch

Workout state, heart rate, calories and logged sets are exchanged between your iPhone and Apple Watch only through Apple's Watch Connectivity framework, which may relay them through Apple when the two devices aren't nearby. They are never sent to us or any third party.

Workouts recorded on Apple Watch are saved to Apple Health with heart rate, active energy and walking/running or cycling distance, if you give permission on the Watch.

## Widgets, Live Activities, Siri and Notifications

- **Widgets and Controls** show a few of your workouts' names and icons so you can start them quickly.
- **Live Activities** show your current workout on the Lock Screen and Dynamic Island.
- **Siri and Shortcuts** can start a workout by name.
- **Notifications** are local reminders scheduled on your device, such as "rest over" alerts when the App is in the background. HIITime does not use push notifications.

All of these run on your device.

## Sharing and AI Workout Import

You can import a workout written by an AI chatbot of your choice:

- The App gives you a prompt to copy, or opens ChatGPT or Claude with that prompt filled in. The prompt only describes HIITime's workout format; the App adds none of your personal or health data to it.
- Whatever you then type into or share with that chatbot is governed by that service's own privacy policy, not this one.
- When you paste the reply back (the App reads your clipboard only when you tap **Paste**) or share text to HIITime from another app, HIITime turns it into a workout on your device. Shared text is kept in the App Group only until the App next opens and imports it.

## Subscriptions

HIITime Pro is sold through Apple's App Store. Apple handles payment; we never see your payment details or Apple ID. The App only checks with Apple whether your subscription is active.

## Deleting Your Data

- **In the App:** delete any workout from History by swiping it. This removes it from HIITime; it does not delete the copy saved in Apple Health.
- **In Apple Health:** delete HIITime's workouts and samples in the Health app, and turn off HIITime's access in the Health app (your profile › Apps, called Sources on older iOS versions) or in Settings › Privacy & Security › Health.
- **Delete the App:** deleting HIITime from your iPhone and Apple Watch removes all data it stored on those devices. Copies in your device backups remain until those backups are deleted. Data already saved to Apple Health stays there until you delete it in Health.

Because we hold no copy of your data, there is nothing for us to delete on our side.

## Children's Privacy

HIITime does not collect any personal data from anyone, including children under the age of 13.

## Changes to This Policy

If we update this policy, we will update the "Last updated" date above and publish the change in this repository, where you can see its full history.

## Contact

If you have any questions about this privacy policy, please [open an issue](https://github.com/pantry-org/HIITime-Support/issues). Issues are public, so please don't include personal or health information.
