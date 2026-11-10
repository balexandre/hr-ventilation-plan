# Heat-recovery ventilation plan

A planning sheet for adding balanced mechanical ventilation with heat recovery (HRV, in Danish *balanceret mekanisk ventilation med varmegenvinding*) to our single-storey house in Lille Skensved, Køge.

The goal is to stop mould and keep fresh air moving through every room, without losing the heat our Vaillant heat pump (7.4 kW) produces.

## What's in the page

| Section | What it covers |
|---|---|
| **Floor plan** | Every tube drawn from the attic distribution boxes to each ceiling valve, plus the unit and the gable terminals |
| **Attic today** | Photos of the attic: the cylinder box, the planned unit spot beside it, the hatch, the network switch, and what they mean for the install |
| **Air flows** | Litres per second for every room, at normal running and at boost |
| **Ducts and joints** | Radial vs. branched vs. single-tube layouts, and a run-by-run table of tubes and lengths |
| **Vents and habits** | Vent types, where each vent goes relative to its doors, distances from walls, the air path between rooms, door advice and everyday habits against mould |
| **Is HRV right?** | The Køge climate, why HRV fits it, and a comparison with decentral units, exhaust-only fans and airing |
| **Machines** | What to look for in a unit, attic placement, a shortlist of models, and which Nilan Comfort 300 LR accessories to buy |
| **Shopping list** | Full bill of materials with quantities, plus notes on the cooker hood, dryer and unused fireplace |
| **Calculator** | Indoor humidity, cold-corner mould risk and yearly savings for any airflow |
| **Costs** | Budget ranges in DKK, running costs, subsidies to check |
| **Next steps** | The order to do things in, and a checklist for comparing installer quotes |

## The plan in short

- **House:** 159 m² heated floor area (BBR, measured to the outside of the walls; about 135 m² inside), 2.30 m ceilings, about 310 m³ of air, 5–6 people.
- **Airflow:** 48 l/s (173 m³/h) all the time, which is the BR18 minimum of 0.3 l/s per m² for 159 m², boosting to 64 l/s (230 m³/h) after showers and cooking.
- **Unit:** about 300 m³/h class, counterflow exchanger of 85% or more, humidity sensor, summer bypass.
- **Placement:** in the attic on the south side of the boarded box that holds the hot-water cylinder and heat-pump electronics (its right-hand side, facing east from the 65 × 117 cm hatch above the laundry room). The box can be extended to keep the unit frost-free. The unit sits above Bedroom 4, so it stands on anti-vibration feet.
- **Intake and exhaust:** through the timber boarding in the south half of the east gable, at least 2 m apart: exhaust high, just south of the cylinder box; intake lower, about 1.7 m further south. The heat pump stands below the laundry window at the north end of that wall, so nothing goes above it. The roof is asbestos cement and is not touched.
- **Ducts:** a radial system in Nilan's NilAir flexible tube. A supply box and an extract box by the hatch, linked to the unit by two insulated Ø160 ducts (about 7 m and 6 m), each feed eight Ø90 mm tubes, one per valve, or two where a valve needs more than about 40 m³/h. That's 16 tubes, about 137 m (buy 150 m), laid on the ceiling joists before the loft insulation is topped up.
- **Budget:** roughly 60,000–110,000 DKK installed.

| Room | Valve | Tubes | Normal l/s | Boost l/s |
|---|---|---:|---:|---:|
| Bedroom 1 (NW) | supply | 2 | 10 | 13 |
| Bedroom 2 (SW) | supply | 1 | 7 | 9 |
| Bedroom 3 (S) | supply | 1 | 7 | 9 |
| Bedroom 4 (E) | supply | 2 | 10 | 13 |
| Living room | supply ×2 | 1 + 1 | 14 | 20 |
| Kitchen | extract | 2 | 14 | 20 |
| Bathroom 1 (bathtub, en-suite) | extract | 2 | 12 | 16 |
| Bathroom 2 (shower) | extract | 2 | 12 | 16 |
| Laundry room | extract | 2 | 10 | 12 |
| **Total (balanced)** | | **16** | **48** | **64** |

## Still open

- Whether the unit fits beside the cylinder box (a truss diagonal and the roof slope limit the height)
- What the insulated pipe and the silver flexible duct by the hatch are
- Exactly where the box's walls are, and how high the two gable holes can go between the studs

## Viewing it

Open `index.html` in any browser. It's a single page with no build step; the site photos live in `photos/` (resized, with camera metadata removed). It loads fonts from Google Fonts and works offline with fallback fonts.

To publish it with GitHub Pages: go to **Settings → Pages**, set the source to **Deploy from a branch**, and choose `main` and `/ (root)`. The page will appear at `https://<your-user>.github.io/hr-ventilation-plan/`.

## Disclaimer

This is a planning estimate, not a ventilation design. Room areas are read from the sales floor plan (*vejledende tegning uden ansvar*) and are approximate. Prices and model names are rough figures for 2026. Final airflows, duct sizes and the unit choice should come from the installer's calculation and the building regulations (BR18) in force when the work is done.
