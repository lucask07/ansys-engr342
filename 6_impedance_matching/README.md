# Impedance Matching: L-Match and Broadband versus Narrowband Lambda/4

## Open the simulation files 

Launch ANSYS Electronics Desktop: 

1. Windows Start Menu -> Ansys EM Suite 2021 R1 -> ANSYS Electronics Desktop 2021
2. Copy the zip folder you downloaded from Canvas to a folder on your OneDrive
3. Extract the zip file to your OneDrive. Right click, *Extract All...* 
4. Open the l_match.aedt project found in the zip folder you downloaded (ignore errors about being created with a different version of ANSYS)
5. If you need to save the file you must save it to a different folder within your OneDrive. This is bizarre...

## Questions before running the L-match simulation (RL = 200 Ohms): 

0. Open l_match.aedt 
1. What does S11 quantify? 
2. Sketch this matching circuit on a Smith Chart
3. Is this circuit an inverted or normal-L? 
4. What does S21 quantify?

## Now, run the L-match simulation 

1. Inspect the S11. At what frequency is the match best? 
2. Calculate the L and C values given the impedances from the L-match calculations and the center frequency found by simulation. Do your calculations match the L and C values on the simulation schematic?
3. Decrease the value of C by x2 and decrease the value of L by x2. Now where is the center frequency? 


## Open Narrow_Lambda/4.  

1. Here we will match a 50 Ohm source to a 10 Ohm load.
2. Click on the transmission line closest to the load port. Then click 'TRL' -> 'Analysis' -> 'Details'. What is the length of the line in degrees (at 1 GHz) [click 'Analysis' and read the value in the box 'E']? 
3. Run the simulation 'Analysis' -> 'Analyze'
4. Inspect the S11 plot
5. Inspect the S21 plot


## Open Broadband_Lambda/4.  

1. Here we will match a 50 Ohm source to a 10 Ohm load using 3 elements to gradually step the impedance increase the bandwidth of the match.
2. What is the Z0 of each element? 
3. Run the simulation 'Analysis' -> 'Analyze'
4. Inspect the S11 plot
5. Inspect the S21 plot
6. Compare the S21 of the broadband lambda/4 versus the narrowband lambda/4. 
