# Ocean Star — Master Engineering Document v1.0
**Date:** 2026-11-17
**Author:** Grok (with Mario)
**Status:** Filed to GitHub + Drive (dual-post rule). This is the single source of truth for the 3D construct.

## 1. Site & Scale
- Principal city at ring 5 core. Five rings, radii 1.2 / 2.4 / 3.6 / 4.8 / 6.0 km (rings 5 through 1).
- 46 round hoops: 10 / 10 / 10 / 8 / 8 across rings 5 through 1.
- Train axis at 127.5°. Gateway Spar is the principal vertical structure anchoring the city.
- Study depth: 80 m.

## 2. Underwater Train System
- Tube at 80 m depth, route ring 5 → ring 1 outer edge along the train axis. Five waypoints.
- Passes under ring 4 away from its gates (R-77). One ring-3 gate sits exactly on the train axis with dedicated underwater platforms (R-81).
- All train platforms are underwater stations at tube depth (R-76).
- Zero-bending condition: tube weight within ~0.5% of displaced water. Free spans 1000 m / 750 m with spar pairs.
- One auxiliary spar pair per lagoon: R5-R4, R4-R3, R3-R2, R2-R1 (R-79).

## 3. Auxiliary Spar — Reconciled Weight Table (R-78)
| Parameter | Value |
|---|---|
| Draught | 180 m |
| Displacement (one spar) | 2.087 Mt |
| Spar own weight (structure + ballast) | 0.687 Mt (~33%) |
| Buoyancy cells | 67% of displacement |
| Net reserve | 1.4 Mt |
| GM | 20 m |
| Centre of gravity above keel | 75 m |

The 60% buoyancy-cell row is retired: at 60% the reserve would only reach 1.25 Mt. 67% yields exactly 1.4 Mt. Stability layout: heavy structure low, cells filling the upper two-thirds.

## 4. Ring 3 Perimeter Logic (R-80 + R-81)
- Gate on train axis at (-2191.5, 2856.1) m. Vessel inflow directly opposite at (2191.5, -2856.1) m.
- Large-vessel traffic bound for rings 2 and 1 enters on the far side from the train gate — the two flows never cross at ring 3.
- Suggested vessel standoff: 2.5× ring-3 radius = 9000 m (to be quantified in the sheet).
- Ring 3 gate orientation is DECIDED. It was the last open geometry question on the main line.

## 5. Lagoon Spar Pair Coordinates (perpendicular to train axis)
- R5-R4 midpoint 1800 m: spar A (-1428.0, -1095.8), spar B (1428.0, 1095.8)
- R4-R3 midpoint 3000 m: spar A (-2380.1, -1826.3), spar B (2380.1, 1826.3)
- R3-R2 midpoint 4200 m: spar A (-3332.1, -2556.8), spar B (3332.1, 2556.8)
- R2-R1 midpoint 5400 m: spar A (-4284.1, -3287.3), spar B (4284.1, 3287.3)

## 6. Decided Rule Register
- R-76: all train platforms underwater at 80 m
- R-77: tube under ring 4 away from gates
- R-78: spar weight table reconciled
- R-79: every lagoon R5→R1 has auxiliary spar pair
- R-80: large vessels to R2/R1 minimize approach to R3
- R-81: R3 gate on train axis; vessel inflow opposite

## 7. Remaining Parametric Work (no Founder input needed)
- Four non-auxiliary spars
- Further train lines
- Strands (function TBD)
- Airstrips as drawings
- R-60: sheet v0.4 → geometry wiring
- Ring 3 gate width + platform layout detail
- R-80 standoff quantification in sheet

## 8. Design Principle
Everything is one system. Rings, tube, spars, vessels, gates are expressions of one geometry. Every rule is a face of it. R-60's job is ensuring the single source of truth carries all of it at once.

— Grok, 17 November 2026