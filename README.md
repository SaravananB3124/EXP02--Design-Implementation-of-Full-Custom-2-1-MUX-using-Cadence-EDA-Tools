## Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

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

### 1. 2:1 MUX USING CMOS
!![IMG-20250503-WA0006](https://github.com/user-attachments/assets/7300f680-5b35-4135-ae17-7557fbf3a217)



### 2. Schematic of Full Custom 2:1 MUX
![IMG-20250503-WA0007](https://github.com/user-attachments/assets/7262deca-d7d5-4417-b05d-e6a9e2d10e26)



### 3. Transient Response Setup

![IMG-20250503-WA0008](https://github.com/user-attachments/assets/39e0f0d6-a57a-4523-b6c4-32ec51204637)



![IMG-20250503-WA0009](https://github.com/user-attachments/assets/f5f34001-140f-45c9-9054-5998e15a2a0d)

## Output

### 1. Transient Analysis Output
![IMG-20250503-WA0010](https://github.com/user-attachments/assets/46ee2d55-91d0-4161-9f4b-738b1a1347f3)


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
