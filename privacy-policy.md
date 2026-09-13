# AlgoScope Privacy Policy

Effective date: 13 September 2026

AlgoScope is a study app for data structures and algorithms. This page explains what the app
does with data, in plain language. The short version: there is no account, the app works
offline, there are no ads, and the only data that can leave your device is anonymous usage
analytics, which you can turn off in Settings.

## What the app stores on your device

- **One preference**: whether analytics is on or off.
- Nothing else. Lesson content is bundled with the app. Appearance and reduced motion follow
  your system settings. Values you type into a lesson, such as your own input array or a search
  term, are used on screen and are not saved when you leave the lesson. No progress is stored,
  so uninstalling the app removes everything.

## What the app can send: usage analytics

AlgoScope can send anonymous usage events to Google Firebase Analytics so that we can see which
topics people want, which lessons hold attention, and whether the prediction questions teach.
This is on by default and the **Share anonymous usage** switch in **Settings** turns it off.

When analytics is on, the app sends events such as:

- which lesson was opened and whether it was completed, and how it was reached (search, filter,
  link);
- whether a prediction was answered correctly, for each lesson;
- which settings were toggled, such as predict mode;
- which lesson tab was viewed and which code language was copied;
- whether a custom input was accepted or rejected (the input itself is never sent);
- that a search happened, with the length of the search term in a coarse bucket and the number of
  results (the search text itself is never sent);
- which unbuilt topic was tapped, so we know what to build next;
- that a lesson failed to load, with the lesson id and an error category.

Every value in these events is an identifier or a fixed category. The app never sends free text.

Alongside the events, Firebase attaches the standard information it attaches for every app: a
random per-install identifier that Firebase generates, the app version, the device model and
operating system version, language, and an approximate country. Google's servers receive your
device's IP address as part of transmitting this, as any internet service does; we do not see IP
addresses, and the reports available to us show location at country level at most.

**What is never collected**: your name, email address, contacts, photos, precise location,
anything you type, or an advertising identifier. AlgoScope does not request the advertising ID on
Android and does not include the identifier module on iOS. There are no accounts, so nothing is
linked to a person.

## Turning analytics off

Open **Settings** in the app and switch off **Share anonymous usage**. From that moment nothing is
sent, and the app asks Firebase to delete the per-install identifier it held on the device, so a
later switch-on starts with a fresh one. Every feature of the app works the same with analytics
off.

Events sent before you switched off remain in Google's aggregated reports. Per-device event data
is retained by Google Analytics for the shortest retention period the service offers, which is
currently two months, after which only aggregate figures remain.

## Who receives the data

Only Google LLC, as the operator of Firebase Analytics, which processes the data on our behalf.
How Google handles it is described in the
[Google Privacy Policy](https://policies.google.com/privacy) and the
[Firebase data processing terms](https://firebase.google.com/terms/data-processing-terms).
Data may be processed on Google servers outside your country, including in the United States.

We do not sell data, do not share it with anyone else, and do not use it for advertising. There
are no ad networks in the app.

## Children

AlgoScope is intended for students aged 13 and over. We do not knowingly collect data from
children under 13. If you believe a child has used the app with analytics on and you want the
identifier removed, switch analytics off in Settings on that device; that deletes it.

## Security

Analytics events travel to Google over encrypted connections. Because the app holds no account,
password or personal data, there is nothing on our side that could expose you if it were
breached.

## Your rights

Depending on where you live, you may have rights to access, correct, delete or object to the
processing of personal data. Because the analytics data is not linked to you, we cannot look up
or delete records for a specific person; the switch in Settings is the deletion mechanism and it
acts immediately on the identifier that ties events together. For anything else, contact us at
the address below and we will help within 30 days.

## Changes to this policy

If the app starts collecting something new, for example crash reports, this page will be
updated before that version ships, with a new effective date. The current version is always at
this address.

## Contact

contact@nublabs.com
