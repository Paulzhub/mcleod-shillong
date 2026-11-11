# McLeodganj → Shillong · 3D Trip Planner

An interactive 3D map that walks through a return trip from McLeodganj (Himachal Pradesh) to Shillong (Meghalaya), leg by leg, with the cost, duration and mode of transport for each leg.

## Features
- 3D map of India (three.js): drag to orbit, scroll/pinch to zoom, pan
- Five routes to compare: train via Pathankot, train via Delhi, train via Amb Andaura, all by bus, and flying
- Trains and buses follow land corridors; flights arc through the air
- Toggles for train class (Sleeper / 3AC) and one-way / return, with live totals
- Guided tour (▶), keyboard controls (← → to step, + − to zoom, 0 to reset, M for music)
- Optional ambient music generated in the browser with Web Audio

## Run it
It's a single static file. Open `index.html` in a browser, or serve it with GitHub Pages (Settings → Pages → deploy from the `main` branch, root folder).

## Notes
Fares were compiled in Nov 2026 from public listings (EaseMyTrip, ixigo, erail, ConfirmTkt, Trekgo, Expedia, Kayak, HappyFares). They are base fares and change with date and season. Fares marked **EST.** are estimates. The map is stylised and not to scale.
