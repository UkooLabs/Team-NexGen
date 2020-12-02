# Input Devices

## Button ID's

DPAD_UP
DPAD_DOWN
DPAD_LEFT
DPAD_RIGHT
START
BACK
L_THUMB
R_THUMB
L_SHOULDER
R_SHOULDER
A
B
X
Y
BLACK
WHITE
L_TRIGGER
R_TRIGGER
L_STICK_X
L_STICK_Y
R_STICK_X
R_STICK_Y

## Button States

0 = Not Pressed
1 = First Press
2 = Continual Press
3 = Last Press
getComtrollerButtonState(port, buttonId)

if port is 0 finds first connected controller otherwise port is 1 - 4
