# Design Log

## Direction

A field-notes editorial treatment: warm paper-like neutrals, deep green-black text, and a restrained rust accent. Serif display headings contrast with plain sans-serif reading text; fine rules and the numbered label establish a quiet print-inspired hierarchy.

## System

- Type: 18px base with a 1.25 ratio; six sizes maximum.
- Spacing: margins, padding, and gaps use the `--space-*` scale.
- Color: OKLCH neutral ramp with role tokens for page background, text, muted text, accent, and borders.
- Contrast: calculated foreground/background ratios are 17.08:1 for primary text, 6.26:1 for muted text, and 9.57:1 for accent links. Confirm these in browser DevTools on the rendered page.
- Layout: two-column editorial grid on wide screens, stacked layout below 58rem, and single-column content below 42rem.
- Accessibility: visible keyboard focus, semantic role selectors, and reduced-motion handling.

## AI Critique Loop

AI corrected any code erros that I had in this.

## Log of Coding

Index.html had been added with zen garden. Project was deleten then restarted due to changes and did not look well so had to ponder on ideas on what to do.
