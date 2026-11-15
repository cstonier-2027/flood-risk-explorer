# Flood Risk Explorer: Raise it, insure it, or move?

An interactive website for a homeowner in a floodplain who has to decide whether to raise the house, buy flood insurance, or sell and move, as rising sea levels make floods more frequent over a 30-year mortgage.

**Live site:** https://cstonier-2027.github.io/flood-risk-explorer/

## What it does

Four sliders set the situation:

- **Hazard today:** the yearly chance a flood reaches the floor (1% = the FEMA "100-year floodplain").
- **Climate change:** how much flood water levels rise over the 30 years (NOAA projects about 1 ft along U.S. coasts, 2020–2050).
- **Location:** the height difference between a 10-year and a 100-year flood, which controls how much a rise in water level multiplies flood frequency.
- **Decision:** how many feet to raise the house.

The page updates live: a chart of the yearly flood chance, a chart of each option's cumulative expected cost, and a comparison table. It explains the math and cites its sources on the page.

Course concepts: return periods (what a "100-year flood" means over a mortgage), sea-level rise as a rising baseline, and Risk = Hazard × Exposure × Vulnerability.

## Group members

- Carolin
- Taelor
- Sophie

## Running it locally

It's a single `index.html` file with no build step. Open it in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.
