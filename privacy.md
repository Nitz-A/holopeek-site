---
title: Holopeek Privacy Policy
permalink: /privacy/
---

# Holopeek Privacy Policy

**Effective date:** 22 November 2026

## The short version

- Holopeek recognizes your cards **on your phone**. Photos you take or pick
  are **never uploaded** and never sent to us. Camera photos are not kept
  after a scan; photos you pick leave only a temporary copy on your phone.
- Your collection is stored **only on your phone**. There is no sign-in and
  no account with a name, email or password.
- **Price alerts** are the one feature that sends data to our server: when you
  save your first price alert, the app creates an **anonymous user** on our
  server and sends it your **price alerts** and your phone's **push token**,
  so we can notify you when a price alert is reached, even when the app is
  closed. You can delete all of it in the app at **Settings › Delete my alert
  data**.
- We use no analytics, advertising or tracking tools.
- To show prices, card details and card pictures, the app downloads them from
  **our server** and from **TCGdex**, a public card database. These requests
  carry only the cards being looked up, plus the technical details that any internet request
  carries, such as your IP address.
- **Apple** handles payments. We never see your card or payment details.

## 1. Who we are

Holopeek is made by Nitzan Aroesty, an individual developer
("we", "us"). We are responsible for this app's handling of personal data
(the "controller" under EU and UK law).

Contact: support@holopeek.com · Basel 9, Tel Aviv 6228508, Israel · https://holopeek.com

## 2. What the app does with your information today

### Camera and card photos
- The app uses your camera only when you open the Scan tab and grant
  permission. iOS asks you first, and you can turn it off at any time in
  **Settings › Holopeek › Camera**.
- Recognition runs entirely on your phone, using models and a card index
  that are built into the app.
- When you tap the shutter, the photo is analyzed and shown to you for review.
  It stays in memory only, is **not saved** to your phone or photo library,
  and is **never sent** anywhere. It is discarded when you close the review.
- We do not use your photos to train or improve our recognition models.

### Photos from your library
- If you choose to scan photos you already have, you pick them in Apple's
  photo picker. The app receives **only the photos you select** and has no
  access to the rest of your library.
- Selected photos are analyzed on the phone and never uploaded. To read them,
  the app works on a temporary copy in its own cache folder on your phone,
  which iOS clears when it needs space; the copies never leave your phone.

### Your collection
- The cards you add are stored **on your phone only**. For each card, that
  means which card it is, its printing, its condition, the quantity, the date
  you added it, and, if you enter it, the price you paid.
- The app also stores a few settings on your phone, such as your sort order,
  your scan mode, whether you have finished the introduction, and whether the
  total value is hidden.
- We cannot see any of this. It is not sent to us or to anyone else.
- If you back up your iPhone to iCloud or to a computer, this data is included
  in that backup like any other app's data. Apple's or your computer's backup
  settings control this, not us.

### Prices and card images
- To show a card's details, such as its set, rarity and printings, the app
  asks **TCGdex** (`api.tcgdex.net`), a public card database.
- To show card pictures, the app loads them directly from TCGdex's image
  server (`assets.tcgdex.net`).
- Each request contains the **identifier of the card** (for example
  "base1-4"). Like every internet request, it also reveals your **IP
  address** and basic technical information, such as the app's version and
  your iOS version. No account, name, email, device identifier or collection
  list is sent.
- TCGdex handles these requests under its own terms and privacy practices.
  We do not control them, and we receive nothing back about you.
- Market prices and their history come from **our server** (hosted by
  Supabase), which stores daily prices from our licensed price source. The
  app sends it the **identifiers of the cards** it needs prices for: the cards
  you scan, collect, look at or set price alerts on. These requests carry no
  account or user ID, and we do not store which cards were asked for. Like
  every internet request, they reveal your IP address to Supabase, which keeps
  its request logs for up to 7 days.
- Prices are saved on your phone so values still show offline. The app asks
  for newer ones when the saved copy is more than an hour old.

### Price alerts and notifications
A price alert tells you once when a card's market price goes above or below a
target price you choose.

- **What is sent to our server, and only once you save your first price
  alert:**
  - an **anonymous user ID**: a random identifier our server creates for
    your phone. It has no name, email, phone number or password behind it;
  - your phone's **push token**: an identifier Apple
    issues so notifications can reach your phone, with the kind of phone and when the
    app last checked in;
  - your **price alerts**: for each one, which card, which printing, above or
    below, the target price, the day you set it, when it was reached, and
    whether it is on or off.

  Nothing else from your collection is sent: not your other cards, their
  conditions or the prices you paid, and never your photos or your age.
