# ESP32 DevKitC 4-Layer PCB Design

## Overview
This project is a custom 4-layer PCB design based on the ESP32 DevKitC module, designed using KiCad 10. It demonstrates multilayer PCB design, schematic capture, PCB layout, component placement, routing, and generation of manufacturing-ready files.

## Features
- ESP32 DevKitC-based design
- 4-layer PCB stack-up
- USB Micro-B interface
- Ground and power planes
- Through-hole and SMD components
- Manufacturing-ready Gerber files

## Software Used
- KiCad 10
- Git
- GitHub

## Repository Structure
```
├── Images/
│   ├── PCB_Layout.png
│   ├── PCB_Schematic.png
│   ├── PCB_3D_Top.png
│   └── PCB_3D_Bottom.png
│
├── Gerber_Files/
│   ├── *.gbr
│   ├── *.drl
│   └── *.gbrjob
│
├── *.kicad_pro
├── *.kicad_sch
├── *.kicad_pcb
└── README.md
```

## Design Verification
- ✔ Electrical Rules Check (ERC) completed
- ✔ Design Rules Check (DRC) completed
- ✔ Gerber and drill files generated successfully

## Images
The `Images` folder contains:
- PCB Layout
- PCB Schematic
- 3D Top View
- 3D Bottom View

## Gerber Files
The `Gerber_Files` folder contains all files required for PCB fabrication.

## License
This project is shared for educational and portfolio purposes.