# ReadXP — Account & Data Deletion

**App Name:** ReadXP — RPG Reading Tracker
**Package:** com.readxp.app
**Developer:** Barbaros Uzunköprü
**Contact:** readxp.app@gmail.com
**Last Updated:** November 18, 2026

---

This page explains how to delete your ReadXP account and the data associated with it.

## Two ways to delete your account

### Option 1 — In the app (recommended, immediate)

If you still have ReadXP installed:

1. Open ReadXP and sign in to the account you want to delete.
2. Go to **Settings**, scroll to **Danger Zone** at the bottom, and tap **Delete My Account**.
3. Confirm the deletion twice and re-authenticate when prompted.
4. Your account and cloud data are deleted immediately.

If you joined the Tavern, the app first takes you out of it: your clubs, your chat messages and room notes, your public reading lists, your shared Library, your username and your card. If your messages, notes or lists cannot be removed (for example, there is no connection), the deletion stops, nothing is deleted, and you can try again.

### Option 2 — By email (for users who have already uninstalled)

If you can no longer access the app, email us:

- **To:** readxp.app@gmail.com
- **Subject:** `DELETE ACCOUNT`
- **Body must include:** the email address tied to the ReadXP account you want deleted.

We'll verify the request by replying to that email address, then delete the account within **30 days** of verification. In practice most requests are handled within a few working days. If you used the Tavern, we remove your Tavern records by hand at the same time.

---

## What gets deleted

When your account is deleted we remove:

- Your Firebase Authentication record (email, user ID)
- Your cloud-synced reading data stored in Firebase Firestore (books, sessions, notes, goals, character progress, badges)
- The cover images you uploaded for your books, stored in Firebase Storage (app version 1.7 and later)
- Your Tavern records, if you joined the Tavern: your card (your name, your @username, your class and level, your room), your friendships and friend requests, your club memberships, your pages in each club's weeks and your lines in each club's activity (with the stamps you left), your club chat messages, the notes you wrote on rooms and the notes on yours, your public reading lists, your shared Library, and your list of blocked readers. Other readers' phones stop showing you the next time they refresh.

If you also want to remove the app's local copy from a device, uninstall the app or clear its data from Android Settings → Apps → ReadXP → Storage → Clear data.

## Leaving the Tavern without deleting your account

You can leave the Tavern and keep your account. In the app, go to **Settings → Tavern**, switch off **In the Tavern** and confirm.

This removes right away your club memberships, your chat messages and room notes, your public reading lists, your shared Library, your username, your card and your friendships. Your account and your reading data stay. If you join again later, you start fresh: old friendships, clubs and lists do not come back.

## What is retained

Some records cannot be deleted by us because they are controlled by third parties or required by law:

- **Purchase records** — Google Play and RevenueCat retain subscription and purchase records per their own policies and tax-record requirements. These records no longer link to an active ReadXP account after deletion.
- **Crash diagnostics** — anonymised crash reports already uploaded to Firebase Crashlytics are retained per Google's Firebase retention schedule. They contain no personally identifying information we control (see the [Privacy Policy §2f](./) for details).
- **Email correspondence** — the email you send us to request deletion is retained in our support inbox for up to 12 months so we can prove the request was handled.
- **Other readers' blocked lists**: if another reader blocked you in the Tavern, the reference of your account (a code, not your name or your email) stays in their private blocked list.
- **Reports**: a report you made, or one made about something you wrote, is kept while it is reviewed. It holds your account's code, never your email.

---

## Related

- [Privacy Policy](./)
- Google Play listing: `com.readxp.app`

For any questions, contact **readxp.app@gmail.com**.
