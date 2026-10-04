---
layout: page
title: Privacy Policy
permalink: /privacy/
---

# Spill Da Beans Privacy Policy

**Effective date:** PUBDATE
**Last updated:** PUBDATE

> **v0.1.0 early-access notice:** all privacy + support contact for Spill Da Beans is handled at **support@spilldabeans.com** during early access. Domain-aliased email addresses (e.g. `privacy@<domain>`) will land in a future release as the brand surface formalizes.

This Privacy Policy explains what information Spill Da Beans collects, how we use it, and the choices you have. We wrote it in plain language so an App Store reviewer or any user can understand it without a lawyer.

If you have questions, contact us at **support@spilldabeans.com**.

---

## 1. Who we are

Spill Da Beans is an iOS app for recommending places to your friends. You "spill a bean" to recommend a place: you choose the place and can add a photo, a short note (up to 280 characters) and quick tags. Beans are positive recommendations only; the app has no ratings. Your friends in the app are your "Pod." Your beans are shared with your Pod. You can see your Pod's beans in a feed and on a map of nearby places, and you can report a bean or block another user. Spill Da Beans is operated by the team behind the app (contact: support@spilldabeans.com).

## 2. Information we collect

We collect the minimum needed to make the app work. We do NOT use your data for advertising. We do NOT sell your data. We do NOT track you across other apps or websites.

### 2.1 Contacts (hashed only)

When you choose to find friends, your device turns each contact's phone number into a one-way code (a hash) and sends only those codes to our server, never the numbers themselves. We do not read or send your contacts' names or email addresses. We use the codes only to see which of your contacts already use Spill Da Beans.

You control whether to grant Contacts access. We only read contacts at the moment you opt in to find friends; we do not read them in the background. To delete the codes we hold, tap Turn off contact matching in the app's Settings, or delete your account. Turning off Contacts permission in your iPhone settings stops the app reading your contacts but does not by itself delete codes already sent.

### 2.2 Location

With your permission, and only while you are using the app, we use your device's precise location to center the map, show nearby places and suggest the place you are at. To do this, your location or the map area you are viewing is sent to our servers and to our map providers (Apple and Mapbox). We do not collect background location. When you spill a bean, we store the location of the place you chose. If you spill a bean at your current spot or a spot you name yourself, that place's location comes from your device.

You control whether to grant Location access. You can revoke access in iOS Settings at any time.

### 2.3 User content (photos, text, tags)

When you spill a bean you choose to upload:
- the place you are recommending (its name, address, location and category)
- an optional photo
- optional tags
- an optional What to order note
- optional text notes

**Photos can become the picture for the place.** When you add a photo to a bean, Spill Da Beans may use that photo as a picture of the place, visible to everyone who uses the app. Only the photo is shared this way. Your bean itself is shown to your Pod. Using the photo as a place picture does not add your note, tags or attribution as its author to that picture. We can also access beans for support and moderation as described below. A photo used as a place picture stays on the place after you delete the bean or your account. You can ask us to remove it by emailing support@spilldabeans.com.

This is your content. You can delete any bean at any time from within the app, which removes the bean and its photo from our server. If the photo is being used as a picture of the place, that picture stays on the place (see above).

**Photos are stored at a web address.** Anyone who has that address can open the photo.

**Profile.** Your display name, username, and optional profile photo and bio. Your display name, username, profile photo and bio are available to other signed-in users, including people finding or connecting with you.

### 2.4 Account identifiers

To sign you in we use Sign in with Apple, your phone number (one-time text code) or your email address (one-time email code). We store:
- an account identifier
- your Apple ID identifier and, if you allow it, the name and email Apple shares (which may be a private relay address); or your phone number and a one-way code of it, used so friends who have your number can find you; or your email address
- a push-notification token, only if you allow notifications

You choose a display name when you sign up, and your Pod sees it.

## 3. How we use your information

