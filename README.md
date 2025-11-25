# P_DINESH_WEEK_8_RISC_V_SoC_Tapeout_Program_VSD
## Week 8 Task – Post-Layout STA & Timing Graphs Across PVT Corners for Routed VSDBabySoC

#Objective
To perform Post-Layout Static Timing Analysis (STA) using the SPEF generated after routing in Week 7, analyze timing across all PVT corners, and compare post-route results with post-synthesis timing data from Week 3.

1. Load Post-Route Design into OpenSTA
• Import:
  - Gate-level netlist
  - Library files for all PVT corners
  - Extracted SPEF file
  - Timing constraints (SDC)
  - Use the provided TCL script to run STA across multiple corners (TT, SS, FF, etc.).
