# PnR-Flow-Digital-Tx-System
Complete RTL-to-GDSII physical design flow for a Digital Transmitter system using Synopsys tools (Design Compiler, ICC2, StarRC, PrimeTime). Includes synthesis, floorplanning, placement, CTS, routing, extraction, and STA. Three flows evaluated for area, timing, and power to study PPA trade-offs in real ASIC implementation.
## 🚀 Project Overview

This project implements a complete **RTL-to-GDSII flow** for a **Digital Transmitter (Tx) System** using **Synopsys EDA tools**. The goal is to take the design through all physical design stages and evaluate three constraint-driven optimization strategies focused on **area, timing, and power**.

---

## 🎯 Project Objectives

### ✅ Build a full ASIC physical design flow from RTL to GDSII
Covering:
- RTL import & constraint setup  
- Synthesis  
- Floorplanning  
- Placement  
- Clock Tree Synthesis (CTS)  
- Routing  
- Parasitic extraction  
- Timing & power sign-off  
- GDSII generation  

### ✅ Run three independent synthesis + PnR optimization flows
- **Area-driven flow**
- **Timing-driven flow**
- **Power-driven flow**

---

## 📊 Evaluation Metrics

- 📏 **Chip area utilization**
- ⏱️ **Timing closure (WNS/TNS)**
- ⚡ **Total power** (dynamic + leakage)

The results are analyzed to highlight **PPA trade-offs** and illustrate how constraint-driven physical design decisions affect final silicon performance.

---

## 🛠️ Toolchain Used

| Stage | Tool | Purpose |
|-------|------|--------|
| Synthesis | Synopsys Design Compiler | RTL → Gate netlist |
| Place & Route | Synopsys ICC2 | Full physical implementation |
| Extraction | Synopsys StarRC | SPEF generation |
| STA & Power | Synopsys PrimeTime | Sign-off timing & power |

---

## 📂 Deliverables

- Synthesis reports (area, power, timing)
- CTS & routing reports
- SPEF & SDF
- Final GDSII & DEF
- PPA comparison table

---

*All design and flow scripts are developed by the author using Synopsys tools for academic research and skill development.*
