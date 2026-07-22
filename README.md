# Bitcoin Mining Calculator

A free, no-signup calculator for bitcoin miners.

**Will your mine pay?** Enter your power cost in ¢/kWh, pick your rig, and see profit per day,
margin, break-even BTC price, break-even power cost, and payback — for grid, hosted, or on-site
gas power.

**Powering a new site?** A second mode compares three ways to get the power: buying your own
gensets, renting power, or buying grid power — over the horizon you choose, with the capital,
fuel, uptime, and resale value all laid out.

## Using it

Just open the page. There is no account, no email gate, and nothing is stored on a server.

- Every input rides in the URL, so **Copy Link** shares the exact scenario you're looking at.
- **Fetch live BTC** pulls the current bitcoin price and network hashrate from public APIs.
- **Print / PDF** produces a one-page summary.
- On a phone, use your browser's "Add to Home Screen" to install it.

## Assumptions and honesty

Rig specs (hashrate, J/TH) are from manufacturer data; **prices are editable because they go stale
fast**. The tool is budgetary — it is not a quote, and it will tell you plainly when a project
doesn't pencil.

Built by [2G Energy Rental](https://www.2g-energy.com/). 2G rents on-site natural gas and propane
power generation; it appears in this tool as one power option among several, and only where the
math actually favors it.

## Development

Single self-contained HTML file — React + Babel from a CDN, no build step. Open `index.html` in a
browser and it runs. `manifest.json` and the three icons only add install-to-home-screen; the page
works without them.
