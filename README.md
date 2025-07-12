# Design2PCB ![Under Construction](https://img.shields.io/badge/status-under%20construction-orange)

## Overview
**🚧 Note: This project is currently under construction.** I'm in the process of adding new designs, refining existing ones, and updating documentation. Expect regular updates, and feel free to contribute or provide feedback!

![Alt Text](example.png)


Welcome to **Design2PCB**, a dynamic repository showcasing custom PCB designs and footprints. Our project elegantly blends detailed KiCad schematics and PCB layouts, originally designed with CAD modeling, and features unique footprints derived from Inkscape illustrations, converted for KiCad use. Dive into the seamless integration of mechanical CAD modeling and graphic design into the PCB design process, employing a powerful combination of FreeCAD, Inkscape, and KiCad.

## Installation and Requirements
Ensure you have the following software installed on your computer:
- **KiCad** (Version 8.0.0 or later)
- **FreeCAD** (Version 0.21.2 or later)
- **Inkscape** (Version 1.3.2 or later)

For installation instructions, please refer to the official websites of [KiCad](https://www.kicad.org/), [FreeCAD](https://www.freecadweb.org/), and [Inkscape](https://inkscape.org/).

## Usage Instructions

- #### KiCad Projects
Navigate to the `/KiCad_Projects` folder to access the KiCad schematics and PCB layout files. Use KiCad to open these files for viewing, editing, or extending the designs.

- #### FreeCAD Footprints
Find custom footprints designed in FreeCAD in the `/FreeCAD_Footprints` folder, ready to be imported into KiCad for your PCB designs.

- #### Inkscape Designs to KiCad Footprints
The `/Inkscape_Designs` folder contains the original SVG files created in Inkscape. Follow the conversion process outlined in the corresponding README to turn these designs into KiCad footprints.

## 🛠️ 3D-Printed Designs

### PRM-4720 Volume Knob — Concept ➜ Print ➜ Reality

| Stage | Preview |
|-------|---------|
| **1. Reference Part**<br>Original PRM-4720 knob used for reverse-engineering | ![PRM-4720 reference](Images/PRM-4720.jpg) |
| **2. CAD Model (FreeCAD)**<br>Parametric model with knurled grip, set-screw slot & indicator line | ![FreeCAD model](Images/freecad.png) |
| **3. Slicer Preview (ideaMaker)**<br>G-code inspection and infill check before printing | ![ideaMaker preview](Images/3d_printed.png) |
| **4. Finished Print**<br>PLA-plus, 0.16 mm layers, silk-black filament | ![Printed knob](Images/PRM-4720_3dPrinted.jpg) |

## License

This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Thank you for visiting Design2PCB!**
