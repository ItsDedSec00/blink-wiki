---
title: PIN and Privacy
description: How the MISTRIX PIN works, what it encrypts, and what happens if you forget it.
tags:
  - safety
  - pin
  - privacy
  - encryption
---


# PIN and Privacy

MISTRIX encrypts the most sensitive parts of your account with a key
derived from a PIN that **only you know**. Your PIN never leaves your
device. This page explains what the PIN protects, what it does not, and
the cost of losing it.

## What the PIN protects

Encrypted with your PIN:

- All your fetish interests and levels.
- Your hard limits list.
- Your full inventory (toys, clothing, accessories) including notes.
- Your routines and your open tasks.
- Your safe word.
- Every chat message you have ever sent or received.

What is **not** encrypted:

- Your username, your email address and your tier.
- Your profile details: the name she calls you, gender, biological sex
  and age. She reads these to write for you, so they sit outside the
  PIN.
- Your level and XP.
- Session details (title, difficulty, time, status).
- Your generated images.
- Your AI Studio prompts.
- Your Domina herself: her name, her style, her personality settings,
  and everything she remembers about you.
- Your billing. You enter your card on the payment page; MISTRIX never
  holds the card details.

The split follows one line: what says something about your tastes is
locked behind your PIN, and what the app has to read in order to run is
not.

## How the encryption works

- Your PIN is turned into an encryption key on your device, using
  **PBKDF2**. That key encrypts the protected data with **AES-GCM**.
- Your PIN itself is never sent anywhere and never stored anywhere.
- Nothing protected ever leaves your device readable. We only ever hold
  the scrambled version, and only your PIN opens it.

The result: nobody at MISTRIX can read your fetishes, your limits, your
inventory or your chat history. Not an admin, not support, not anyone
who got hold of a copy of our data.

## When you'll be asked for the PIN

- On a new browser or device when you first sign in.
- After you clear your browser data.
- After you sign out, on that device.
- Every so often on a device you already use, so a device you stop
  using does not stay unlocked forever.

You do not have to type it every time you open the app on a device you
have already unlocked.

## What happens if you forget the PIN

The protected data is unrecoverable.

- Gone: your chat history with every Domina, your fetish interests,
  your hard limits, your inventory, your safe word, your routines and
  your open tasks.
- Kept: your profile details, your Domina and everything she remembers
  about you, your images, your sessions, your level and XP, your tier
  and billing.
- Support cannot bring the rest back. The PIN is not stored anywhere.

Your account is still usable and your Domina is still there. The
protected parts start empty. You can re-enter everything and set a new
PIN.

## When you change your PIN

- You will be asked for the **old PIN** to authorise the change.
- Everything protected is re-encrypted with the key from your new PIN,
  on your device.
- You will see a locked loading screen while that runs. Let it finish.
- If it is interrupted, your old PIN still works and nothing is lost.
  Some chats and settings will look empty until the change is done, and
  the app offers to finish it the next time you unlock.

## Is the PIN the same as my password?

No. Your password gets you into your account. Your PIN unlocks the
protected data once you are in. Resetting one does not reset the other.

If you forgot the password, use **Forgot password?** on the sign-in
screen. We send a reset link to your email address.

If you forgot the PIN, the protected data is gone; the rest of the
account is fine.
