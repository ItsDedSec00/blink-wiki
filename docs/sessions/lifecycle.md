---
title: Lifecycle of a Session
description: Every state a session passes through, from proposal to summary.
tags:
  - sessions
  - lifecycle
---


# Lifecycle of a Session

A MISTRIX session moves through a fixed set of states. Knowing the states
helps when something doesn't behave the way you expect.

## States

| State | What is happening |
|---|---|
| **Proposed** | The Domina sent a session-proposal sheet. You have not confirmed yet. |
| **Active** | You confirmed. Cards are flowing. The safe-word button is visible. |
| **Completed** | You reached the outro and confirmed the end. She passes her verdict, XP is awarded, the summary is stored. |
| **Safeworded** | You tapped the safe word. Session ends immediately. No XP. Her mood resets to neutral. |
| **Closed for inactivity** | You left the session sitting for more than about two hours. It is closed for you, and the next time you open the chat a **Session closed** notice tells you how long it had been idle. No XP and no summary. |

## The flow

```
Idle chat
   |
   v
Proposed -------> Active -----+-----> Completed
   |                          |
   |                          +-----> Safeworded
   |                          |
   |                          +-----> Closed for inactivity
   v
Declined / Replanned
```

A session can only be in one state at a time. There are no half-states.

A scene cannot be paused for hours and picked up mid-beat, which is why
a cold session is closed rather than resumed. Start a fresh one
whenever you are ready.

## Replanning

If you decline a proposal, the Domina can offer a new one in the same
chat. There is no penalty. Tell her what you wanted different and she
adjusts:

- "Shorter, around 15 minutes."
- "Skip impact tonight."
- "I want chastity to be the centre."

She drafts a new proposal sheet. Confirm or decline again.

## Mid-session adjustments

Inside an Active session you can:

- Send a message between task cards - she reads it and the next card
  reflects it.
- Send a photo (see [Photo Uploads](./photo-uploads.md)).
- Pause - tell her "hold for a few minutes" and she waits until you
  come back and say so. Keep it short. Leave it for hours and the
  session closes.

Things you cannot do mid-session:

- Change the active Domina. The scene is hers, and switching part-way
  leaves it stranded.
- Edit hard limits or interests and have them affect the in-progress
  session. The plan is fixed at confirmation time.
- Stack two active sessions. One at a time, always.

## What is stored

After a session ends in any state, you keep:

- The title, the difficulty, and the items it called for.
- The session text (intro, tasks, outro).
- Generated images.
- Your rating.
- Her verdict on the session, and the line she left with it.
- The Domina-authored summary.

All of this is visible in your **Session History**, and nowhere else.
