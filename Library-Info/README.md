[English](README.md) | [فارسی](README.fa.md)

# Library Info

Back to the [main page](../README.md) · Browse the parts in [Components](../Components/)

## Formats

Every part is provided in as many of these formats as available:

| Folder inside the part | Files | Used by |
|---|---|---|
| `Altium/` | `.SchLib`, `.PcbLib` | Altium Designer |
| `KiCad/` | `.kicad_sym`, `.kicad_mod` | KiCad |
| `STEP/` | `.step` | any CAD / EDA tool |

The `.step` files are neutral, so you can use the 3D models with any software even if you don't use Altium or KiCad.

## How to use in Altium Designer

1. Download the complete library from [Releases](https://github.com/africazani/africazani-altium-library/releases/latest), or a single part from its folder.
2. In Altium Designer, add the `.SchLib` / `.PcbLib` files (or the `.IntLib`) via *Components → File-based Libraries Preferences*.
3. The 3D body is linked to the footprint. If it doesn't show, re-link the `.step` file in the PCB Library panel.

## How to use in KiCad

Menu names can differ slightly between KiCad versions.

1. **Symbol:** in the Schematic Editor open *Preferences → Manage Symbol Libraries*, add the `.kicad_sym` file as a new library (global or project).
2. **Footprint:** KiCad footprint libraries are folders ending in `.pretty`. Put the `.kicad_mod` file inside such a folder, then add the folder via *Preferences → Manage Footprint Libraries*.
3. **3D model:** open the footprint properties, go to the *3D Models* tab and select the `.step` file from the `STEP/` folder.

## Crediting this library in your project

The files are licensed under CC BY 4.0, so you need to give credit. You don't have to put it on the PCB itself. Add one line wherever your project is documented (README, credits page, BOM notes, video description):

```
Altium/KiCad library and 3D models by africazani – https://github.com/africazani/africazani-altium-library (CC BY 4.0)
```

If you modified the files, mention that they were changed.

## Notes

- Dimensions follow the manufacturer's datasheet. Always verify against the latest datasheet before manufacturing a board.
- Logos and trademarks printed on the models belong to their respective owners.

## Changelog

See the notes of each version on the [Releases](https://github.com/africazani/africazani-altium-library/releases) page, and [CHANGELOG.md](CHANGELOG.md).
