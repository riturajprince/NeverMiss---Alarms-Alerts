# Privacy Policy for NeverMiss

**Last Updated: June 3, 2026**

This Privacy Policy describes how the **NeverMiss** mobile application (referred to as "the App", "we", "us", or "our") handles user information. NeverMiss is built to be a beautiful, minimalist, and private alarm, reminder, and bill-tracking app.

We take your privacy seriously. Please read this Privacy Policy carefully to understand how your information is handled.

---

## 1. No Collection of Personal Data

**NeverMiss is a local-first application.** 

* **No Server Storage:** We do not host or operate external servers to store your personal information. All your schedules, alarms, reminders, habits, and bill details are stored directly on your mobile device.
* **No Account Creation:** You do not need to create an account, log in, or provide any personal information (such as your name, email, phone number, or payment details) to use the App.
* **No Analytics or Tracking:** The App does not contain third-party tracking scripts, advertiser toolkits, or telemetry frameworks. We do not track your behavior, device ID, location, or usage patterns.

---

## 2. Information Stored Locally on Your Device

All information you input into the App is stored in a private, sandboxed SQLite database (managed via Android's Room library) on your device. This data includes:
* **Alarms:** Wake-up times, days of repetition, and alarm labels.
* **Reminders & Tasks:** Title, description, due date, priority, and completion status.
* **Bills & Subscriptions:** Bill name, amount, due date, category, and payment history.

This data is stored securely within the app's private directory and is inaccessible to other apps installed on your device. If you uninstall the App, this data is permanently deleted unless you have backed it up using Android's system-level backup utilities.

---

## 3. Permissions Used by the App

To function correctly, NeverMiss requires specific Android system permissions. Below is a detailed explanation of why each permission is required and how it is used:

### A. Schedule Exact Alarm (`android.permission.SCHEDULE_EXACT_ALARM` & `android.permission.USE_EXACT_ALARM`)
* **Purpose:** Allows the App to schedule alarms and reminders at precise times.
* **Usage:** This is critical to ensure that wake-up alarms and time-sensitive reminders trigger at the exact second configured by the user, rather than being delayed by Android's battery-saving stand-by modes.

### B. Full-Screen Intent (`android.permission.USE_FULL_SCREEN_INTENT`)
* **Purpose:** Allows the App to display a full-screen interface when an alarm or reminder triggers.
* **Usage:** When your phone is locked and an alarm goes off, this permission lets NeverMiss launch the custom wakeup/reminder screen immediately, allowing you to dismiss, snooze, or read the alert without having to unlock your phone first.

### C. Post Notifications (`android.permission.POST_NOTIFICATIONS`)
* **Purpose:** Allows the App to send system notifications.
* **Usage:** Used to display alerts for upcoming due bills, task reminders, and active alarm states in your device's notification tray.

### D. Receive Boot Completed (`android.permission.RECEIVE_BOOT_COMPLETED`)
* **Purpose:** Allows the App to run a background receiver when the device finishes booting.
* **Usage:** Android clears all scheduled alarms when a device is turned off or restarted. This permission allows NeverMiss to automatically restore and re-schedule your upcoming alarms, reminders, and bill alerts immediately after your device restarts so that you "Never Miss" a schedule.

---

## 4. Third-Party Services and Links

The App contains contact buttons linking to external websites/services (such as email clients and Instagram). If you click these links:
* You will be redirected to the respective third-party platform (such as Instagram or your email client).
* Your interaction on those platforms will be governed by their respective privacy policies. We do not control or assume responsibility for the content or privacy practices of these third-party platforms.

---

## 5. Children's Privacy

Because the App does not collect, process, or share any personal information, it is fully compliant with the Children's Online Privacy Protection Act (COPPA) and the General Data Protection Regulation (GDPR). The App is safe to be used by individuals of all ages, including children under the age of 13.

---

## 6. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. Since the App does not collect contact information, we cannot notify users of changes individually. Any updates to this policy will be published in this document or inside the App. We recommend reviewing this page periodically for any changes.

---

## 7. Contact Us

If you have any questions, suggestions, or concerns regarding your privacy or the functionality of NeverMiss, please feel free to reach out to the developer:

* **Developer:** Ritu Raj Prince
* **Support Email:** [medicobhai@gmail.com](mailto:medicobhai@gmail.com) | [riturajprince@outlook.com](mailto:riturajprince@outlook.com)
* **Instagram Handles:** 
  * [@theriturajprince](https://www.instagram.com/theriturajprince)
  * [@riturajprinceofficial](https://www.instagram.com/riturajprinceofficial)
