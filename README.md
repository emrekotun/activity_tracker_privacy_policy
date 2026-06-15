# Run Tracker Privacy Policy

**Last updated:** June 15, 2026

Run Tracker is a privacy-first fitness tracker. This policy explains what information the app accesses and how it is handled.

## Data Collection

Run Tracker **does not collect, transmit, or share any personal data**. The app operates entirely on-device with no account system, no cloud sync, and no network communication.

The app does not include any third-party analytics, crash reporting, advertising, or tracking SDKs.

## Data Storage

All data — including activity records, GPS routes, strength logs, gear tracking, and interval workouts — is stored locally on your device using SwiftData (Apple's on-device persistence framework). No data is sent to any server or cloud service.

If you delete the app, all associated data is removed from your device.

## Permissions and Data Access

### Location (GPS)
Run Tracker accesses your location only while you are recording an outdoor activity. Background location access is requested solely to continue GPS tracking when the screen is locked during an active workout. Location data is never transmitted off your device.

### HealthKit
Run Tracker can optionally read heart rate and step data from HealthKit to enrich activity summaries. It can also write completed workouts to HealthKit if you enable sync. All HealthKit access is opt-in, managed through Apple's system privacy controls. Data is only accessed on your device and is never shared externally.

### Motion
Run Tracker uses the Core Motion framework to detect when you have stopped moving (for auto-pause) or are traveling by vehicle. Motion data is processed locally and is not stored beyond the current session or transmitted.

### Notifications
Run Tracker uses local notifications for optional training reminders. No notification data leaves your device.

## Data Export

Run Tracker allows you to export your data as JSON, CSV, or GPX files. These exports are written to a temporary directory on your device and shared only through the system share sheet — you choose where to send them. Export is entirely user-initiated.

## Data Import

Run Tracker can import GPX files you select via the system file picker. Imported data is stored locally on your device.

## Third-Party Services

Run Tracker does not integrate with any third-party services, APIs, or SDKs that process user data.

## Children's Privacy

Run Tracker does not knowingly collect any personal information from children. The app is rated 4+ on the App Store.

## Your Control

- All permissions (Location, HealthKit, Motion, Notifications) can be granted or revoked at any time through your device Settings.
- All data can be deleted by deleting individual activities or removing the app.
- Export your complete data at any time via the Export feature.

## Changes to This Policy

If this policy is updated, the "Last updated" date at the top will reflect the change. Since the app has no network capability, updates will be distributed exclusively through App Store updates.

## Contact

If you have questions about this privacy policy, please contact:

**Email:** ktnapps@gmail.com

---

## Summary

| Area | What Run Tracker Does |
|------|-------------------|
| Data collection | None |
| Data transmission | None |
| Third-party SDKs | None |
| Analytics | None (local-only computation) |
| Account required | No |
| Cloud sync | No |
| Internet required | No |
| Data storage | On-device only |
| User data export | Yes (JSON, CSV, GPX) |
