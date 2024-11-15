# Ex No: 04 Design-Implementation-of-6T---SRAM-Cell-using-Cadence-EDA-Tools
   
### Aim:
To design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools, simulate its functionality, and analyze key performance parameters such as read/write operations, power consumption, and stability to understand its behavior in memory design.

### Tools Required:
•	Personal Computer<br>
•	Cadence Virtuoso Software<br>

### S C H E M A T I C S I M U L A T I O N - PROCEDURE FOR CREATING THE SCHEMATIC SIMULATION -Commands to get into Cadence

1.	Right Click and open the terminal window<br>
2.	Type the following commands as follows and press enter.<br>
•	csh<br>
•	source /cadence/install/cshrc<br>
•	virtuoso <br>
### Procedure for Schematic simulation using Cadence

1.	Now two windows must open i) virtuoso/command interpreter window ii)”Whats New…”<br>
2.	Close the 2nd window<br>
3.	Use 1st window i.e virtuoso window (CIW) for further processing.<br>
i.	Create a New Library<br>
ii.	Create Schematic Cell view.<br>
iii.	Create the Symbol for schematic Cell view.<br>
iv.	Create the test Cell view.<br>
v.	Analog simulation by spectre<br>


### i)	Procedure for Creating New Library.
•	File –New – Library<br>
•	Name: Give name for ur library Ex: VLSILAB_EXP_1<br>
•	Enable Attach to an existing technology library, Click OK<br>
•	Attach the library to the technology library gpdk045.Click OK<br>
### ii)	Create Schematic Cell view.
•	Go to 1st window i.e virtuoso (CIW)<br>
•	File-New-Cell view<br>
•	Setup the new file form<br>
	Library: Select the one you created.<br>
	Cell: Give the experiment name Ex: Inverter ViewSchematic<br>
	Type: Schematic press OK<br>
•	Add the required components from the libraries and make the connections.<br>
	Go to instance fixed menu or use shortcut key “I” from keypad to go instances<br>
	Click on browse. This opens the library browser<br>
	Now select the appropriate library for components like <br>
	Gpdk45 ------------------------nmos1v, pmos1v<br>
	Create Input and Output pins<br>
	Make the connections by using fixed narrow wire key<br>
	Click Check and Save button<br>
![WhatsApp Image 2024-11-14 at 13 58 13](https://github.com/user-attachments/assets/bd2012e1-6d8d-4fd6-ada9-901fe6b6d011)



 
### iii)	Creating the Symbol for schematic Cell view

•	In the schematic window, execute <br>
	Create – Cell view – From Cell view<br>
	The cell view from cell view window appears<br>
	Check Lib Name, Cell Name, From View name must be schematic Press ok<br>
•	Now Symbol generation form appears. Click Ok If No changes required<br>
•	A new window with with default symbol is created.<br>
•	Edit the symbol if you want to give actual symbol shape else continue.<br>
•	Execute Create-Cell view-from cell view<br>
•	Library Name and Cell Name must be same which you have used for schematic. Press OK<br>
•	Check for the position of pin side.Prss OK<br>
•	Edit for the shape by Create-Shape-Choose required options to edit.<br>

### Analog simulation by SPECTRE.
•	In test cell view window<br>
•	Launch – ADE L(Analog Design Environment)<br>
	Execute Setup—Simulation/directory/Host A new window opens<br>
	Set the simulation window to spectre and click ok<br>
	Execute Analysis – Choose. A window opens.<br>
	Select the type and set the specifications and press OK<br>
	Execute Output s—to be plotted – Select on Schematic<br>
	Then Select the INPUT WIRE(Vin ) and OUTPUT WIRE(Vout) from your test Schematic using mouse<br>
•	Execute Simulation -- Net list and Run<br>
![WhatsApp Image 2024-11-14 at 13 58 14](https://github.com/user-attachments/assets/4bec1638-c9fe-48c5-b5d3-f1cdb0f54040)


For Transient Analysis Settings and Output<br>


![WhatsApp Image 2024-11-14 at 13 58 12](https://github.com/user-attachments/assets/0ffda40e-3cd3-44e5-9f5b-8b45ba66feb9)

![WhatsApp Image 2024-11-14 at 13 58 14 (1)](https://github.com/user-attachments/assets/f7eba207-b9b7-40e0-bb85-17fc2636f33f)


### Results:
The design and implementation of the 6T SRAM cell using Cadence EDA tools were successfully achieved. Simulation results validated the correct functionality and performance of the SRAM cell, including stable read/write operations,










