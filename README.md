
# ESP-WROOM-32 KiCad Prototype

A hardware prototyping project based on the ESP-WROOM-32 module, designed using KiCad. This repository contains the circuit schematic, PCB layout, Gerber manufacturing files, design screenshots, datasheets and supporting documentation.

The project was developed as a learning and hardware prototyping exercise, using technical documentation and component datasheets as references.

## Project Overview

| Parameter | Details |
|---|---|
| Project Name | ESP-WROOM-32 KiCad Prototype |
| Microcontroller Module | ESP-WROOM-32 |
| Design Software | KiCad |
| Project Type | Hardware / PCB Design |
| Design Stage | Prototype |
| Repository | ESP-WROOM-32-Development-Board |
| Author | Armaan |

## Repository Structure

```text
esp-wroom-32/
│
├── esp_wroom_32.kicad_pro       # KiCad project settings
├── esp_wroom_32.kicad_sch       # Circuit schematic
├── esp_wroom_32.kicad_pcb       # PCB layout
│
├── ESP-WROOM-32.PDF             # ESP-WROOM-32 datasheet
├── DRC.rpt                      # Design rule check report
│
├── gerber/                      # PCB manufacturing files
│   ├── esp_wroom_32-B_Cu.gbr
│   ├── esp_wroom_32-F_Cu.gbr
│   ├── esp_wroom_32-B_Mask.gbr
│   ├── esp_wroom_32-F_Mask.gbr
│   ├── esp_wroom_32-B_Paste.gbr
│   ├── esp_wroom_32-F_Paste.gbr
│   ├── esp_wroom_32-B_Silkscreen.gbr
│   ├── esp_wroom_32-F_Silkscreen.gbr
│   ├── esp_wroom_32-Edge_Cuts.gbr
│   ├── esp_wroom_32-NPTH.drl
│   ├── esp_wroom_32-PTH.drl
│   └── esp_wroom_32-job.gbrjob
│
├── images/                      # Design screenshots
│   └── *.png
│
├── README.md                    # Project documentation
└── LICENSE                      # Licence, if applicable
```

## Hardware Design

This project uses the ESP-WROOM-32 module, which provides integrated Wi-Fi and Bluetooth connectivity.

The KiCad project includes the following design files and documentation:

- **Schematic:** Circuit diagram and electrical connections.
- **PCB Layout:** Component placement, copper routing and board layout.
- **Gerber Files:** PCB fabrication outputs.
- **DRC Report:** Design rule check results from the saved design.
- **Datasheet:** Technical specifications and reference information for the ESP-WROOM-32 module.
- **Design Images:** Screenshots documenting the schematic, PCB and design process.

Refer to the KiCad schematic and PCB files for the actual circuit implementation and board layout.

## Tools and Software

The following tools and resources are used in this project:

- [KiCad](https://www.kicad.org/) — Electronic schematic capture and PCB design.
- [Git](https://git-scm.com/) — Version control.
- [GitHub](https://github.com/) — Project hosting and version management.
- [Espressif Documentation](https://www.espressif.com/) — Technical documentation and component specifications.

## Getting Started

### 1. Clone the Repository

Clone the project from GitHub using:

```bash
git clone https://github.com/arm-n/ESP-WROOM-32-Development-Board.git
```

Navigate to the project directory:

```bash
cd ESP-WROOM-32-Development-Board
```

### 2. Open the KiCad Project

1. Install and launch KiCad.
2. Open the KiCad Project Manager.
3. Select **File → Open Project**.
4. Navigate to the cloned repository.
5. Open `esp_wroom_32.kicad_pro`.

### 3. Explore the Design

**Schematic**

Open the schematic editor to inspect the circuit diagram, components and electrical connections.

**PCB Layout**

Open the PCB editor to examine component placement, copper routing, board outline and PCB design.

**Design Rule Check**

The repository includes a `DRC.rpt` file containing the design rule check results from the time it was generated.

Run a fresh Design Rule Check (DRC) in KiCad before modifying, fabricating or using the PCB.

## PCB Manufacturing Files

The `gerber/` directory contains the PCB fabrication files generated from the KiCad PCB layout.

| File | Description |
|---|---|
| `F_Cu.gbr` | Front copper layer |
| `B_Cu.gbr` | Back copper layer |
| `F_Mask.gbr` | Front solder mask |
| `B_Mask.gbr` | Back solder mask |
| `F_Paste.gbr` | Front solder paste |
| `B_Paste.gbr` | Back solder paste |
| `F_Silkscreen.gbr` | Front silkscreen |
| `B_Silkscreen.gbr` | Back silkscreen |
| `Edge_Cuts.gbr` | PCB board outline |
| `PTH.drl` | Plated through-hole drill file |
| `NPTH.drl` | Non-plated through-hole drill file |
| `job.gbrjob` | Gerber job configuration |

### Manufacturing Considerations

Before submitting the PCB for fabrication:

1. Verify the schematic and PCB layout.
2. Run the latest Electrical Rules Check (ERC) and Design Rules Check (DRC).
3. Inspect component footprints, placement and routing.
4. Verify the board outline and dimensions.
5. Inspect the Gerber files using a Gerber viewer.
6. Confirm that the drill files and fabrication outputs correspond to the latest PCB revision.
7. Check the fabrication requirements of the selected PCB manufacturer.

**Note:** The included manufacturing files represent a saved design revision. Verify them before ordering a PCB, as they may not reflect subsequent design changes.

## Design References

This project was developed using publicly available technical documentation and component datasheets for learning and design reference.

### Datasheets

- [ESP-WROOM-32 Datasheet — Espressif](https://documentation.espressif.com/esp32-wroom-32_datasheet_en.pdf)
- [ESP32 Datasheet — Espressif](https://documentation.espressif.com/esp32_datasheet_en.pdf)

These documents provide technical specifications, electrical characteristics, pin information and other reference material relevant to the ESP32 platform.

Third-party documentation, designs, images and other materials retain their respective copyrights and licences.

## Design Status

**Current Status: Prototype**

The repository contains the KiCad project files, schematic, PCB layout, Gerber manufacturing outputs, DRC report, datasheet and design screenshots.

The project is intended for educational purposes, hardware experimentation and PCB design practice.

Further review and validation are required before fabrication or use in a production application.

## Licence

The licensing of this project is subject to the ownership and permissions applicable to its individual design contributions and included third-party materials.

The **CERN Open Hardware Licence Version 2 — Permissive (CERN-OHL-P-2.0)** is a potential licence for original hardware design contributions, provided the contributor has the necessary rights to distribute them under its terms.

Third-party materials, including any incorporated reference designs, schematics, PCB layouts, symbols, footprints, images and documentation, remain subject to their respective copyrights and licences.

Attribution alone does not grant permission to redistribute or relicense third-party material.

Refer to the `LICENSE` file, if included, for the applicable licence terms.

## Author

**Armaan**

Hardware prototyping, KiCad schematic design and PCB development.

## Disclaimer

This project is provided for educational, experimental and hardware prototyping purposes.

The design and associated manufacturing files are provided without a guarantee of fitness for a particular purpose.

Users should independently verify the circuit, component specifications, electrical characteristics, PCB layout, manufacturing outputs and safety requirements before fabrication or use.
