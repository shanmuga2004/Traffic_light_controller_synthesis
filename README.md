# EXP-6 Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.
![386830919-aaa659e8-c2a2-4be3-aa5e-f20ca8efdb6d](https://github.com/user-attachments/assets/4f7c6995-921b-470f-a9ee-2bf875999d0a)

Synthesis RTL Schematic :

![386831050-ce5b5961-0392-49d6-a6fd-d139b6fc8c81](https://github.com/user-attachments/assets/dced9c6c-c55c-436b-a338-1c851c9e79ee)

Area report:

![386831083-4483ca13-2a96-4a32-95f0-1a70acf6f5e4](https://github.com/user-attachments/assets/99a87492-0860-491c-8644-e7d7496eefc4)

Power Report:

Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
