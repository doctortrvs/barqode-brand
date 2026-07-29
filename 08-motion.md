# 08 — Motion

> This document defines the principles that govern motion throughout the Barqode ecosystem.
>
> Motion exists to communicate action performed.
>
> It should confirm change, explain direction and make the interface feel immediate, organised and dependable.

---

# Philosophy

Motion is not decoration.

It is communication.

Every movement should explain:

- What just happened.
- Where something moved.
- What changed.
- Whether an action was completed.
- What the operator should expect next.

Movement should never exist purely because it looks impressive.

If an animation does not communicate or explain something, it should not exist.

---

# Action Performed

Motion should confirm that the operator's intended action has taken place.

When an operator clicks, opens, closes, submits, moves or completes something, the interface should respond immediately.

The response should be:

- Clear.
- Subtle.
- Deliberate.
- Fast.
- Easy to understand.

Motion should never leave the operator wondering whether the system received their input.

---

# Motion Hierarchy

Motion should follow the importance of the action.

## Immediate feedback

Used for:

- Button presses.
- Selections.
- Toggles.
- Checkbox changes.
- Row actions.
- Status changes.

These responses should happen almost instantly.

---

## Directional movement

Used for:

- Opening records.
- Closing records.
- Moving forward.
- Moving backward.
- Opening drawers.
- Navigating between related views.

Directional motion should help the operator understand spatial relationships.

---

## Progress

Used for:

- Uploads.
- Imports.
- Exports.
- Synchronisation.
- Batch operations.
- Long-running tasks.

Progress motion should explain how much work has been completed and how much remains.

---

## Attention

Used only when something genuinely requires notice.

Examples include:

- New notifications.
- Failed actions.
- Blocking errors.
- Critical operational changes.

Attention should come from importance, not constant movement.

---

# Immediate and Deliberate

Barqode should feel immediate.

Motion should never make the interface feel slower than it is.

Animations should be rapid enough to preserve momentum while deliberate enough to communicate what occurred.

The operator should feel that the system responds the moment they act.

If motion causes lag, hesitation or friction, it should be reduced or removed.

Performance always takes priority over animation.

---

# Direction

Motion should communicate direction wherever direction matters.

Opening a deeper view should move forward.

Returning should move backward.

Drawers should enter from the side they belong to and return in the opposite direction when closed.

This should feel similar to moving through organised papers or records.

The movement should reinforce the relationship between screens without becoming performative.

Direction should remain consistent throughout the product.

---

# Navigation

Navigation transitions may use short, rapid slides to indicate forward and backward movement.

Examples:

- Opening an order moves forward.
- Returning to the order list moves backward.
- Opening a side panel moves inward from its anchored edge.
- Closing it returns toward that edge.

Transitions should be nearly instant.

The purpose is orientation, not spectacle.

When an instant transition communicates more clearly or performs better, use the instant transition.

---

# Buttons and Controls

Interactive controls should respond visibly to input.

## Hover

Hover states should change colour very slightly.

The change should be strong enough to confirm that the control is interactive, but restrained enough to avoid visual noise.

Buttons should not:

- Jump.
- Lift dramatically.
- Expand unnecessarily.
- Bounce.
- Create distracting shadows.

---

## Pressed

A clicked or pressed control should animate subtly to confirm the action.

The response may include:

- A slight tonal change.
- A minimal scale change.
- A brief compression.
- A state transition.

The effect should be soft and almost unnoticeable while still confirming:

> The system received the action.

---

# Notifications

Notifications should pop into view.

The entrance should be immediate and recognisable rather than theatrical.

A notification may:

- Appear directly.
- Use a very short scale transition.
- Use a brief fade.
- Combine a small pop with a fast fade.

It should not bounce repeatedly, float around the screen or remain animated after appearing.

Once visible, it should become still.

---

# Loading and Progress

Progress bars are the preferred loading indicator.

They communicate movement toward completion more clearly than indefinite animation.

Where possible, progress should include:

- Percentage completed.
- Current stage.
- Items processed.
- Items remaining.
- Estimated time remaining.

Operators should understand whether a process is progressing, paused or blocked.

Indefinite spinners should be avoided where measurable progress exists.

A spinner may only be used for brief operations where progress cannot reasonably be calculated.

---

# Continuous Motion

Continuous animation should be extremely rare.

Movement that repeats indefinitely creates distraction and visual fatigue.

Barqode may use continuous motion only when it represents genuine live activity, such as:

- Synchronisation in progress.
- A live data connection.
- An active upload.
- A currently running process.

The motion should stop when the activity stops.

The interface should never animate simply to appear alive.

---

# Attention and Pulse

Pulsing should be used only when an operator must notice a new or unresolved state.

Any pulse should be:

- Small.
- Infrequent.
- Temporary.
- Easy to disable.
- Limited to one or very few elements.

A pulse should stop once the operator has acknowledged or addressed the item.

Repeated movement should never become background noise.

---

# Seamlessness

Motion should make the system feel organised.

Elements should move in ways that feel connected to their origin and destination.

Nothing should appear to jump unpredictably.

Nothing should move without cause.

Transitions should feel soft, controlled and structurally logical.

The objective is not to make the product feel animated.

The objective is to make the product feel coherent.

---

# Reduced Motion

Barqode must respect the user's operating-system reduced-motion preference.

When reduced motion is enabled:

- Sliding should become a fade or instant transition.
- Scaling effects should be removed.
- Pulsing should stop.
- Repeated movement should stop.
- Progress should remain understandable without animation.

Reducing motion must never reduce clarity.

The action, state and result should remain fully understandable.

---

# Performance

Motion must never compromise operational performance.

Animations should use efficient properties and avoid unnecessary rendering work.

They should remain smooth on:

- Older computers.
- Low-powered devices.
- Poor displays.
- Busy warehouse workstations.
- High-density operational screens.

If an animation causes delay, dropped frames or input lag, remove it.

A fast interface is more important than a polished transition.

---

# Consistency

The same action should produce the same type of movement.

Forward navigation should always move forward.

Back navigation should always move backward.

Drawers should always emerge from their anchored side.

Buttons should always provide immediate feedback.

Progress should always move toward completion.

Consistency helps operators understand the system without conscious thought.

---

# Final Principle

A successful animation is one where the operator immediately understands that the action they intended to perform has been performed.

Motion should confirm action, explain direction and communicate progress.

It should be immediate and deliberate.

When movement adds clarity, use it.

When it adds delay, noise or performance cost, remove it.
