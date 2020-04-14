# Pad-mapper

The idea is to map buttons and axies from dualshock controller (or any other pad) to keys on keyboard. Pressing button on pad will emit a keystroke on the keyboard that can be used in games. Examples:
  * Silent Hill 3 did not recognize some of the buttons on the PS3 pad as separate and also does not allow to press multiple keys for single action (e.g. pressing L1 + R1 to zoom)

## ToDo:
* Acquire buttons presses from pad
* Bind pad keys and axes to the keyboard strokes
* Store and load key bindings from file
* Emit keystrokes when user press equivalent set on pad