We use your information to run the app:
- Authenticating you and keeping your session secure
- Letting people who have your phone number find you, letting you find them, and handling friend requests
- Showing your beans to your Pod
- Registering your device for push notifications if you allow them
- Reviewing reports and enforcing blocks to keep the app safe (reports, and any details you add, are seen by our moderation team)

We do not use your information for advertising, profiling, or any purpose unrelated to running the app.

## 4. Who has access

Your content and identifiers are handled by the following service providers under their respective data-processing terms. We do not sell your data, and we do not share it with anyone else except as described in this policy (for example, place pictures).

| Service | Purpose | What they see |
| --- | --- | --- |
| Supabase | Database, sign-in and photo storage | Your account data, beans, photos, contact codes |
| Apple | Maps, place search, location lookups, Sign in with Apple, push notifications | Your search text, the map area or your location, your Apple ID identifier, push tokens |
| Twilio (via Supabase) | Sign-in text messages | Your phone number and the code |
| Resend | Sign-in emails | Your email address and the code |
| Mapbox | Map display | The map area and your location while the map is open |
| Google (Places) | Place photos | Only which place is being looked up; no account data and no location |
| Cloudflare | DNS and email-routing records for spilldabeans.com | Domain and email-routing records |

These providers are contractually limited to using your data only to provide their service to us.

## 5. Where your data is stored

Your data is stored in the United States on infrastructure operated by the providers listed above. The contact codes are stored only as one-way codes of phone numbers. We use them for nothing except finding friends.

## 6. How long we keep it

- Account data: until you delete your account.
- Beans: while the bean is live. You can delete any bean at any time.
- Photos used as place pictures: kept as part of the place until removed on request.
- Contact codes: we delete them when you tap Turn off contact matching or delete your account.
- Account deletion records: we keep your former account identifier, the date of deletion and whether deletion was initiated by you or by an administrator or policy. Any optional reason you give for leaving is stored separately without an account identifier attached.
- Moderation records: reports, reasons and details may remain after account deletion. We remove the deleted account's identifier from the report's account-link fields; identifying information included in written details may remain.
- Server logs (for operational debugging): up to 30 days.

## 7. Your rights and choices

You can, at any time:
- **Delete any individual bean** from the bean's menu in the feed or from the place sheet on the map.
- **Delete your entire account** in the app from Settings, then Delete Account. Deletion removes your profile (name, username, photo and bio), your beans and their photos, your Want to Spill list, your Pod connections, your contact codes and your sign-in record. It cannot be undone. Photos already used as place pictures stay on those places, and we keep the deletion and moderation records described above. Photo removal is processed separately, and cached copies may remain available for a time after deletion.
- **Revoke iOS permissions** (Contacts, Location, Camera, Photos, Notifications) at any time in iOS Settings -> Spill Da Beans. Revoking a permission disables the feature that requires it but does not delete past data; use account deletion for that.
- **Ask us a question** about your data at support@spilldabeans.com.

If you are in the European Economic Area, the United Kingdom, or a jurisdiction with comparable privacy rights (e.g. California), you may also request: access to your data, correction, deletion, or a copy of what we hold. Email support@spilldabeans.com and we will respond within 30 days.

## 8. Children

Spill Da Beans is not intended for users under 13. We do not knowingly collect data from anyone under 13. If you believe a child under 13 has registered, contact us at support@spilldabeans.com and we will delete the account.

## 9. Security

- We use database access rules so that people can see only the beans they are allowed to see. Photos are the exception described above.
- We use encrypted connections between the app and our servers.

No system is perfectly secure. If we learn of a breach that affects your data, we will notify you within the timeframe required by applicable law.

## 10. Changes to this policy

If we make material changes, we will update the "Last updated" date above and notify users in-app before the changes take effect. Continued use of Spill Da Beans after a change means you accept the updated policy.

## 11. Contact

Privacy questions, data requests, or anything else related to this policy:
**support@spilldabeans.com**
