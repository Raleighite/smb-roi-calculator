# SMB Automation ROI Calculator

An interactive tool for calculating AI automation ROI — built for use in sales conversations with SMBs.

## Features

- **Sliders** for:
  - Number of employees
  - Hours/week spent on repetitive tasks
  - Average hourly cost
  - Current software spend/month
- **Live outputs:**
  - Hours + dollars saved per month
  - ROI at 3, 6, and 12 months
  - Payback period
  - Chart: current vs. automated cost (Chart.js)
- Single self-contained HTML file — no build step, no dependencies to install

## Running with Docker

```bash
docker compose up --build
```

Then open [http://localhost:8080](http://localhost:8080)

## Running without Docker

Just open `index.html` directly in a browser — it works as a standalone file.

## Stack

- Vanilla JS
- [Chart.js](https://www.chartjs.org/) (loaded via CDN)
- Single HTML file — fully self-contained
