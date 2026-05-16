# Privacy Policy for Azuu

**Effective Date:** May 16, 2026

## 1. Introduction
This Privacy Policy outlines how Azuu ("we", "our", or "the app") collects, uses, and protects your information. Azuu is designed as a productivity and focus tool. We prioritize your privacy above all else: **we do not collect, transmit, or sell any of your personal data to external servers or third parties.** All data processing occurs entirely locally on your device.

## 2. Permissions & Data Usage
To function correctly as an app blocker and focus tool, Azuu requires specific sensitive permissions. This section clearly discloses how these permissions are used.

### A. Usage Access (PACKAGE_USAGE_STATS)
*   **Why we need it:** Azuu requires the Usage Access permission to monitor which application is currently in the foreground.
*   **How it is used:** When an active Focus Session is running, the app checks if the foreground application is on your "Allowed Apps" list. If it is not, Azuu intervenes to block the distraction.
*   **Data Handling:** We do not record, save, or transmit your app usage history. The foreground app check is performed locally and transiently.

### B. Display Over Other Apps (SYSTEM_ALERT_WINDOW)
*   **Why we need it:** Azuu requires the Display Over Other Apps permission to render the "Focus Shield" or penalty banner over distracting applications.
*   **How it is used:** If you attempt to open a non-allowed app during a Focus Session, Azuu will draw an overlay screen on top of the distraction to prevent you from using it.
*   **Data Handling:** This permission is solely used for displaying the UI overlay and does not collect any data.

### C. Notification Access (BIND_NOTIFICATION_LISTENER_SERVICE)
*   **Why we need it:** Azuu uses Notification Access to silence and dismiss distracting notifications while you are focusing.
*   **How it is used:** The app filters incoming notifications against your "Allowed Apps" list. Notifications from non-allowed apps are muted and dismissed to prevent distraction.
*   **Data Handling:** Azuu does not read the content of your messages, nor does it save or transmit notification data.

## 3. Data Storage
All data related to your focus sessions, target goals, custom messages, and allowed apps configurations is stored locally on your device using SQLite and SharedPreferences.

*   **No Cloud Sync:** We do not offer cloud synchronization.
*   **Data Retention:** Azuu automatically deletes session history data that is older than 3 days from your device to save space.
*   **Data Deletion:** If you uninstall the app or clear its data via Android Settings, all stored information is permanently deleted.

## 4. Third-Party Services
Azuu is a strictly local application. We do not integrate with third-party tracking services, analytics platforms, or ad networks.

## 5. Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Since the app operates entirely offline without an account system, we encourage you to review this policy periodically. Any changes will be effective immediately upon publishing the updated policy.

## 6. Contact Us
If you have any questions or suggestions regarding our Privacy Policy, please contact us at:
**Email:** azuu2focus@gmail.com
