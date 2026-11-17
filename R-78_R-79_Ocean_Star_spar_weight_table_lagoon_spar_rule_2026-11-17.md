# R-78 & R-79 — Ocean Star Spar Weight Table + Lagoon Spar Rule
**Date:** 2026-11-17
**Author:** Grok
**Status:** Filed to GitHub + Drive (dual-post rule). Decided in conversation with Mario.

## R-78 — Spar weight table reconciliation (auxiliary spar)

Three earlier figures could not all hold: 180 m draught, 60% buoyancy cells, 1.4 Mt net reserve. Reconciled:

| Parameter | Value |
|---|---|
| Draught | 180 m |
| Displacement (one spar) | 2.087 Mt |
| Spar own weight (structure + ballast) | 0.687 Mt (~33% of displacement) |
| Buoyancy cells | 67% of displacement (not 60%) |
| Net reserve | 1.4 Mt |
| GM | 20 m |
| Centre of gravity above keel | 75 m |

**Reasoning:** At 60% buoyancy cells the non-buoyant mass would be 0.835 Mt and the reserve would only reach 1.25 Mt, not 1.4. Raising cells to 67% gives non-buoyant mass 0.687 Mt and reserve exactly 1.4 Mt. GM of 20 m with CoG at 75 m above keel holds if heavy structure sits low and cells fill the upper two-thirds — standard spar stability layout.

The 60% row is retired. Sheet v0.4 row for auxiliary spar buoyancy cells updates to 67%.

## R-79 — Lagoon spar rule (train line)

Every lagoon between ring 5 and ring 1 carries its respective auxiliary spar pair for the underwater train tube. The tube rides the spar pairs the entire route from ring 5 to ring 1's outer edge, where it terminates. Ring 4 having no gates makes zero consequence to the train: spars remain in the lagoon as before, tube passes beneath ring 4 away from any gate position (per R-77). Ring 3's gate orientation is now a station-placement detail, not a routing constraint.

## Open items after these two
- Ring 3 gate line facing (station placement only)
- Remaining four spars (not auxiliary)
- Further train lines
- Strands
- Airstrips as drawings
- Sheet v0.4 → geometry wiring (R-60)

— Grok, 17 November 2026