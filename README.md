# RISC-V-SoC-TAPEOUT_OPENROAD

# OpenROAD RTL-to-GDSII Flow

OpenROAD is an open-source, fully automated RTL-to-GDSII flow for digital IC design. It supports synthesis, floorplanning, placement, clock tree synthesis, routing, and final layout generation. Below is a summary of each design stage:

## 1. RTL Synthesis
- Converts RTL code (Verilog/VHDL) into a gate-level netlist.
- Optimizes logic for area, speed, and power.
- Produces a technology-mapped netlist ready for physical design.

## 2. Floorplanning
- Defines the chip’s physical boundaries, core area, and placement regions.
- Determines approximate positions for standard cells, macros, and I/O pins.
- Optimizes for power, routing congestion, and timing considerations.

## 3. Placement
- Assigns exact locations to all standard cells within the floorplan.
- Minimizes wirelength, congestion, and timing violations.
- Prepares the design for clock tree synthesis and routing.

## 4. Clock Tree Synthesis (CTS)
- Designs the clock network to deliver low-skew, balanced clock signals.
- Inserts buffers and clock trees while meeting timing constraints.
- Ensures reliable operation at the target frequency.

## 5. Routing
- Connects all placed cells using metal layers according to the netlist.
- Resolves congestion and meets design rules (DRC-compliant).
- Produces a fully connected, manufacturable layout.

## 6. Final Layout / GDSII Generation
- Verifies design rules (DRC) and electrical rules (LVS) on the final layout.
- Produces GDSII, the standard file format for fabrication.
- Ready for tape-out and manufacturing.
