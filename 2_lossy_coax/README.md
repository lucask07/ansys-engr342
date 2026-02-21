# Day 3 lossy cable: Coaxial cable attenuation

## Open the simulation files 

Launch ANSYS Electronics Desktop: 

1. Windows Start Menu -> Ansys EM Suite 19.2 -> ANSYS Electronics Desktop 2018.2
2. Copy the zip folder you downloaded from Canvas to a folder on your OneDrive
3. Extract the zip file to your OneDrive. Right click, *Extract All...* 
4. Open the lossy_coax.aedt project found in the zip folder you downloaded (ignore errors about being created with a different version of ANSYS)
5. If you need to save the file you must save it to a different folder within your OneDrive. This is bizarre and I'm working with Tech Support to understand what is going on...

## A description of the simulation: 

1. The source on the left is now a sinusoidal generator with 1 V amplitude
2. We will be investigating how the signal is attenuated as it travels down the line 

## Run transient simulations at 0.1 GHz, 1 GHz, and 10 GHz

1. For each simulation record the frequency and peak-to-peak voltage at the driver, midpoint, and load. Create 1 row for each frequency. Use Excel so you can do a few quick calculations afterwards.

The attenuation in dB/m is given as: 

Att = C1 \* sqrt(f_{GHz}) + C2 \* f_{GHz}

Where C1 is the conductor loss coefficent and C2 is the dielectic loss coefficent. 

Click on the coax to check the properties: in these simulations C1 = 0.4, C2 = 0.0

Use this equation to calculate the signal attenuation in the Excel spreadsheet. How close is the calculation to the simulated values? Upload your excel spreadsheet to Canvas. 
