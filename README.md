# CMOS 2-Input NOR Gate Project

## Overview
This project involves designing, simulating, and analysis of a **CMOS 2-Input NOR Gate** using **Cadence Virtuoso**. The NOR gate is a fundamental digital logic gate that outputs a high signal only when both inputs are low, making it essential in combinational logic circuits.

## Software & Tools Used
- **Cadence Virtuoso** (for schematic capture, layout, and simulation)
- **Assura** (for DRC and LVS verification)
- **Analog Design Environment (ADE)** (for waveform analysis)

## Project Workflow
### Schematic Design
- Designed using **Virtuoso Schematic Editor**.
- Includes **four MOSFETs** (2 PMOS & 2 NMOS) arranged in a pull-up and pull-down network.
- Verified through **Transient analysis**.

### Layout Design
- Created using **Virtuoso Layout Editor**.
- Optimized for **area efficiency** and minimal parasitics.
- Design Rule Check (**DRC**) performed for layout validation.

### Layout Versus Schematic (LVS) Check
- Ensured the layout matches the schematic using **LVS**.

### Parasitic Extraction & Post-Layout Simulation
- Extracted layout using **Assura**.
- Post-layout simulation performed to analyze parasitic effects.

## Technical Specifications
- **Technology Node**: 90nm (as per design constraints)
- **Supply Voltage (VDD)**: 1V
- **Logic Operation**: NOR (Y = NOT(A + B))

## Results & Observations
- **Schematic Simulation**: Verified correct NOR logic functionality.
- **Layout Optimization**: Ensured minimal area and **DRC compliance**.
- **Post-Layout Simulation**: Observed deviations due to parasitic capacitance and resistance.

## Testing
- A separate **test folder** has already been created for verification and simulation.

## Reference Images
- **2_Input_NOR_Schematic**
  
  ![Nor_Schematic](https://github.com/user-attachments/assets/19a8faf0-1883-450e-b3d1-a5e7e4675fb9)

- **2_Input_NOR_Test**
  
  ![Nor_Test](https://github.com/user-attachments/assets/8ee6ffa0-3558-4344-a98e-a45fc44082e2)

- **2_Input_NOR_Layout**
  
![Nor_Layout](https://github.com/user-attachments/assets/54fb8da7-3c62-49cd-83aa-bfdc44fbf30f)

- **2_Input_NOR_AV_Extracted**
  
![Nor_AV_Extracted](https://github.com/user-attachments/assets/e1eaa867-caae-476c-92f5-e9773251f71e)

---
*This project is developed for educational and research purposes.*

