---
title: PIN and Recovery
description: Changing your PIN, how long a device stays unlocked, and what happens if you forget it.
tags:
  - account
  - pin
  - recovery
---


# PIN and Recovery

This page covers the operational side of the PIN. For the concept and
threat model, see [PIN and Privacy](../safety/pin-and-privacy.md).

## Changing your PIN

From **You > Privacy & Security > PIN & encryption**:

1. Enter the **current PIN**.
2. Enter the **new PIN** twice.
3. Tap **Change PIN**.

Your saved data is unlocked with the old PIN and locked again with the
new one, on your device. It takes a moment if you have a lot of chat
history, so leave the screen open.

If the new PIN does not match its confirmation, nothing changes. If
the current PIN you entered is wrong, the change refuses. If the
connection drops halfway, nothing is lost: come back and finish the
change with the same new PIN.

Before anything is re-locked, the app checks that your current PIN can
still open everything you have saved. If something cannot be opened,
the change stops and points you at **Repair locked data** in the same
panel. See [Repair locked data](./settings.md#repair-locked-data).

## What a PIN may contain

A new PIN is **6 to 12 digits**, digits only. The field drops anything
else while you type. The rule holds everywhere a PIN is chosen: at
onboarding, in the panel above, and in the prompt described next.

A PIN chosen before this rule can contain letters and still unlocks
normally. A phone number pad cannot type those, so every unlock field
carries a **My PIN contains letters** link that switches the keyboard.

When you unlock by typing such a PIN, you are asked once to pick a
numeric one. Nothing is deleted: your locked data is opened with the
old PIN and locked again with the new one, and **Remind me next time**
puts the question off until the next unlock.

## Staying unlocked

Once you unlock with your PIN, that device stays unlocked so you are
not asked again on every screen.

- It lasts up to **7 days** in a browser, up to **2 days** in the
  companion app.
- It is per device and per browser. A new device or a new browser asks
  for the PIN again.
- Signing out from the MISTRIX menu locks that device again.
- Clearing browser data does the same.

If you want a fresh PIN prompt for any reason, sign out and back in.

## What happens if you forget your PIN

Your encrypted data is **unrecoverable**.

Specifically, you lose:

- Your safe word.
- All fetish interest levels, learned ones included.
- The hard limits list.
- The full inventory (toys, clothing, accessories) and notes.
- Your routines and any open tasks.
- The long-term goal and standing rules you set for her.
- Every chat message ever sent or received, with every Domina.

You keep:

- The account itself.
- Your profile details: your name, gender, biological sex and age.
- Your tier and your Charm balance.
- Your level and XP.
- Your sessions, their text and their summaries.
- Generated images, AI Studio images and the photos you sent her.
- Your personal Domina(s), name and personality.
- What she remembers about you.

The rest of the account is still there and still works, but the locked
part is gone.

## Forgot-PIN flow

Nobody can hand the PIN back to you. We cannot read what it locks, so
we cannot unlock it for you either. What you can do is throw the
locked data away and start that part over:

1. On the PIN screen, under **Forgot your PIN?**, tap **Reset account
   & delete encrypted data**. Inside the app the same thing sits at the
   bottom of **You > Privacy & Security > PIN & encryption**, as **Reset
   PIN (erases encrypted data)**.
2. Read the list of what goes. On the PIN screen you confirm by typing
   `DELETE`; inside the app you tap **Confirm**.
3. Everything the old PIN locked is deleted and the PIN is switched
   off.
4. Set a new PIN as if you were onboarding again.
5. Re-enter your fetishes, hard limits, inventory, safe word, and your
   goal and standing rules. Your name, gender, biological sex and age
   are still there.

This is destructive but does not delete your account. Sessions,
images, her memories and billing carry over.

## Switching devices safely

If you are about to sign in on a brand-new device:

- Make sure you remember the PIN.
- The new device will prompt for it on first unlock.
- Once unlocked, that device stays unlocked for the usual 7 days, or 2
  in the companion app.

There is no "trust this device" prompt - the PIN is the trust signal.
