---
title: "Talimelo — Privacy Policy"
lang: en
---

# Talimelo — Privacy Policy

Last updated: 2026-09-22

Talimelo (the "App") is a read-aloud picture book app
for children aged 0 to 8. The developer of the App (the "Developer") designed it so that
**the App collects no information that can identify a user.**

This page explains what that means in practice.

---

## 1. Summary

- The App does **not** collect names, email addresses, phone numbers, postal addresses,
  dates of birth, photos, contacts, or location.
- There is **no account and no sign-in**.
- **There are no ads.** The App contains no advertising SDK and does not use an advertising ID.
- **There is no analytics SDK and no crash-reporting SDK.**
- The only Android permission the App requests is **internet access**.
- Because nothing is collected, the Developer holds no personal information about users,
  and therefore none is shared or sold.

---

## 2. Information the App does not collect

The App neither collects nor transmits any of the following:

- Contact details such as name, email address, phone number, or postal address
- Attributes of a child such as age, date of birth, or gender
- Photos, camera images, microphone audio, contacts, or calendar data
- Location by any means (GPS, Wi-Fi, or cell tower)
- The Android advertising ID (AAID) or any other cross-app tracking identifier
- A list of other apps installed on the device

The App requests no camera, microphone, location, contacts, or storage permission.
In the Android app info screen, the only permissions shown for the App are
`INTERNET` and the Google Play Store billing permission.

---

## 3. Services the App connects to

The App connects to exactly two destinations, and to nothing else.

### 3.1 Content delivery (Cloudflare R2)

Used to fetch the book list, cover images, page artwork, story text, and audio files.

- The only thing sent is which file is being requested. It contains nothing that identifies a user.
- However, as with any web server, Cloudflare, Inc. — which operates the delivery
  infrastructure — may record standard access logs (source IP address, timestamp, and the
  name of the file served) for the operation and abuse prevention of its service.
  These are Cloudflare's infrastructure logs; the Developer does not use them to identify
  individuals or to analyse usage.
- Once a book has been downloaded it is stored on the device and can be read offline.

### 3.2 Purchases (Google Play and RevenueCat)

Used for the optional purchase of paid books.

- **Payment itself is handled by Google Play.** Payment details such as card numbers are
  never passed to the App or to the Developer.
- Purchase records and restore handling use the service of RevenueCat, Inc.
  The first time the App is launched, RevenueCat generates one random **anonymous ID**.
  This ID is not linked to a name or an email address and cannot be traced back to a person.
- RevenueCat receives that anonymous ID, records of purchases and restores, and technical
  information such as the app version, OS version, device model, and country
  (estimated from the IP address). This is used only to verify and restore purchases and to produce aggregate sales figures that identify no one.
- If the App is uninstalled and reinstalled, a new anonymous ID is generated. Earlier
  purchases can be recovered with "Restore purchases" inside the parents' area, based on
  the purchase history held by the Google account.

---

## 4. Information stored on the device

The following is stored **only on the device and is never transmitted**:

- Settings (display language, chosen voice, automatic page turning on/off, reading mode)
- Downloaded books (artwork, text, audio) and the record of what has been downloaded
- A cached copy of the most recently retrieved book catalogue

All of this is removed from the device when the App is uninstalled. Individual books can
also be deleted from the parents' area inside the App.

---

## 5. Advertising

The App **shows no advertising whatsoever.** It contains no advertising network SDK, and
the permission that would allow use of the advertising ID (AAID) is explicitly removed from
the App's manifest. Screens that children see contain no links to external sites, no social
media, and no promotion of other apps.

---

## 6. Children's privacy

The App is built for children aged 0 to 8 and is designed with reference to the requirements
of the Google Play Families programme, the United States Children's Online Privacy Protection
Act (COPPA), the provisions concerning children in the EU General Data Protection Regulation
(GDPR), and Japan's Act on the Protection of Personal Information.

- The App collects **no personal information** from children or from parents. Because there
  is nothing to collect, there is no mechanism for obtaining verifiable parental consent
  before collection.
- **Purchases, restoring purchases, bulk downloads, and deleting data are all placed behind
  a parental check screen** that requires entering a set of digits in a stated order.
  None of these can be triggered by a child's incidental taps alone.
- Screens that children see contain no external links, no visible URLs, no social media, and
  no advertising-like elements.

If you believe that information about a child has nevertheless reached the Developer, please
use the contact details below and it will be checked and deleted.

---

## 7. Sharing and sale of information

The Developer holds no personal information about users, so there is nothing to share with or
sell to third parties. The App passes no information to any third party for advertising purposes.

Even in response to a lawful disclosure request, the Developer holds no personal information
about users that could be produced.

---

## 8. Security

All network communication by the App uses encrypted connections (HTTPS).

---

## 9. Changes to this policy

If this policy changes, this page will be updated and the "Last updated" date at the top will
be revised. If a change materially affects users, it will be noted in the App's release notes.

---

## 10. Contact

For questions about this policy or about privacy in the App, please contact:

- Developer: yoshiidev
- Email: jcom.japan.jumpei@gmail.com

日本語版: [https://jumpei441.github.io/talimelo-privacy/ja/](https://jumpei441.github.io/talimelo-privacy/ja/)
