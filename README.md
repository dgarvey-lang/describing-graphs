# Describing Graphs: Polynomial Graph Explorer

`index.html` is an interactive page for finding **real zeros, turning points, relative maximums, and relative minimums** of polynomial functions. Open it in any browser, or turn on **GitHub Pages** (Settings → Pages → Deploy from branch → `main`, root) to get a link you can share with students.

## Explore tab
- **Type an equation:** students type any polynomial (up to degree 8) and press **Graph it**. The graph and the “What the graph shows” box then list the real zeros, relative maximum and minimum points, and the intervals where the function is increasing and decreasing. It accepts standard form (`2x^3 - 5x^2 + 3`), factored form (`-(x+1)(x-2)^2`), or a mix (`0.5x(x^2 - 9)`). A leading `y =` or `f(x) =` is fine. Typing mistakes get a plain-language message, such as a missing `)` or a variable other than *x*.
- Build a polynomial in **factored form**: set the leading coefficient with a slider, drag the purple zeros along the x-axis, set each factor's multiplicity (×1, ×2, ×3), and add an (x² + 1) factor, which has no real zeros. You can also switch to **standard form** and type coefficients.
- The curve is blue where it rises and orange where it falls, so turning points show up where the color changes. Zeros, relative maxima (▲), and relative minima (▼) are marked with coordinates.
- **Calculator** buttons (zero, maximum, minimum) work like a TI-84: Left Bound, Right Bound, Guess. Bad bounds produce an error explaining why, such as no peak between the bounds.
- "What the graph shows" lists the zeros (crosses or bounces), turning points, max/min, increasing/decreasing intervals, and end behavior, along with the degree rule (at most *n* zeros and *n* − 1 turning points).
- **Show** checkboxes hide the zeros, max/min, colors, coordinates, or summary, so you can project a graph and have students predict before you reveal.
- **Examples** menu and auto-checking **Challenges**, for example "a cubic with 1 real zero but 2 turning points."

## Practice tab
- Random cubic and quartic functions. Students answer five questions: number of real zeros, the zeros, number of turning points, relative max point(s), and relative min point(s), rounded to the nearest hundredth.
- Feedback catches common mistakes: "f(7) = −300, not 0," a max entered as a min, coordinates in the wrong order, or answers that are close but not rounded.
- **Show answers on graph** unlocks only after every question has been checked once.
