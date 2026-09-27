
# ESP-WROOM-32 KiCad Prototype

A PCB design project based on the ESP-WROOM-32 module, developed using KiCad. This repository contains the circuit schematic, PCB layout, Gerber manufacturing files, design screenshots, datasheets and supporting documentation.

The project was developed as a hardware prototyping and learning exercise, using technical datasheets and educational references.

## Project Overview

| Parameter | Details |
|---|---|
| Project Name | ESP-WROOM-32 KiCad Prototype |
| Microcontroller Module | ESP-WROOM-32 |
| Design Software | KiCad |
| Project Type | Hardware / PCB Design |
| Design Stage | Prototype |
| Repository | ESP-WROOM-32 KiCad Prototype |
| Hardware Licence | CERN-OHL-P-2.0 |

## Repository Structure

```text
esp-wroom-32/
│
├── esp_wroom_32.kicad_pro
├── esp_wroom_32.kicad_sch
├── esp_wroom_32.kicad_pcb
│
├── ESP-WROOM-32.PDF
├── DRC.rpt
│
├── gerber/
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
├── images/
│   └── *.png
│
├── README.md
└── LICENSE
```

## Hardware Design

The project is based on the ESP-WROOM-32 module, which incorporates Wi-Fi and Bluetooth connectivity.

The KiCad project includes:

- **Schematic:** Circuit design and electrical connections.
- **PCB layout:** Component placement, copper routing and board design.
- **Gerber files:** PCB fabrication outputs.
- **DRC report:** Design rule check results.
- **Datasheet:** Technical reference for the ESP-WROOM-32 module.
- **Images:** Screenshots documenting the design process.

Refer to the schematic and PCB files for the actual circuit implementation and board layout.

## Tools and Software

- [KiCad](https://www.kicad.org/) — Schematic capture and PCB design.
- [Git](https://git-scm.com/) — Version control.
- [GitHub](https://github.com/) — Source and hardware design hosting.

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/arm-n/esp-wroom-32-kicad.git
```

### 2. Open the KiCad Project

1. Install and launch KiCad.
2. Open the project manager.
3. Select **File → Open Project**.
4. Navigate to the cloned repository.
5. Open `esp_wroom_32.kicad_pro`.

### 3. Explore the Design

Open the schematic editor to inspect the circuit and electrical connections.

Open the PCB editor to examine component placement, copper routing, board outline and design rules.

The included `DRC.rpt` provides a record of the design rule check at the time it was generated. Run a fresh DRC check after making modifications.

## PCB Manufacturing Files

The `gerber/` directory contains the PCB fabrication outputs.

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

**Manufacturing note:** Verify the schematic, PCB layout, DRC results, Gerber layers, drill files and board dimensions before ordering a PCB. Ensure that the manufacturing files correspond to the latest PCB revision.

## Design References and Acknowledgements

This project was developed with the help of educational resources, technical documentation and component datasheets.

### Datasheets

- [ESP-WROOM-32 Datasheet — Espressif](https://documentation.espressif.com/esp32-wroom-32_datasheet_en.pdf)
- [ESP32 Datasheet — Espressif](https://documentation.espressif.com/esp32_datasheet_en.pdf)


## Design Status

**Current Status: Prototype**

This repository contains the KiCad project files, PCB fabrication outputs, datasheet, DRC report and design screenshots.

The design should be reviewed and validated before fabrication or use in a production application.

## Licence

The original hardware design contributions in this repository are intended to be licensed under the **CERN Open Hardware Licence Version 2 — Permissive (CERN-OHL-P-2.0)**.

See the [LICENSE](LICENSE) file for the complete licence terms.

The licence applies only to material that the project contributor has the right to license. Third-party materials, including any incorporated reference designs, symbols, footprints, images or documentation, retain their respective copyrights and licensing terms.

Attribution does not replace permission where permission is required.

## Author

**Armaan**

Hardware design and KiCad prototyping.

## Disclaimer

This repository is shared for educational, development and hardware prototyping purposes. Users should independently verify the design, component specifications, electrical safety and manufacturing outputs before building or using the hardware.
