# UMB Circular Intelligence — Starter Project

A free, single-file frontend demo for the Urban Material Bank project.

## Features
- Responsive homepage and navigation
- Searchable/filterable demo material marketplace
- UMB Mitra local rule-based chatbot
- Material Rescue Mode with a copyable draft recovery checklist
- Impact dashboard with clear demo/estimate disclaimers
- Eight sample material listings
- No paid API, backend, account, or build step required

## Run it
1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. For best compatibility, serve the folder with a local web server:
   - If Python is installed, open a terminal in this folder and run: `python -m http.server 8000`
   - Visit `http://localhost:8000`

## Important limitations
- All listings, prices, quantities and availability are simulated.
- Mitra uses local keyword/rule matching, not an LLM.
- The impact page intentionally does not invent a CO2 savings number.
- Rescue submissions are not stored or published.
- There is no real supplier database, login, map, messaging backend, AI vision, payment, or booking integration.
- Before using this for real suppliers, add a database, authentication/authorization where needed, server-side validation, privacy controls and verified environmental factors.
