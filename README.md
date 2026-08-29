# Excavator Trainer V7 — Realistic Hydraulics

Major visual and control-state rebuild.

## What changed
- More realistic LOVOL-style excavator rendering with:
  - detailed body/cab
  - tracks/rollers
  - hydraulic cylinders
  - shaded boom/stick/bucket
  - terrain, hills, soil pile, truck, shadows
- Persistent hydraulic state:
  - move boom -> release joystick -> boom stays there
  - curl bucket -> release -> bucket stays curled
  - move stick -> release -> stick stays where you left it
  - swing -> release -> upper structure holds its new position
- Joystick knobs spring back to center, while machine state remains.
- Continuous movement while a joystick is held.
- Soil can enter the bucket when curling in the dirt pile.
- Material can be dumped into the truck when positioned correctly.
- Live hydraulic status shows Flowing vs Holding.
- Reset machine and refill soil controls.
- Cache bumped to V7.

## ISO pattern used
LEFT:
- Forward = stick OUT
- Back = stick IN
- Left/right = swing

RIGHT:
- Forward = boom DOWN
- Back = boom UP
- Left = bucket CURL
- Right = bucket DUMP

Training aid only. Verify the real machine control pattern and use supervised real-machine practice.
