[English](README.md) | [فارسی](README.fa.md)

# Altium Library

A collection of component libraries for **Altium Designer** and **KiCad**, with detailed **3D STEP models** (including the markings printed on the ICs): schematic symbols, footprints and 3D bodies for modules, ICs, connectors, passives and many other parts.

---

## Categories

| Folder | Contents |
|---|---|
| [`Resistors`](Components/Resistors/) | Resistors |
| [`Capacitors`](Components/Capacitors/) | Capacitors |
| [`Inductors-Relays-Chokes`](Components/Inductors-Relays-Chokes/) | Inductors, relays and chokes |
| [`Diodes-LEDs`](Components/Diodes-LEDs/) | Diodes and LEDs |
| [`Transistors`](Components/Transistors/) | Transistors and MOSFETs |
| [`ICs`](Components/ICs/) | Integrated circuits |
| [`MCUs`](Components/MCUs/) | Microcontrollers |
| [`Modules`](Components/Modules/) | Modules (ESP32-WROOM-32U, ...) |
| [`Connectors`](Components/Connectors/) | Connectors |
| [`Sensors`](Components/Sensors/) | Sensors |
| [`Crystals-Oscillators`](Components/Crystals-Oscillators/) | Crystals and oscillators |
| [`Switches-Buttons`](Components/Switches-Buttons/) | Switches and buttons |
| [`Displays`](Components/Displays/) | Displays |
| [`Protection`](Components/Protection/) | Fuses, TVS, varistors and other protection |
| [`Mechanical`](Components/Mechanical/) | Mechanical parts (holes, standoffs, enclosures) |
| [`Misc`](Components/Misc/) | Everything else |

## Repository layout

```
/
├── Components/     all parts, sorted by category (one folder per part)
├── Library-Info/   how to use the library, notes and changelog
├── LICENSE
├── README.md
└── README.fa.md
```

- Looking for a specific part? Open [`Components`](Components/) and pick its category.
- Want to know how to install and use the library? See [`Library-Info`](Library-Info/).

Each part lives in its own folder inside its category:

```
Components/<Category>/<Part-Name>/
├── Altium/    (.SchLib, .PcbLib)
├── KiCad/     (.kicad_sym, .kicad_mod)
├── STEP/      (.step – works in any CAD/EDA tool)
└── preview.png
```

## Download

**Option 1 – The complete library (recommended)**
Everything in one package: go to the [**Releases**](https://github.com/africazani/africazani-altium-library/releases/latest) page and download the latest `.zip` from the *Assets* section. Each release has release notes listing what was added or changed.

**Option 2 – A single part**
Browse the [`Components`](Components/) folder, open the part you need and download its files:

1. Open the part folder (e.g. `Components/Modules/ESP32-WROOM-32U/`).
2. Click a file, then the **Download raw file** button (or use *Code → Download ZIP* to get the whole repository).

Installation steps and notes: see [Library-Info](Library-Info/).

## License

This work is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
You are free to use, modify, and distribute these files, including commercially, as long as you give credit:

> 3D models and Altium library by **africazani** – https://github.com/africazani/africazani-altium-library

How to credit the library in your own project: see [Library-Info](Library-Info/#crediting-this-library-in-your-project).

## Contact

Found a mistake or want a new part? Open an issue or message me on Telegram: **@africazani**
