# ReadXP — Account & Data Deletion

**App Name:** ReadXP — RPG Reading Tracker
**Package:** com.readxp.app
**Developer:** Barbaros Uzunköprü
**Contact:** readxp.app@gmail.com
**Last Updated:** April 20, 2026

---

This page explains how to delete your ReadXP account and the data associated with it.

## Two ways to delete your account

### Option 1 — In the app (recommended, immediate)

If you still have ReadXP installed:

1. Open ReadXP and sign in to the account you want to delete.
2. Go to **Settings → Account → Delete Account** (Danger Zone, at the bottom of Settings).
3. Confirm the deletion twice and re-authenticate when prompted.
4. Your account and cloud data are deleted immediately.

### Option 2 — By email (for users who have already uninstalled)

If you can no longer access the app, email us:

- **To:** readxp.app@gmail.com
- **Subject:** `DELETE ACCOUNT`
- **Body must include:** the email address tied to the ReadXP account you want deleted.

We'll verify the request by replying to that email address, then delete the account within **30 days** of verification. In practice most requests are handled within a few working days.

---

## What gets deleted

When your account is deleted we remove:

- Your Firebase Authentication record (email, user ID)
- Your cloud-synced reading data stored in Firebase Firestore (books, sessions, notes, goals, character progress, badges)

If you also want to remove the app's local copy from a device, uninstall the app or clear its data from Android Settings → Apps → ReadXP → Storage → Clear data.

## What is retained

Some records cannot be deleted by us because they are controlled by third parties or required by law:

- **Purchase records** — Google Play and RevenueCat retain subscription and purchase records per their own policies and tax-record requirements. These records no longer link to an active ReadXP account after deletion.
- **Crash diagnostics** — anonymised crash reports already uploaded to Firebase Crashlytics are retained per Google's Firebase retention schedule. They contain no personally identifying information we control (see the [Privacy Policy §2f](./) for details).
- **Email correspondence** — the email you send us to request deletion is retained in our support inbox for up to 12 months so we can prove the request was handled.

---

## Related

- [Privacy Policy](./)
- Google Play listing: `com.readxp.app`

For any questions, contact **readxp.app@gmail.com**.
