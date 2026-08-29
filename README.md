# Excavator Trainer V5 — Literal Joysticks

This version intentionally rebuilds the controls instead of patching the round touch pads.

## What changed
- Two visible, real-style joystick stalks with handles and console bases.
- User physically drags the joystick toward:
  - WINDSHIELD / FORWARD
  - SEAT / BACK
  - LEFT
  - RIGHT
- Each movement immediately states the command being interpreted.
- Eight-direction verification must be passed before digging unlocks.
- Visual excavator response is separated from the control interpretation so mapping errors are easier to detect.

## ISO mapping used
LEFT:
- Forward toward windshield = stick OUT
- Back toward seat = stick IN
- Left = swing LEFT
- Right = swing RIGHT

RIGHT:
- Forward toward windshield = boom DOWN
- Back toward seat = boom UP
- Left = bucket CURL
- Right = bucket DUMP

This matches the common ISO excavator pattern. Actual machine configuration still must be verified from its cab decal/operator manual before real-machine practice.
