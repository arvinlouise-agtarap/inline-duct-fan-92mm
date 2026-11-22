# CAD Files

Native and neutral-format CAD source files for inline-duct-fan-92mm/(../README.md).

## Software

| | |
|---|---|
| **Designed in** | [OnShape CAD](https://cad.onshape.com/) |
| **Software version** | N/A - Web Based |
| **Units** | [mm] |

## Files

| File | Format | Description | Version |
|---|---|---|---|
| [`Fan-Mount-Inser-Body.step`](cad/Fan-Mount-Inser-Body.step) | STEP | Neutral format, opens in any CAD software | v1.0 |
| `[project-name]_v2.0.step` | STEP | Neutral format, opens in any CAD software | v2.0 |
| `[part-name].step` | STEP | [Individual part, if exported separately] | v2.0 |

<!-- TODO: remove any rows that don't apply -->

## Opening the Files

- **Same software:** open the native file directly. All sketches, parameters, and the feature history are intact.
- **Different software:** import the `.step` file. This keeps the geometry but not the feature history, so edits are harder.
- **Print-ready exports** (STL/3MF) are in [`/stl`](../stl/).

## Key Parameters

<!-- List the dimensions someone would want to change. If your CAD tool supports named parameters, use those names here. -->

| Parameter | Value | Purpose |
|---|---|---|
| `[fan_size]` | [92 mm] | [Fan frame dimension] |
| `[duct_diameter]` | [100 mm] | [Outer diameter of duct connection] |
| `[clearance]` | [0.2 mm] | [Fit tolerance used for mating parts] |

## Modeling Notes

- **Origin and orientation:** [Where the origin sits and which axis is "up"]
- **Design approach:** [Parametric / direct modeling; how it's structured]
- **Tolerances:** [Tolerances baked into the model vs. added in the slicer]
- **Known issues:** [N/A or TBD]

## Naming Convention

Files follow `[project-name]_[part]_v[major.minor].[ext]`. The version number matches the Revision History in the [main README](../README.md#revision-history).

## License

See [LICENSE](../LICENSE).
