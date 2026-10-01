---
layout: page
title: Privacy Policy
permalink: /privacy/
---

# Spill Da Beans Privacy Policy

**Effective date:** 2026-05-12
**Last updated:** 2026-05-12

> **v0.1.0 early-access notice:** all privacy + support contact for Spill Da Beans is handled at **support@spilldabeans.com** during early access. Domain-aliased email addresses (e.g. `privacy@<domain>`) will land in a future release as the brand surface formalizes.

This Privacy Policy explains what information Spill Da Beans collects, how we use it, and the choices you have. We wrote it in plain language so an App Store reviewer or any user can understand it without a lawyer.

If you have questions, contact us at **support@spilldabeans.com**.

---

## 1. Who we are

Spill Da Beans is an iOS app for recommending places to your friends. You "spill a bean" to recommend a place: you choose the place and can add a photo, a short note (up to 280 characters) and quick tags. Beans are positive recommendations only; the app has no ratings. Your friends in the app are your "Pod." For each bean you choose who can see it: your Pod, or only you (a "Secret bean"). You can see your Pod's beans in a feed and on a map of nearby places, and you can report a bean or block another user. Spill Da Beans is operated by the team behind the app (contact: support@spilldabeans.com).

## 2. Information we collect

We collect the minimum needed to make the app work. We do NOT use your data for advertising. We do NOT sell your data. We do NOT track you across other apps or websites.

### 2.1 Contacts (hashed only)

When you choose to find friends, we send a one-way cryptographic hash of each contact's phone number or email to our server, never the original value. The server uses the hashes only to check whether anyone in your address book already has a Spill Da Beans account. We never store your contacts' plaintext phone numbers or emails.

You control whether to grant Contacts access. You can revoke access in iOS Settings at any time. We only read contacts at the moment you opt in to find-friends; we do not read them in the background.

### 2.2 Location (coarse, only when you spill a bean)

We collect coarse location only at the moment you choose to "spill a bean." We do NOT track your continuous location. We do NOT collect background location. The coarse location is attached as metadata to the bean you just created so it can appear on the map.

You control whether to grant Location access. You can revoke access in iOS Settings at any time.

### 2.3 User content (photos, text, tags)

When you spill a bean you choose to upload:
- an optional photo
- optional tags
- who can see the bean (your Pod, or only you as a Secret bean)
- optional text notes

This is your content. You can delete any bean at any time from within the app, which removes it from our server.

### 2.4 Account identifiers

To sign you in we use either Sign in with Apple or phone-number verification (one-time SMS code). We store:
- a Spill Da Beans account identifier (UUID)
- the Apple Sign In identifier OR your phone number in E.164 format
- a device push-notification token, only if you opt in to push notifications

We do NOT collect your name unless you choose to provide it as part of your profile.

## 3. How we use your information

Solely for app functionality:
- Authenticating you and keeping your session secure
- Letting your friends find you when they grant contacts access (via hashed match)
- Displaying your beans to the audience you selected (your Pod, or only you for a Secret bean)
- Delivering push notifications you opted into

We do not use your information for advertising, profiling, or any purpose unrelated to running the app.

## 4. Who has access

Your content and identifiers are stored on the following service providers under their respective data-processing terms. We do not sell or share your data with anyone else.

| Service | Purpose | What they see |
| --- | --- | --- |
| Supabase | Database + authentication | Your account data, beans, hashed contacts |
| Apple | Sign in with Apple, push notifications | Your Apple Sign In identifier; push tokens |
| Twilio (via Supabase) | Phone OTP delivery | Your phone number during SMS verification |
| Mapbox | Map tiles | Anonymous map-view requests (no account data) |
| Cloudflare | DNS, edge | Routing only, no message content |

These providers are contractually limited to using your data only to provide their service to us.

## 5. Where your data is stored

Your data is stored in the United States on infrastructure operated by the providers listed above. The hashed-contact graph is stored only as opaque hashes — we cannot reverse them to your contacts' phone numbers or emails.

## 6. How long we keep it

- Account data: until you delete your account.
- Beans: while the bean is live. You can delete any bean at any time.
- Hashed contacts: while you remain opted in to find-friends. We delete them when you revoke contacts access in-app or delete your account.
- Server logs (for operational debugging): up to 30 days.

## 7. Your rights and choices

You can, at any time:
- **Delete any individual bean** from the bean's menu in the feed or from the place sheet on the map.
- **Delete your entire account in-app** from Settings -> Delete Account. Deletion removes your profile, beans, hashed contacts, and authentication record from our database. It cannot be undone.
- **Revoke iOS permissions** (Contacts, Location, Photos, Notifications) at any time in iOS Settings -> Spill Da Beans. Revoking a permission disables the feature that requires it but does not delete past data; use account deletion for that.
- **Ask us a question** about your data at support@spilldabeans.com.

If you are in the European Economic Area, the United Kingdom, or a jurisdiction with comparable privacy rights (e.g. California), you may also request: access to your data, correction, deletion, or a copy of what we hold. Email support@spilldabeans.com and we will respond within 30 days.

## 8. Children

Spill Da Beans is not intended for users under 13. We do not knowingly collect data from anyone under 13. If you believe a child under 13 has registered, contact us at support@spilldabeans.com and we will delete the account.

## 9. Security

- Authentication and content access are protected by row-level security on our database.
- Apple Sign in tokens use refresh-token rotation.
- All client-server traffic is encrypted in transit (TLS).
- Service-role credentials never ship in the iOS app.

No system is perfectly secure. If we learn of a breach that affects your data, we will notify you within the timeframe required by applicable law.

## 10. Changes to this policy

If we make material changes, we will update the "Last updated" date above and notify users in-app before the changes take effect. Continued use of Spill Da Beans after a change means you accept the updated policy.

## 11. Contact

Privacy questions, data requests, or anything else related to this policy:
**support@spilldabeans.com**
