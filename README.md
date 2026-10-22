# 2portnw

A simple two-port network parameter calculator for ECE students. Enter one known 2×2 parameter matrix and calculate the equivalent Z, Y, hybrid h, inverse hybrid g, and ABCD parameter sets. The app displays final numerical answers only—no step-by-step derivations.

## Use it

Open `index.html` in a browser. No dependencies or build step are required.

## Parameter convention

ABCD uses I₂ entering port 2:
- V₁ = A V₂ − B I₂
- I₁ = C V₂ − D I₂

## Notes

- Selecting variables alone cannot uniquely determine a network. You need a known parameter set or enough independent measurements/equations.
- Singular conversions are marked unavailable; other valid conversions remain visible.
- Parameter conversion does not independently verify whether a physical network is passive.
