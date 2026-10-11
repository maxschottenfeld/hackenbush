# Hackenbush Workbench

Draw Blue-Red Hackenbush positions in the browser and see their values as dyadic rationals.

Live: https://maxschottenfeld.github.io/hackenbush/

- **Draw** blue and red edges; ends on the ground are rooted there.
- Each grounded piece gets a dot and its value. The panel shows the total, who wins, the `{L | R}` options, and the sign expansion.
- **Cut** an edge to make a move; hover to preview the resulting value.
- **Stalk derivation:** pick a stalk from the board or type one (e.g. `BBRB`) to see its value built up edge by edge with the simplicity rule, checked against Berlekamp's rule.

Values come from an exact memoized game search (pieces meeting only at the ground are summed), so cycles and non-tree graphs are handled, not just stalks.