- **Why:** so our server can check your price alerts after each daily price
  update and send you a notification when one is reached, even when the app
  is closed. If you have more than one price alert, our server asks
  **RevenueCat** whether you have Pro, using your anonymous user ID, because
  without Pro only your oldest price alert is checked.
- **The notification** says, for example, "Charizard (Holo) is $412.00 —
  above your $400.00 target. Estimate · Scrydex · 2 Nov". To deliver it, its
  text and your push token pass through **Expo** (650 Industries, Inc., USA),
  whose push service hands it to **Apple** (Apple Push Notification service).
  iOS asks your permission before
  any notification is shown. Without that permission your price alerts are
  still kept on the server, but nothing is sent to your phone.
- **Where it is kept:** our server is hosted by **Supabase, Inc.** in the
  **United States (AWS us-east-1)**. Supabase, Expo and RevenueCat process
  this data only to provide their service to us.
- **How long:** a price alert is kept until you delete it in the app (deleting
  it on the phone deletes it on the server too); one you switch off is kept,
  switched off, until you delete it. Your push token and anonymous user ID are
  kept until you use **Delete my alert data**; a push token is also deleted
  when Expo tells us it no longer works. Data of a phone our server has not
  seen for 13 months is deleted.
- **How to delete it:** **Settings › Delete my alert data** deletes your
  price alerts, your push tokens and your anonymous user from our server. Your
  price alerts stay on your phone; if you save one again, the app creates a
  new anonymous user. **Deleting the app does not delete this data from our
  server**, so use Delete my alert data first. Deleting your alert data does
  not cancel a subscription: billing continues through the App Store until you
  cancel it there.
- *Legal basis: performing the service you asked for (contract).*

### Purchases
- Subscriptions are sold and billed by **Apple**
  through the App Store. Apple processes your payment under its own privacy
  policy. We never receive your name, email or payment details.
- We use **RevenueCat, Inc.** (USA) to check whether you have Pro and to
  restore purchases. RevenueCat receives your App Store purchase receipts, the
  product bought, prices, dates, the store country and a random app user ID;
  once you save a price alert, that ID is your anonymous user ID. It does not
  receive your payment card details. For price alerts, our server asks
  RevenueCat whether you have Pro (see above). *Legal basis: contract.*
- RevenueCat keeps your purchase history under its own retention rules.
  **Delete my alert data** does not delete it, because the store keeps billing
  your subscription until you cancel it. To have it deleted, email
  support@holopeek.com. Because it has no name or email behind it, we will ask
  you for details from your App Store receipt to find it, then ask RevenueCat
  to delete it.
- Apple gives us sales reports (such as the number of sales and the country)
  that do not identify you.

### Usage events
- The App Store version of the app records no usage events and sends none to
  us or to any analytics service.

### Information Apple shares with us
- If you have turned on **Share with App Developers** in
  **iOS Settings › Privacy & Security › Analytics & Improvements**, Apple may
  share crash reports and app usage statistics with us. Apple controls this,
  and the reports do not identify you to us. You can turn it off at any time.

## 3. What we do not do

- No sign-in, accounts with your details, or profiles. Price alerts use an
  anonymous user with no name, email or password (section 2).
- No advertising, no ad networks, and no tracking across other companies' apps
  or websites. We do not use the advertising identifier.
- No selling or "sharing" of personal information (as California law uses
  those words).
- No location, contacts, microphone or health data.
- No uploading of your photos.

## 4. Planned features and how they would change this policy

We will update this policy **before** any of the following ships, and the app
will tell you about any change that matters.

- **Accounts, backup or sync** of your collection.
- **Usage analytics** sent off your phone.
- **The Android app.**

## 5. Who receives information

| Recipient | What | Why | Today? |
|---|---|---|---|
| Apple | Payment and App Store account data (handled by Apple, not us); optional crash and usage reports; push token and notification text | Sales, billing, app distribution; delivering notifications | Yes |
| TCGdex | Card identifier, IP address, basic technical request data | Supplies prices and card images | Yes |
| Supabase (US) | Anonymous user ID, push token, price alerts | Hosting our server and its sign-in | Yes, once you save a price alert |
| Expo (US) | Push token, notification text | Delivering price-alert notifications | Yes, once you save a price alert and allow notifications |
| RevenueCat (US) | Purchase receipts, random app user ID (your anonymous user ID once you save a price alert) | Subscription management; telling our server whether you have Pro | Yes |

