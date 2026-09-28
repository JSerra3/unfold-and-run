# Unfold and Run

An expression taken apart into the function machine it stands for, then numbers run through that machine into a T-table, and the table's points put on a graph.

Open: https://jserra3.github.io/unfold-and-run/

Set a problem with a link: https://jserra3.github.io/unfold-and-run/?expr=2x%2B8&x=-2,-1,0,1,2

Keys: → / Space / Page Down = next · ← / Page Up = back · P = play · type a number to run it · G = graph the table (and back) · M = settings · F = full screen

On the graph, each Next plots the next row of the table: the point starts on the x-axis at x and rises (or sinks) straight to y. Turn on "draw the line" in settings (or add `&line=1` to the link) and one more Next draws the line through the points.

Built from the elm-obs Unfold and Run It apps by `tools/build-unfold-run.mjs`.
