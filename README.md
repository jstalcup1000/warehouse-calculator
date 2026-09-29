# Warehouse Calculator

A simple web app for everyday warehouse math. It runs in any browser, including phones.

**Live site:** https://jstalcup1000.github.io/warehouse-calculator/

## Features

### Pallet Build
- **Cases per pallet**: Ti (cases per layer) × Hi (layers)
- **Cube per pallet**: cases per pallet × case cube (cu ft)
- **Pallets needed**: total cases to ship ÷ cases per pallet, rounded up, with the case count on the last pallet

### Height Check
- **Built height**: pallet base height + (Hi × case height)
- Warns when the pallet is over the max height, and shows the most layers that fit

### Cycle Count Variance
- **Variance**: counted quantity − system OHB, in units and %
- Flags a recount when the variance is outside the tolerance you set

## How it works

Everything is in a single file, `index.html` (HTML, CSS, and JavaScript). There's nothing to install. GitHub Pages hosts the site and updates it automatically on every push to `main`.

To run it locally, open `index.html` in a browser.

## Note

This app uses sample numbers only. It does not connect to WMS or store any data.
