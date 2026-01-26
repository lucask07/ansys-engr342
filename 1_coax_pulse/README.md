# Day 1 Introduction: Voltage pulse in a coaxial cable

## Open the simulation files 

Launch ANSYS Electronics Desktop: 

1. Windows Start Menu -> Ansys EM Suite 2025 R2 -> ANSYS Electronics Desktop 2025 R2
2. Copy the zip folder you downloaded from Canvas to your OneDrive
3. Extract the zip file to your OneDrive. Right click, *Extract All...* 
4. Open the coax_pulse.aedt project found in the zip folder you downloaded (ignore errors about it being created with a different version of ANSYS)

## Questions before running a simulation: 

1. Describe this circuit, think of the coaxial cables as wires in MultiSim.
2. What will happen?

## Now, run a transient simulation with a 3 V step from the function generator. 

1. Click the + button to the left of *coax_pulse* in the Project Manager.
2. Next, click the + button to the left of *Circuit1*
3. Right click *Analysis* and then left click *Analyze*  ![Alt text](docs/screenshots/analyze.png?raw=true "Analyze Screenshot")
4. Allow the simulation a few seconds to execute
5. Click the + button to the left of *Results* and then double lift click on *Transient Voltage Plot 1*

## Describe what you see
1. The voltage measured at the load trails the voltage at the driver. By how much? Why?
2. Your own observation #1
3. Your own observation #2
4. Others?

## Finally, change the cable length and re-run 
1. Double click on both cables and change the property *P* (the Physical length) to 10 mm.
2. Save the changes and re-run the simulation.
3. What changed? Why? 
