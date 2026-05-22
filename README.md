# Soc_design_-_Planning
VSD- OpenLane Sky130
# SoC Design and Implementation using OpenLANE & Sky130 PDK
This repository captures my exploration of System-on-Chip (SoC) design and physical implementation using open-source EDA tools.
It documents the complete RTL-to-GDSII flow, practical experiments, and insights gained through the VSD open-source silicon initiative.

I have learnt how the modern chip design can be achieved using accessible, open-source frameworks
# Understanding the Foundation of Open Silicon
When observing a chip mounted on a PCB, what we see is the package, not the silicon itself.
The die resides inside, connected to the external devices through pads and bond wires.

Traditional ASIC design demanded:

Costly proprietary EDA tools

Restricted PDKs under NDA

Limited academic accessibility
# Tools and Frameworks
OpenLANE – End-to-end ASIC flow automation

Sky130 PDK – Open-source process design kit

Magic VLSI – Layout visualization and editing

KLayout – GDSII inspection and verification

Yosys – Logic synthesis engine
The collaboration between Google and SkyWater Technologies introduced Sky130, the first open-source PDK, enabling anyone to design and fabricate chips without licensing barriers.
| Stage | Objective | Toolchain |
| --- | --- | --- |
| **RTL Design** | Develop Verilog modules | Custom RTL / PicoRV32 |
| **Synthesis** | Convert RTL to gate-level netlist | Yosys |
| **Floorplanning** | Define chip area, power grid, and IO placement | OpenLANE |
| **Placement** | Optimize standard cell positions | OpenLANE |


# Attachements of Work Done
<img width="1870" height="866" alt="Screenshot (81)" src="https://github.com/user-attachments/assets/104ab1a7-1617-497b-8169-37f84792cdc0" />

This image shows the "deployment of openlane" , "preparing the picorv32a design" and with the steps of "synthesis and floorplan"

<img width="1733" height="843" alt="Screenshot 2026-05-22 225933" src="https://github.com/user-attachments/assets/07b73731-fbed-439e-a81e-e20962f4945f" />

The "Placement" step followed by synthesis and floorplan

<img width="1583" height="908" alt="Screenshot 2026-05-22 221209" src="https://github.com/user-attachments/assets/81bb4f9a-8f26-4421-95fd-ee4811c9f9d3" />

The detailed table view of the Design- picorv32a by taking a look onto the config.tcl file using the command "less config.tcl"

<img width="1476" height="901" alt="Screenshot 2026-05-22 222412" src="https://github.com/user-attachments/assets/ec5b4d1b-a7d5-4875-98a5-461aa0e9ee3e" />

Layout of picorv32a - floorplan def in magic

<img width="1920" height="1080" alt="Screenshot (77)" src="https://github.com/user-attachments/assets/49e22472-45b4-46be-9654-747e2171ba5c" />

Inverter layout in magic
