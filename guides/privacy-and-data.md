# Privacy and data controls

[Guide index](../README.md) · [Private security reports](../SECURITY.md)

This page explains controls in the current development build. Read the [SavorLoop Privacy Policy](../PRIVACY.md) for the current policy. GitHub is a separate service: information you post in a public issue is not confined to your iPhone.

## What is stored locally

The current app keeps its profile, saved plans, meal feedback, behavior records, checklist state, and settings in its local app storage. Core planning and preference learning do not require a SavorLoop account or a remote meal-planning service.

The current build excludes its personal database from device backups. Do not assume that cloud device backup will recover this database or that a second device will automatically receive your plan. No cross-device account sync is provided in the documented build.

## Export your information

1. Open **You**.
2. Find **Privacy & data**.
3. Choose **Export my data**.
4. Use the system share sheet to choose a destination, or cancel it.
5. If **Remove temporary export** is visible afterward, use it to remove the app's temporary copy when no longer needed.

An export can include personal preferences, plans, feedback, behavior, and settings. Treat the file as sensitive. Verify that a copy exists in the destination you selected before relying on it.

Removing the temporary export removes the temporary copy managed by the app. It does not recall an email attachment, delete a file you saved elsewhere, or remove copies another service has retained. The current interface does not provide a general import/restore workflow, so an export should not be described as a one-tap restorable backup.

**Do not attach this export to a GitHub issue.** Most support problems can be explained with fictional inputs, the affected screen, the exact error text, and the app build.

## Delete local app data

1. Decide whether you need to keep an export first.
2. Open **You → Privacy & data**.
3. Choose **Delete all local data**.
4. Read the confirmation before choosing the destructive action.

The confirmation explains that the profile, saved plans, feedback, and checklists will be removed. The app returns to a fresh setup state. This action cannot be undone through the app. Exported copies remain wherever you saved or shared them.

Deleting local data or deleting the app does not cancel any Apple subscription. Purchases are disabled in the current development build; if a future version enables them, billing controls remain separate from local deletion.

## A storage error is not a request to erase data

If the app cannot open or interpret saved information, it is designed to preserve data and report a problem. Do not delete the app or erase its data as the first troubleshooting step. Record the non-sensitive error wording, app build, device/OS version, and whether an update happened just before the error. See [troubleshooting](troubleshooting.md).

## Share support details safely

Public tickets can be read, copied, indexed, or emailed to other people. Omit names, addresses, body measurements, medical conditions, personal allergy profiles, receipts, tokens, and complete device logs. Use made-up inputs that reproduce the problem. Crop or redact screenshots and inspect the final image before submitting it.

Private vulnerability reporting is for suspected security flaws or unintended exposure of information. It is not a general-purpose private medical or account-support inbox. If you cannot explain a general question safely in public, do not post sensitive details; ask a generic question about the available support route.
