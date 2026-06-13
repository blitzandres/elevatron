# Experiments

Build notes and data templates for the **safe, supervised** benchtop demonstrations described in [`../docs/07-homemade-experiments.md`](../docs/07-homemade-experiments.md).

> ⚠️ **Read the safety preamble in `docs/07` first.** Everything here is extra-low-voltage / sealed-apparatus only. No capacitor-bank Z-pinches, no can-crushers — those are facility-grade and explicitly out of scope.

## Demo index

| ID | Title | Maps to | Hardware cost | Risk |
|----|-------|---------|---------------|------|
| A | Ampère force between parallel currents | §2.1 | ~$0 (foil + bench supply) | Low (≤12 V) |
| B | Electrolytic / liquid pinch | §2.2–2.3 | ~$0–low | Low (≤24 V) |
| C | Electron-beam focusing in a sealed teaching tube | §3.1 | lab-owned set | Medium (HV — matched supply only) |
| D | Plasma globe filamentation | §2.4–2.5 | ~$20 (consumer globe) | Low |
| E | Bennett-relation estimation (analysis) | §2.2 | none | None |

## Data template (per run)

```
demo_id:            A | B | C | D | E
date:
operator:
supervisor:
apparatus:          (description + ratings)
controlled_vars:    (voltage, geometry, spacing, ...)
measured:           current [A], deflection [mm/deg], onset current [A], ...
prediction:         (from the §2 equation, with the formula written out)
result_vs_predict:  (ratio + error estimate)
elevatron_link:     which §3.4 sub-claim this supports/undermines
safety_controls:    (what kept it safe)
notes:
```

Copy the block into a per-demo log file (e.g. `demo-A/run-2026-06-12.md`) and fill it in. The goal of each run is to connect a measurement back to a specific Elevatron sub-claim — supporting the conductor role, or illustrating why the structural role fails.
