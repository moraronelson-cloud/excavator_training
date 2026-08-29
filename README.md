# Excavator Trainer V6.1 — Direction Fix

Cumulative replacement for V6.

## Fixed
The visible joystick animation was horizontally mirrored:
- dragging RIGHT made the joystick appear to lean LEFT
- dragging LEFT made the joystick appear to lean RIGHT

This has been corrected on BOTH joysticks.

Now:
- slide right → joystick visibly leans right
- slide left → joystick visibly leans left
- slide forward → joystick leans toward windshield
- slide back → joystick leans toward seat

The interpreted ISO command mapping is unchanged.

A cache version bump is included so the new build replaces the previous service-worker cache.

Training aid only. Verify the actual excavator control-pattern decal/manual before supervised real-machine practice.
