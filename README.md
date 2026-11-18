# GC-NQ-Premkt-analysis

Interactive static web application for Gold (`GC`) and Nasdaq (`NQ`) futures session and pre-market volatility timing analysis.

## Live Webpage

- **GitHub Pages:** <https://dragontech96.github.io/GC-NQ-Premkt-analysis/>
- **Shell entrypoint:** [`index.html`](./index.html) / [`gold_nasdaq.html`](./gold_nasdaq.html)

## Included Views

1. **Gold or Nasdaq** (`gc_or_nq_focus.html`) — Side-by-side comparison across sessions and market clocks, with a live recalculation panel driven by per-market label settings.
2. **Gold** (`price_travel_curves.html`) — 10-year and recent 1-minute Gold (`GC`) study with configurable Trend / Swing / Whipsaw label settings.
3. **Nasdaq** (`price_travel_curves_nq.html`) — 10-year and recent 1-minute Nasdaq (`NQ`) study with configurable Trend / Swing / Whipsaw label settings.

## Custom Settings Persistence

Settings adjusted inside the **Gold** or **Nasdaq** tabs are stored locally in browser storage (`localStorage`) and can also be exported to or loaded from `.json` files directly via the shell bar (`Save settings to a file` / `Load settings from a file`).
