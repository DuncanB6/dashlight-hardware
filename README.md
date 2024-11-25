# PCB Design for Dashlight Project

This repository includes files used in the design and build of a PCB for the Dashlight project. Find more information about the project at https://github.com/DuncanB6/dashlight-firmware.

## Overview

This PCB houses a PCI32 microcontroller and the hardware necessary for interface with a 7 segment LED as well as several peripherals. Also includes a RTCC for timekeeping. It's a simple 2 layer PCB equiped with test points, JTAG connectors, and supporting components for the microcontroller. All components are through hole.

---

## Version 1

### Schematic

![Version 1 Schematic](path_to_version_1_schematic_image.png)

Version 1 is designed with [describe design goals for Version 1, e.g., low power, compact form factor]. It uses components such as [list key components], which are carefully selected to balance performance and cost.

### PCB Layout

![Version 1 PCB Layout](path_to_version_1_pcb_image.png)

The PCB layout for Version 1 features [describe layout features, e.g., minimal routing, compact size, etc.]. The board is optimized for easy manufacturing and soldering, with clear silkscreen markings for all components.

---

## Design Files

The design files for both versions are available in the following formats:

- **Schematic**: `.sch` (Schematics for both versions)
- **PCB Layout**: `.brd` (PCB layout files for both versions)
- **Gerber Files**: `.zip` (Gerber files for manufacturing)
- **Bill of Materials (BOM)**: `.csv` (List of components used in both versions)

You can download the design files from the following link:

[Download Design Files](#link-to-design-files)

---

## How to Use

1. **Schematic and PCB Design**: Open the provided `.sch` and `.brd` files in your preferred PCB design software (e.g., KiCad, Eagle).
2. **Manufacturing**: If you plan to manufacture the PCB, you can use the Gerber files and BOM to order the PCB and components from any PCB manufacturer.
3. **Assembly**: Follow the silkscreen markings on the PCB for component placement. Make sure to follow the recommended soldering guidelines for each component.
4. **Testing**: After assembly, use a multimeter to check for shorts or open circuits before powering on the board. Follow the testing procedure outlined in the documentation.

---

## License

This project is licensed under the [MIT License](LICENSE), which allows for modification and redistribution. Please see the LICENSE file for more details.

---

## Acknowledgements

- Special thanks to [mention contributors, libraries, tools, or resources used].
- Thanks to [mention any mentors, collaborators, etc.].

