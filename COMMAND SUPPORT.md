-----
Supported commands:

If the command has an *, see description of the command
for an explanation.

Commands with a / are in progress.
Commands with an @ are future commands to be intergrated.

G1 * /
G4 @
G28 @
G92 @

M20 (used to show a list of gcode programs in a file) will be
replaced by manually pressing a "list gcode programs" button on
the on-board UI.

-----
[G1]

This is the usual format of G1 and G0 commands:

G1 Xnnn Ynnn Znnn Ennn Fnnn Snnn

At least one parameter must be present.

X = X axis

Y = Y axis

Z = Z axis

E = The amount to extrude between the starting point and ending point

F = The feedrate per minute of the move between the starting point
and ending point. 

S = For endstops.

The feedrate cannot be comtrolled easily so I thought of controlling with this method:

Slower movement = more depositing of plastic.

Faster movement = less depositing of plastic.

-----

[G4]

This is the usual format of G4 commands:

G4 Snnn
or
G4 Pnnn

Snnn = Wait x amount of time in seconds.

Pnnn = Wait x amount of time in milliseconds.

-----

[G28]

This is the usual format of G28 commands:

G28 X Y Z

This will move the print head to home.

If you add parameters, they will be ignored.

-----

[G92]

Used to reset the position of axes.

This is the usual format of G92 commands:

G92 Xnnn Ynnn Znnn Ennn

The parameters specify the new position you would like
to reset the axes to.

If parameters are not specified, the program will reset all
axes to 0.

-----
