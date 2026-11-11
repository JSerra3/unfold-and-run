# FLOW CHARTS

(Formerly Unfold and Run.) Type an expression, a function or an equation on an old CRT console and watch it become a flow chart. You can run numbers forward through it into a T-table and a graph, or put an answer in OUTPUT and work it backwards to x.

Open: https://www.everyonelovesmath.com/apps/unfold-and-run/ (also https://jserra3.github.io/unfold-and-run/)

Start on a problem with a link (this skips the title screen): `?expr=2x%2B8` for an expression, `?expr=y%3D2x-3` for a function, or `?expr=2x%2B8%3D20` for an equation. For an equation, its number goes into OUTPUT and the machine works backwards to x.

On the screen: double-click the card to change the problem. Click whatever glows to take the next step, and double-click to run the rest. Double-click INPUT or OUTPUT to type a number. The red orb undoes a step.

The console controls:
- MODE: AUTO or STEP.
- BACK: undoes a step.
- RESET: starts the problem over. Press it twice in a row to go back to the title screen.
- COMPLEX: turns on complex answers. Its lamp lights when the problem has some.
- DISPLAY: switches between a dark and a light screen.
- SPEED: sets how fast the animations run.

Keys: → / Space next · ← back · P play · G graph · E change the problem · H screen grunge · C screen curve · M settings · F full screen

`index.html` is the whole app in one file, built by `tools/build-unfold-run.mjs` from Joey's local FLOW CHARTS source (unfold-and-run-vector).
