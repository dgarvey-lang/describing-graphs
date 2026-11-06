# Describing Graphs: Polynomial Graph Explorer

`index.html` is an interactive page for finding the key features of a polynomial function. It's published with GitHub Pages, so the repository's Pages link opens it directly.

## Explore tab
Students type a polynomial (up to degree 8) and press **Graph it** (or Enter). The page graphs it and lists:
- the real zeros, and whether the graph crosses or bounces at each one
- the turning points as (x, y)
- the relative maximum and minimum values (y-values only)
- the intervals where the function is increasing and decreasing
- end behavior, plus the degree rule (at most *n* zeros and *n* − 1 turning points)

It accepts standard form (`2x^3 - 5x^2 + 3`), factored form (`-(x+1)(x-2)^2`), or a mix (`0.5x(x^2 - 9)`). A leading `y =` or `f(x) =` is fine. Typing mistakes get a plain-language message, such as a missing `)` or a variable other than *x*. On the graph the curve is blue where it rises and orange where it falls; hover or tap to trace it, and use −, +, and **Fit graph** to zoom.

## Practice tab
- Random cubic and quartic functions. Students answer six questions: number of real zeros, the zeros, number of turning points, the turning points as (x, y), relative max value(s), and relative min value(s) (y-values only), rounded to the nearest hundredth.
- **Calculator** buttons (zero, maximum, minimum) work like a TI-84: Left Bound, Right Bound, Guess.
- Feedback catches common mistakes: "f(7) = −300, not 0," a max entered as a min, an x-value or a full point typed instead of the y-value, coordinates in the wrong order, or answers that are close but not rounded.
- **Show answers on graph** unlocks only after every question has been checked once.
