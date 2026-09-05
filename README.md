# AnalogRedstone

AnalogRedstone is an open-source hardware project that recreates Minecraft Redstone components in real life using analog electronics.

> ⚠️ This project is currently under development. Design files, documentation, and manufacturing outputs will be added gradually.

## Project goals

- Represent Redstone signal strength as an analog voltage.
- Reproduce the behaviour of familiar Redstone components with physical electronic circuits.
- Use modular, mechanically compatible circuit boards.
- Provide editable source files and sufficient documentation for reproduction and modification.

## Modules

| Module | Description | Status |
| --- | --- | --- |
| Connector PCB | Provides the mechanical and electrical connection between adjacent AnalogRedstone modules. | 🚧 In development |
| Redstone Dust | Transfers an analog signal between modules. | 🚧 In development |
| Repeater | Repeats and delays a signal, with selectable delay and locking functionality. | 🚧 In development |
| Comparator | Performs Redstone-inspired analog signal comparison and subtraction. | 🚧 In development |
| Redstone Torch | Inverts the input signal and provides a full-strength output when the input is inactive. | 📋 Planned |
| Lever | Provides a manually controlled on/off signal for the connected modules. | 📋 Planned |
| Redstone Lamp | Provides a visual indication when it receives an active input signal. | 📋 Planned |


Additional modules may be added as the project develops.

## Repository structure

```text
AnalogRedstone/
├── Libraries/        # Shared symbols, footprints, and component models
├── Modules/          # Electronic modules and connector boards
├── Mechanical/       # Shared mechanical designs and enclosures
├── Documentation/    # Project documentation and design notes
├── LICENSE.md        # Project licence terms
└── README.md         # Project overview
```

Each module will contain its editable design sources and, where applicable, exported manufacturing and 3D-printing files.

## Documentation

Detailed circuit descriptions, design decisions, interface specifications, and assembly information are being prepared. Until the first stable release, files and interfaces may change without notice.

## Licence

Hardware and mechanical design files are licensed under the [CERN Open Hardware Licence Version 2 – Permissive (CERN-OHL-P-2.0)](LICENSES/CERN-OHL-P-2.0.txt).

Copyright (c) 2026 Daniel Sinko

## Disclaimer

AnalogRedstone is an independent, fan-made engineering project. It is not affiliated with, endorsed by, or sponsored by Mojang Studios or Microsoft. Minecraft and Redstone are trademarks or intellectual property of their respective owners.
