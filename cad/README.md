# CAD Files

Native and neutral-format CAD source files for [inline-duct-fan-92mm/](../README.md). Print-Ready files are in [`/stl`](../stl/).

## Software

| | |
|---|---|
| **Designed in** | [OnShape CAD](https://cad.onshape.com/) |
| **Software version** | N/A - Web Based |
| **Units** | [mm] |

## Files

| File | Format | Description | Version |
|---|---|---|---|
| [`Fan-Mount-Inser-Body-v1.1.step`](./Fan-Mount-Inser-Body-v1.1.step) | STEP | Neutral format, opens in any CAD software | v1.1 |
| [`Wall-Mount-Enclosure-Body-v1.1.step`](./cad/Wall-Mount-Enclosure-Body-v1.1.step)| STEP | Neutral format, opens in any CAD software | v1.1 |


## Opening the Files

- **OnShape CAD** [Project Link : View Only](https://cad.onshape.com/documents/b9e0e87d5984c5b129224080/w/06f51b4a7c559cc40fa8c72a/e/9bce01a428b44037feeb6a47?renderMode=0&uiState=6b0295cdfda77f119cad8a82)
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
