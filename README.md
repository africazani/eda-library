[English](README.md) | [فارسی](README.fa.md)

# Altium Library

A collection of **Altium Designer** component libraries with detailed **3D STEP models** (including the markings printed on the ICs): schematic symbols, footprints and 3D bodies for modules, ICs, connectors, passives and many other parts.

---

## Categories

| Folder | Contents |
|---|---|
| [`Resistors`](Resistors/) | Resistors |
| [`Capacitors`](Capacitors/) | Capacitors |
| [`Inductors-Relays-Chokes`](Inductors-Relays-Chokes/) | Inductors, relays and chokes |
| [`Diodes-LEDs`](Diodes-LEDs/) | Diodes and LEDs |
| [`Transistors`](Transistors/) | Transistors and MOSFETs |
| [`ICs`](ICs/) | Integrated circuits |
| [`MCUs`](MCUs/) | Microcontrollers |
| [`Modules`](Modules/) | Modules (ESP32-WROOM-32U, ...) |
| [`Connectors`](Connectors/) | Connectors |
| [`Sensors`](Sensors/) | Sensors |
| [`Crystals-Oscillators`](Crystals-Oscillators/) | Crystals and oscillators |
| [`Switches-Buttons`](Switches-Buttons/) | Switches and buttons |
| [`Displays`](Displays/) | Displays |
| [`Protection`](Protection/) | Fuses, TVS, varistors and other protection |
| [`Mechanical`](Mechanical/) | Mechanical parts (holes, standoffs, enclosures) |
| [`Misc`](Misc/) | Everything else |

## Folder structure

Each part lives in its own folder inside its category:

```
<Category>/
└── <Part-Name>/
    ├── <Part-Name>.step
    ├── <Part-Name>.SchLib
    ├── <Part-Name>.PcbLib
    └── preview.png
```

## Download

**Option 1 – The complete library (recommended)**
Everything in one package: go to the [**Releases**](https://github.com/africazani/africazani-altium-library/releases/latest) page and download the latest `.zip` from the *Assets* section. Each release has release notes listing what was added or changed.

**Option 2 – A single part**
Browse the category folders in this repository, open the part you need and download its files:

1. Open the part folder (e.g. `Modules/ESP32-WROOM-32U/`).
2. Click a file, then the **Download raw file** button (or use *Code → Download ZIP* to get the whole repository).

## How to use in Altium Designer

1. Download the complete library from [Releases](https://github.com/africazani/africazani-altium-library/releases/latest), or a single part from its folder.
2. In Altium Designer, add the `.SchLib` / `.PcbLib` files (or the `.IntLib`) via *Components → File-based Libraries Preferences*.
3. The 3D body is linked to the footprint. If it doesn't show, re-link the `.step` file in the PCB Library panel.

## Notes

- Dimensions follow the manufacturer's datasheet. Always verify against the latest datasheet before manufacturing a board.
- Logos and trademarks printed on the models belong to their respective owners.

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
You are free to use, modify, and distribute these files, including commercially, as long as you give credit:

> 3D models and Altium library by **africazani** – https://github.com/africazani/africazani-altium-library

## Contact

Found a mistake or want a new part? Open an issue or message me on Telegram: **@africazani**
