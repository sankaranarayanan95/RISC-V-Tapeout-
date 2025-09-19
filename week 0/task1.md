# DIGITAL VLSI SoC DESIGN AND PLANNING  

---

## Task-1: SoC Design Flow Summary  

The video explained the SoC design workflow, moving from specification to silicon.  

---

### 🔹 Workflow Steps  

1. **Chip Modelling (O1)**  
   - Specifications are written in C model.  
   - Testbenches are developed in C for functional validation.  

2. **RTL Architecture (O2)**  
   - Hardware is described in RTL (Verilog).  
   - Components include the Processor and Peripherals/IPs.  

3. **Synthesis & Netlist Generation**  
   - RTL is converted into Gate-Level Netlist.  
   - Integration of Macros (synthesized RTL) and Analog IPs (functional RTL).  

4. **SoC Integration (O3)**  
   - All blocks are combined (Processor, IPs, Macros, Analog IPs).  
   - Integration also involves GPIOs and interconnects.  

5. **Physical Design (RTL2GDS)**  
   - Steps: Floorplanning → Placement → CTS (Clock Tree Synthesis) → Routing.  
   - Output: GDSII file.  

6. **Final Verification & Fabrication**  
   - DRC/LVS checks ensure design correctness.  
   - GDSII is sent for fabrication to produce the final chip.  

---

### 🔹 Key Notes  

- Macros and Analog IPs can be hard macros (HM).  
- Processors are usually soft logic, but sometimes delivered as HM.
- The key outputs :
- O1: Specs in C (with testbench).  
- O2: RTL in Verilog.  
- O3: Integrated SoC (netlist + macros).  
- **O1 == O2 == O3**  

---
