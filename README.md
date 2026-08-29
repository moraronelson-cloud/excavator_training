# Excavator Trainer V4.1 — Corrected ISO Controls

This is a cumulative replacement for V4.

## Fix
The joystick labels in V4 described the ISO pattern correctly, but three visual motion signs in the simulator geometry were reversed.

Corrected ISO behavior:
- LEFT joystick forward / screen up = STICK OUT
- LEFT joystick back / screen down = STICK IN
- LEFT joystick left/right = SWING LEFT/RIGHT
- RIGHT joystick forward / screen up = BOOM DOWN
- RIGHT joystick back / screen down = BOOM UP
- RIGHT joystick left = BUCKET CURL
- RIGHT joystick right = BUCKET DUMP

A LIVE INPUT readout has also been added so the learner can see the exact command the simulator is interpreting while moving either joystick.

All V4 micro-task/full-cycle learning logic is retained.

Training aid only. Verify the actual machine's cab control-pattern decal/manual before real-machine practice.
