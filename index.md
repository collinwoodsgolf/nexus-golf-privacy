# Privacy Policy

**NEXUS Golf Club** (iOS app, `com.nexusclubny.golf`)

Last updated: 4 August 2026

This policy explains what the NEXUS Golf Club app does with your information. It
covers the app only — the club's website and the Your Golf Booking site have
their own terms.

## The short version

The app is a front end for your existing Your Golf Booking membership. It does
not have its own user database. It collects no analytics, contains no
advertising or tracking SDKs, and does not sell or share your information with
anyone.

## What we collect, and why

**Your sign-in details.** When you sign in, your Your Golf Booking username or
email and your password are sent to Your Golf Booking (`api.yourgolfbooking.com`)
to authenticate you. Your password is not stored on your device and is not sent
anywhere else. The session token that comes back is kept in the iOS Keychain via
Apple's secure storage and is used only to prove who you are on later requests.

**Your membership profile.** Your name, email address, member number and
membership tier are read from Your Golf Booking so the app can greet you, show
your access card, and display the number the door keypad accepts. This
information is read each session and is not copied to any server we operate.

**Your reservations.** Bay bookings are read from Your Golf Booking to populate
the Bookings screen and to schedule reminders. Booking access PINs are stored on
your device so you can find them without a network connection. The app only
reads from Your Golf Booking — it cannot alter or cancel a reservation.

**Payment information.** Card details are collected by Stripe's own payment
sheet, which runs on your device and sends the card directly to Stripe. The app
never sees, stores, or transmits your card number. Our payments endpoint
(`nexus-golf-app.vercel.app`) receives only your Your Golf Booking session token
and asks Stripe for the short-lived keys the payment sheet needs; it does not
receive card data. Stripe's handling of your card is governed by
[Stripe's privacy policy](https://stripe.com/privacy).

**Camera.** The app requests camera access only if you choose to scan a payment
card rather than type the number. No photograph is taken, saved, or transmitted.
You can decline this permission and enter card numbers by hand.

**Notifications.** Reservation reminders are scheduled locally on your device
from bookings the app has already fetched. The app does not register a push
token, and no notification content leaves your phone.

## What we do not do

- No analytics, crash reporting, or usage-tracking services are built into the app.
- No advertising identifiers are collected, and no data is used for advertising.
- Your information is not sold, rented, or shared with third parties for their
  own purposes.
- No location data is collected.
- No contacts, photos, or health data are accessed.

## Who processes your data

Three services, each acting on your behalf:

| Service | Role |
| --- | --- |
| Your Golf Booking | Membership records, authentication, reservations |
| Stripe | Payment processing and stored cards |
| Vercel | Hosting for the app's small payments endpoint |

## Data stored on your device

Your session token (in the iOS Keychain) and your booking access PINs (in app
storage). Both are removed when you sign out or delete the app.

## How long we keep things

We operate no user database, so there is nothing for us to retain. Your
membership record lives with Your Golf Booking and your payment record with
Stripe, each subject to that company's own retention practices.

## Your choices

- **Sign out** clears your session and stored PINs from the device.
- **Delete the app** removes everything the app has stored locally.
- **Remove a saved card** from the Billing screen at any time.
- **To correct or delete your membership record**, contact the club — that data
  is held in Your Golf Booking, not by the app.

## Children

The app is intended for club members and is not directed at children under 13.
We do not knowingly collect information from children.

## Changes

If this policy changes materially, the updated version will be posted here with
a new date.

## Contact

Questions about this policy: **info@collinwoodsgolf.com**
