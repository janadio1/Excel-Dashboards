# MAR Chart Audit Tool

A lightweight browser-based checklist for auditing MAR chart completion across every week of the year, Monday to Sunday, for each placement.

## File

- `mar-chart-audit-tool.html`

## Features

- Tracks weeks **1 to 52/53** for a selected year.
- Day-by-day checkboxes (**Mon-Sun**) for each week.
- Supports **multiple placements** with a placement selector.
- Stores data in browser `localStorage` so progress persists on that machine.
- Calculates weekly completion percentage automatically.
- Highlights fully completed weeks.
- Exports the active placement to CSV.

## Usage

1. Open `mar-chart-audit-tool.html` in a web browser.
2. Enter your placements (one per line) and click **Save placements**.
3. Choose the active placement and tick each day once MAR is audited.
4. Optionally export the active placement data using **Export active placement as CSV**.

## Notes

- The tracker is local to the browser/computer where it is used.
- To share progress with others, use CSV export or host this file with a shared backend later.
