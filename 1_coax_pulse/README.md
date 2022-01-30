# Day 1 Introduction: Voltage pulse in a coaxial cable

## Open the simulation files 

Launch ANSYS Electronics Desktop: 

0. Setup your Microsoft OneDrive on the VM
1. Windows Start Menu -> Ansys EM Suite 19.2 -> ANSYS Electronics Desktop 2018.2
2. Copy the zip folder you downloaded from Canvas to your OneDrive
3. Extract the zip file to your OneDrive. Right click, *Extract All...* 
4. Open the coax_pulse.aedt project found in the zip folder you downloaded (ignore errors about being created with a different version of ANSYS)
5. If you need to save the file you must save it to a different folder. This is bizarre and I'm working with Tech Support to understand what is going on...

## Questions before running a simulation: 

1. Describe this circuit, think of the coaxial cables as wires in MultiSim.
2. What will happen?


## Now, run a transient simulation with a 3 V step from the function generator. 

1. Click the + button to the left of *coax_pulse* in the Project Manager.
2. Next, click the + button to the left of *Circuit1*
3. Right click *Analysis* and then left click *Analyze*  ![Alt text](docs/screenshots/analyze.png?raw=true "Analyze Screenshot")
4. Allow the simulation a few seconds to execute
5. Click the + button to the left of *Results* and then double lift click on *Transient Voltage Plot 1*

## OK, now describe what you see! 
1. Observation one
2. Observation two 
3. Others?


## Finally, change the cable length and re-run 
1. Double click on both cables and change the property *P* (the Physical length) to 10 mm. (saving the changes will fail unless you 'Save As' to a new folder. However, you can re-run the simulation without saving)
2. Re-run the simulation. What changed? Why? 
