# RISC-V-Tapeout-
RISC V tapeout using sky water 130 nm tech lib


# 🚀 RISC-V SoC Design Journey

This repository documents my progress in designing a **System-on-Chip (SoC) based on the RISC-V architecture**. The repo captures learnings, implementations, and outputs from each stage of the design flow — from specification to tapeout.

---

## 📌 Objectives

* Understand the **end-to-end SoC design flow**.
* Build and verify a **RISC-V based processor core** with peripherals.
* Perform **RTL to GDSII flow** using open-source EDA tools.
* Document progress and results step by step.

---

## 🏗️ Design Flow Overview

1. **Chip Modeling (O1)**

   * Define system specifications.
   * Create a C-model and verify with testbenches.

2. **RTL Architecting (O2)**

   * Develop RTL (Verilog) for processor + peripherals.
   * Run functional verification.

3. **Synthesis & Netlist Generation**

   * Convert RTL → Gate-level netlist.
   * Add standard cells, macros (e.g., SRAM), and analog IPs.

4. **SoC Integration (O3)**

   * Integrate processor, peripherals, and IOs.
   * Floorplanning, placement, CTS, routing.

5. **Physical Design**

   * Run DRC & LVS checks.
   * Generate **final GDSII**.

6. **Tapeout**

   * Fabrication → Silicon chip.

---

## 📂 Repository Structure

```
.
├── docs/              # Notes, references, diagrams
├── rtl/               # RTL design files (Verilog)
├── tb/                # Testbenches
├── synthesis/         # Netlists, constraints
├── pd/                # Physical design outputs (DEF, GDSII, reports)
└── README.md          # Project overview
```

---

## 🧰 Tools & Technologies

* **HDL**: Verilog, SystemVerilog
* **Simulation**: Icarus Verilog / Verilator
* **Synthesis**: Yosys
* **Physical Design**: OpenLane, Magic, KLayout
* **PDK**: SkyWater 130nm

---

## 📅 Progress Tracking

* [ ] Chip Modeling (O1)
* [ ] RTL Design & Verification (O2)
* [ ] Synthesis
* [ ] SoC Integration (O3)
* [ ] Physical Design (RTL2GDS)
* [ ] DRC/LVS Sign-off
* [ ] Final Tapeout

---

## 📖 References

* [RISC-V ISA Specification](https://riscv.org/specifications/)
* [OpenLane Documentation](https://github.com/The-OpenROAD-Project/OpenLane)
* [SkyWater 130nm PDK](https://github.com/google/skywater-pdk)



**Sankararayanan V**
🎓 BE in VLSI Design & Technology | Enthusiast in SoC & Chip Fabrication
