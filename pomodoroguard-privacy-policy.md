# Privacy Policy — PomodoroGuard

**Last Updated:** March 17, 2026

## Introduction
At **PomodoroGuard**, we respect your privacy. This Privacy Policy explains what information is collected, how it’s used, and the choices you have when using the PomodoroGuard app.

## Summary (Key Points)
- **Core features work entirely on your device.**
- We **do not require accounts** and we do not ask for your email or phone number to use the app.
- We use Apple's **Family Controls (Screen Time)** API to block distracting apps. We **never** see which apps you choose to block.
- We **do not collect, store, or transmit** any of your app usage data or browsing history.

## Information We Collect

### 1) Screen Time Data (Family Controls)
PomodoroGuard uses Apple's **Family Controls** and **Managed Settings** frameworks to provide its core functionality.
- **Tokens only**: When you select apps to block, our app receives opaque "tokens" from the system. We **cannot** see the names, icons, or content of the apps you have selected.
- **Local Storage**: These tokens are stored locally on your device in a secure App Group container so that our background monitor can apply and remove shields as needed.
- **No Transmission**: These tokens and any associated shielding state **never** leave your device.

### 2) Data Stored on Your Device (App Settings & State)
PomodoroGuard stores certain data locally so the app can function properly, such as:
- Timer state (Focus/Reward duration and current progress)
- Your app selection tokens for shielding
- Onboarding completion state

This data is stored locally (for example, using iOS app storage like `UserDefaults` / `AppStorage`).

## How We Use Information
We use information to:
- Provide app functionality (Pomodoro timer, app shielding)
- Enforce focus sessions by blocking distracting apps via the system's Managed Settings.
- Automatically unblock apps during your scheduled reward periods.

## Sharing of Information
- We **do not sell** your personal information.
- We **do not share** your app selections or usage data with any third parties. All data remains strictly on your device.

## Permissions the App May Request
- **Family Controls (Screen Time):** To allow you to select apps to block and to enforce those blocks during focus sessions. This requires your explicit authorization.
- **Notifications:** To alert you when a focus or reward session begins or ends.
- **Live Activities:** To show your current timer progress on the Lock Screen and Dynamic Island.

## Data Retention
- **On-device app data** remains until you delete the app.
- **Screen Time tokens** are managed by the system and are cleared if you revoke the app's Screen Time permission in iOS Settings or delete the app.

## Children’s Privacy
PomodoroGuard is a productivity tool for general use. We do not knowingly collect personal information from children. If you believe a child has provided personal information, contact us and we’ll address it.

## Changes to This Privacy Policy
We may update this Privacy Policy from time to time. Updates will be posted with a revised **Last Updated** date.

## Contact Us
If you have questions about this Privacy Policy, contact:

- **Email:** rahulbhalley@icloud.com
- **Website:** [rahulbhalley.github.io/pomodoroguard/](https://rahulbhalley.github.io/pomodoroguard/)
