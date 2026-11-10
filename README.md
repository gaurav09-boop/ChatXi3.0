# ChartXi — Data Visualization Studio

A responsive chart-making website inspired by the supplied dashboard reference and using the supplied ChartXi logo.

## Features
- 10 chart types: bar, line, pie, doughnut, radar, polar area, scatter, bubble, area and mixed.
- Manual CSV-style data entry, CSV/XLSX/XLS upload, and public Google Sheets CSV import.
- Automatic coordinated color shades from a selected main color.
- Manual color picker for each bar or pie/doughnut/polar slice (and each series for other chart types).
- Chart title, canvas background, legend and gridline controls.
- PNG chart export and reset design.
- No login, backend, API keys or environment variables. Data is processed in the browser.

## Deploy on Render
Create a **Static Site** connected to this GitHub repository.
- Branch: `main`
- Root directory: leave blank
- Build command: leave blank
- Publish directory: `.`

The site uses Chart.js and SheetJS via CDN, so visitors need internet access. For Google Sheets import, enable **Anyone with the link — Viewer**.
