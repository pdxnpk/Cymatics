# Cymatics

Integrated PCBs for AudioLux and Vibrosonics

# Development

Install KiCad (version 8.0 or higher): https://www.kicad.org/download/

Open KiCad project file (Cymatics/Cymatics.kicad_pro)

# Build a PCB

## Order PCB

Go to JLCPCB (https://jlcpcb.com/) or PCBWay (https://www.pcbway.com/) to order a PCB

Start an order for a 2-layer PCB (Standard)

Add zip file of Gerber and Drill files (Fabrication/Cymatics_Gerber_Drill_03-21-25.zip)

Default specifications and options are OK

## Parts and Assembly

You may choose to have the PCB manufacturer assemble the boards for you, or you may order the parts separately and assemble the board on your own.

### Order PCB assembly

Provide the BOM and CPL (component placement list, or Centroid) for the manufacturer when requesting PCB assembly.

- Fabrication/Fabrication-BOM.xlsx: BOM adhering to PCBWay format (may need to revise for other manufacturers)

- Fabrication/Fabrication-CPL.csv: CPL or Centroid

### Order components separately

Open bill of materials (BOM.csv) to find links to order parts

Go to DigiKey (https://www.digikey.com/) and order listed part quanities

# Program the Microcontroller

To program the ESP32 with AudioLux and/or VibroSonics software, refer to their respective GitHub repositories.

- AudioLux software: https://github.com/OPEnSLab-OSU/Nanolux

- VibroSonics software: https://github.com/udellc/Vibrosonics

