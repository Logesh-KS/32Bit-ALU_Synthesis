# EXPT 5: 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :
![WhatsApp Image 2024-11-21 at 18 41 20_5dbf53bb](https://github.com/user-attachments/assets/dd059a0d-aff6-4d52-9108-ecc7cfadf0f0)

#### Area report:
![WhatsApp Image 2024-11-21 at 18 41 21_95f7dcbb](https://github.com/user-attachments/assets/8b0a595b-e8d0-4d80-a98d-f282a5236943)

#### Power Report:
![WhatsApp Image 2024-11-21 at 18 41 25_f3daabd0](https://github.com/user-attachments/assets/496de098-7b91-4680-a290-60295fa437e4)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