We may also disclose information if the law requires it, to protect rights or
safety, or as part of a sale or transfer of the app. In that last case, this
policy, or one at least as protective, will continue to apply.

## 6. International transfers

Requests to TCGdex go to TCGdex's servers, wherever TCGdex hosts them.

If you save a price alert, your anonymous user ID, push token and price alerts
are stored on our server in the United States (Supabase), and the push token
and notification text pass through Expo in the United States. For people in
the EEA, UK and Switzerland, these transfers rely on the Standard Contractual Clauses in each provider's
data processing agreement (Supabase, Expo and RevenueCat). We, the developer,
are based in Israel.

## 7. How long we keep data

- **On your phone:** your collection, settings and stored prices stay until
  you remove them or delete the app.
- **Photos:** camera photos are discarded after each scan. Photos you pick
  leave a temporary copy in the app's cache on your phone until iOS clears it.
- **Our server:** price alerts until you delete them in the app; your push
  token and anonymous user ID until you use **Delete my alert data** (a push
  token also goes when Expo reports it no longer works); everything of a phone
  not seen for 13 months. Deleted data leaves our backups
  within 7 days. Server request logs: up to 7 days.
  See "Price alerts and notifications" in section 2.

## 8. Deleting your data

- **One card:** open the card and choose **Remove from collection**, or swipe
  it left in your collection list.
- **Everything:** delete the app (touch and hold its icon › **Remove App** ›
  **Delete App**). This erases your collection, settings and stored prices
  from the phone. Copies in an existing iCloud or computer backup remain until
  that backup is replaced or deleted.
- **Your price alert data on our server:** **Settings › Delete my alert
  data** deletes your price alerts, push tokens and anonymous user from our
  server. Deleting the app does **not** do this, so use it first.
- **Subscriptions:** deleting the app, or your alert data, **does not cancel**
  a subscription. See "Managing your subscription" in our Terms of Use.

## 9. Your rights

Unless you save a price alert, we hold no personal data about you on any
server, and your data is on your phone and under your control. If you save a
price alert, our server holds your anonymous user ID, push token and price
alerts. You can see your price alerts in the app and delete all of it at
**Settings › Delete my alert data**. Because that data has no name or email
behind it, we may not be able to find it from an email request alone; the
in-app control is the reliable way. You can still contact us at any time.

**EEA, UK and Switzerland (GDPR).** You have the right to access, correct,
delete or export your personal data, to restrict or object to our use of it,
and to withdraw consent at any time. You can also complain to your local data
protection authority.

**Legal bases we rely on:** performing our contract with you (running the app
and the features you use); our legitimate interests (keeping the app secure
and working); your consent (for
camera access and notifications, which iOS asks for); and legal obligations.

**California (CCPA/CPRA) and other U.S. states.** You have the right to know
what personal information we collect, to delete it, to correct it, and to opt
out of its sale or sharing. We do not sell or share personal information, and
we do not use sensitive personal information. We will not treat you
differently for using these rights.

**How to make a request:** email support@holopeek.com. We reply within 30 days,
or sooner where the law requires. We may need to confirm that a request is
really yours.

## 10. Children

Holopeek is **not directed to children under 13** (or the higher age that
applies where you live), and we do not knowingly collect personal information
from them. The only personal information the app sends to us is for price
alerts: an anonymous user ID, a push token and the price alerts themselves
(section 2). None of it includes a name, contact details or age, so our
server cannot tell who is a child.

Where the law requires it (for example in Texas), the app asks Apple whether
you are an adult, using Apple's Declared Age Range feature. The answer is used
on your phone only, to decide whether a parent or guardian must approve a
significant change to the app. It is not stored and is never sent to us or
anyone else. Apple handles parental consent for downloads and purchases.

If you are a parent or guardian and believe your child has given us personal
information, email support@holopeek.com. We will delete it. To remove everything
the app stores on a child's phone, delete the app.

## 11. Security

Your data stays on your phone, protected by iOS. That includes the device
passcode and encryption. All network requests use encrypted HTTPS.
Price-alert data on our server is encrypted in transit and at rest. The app
can reach it only through functions that act on its own anonymous user, so no
one can read or change another phone's price alerts; row-level security is on
for every table.

## 12. Changes to this policy

We will post any change here and update the effective date. If a change
affects how your data is used, for example when a planned feature in section
4 launches, we will tell you in the app before it takes effect.

## 13. Contact

Nitzan Aroesty · support@holopeek.com · Basel 9, Tel Aviv 6228508, Israel · https://holopeek.com
