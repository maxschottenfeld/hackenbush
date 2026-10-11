# Hackenbush Workbench

Draw Blue-Red Hackenbush positions in the browser and see their values as dyadic rationals.

Live: https://maxschottenfeld.github.io/hackenbush/

- **Draw** blue and red edges; ends on the ground are rooted there.
- Each grounded piece gets a dot and its value. The panel shows the total, who wins, the `{L | R}` options, and the sign expansion.
- **Cut** an edge to make a move; hover to preview the resulting value.

Values come from an exact memoized game search (pieces meeting only at the ground are summed), so cycles and non-tree graphs are handled, not just stalks.
