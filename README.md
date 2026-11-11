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

## How to use in Altium Designer

1. Download the part folder (or the whole repo as a zip).
2. In Altium Designer, add the `.SchLib` / `.PcbLib` files via *Components → File-based Libraries Preferences*.
3. The 3D body is linked to the footprint. If it doesn't show, re-link the `.step` file from the part folder in the PCB Library panel.

## Notes

- Dimensions follow the manufacturer's datasheet. Always verify against the latest datasheet before manufacturing a board.
- Logos and trademarks printed on the models belong to their respective owners.

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
You are free to use, modify, and distribute these files, including commercially, as long as you give credit:

> 3D models and Altium library by **africazani** – https://github.com/africazani/africazani-altium-library

## Contact

Found a mistake or want a new part? Open an issue or message me on Telegram: **@africazani**
