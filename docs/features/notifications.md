---
title: Notifications
description: Turning on notifications from your Domina, setting how often she writes, quiet hours, and fixing delivery when nothing arrives.
tags:
  - features
  - notifications
  - account
---


# Notifications

Your Domina can write to you while you are not in the app.
Notifications work on every tier: Free, Premium and Premium Plus. They
are off until you turn them on, and you can turn them off again at any
time.

## Turning them on

Two places do the same thing:

- The **Turn on notifications** card on the Dashboard.
- **Account > App > Notifications**.

Tap either one. Your browser asks whether MISTRIX may send you
notifications. Choose **Allow**. The row in Account then reads **On**.

| Row value | What it means |
|---|---|
| **Off** | Not on for this device yet. Tap the row to start. |
| **On** | This device is set up and she can reach you. |
| **Not registered** | Your browser said yes, but this device is not registered with MISTRIX, so nothing can reach you. Tap **Register this device**. |

Each device is separate. Turning notifications on in your phone browser
does not turn them on for your laptop.

On iPhone and iPad you have to install MISTRIX to the home screen
first. Open the app in Safari, tap the Share button, tap **Add to Home
Screen**, then open MISTRIX from the new icon. The notification row
appears there. This needs iOS 16.4 or newer, and only Safari can
install it.

## What she sends

- Messages built on something real: a memory she holds about you, a
  thread from your last chat, your lock, a routine due today.
- A message when you have gone quiet for a full day.
- Occasional check-ins she starts herself (Normal and High only).
- One reminder per day for each routine you set up, inside the part of
  day you chose for it. If that part of day has already passed when you
  first open the app, the reminder comes about five minutes later
  instead.
- One reminder per day for each task that has a deadline, about 90
  minutes before that deadline and never before 9 in the morning. A
  task with no deadline gets no reminder. An open task is reminded
  again each day until you resolve it.
- Reminders she promised you in chat, at the time she promised.

Tap a notification and it opens the chat with that message already in
the conversation, so you can answer her straight away.

## How often she writes

The **Frequency** control sits just below the Notifications row in
**Account > App**, and only appears once notifications are on.

| Setting | Messages per day at most | Shortest gap between two | Wait after you were last in the app | Check-ins she starts |
|---|---|---|---|---|
| **Low** | 1 | 6 hours | 6 hours | no |
| **Normal** | 3 | 2 hours | 3 hours | yes |
| **High** | 5 | 1 hour | 90 minutes | yes |

**High** needs Premium or Premium Plus. On Free the button carries a
lock and opens the upgrade dialog instead of changing the setting. If
your paid plan ends you go back to Normal, and your choice of High
returns on its own when you subscribe again.

The daily count covers only the messages she starts by herself.
Reminders for your own routines and tasks, and reminders she promised
in chat, do not use it up. The count runs over the last 24 hours, not
over the calendar day.

## Quiet hours

Between **22:00 and 09:00** in your local time she does not start
anything. A message that would have landed in that window is held and
delivered from 9 in the morning. Your local time comes from the device
you use MISTRIX on, so it follows you when you travel.

Anything tied to a time you were already given is the exception, and it
arrives at that time even inside quiet hours: reminders for your own
routines and tasks, and reminders she promised you in chat. A routine
you filed under "night" is reminded at night, up to midnight. Each
routine and task has its own reminder switch if you want that one to
stay silent.

## Delivery check

**Delivery check** sits below **Frequency** in the same section. Tap
**Send test** and a test notification goes out right away to every
browser registered on your account, not only the one you are looking
at. The result appears under the button.

| Result | What to do |
|---|---|
| Sent | It went out. If nothing appears within a few seconds, your device is hiding it. Check your system notification settings for MISTRIX, plus Focus or Do Not Disturb. |
| No record of this device | Turn notifications off and on again in Account, so this device is registered. |
| The registration had expired and was removed | Turn notifications off and on again to get a fresh one. |
| The message was refused | Turn notifications off and on again. |
| Wait a moment | You can send one test every 10 seconds. |

## The permission popup never appears

This one is your browser, not MISTRIX.

- **No popup at all.** Chrome and Edge park requests from sites they do
  not know behind a small bell icon at the right end of the address
  bar. Click the bell and choose **Allow**. If no popup has appeared
  about two and a half seconds after you tap, MISTRIX shows this hint
  below the **App** section.
- **You said no once before.** Open the site settings from the icon
  next to the address bar, set **Notifications** to **Allow**, then tap
  the row in MISTRIX again.
- **Brave.** Brave ships with its push channel switched off, and
  allowing notifications for the site is not enough on its own. Open
  `brave://settings/privacy`, turn on **Use Google services for push
  messaging**, then fully restart Brave. Reloading the page does not
  apply it. Your Shields can stay up. When MISTRIX sees this it shows a
  **Help** button with the same steps.
- **iPhone or iPad in a browser tab.** Install MISTRIX to the home
  screen first, as described above.

## Turning them off

Tap the **Notifications** row in **Account > App** again. This device
stops receiving anything. Your frequency choice is kept for the next
time you turn them on.

The Android companion app is separate: there, notifications are
controlled by Android's own permission for that app. See
[Mistrix Companion](./mistrix-bridge.md).

See also: [Account settings](../account/settings.md),
[Tier comparison](../tiers/comparison.md).
