# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools
JAYA VISHAL M 
212223060102
## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. Schematic of Full Custom 2:1 MUX
![3e94m7r5](https://github.com/user-attachments/assets/60fe4f1d-46b8-43c1-ac70-7e4e750bf927)


### 2. Transient Response Setup
![e3xwraac](https://github.com/user-attachments/assets/03d7d3e0-6abe-435d-a640-cbb64c541e86)
![rn1cndv5](https://github.com/user-attachments/assets/3259dfd6-8e00-42fb-ae5f-71e80625e1b7)



## Output

### 1. Transient Analysis Output
![aedrc4lq](https://github.com/user-attachments/assets/79eb5016-9b50-4be5-a514-e0cd08c5f292)


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
