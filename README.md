# Unfold and Run

An expression taken apart into the function machine it stands for, then numbers run through that machine into a T-table, and the table's points put on a graph.

Open: https://jserra3.github.io/unfold-and-run/

Set a problem with a link: https://jserra3.github.io/unfold-and-run/?expr=2x%2B8&x=-2,-1,0,1,2

Solve an equation: https://jserra3.github.io/unfold-and-run/?expr=2x%2B8%3D20 — the x side unfolds into the machine, then 20 goes into OUTPUT and the machine works backwards to x.

Click things: the card to type a new expression (y = …, f(x) = …, or an equation), INPUT to put a number in, OUTPUT to put an output in and work backwards. Working back through a square or an absolute value gives both answers (±), and every answer goes in the table.

Keys: → / Space / Page Down = next · ← / Page Up = back · P = play · type a number to run it · O = an output to work back · E = change the expression · G = graph the table (and back) · M = settings · F = full screen

On the graph, each Next plots the next row of the table: the point starts on the x-axis at x and rises (or sinks) straight to y. Turn on "draw the line" in settings (or add `&line=1` to the link) and one more Next draws the line through the points: solid across the x's the table covers, lighter beyond them, where none of the points say how it behaves.

Built from the elm-obs Unfold and Run It apps by `tools/build-unfold-run.mjs`.
