---
layout: page
title: "PomodoroGuard - Focus & Productivity"
permalink: /pomodoroguard/
---

# PomodoroGuard

**Take control of your time. Shield your focus.**

PomodoroGuard is a productivity tool designed to help you stay focused by temporarily blocking distracting apps during your work sessions. Using the Pomodoro technique, it balances deep work with rewarding breaks.

## How it Works

1.  **Choose Your Distractions**: Select the apps and categories you want to block during your focus sessions.
2.  **Start the Timer**: Begin a 25-minute "Focus" session.
3.  **Automatic Shielding**: PomodoroGuard uses Apple's **Screen Time (Family Controls)** API to automatically block your selected distracting apps.
4.  **Earn Your Reward**: After 25 minutes of focus, the shields are lifted for a 5-minute "Reward" period.
5.  **Stay on Track**: Once the reward period ends, PomodoroGuard re-applies the shields to help you start your next focus session.

## Screen Time & Privacy

PomodoroGuard is built with privacy at its core. We use Apple's **Family Controls** and **Managed Settings** frameworks to provide a seamless and secure experience.

### Why we use Screen Time APIs:
- **App Shielding**: To effectively block distracting apps without requiring you to manually close them or rely on willpower alone.
- **Background Enforcement**: Our **Device Activity Monitor** ensures that shields are consistently applied and removed, even if you navigate away from the app.

### Your Privacy Matters:
- **No Data Collection**: PomodoroGuard **does not** collect, store, or transmit any information about which apps you use or how often you use them.
- **Token-Based System**: We use Apple's secure token-based system (`FamilyActivitySelection`). This means our app only receives "tokens" representing your app selections. We never see the actual names, icons, or content of the apps you choose to block.
- **Local Processing**: All shielding logic happens locally on your device. No browsing history or app usage data ever leaves your phone.

## Support

If you have any questions or need assistance, please contact us at [rahul.bhalley@gmail.com](mailto:rahul.bhalley@gmail.com).

---
[Privacy Policy](/pomodoroguard-privacy-policy/)
