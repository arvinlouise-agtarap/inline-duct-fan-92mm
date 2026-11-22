# Print Files

Print-ready exports for [inline-duct-fan-92mm](../README.md). Editable source files are in [`/cad`](../cad/).

## Files

| File | Format | Qty | Material | Supports | Print Time |
|---|---|---|---|---|---|
| `[part-name]_v2.0.stl` | STL | [1] | [PETG] | [No] | [TBD] |
| `[part-name]_v2.0.stl` | STL | [2] | [PETG] | [Yes: overhang at top] | [TBD] |
| `[project-name]_v2.0.3mf` | 3MF | [All] | [PETG] | [As saved] | [TBD] |

<!-- TODO: remove any rows that don't apply -->

## Print Orientation

![Orientation reference](../images/print-orientation.jpg)

| Part | Orientation | Reason |
|---|---|---|
| `[part-name]` | [Flat on bed, mounting face down] | [Layer lines run perpendicular to load; best surface finish on visible face] |
| `[part-name]` | [On its side] | [Avoids supports on the duct connection] |

<!-- Orientation reasoning is the most valuable part of this page. Keep it specific. -->

## Recommended Settings

| Setting | Value |
|---|---|
| Slicer / version | [Bambu Studio / PrusaSlicer / Cura, TBD] |
| Nozzle | [0.4 mm] |
| Layer height | [0.2 mm] |
| Walls / perimeters | [3] |
| Infill | [20% gyroid] |
| Bed / nozzle temp | [TBD] |
| Cooling | [TBD] |

Per-part settings that differ from these are noted in the Files table above.

## Notes

- **Units and scale:** STL files carry no unit information. These are modeled in [mm] and should import at 100% scale.
- **3MF vs. STL:** the 3MF includes orientation and slicer settings, so it's the quickest way to reproduce my print. The STLs work in any slicer.
- **Post-processing:** [N/A / Remove supports, ream the duct bore, heat-set inserts]
- **Fit and tolerances:** [Clearances are built into the model, so no scaling is needed]
- **Tested on:** [Printer model, material brand and color]

## Naming Convention

Files follow `[part-name]_v[major.minor].[ext]`. The version number matches the Revision History in the [main README](../README.md#revision-history).

## License

See [LICENSE](../LICENSE).
