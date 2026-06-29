# Privacy Policy for Azuu

**Effective Date:** May 24, 2026

## 1. Introduction
This Privacy Policy outlines how Azuu ("we", "our", or "the app") collects, uses, and protects your information. Azuu is designed as a productivity, mindfulness, and focus tool. We prioritize your privacy above all else: **we do not collect, transmit, or sell any of your personal data to external servers or third parties.** All data processing and storage occur entirely locally on your device.

## 2. Permissions & Data Usage
To function reliably as an app blocker and mindfulness tool, Azuu requires specific system permissions. This section clearly discloses why these permissions are needed and how they are used.

### A. Usage Access (PACKAGE_USAGE_STATS)
*   **Why we need it:** To monitor which application is currently in the foreground.
*   **How it is used:** When an active Focus Session is running, the app checks if the foreground application is on your "Allowed Apps" list. If it is a blocked app, Azuu intervenes to prevent the distraction.
*   **Data Handling:** App usage checks are performed locally, dynamically, and transiently. We do not save, record, or transmit your app usage history.

### B. Display Over Other Apps (SYSTEM_ALERT_WINDOW)
*   **Why we need it:** To render the "Focus Shield" blocker overlay on top of distracting applications.
*   **How it is used:** If you attempt to open a blocked app during a Focus Session, Azuu draws a full-screen overlay to block access and remind you of your focus commitment.
*   **Data Handling:** This permission is strictly used for UI rendering and does not collect or log any data.

### C. Notification Access (BIND_NOTIFICATION_LISTENER_SERVICE)
*   **Why we need it:** To temporarily quiet and dismiss notifications while you are focusing.
*   **How it is used:** During a Focus Session, incoming notifications from blocked apps are automatically muted and dismissed to prevent immediate disruption.
*   **Data Handling:** Notification filtering is processed locally. Azuu never reads the content of your notifications, nor does it save or transmit notification details.

### D. Foreground Service (FOREGROUND_SERVICE & FOREGROUND_SERVICE_SPECIAL_USE)
*   **Why we need it:** To run a persistent background service while a session is active.
*   **How it is used:** Running as a foreground service with a visible persistent notification ensures that the Android OS does not unexpectedly terminate the app blocker when your device runs low on memory.
*   **Data Handling:** This service is used purely to maintain blocker reliability and does not gather or upload any data.

### E. Alarm & Boot Maintenance (RECEIVE_BOOT_COMPLETED, SCHEDULE_EXACT_ALARM & USE_EXACT_ALARM)
*   **Why we need it:** To schedule and maintain your custom focus schedules.
*   **How it is used:** The app uses exact alarms to trigger scheduled focus session notifications precisely on time. The boot permission allows the app to automatically reschedule these alarms and recover any active sessions if your device restarts.
*   **Data Handling:** Alarms and schedules are managed locally on your device's alarm manager. No calendar or schedule details are shared externally.

### F. Notifications & High-Priority Alerts (POST_NOTIFICATIONS & USE_FULL_SCREEN_INTENT)
*   **Why we need it:** To notify you about focus milestones and show deterrent screens.
*   **How it is used:** `POST_NOTIFICATIONS` is used to send session start/end reminders and keep a persistent status notification active. `USE_FULL_SCREEN_INTENT` allows the app to show your custom focus deterrent overlay immediately, even if your screen is locked or sleeping, when a distraction block is triggered.
*   **Data Handling:** Used strictly for localized user notification and UI display; no alert data is collected or exported.

### G. Ignore Battery Optimizations (REQUEST_IGNORE_BATTERY_OPTIMIZATIONS)
*   **Why we need it:** To prevent background service termination by the system.
*   **How it is used:** Prompts the user to exclude Azuu from Android's aggressive system battery savers, which ensures that the app blocking background monitor functions uninterrupted.
*   **Data Handling:** Used only to adjust local system settings. No data is stored or processed.

### H. Wake Lock (WAKE_LOCK)
*   **Why we need it:** To keep the CPU active during monitoring.
*   **How it is used:** Keeps the background blocker service running reliably during active sessions, preventing the device from putting the block checks to sleep.
*   **Data Handling:** This is a system-level utility and does not store or process data.

### I. Internet & Network State (INTERNET & ACCESS_NETWORK_STATE)
*   **Why we need it:** To fetch dynamic font assets and support external link launching.
*   **How it is used:** Used by the system to download dynamic typography resources (Google Fonts) on launch, and when you explicitly choose to click on external links inside the app (e.g., contacting support via email, opening the developer's LinkedIn profile, or viewing this Privacy Policy online).
*   **Data Handling:** Used strictly for static asset loading and link redirection. No personal, focus, or app usage data is ever collected, transmitted, or synchronized over the internet.

## 3. Data Storage
All data related to your focus sessions, statistics, target goals, custom deterrent messages, and allowed exception configurations is stored locally on your device using SQLite and SharedPreferences.

*   **No Cloud Sync:** We do not offer cloud synchronization. Your data never leaves your device.
*   **Data Retention:** Azuu automatically deletes session history data that is older than 3 days from your local database to optimize space.
*   **Data Deletion:** If you uninstall the app or clear its data via Android Settings, all stored information is permanently and irreversibly deleted.

## 4. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Since the app operates entirely offline without an account system, we encourage you to review this policy periodically. Any changes will be effective immediately upon publishing the updated policy.

## 5. Contact Us
If you have any questions or suggestions regarding our Privacy Policy, please contact us at:
*   **Email:** azuu2focus@gmail.com
