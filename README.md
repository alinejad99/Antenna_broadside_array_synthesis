# Antenna_broadside_array_synthesis

Broadside Array Synthesis
This repository contains a project for the synthesis and analysis of a one-dimensional broadside array with 10 half-wave dipole elements. The main objective is to achieve a radiation pattern where the main lobe is directed perpendicular to the plane of the antennas.

Array Configuration
One-dimensional array with 10 elements.
Half-wave dipoles placed parallel to the ground.
Array axis in the x-direction.
Dipoles are parallel with the z-axis.
Design frequency: ab * 10^6 Hz, where "ab" is the two last digits of my student number which was 31
Synthesis Steps
a. Excitation Amplitude Selection
Choose an appropriate form of excitation amplitude that optimizes the array performance.
b. Grating Lobe Elimination
Perform a simple optimization using MATLAB to find the maximum distance between elements that eliminates grating lobes.
c. Phase Adjustment for Broadside Pattern
Use the selected excitation amplitude from step (a) to determine the phase of each element to achieve a broadside pattern with φ = 90°.
d. Array Factor Plot
Plot the array factor using MATLAB to visualize the radiation pattern and verify the broadside pattern obtained in step (c).
e. Element-Factor Analysis in CST or HFSS
Use CST or HFSS (Computer Simulation Technology) to analyze the element-factor of the dipoles in both the E-plane and H-plane, considering the ground effect.
f. Null Steering
Modify the synthesis properties in MATLAB to introduce a null in the radiation pattern at φ = 75°.
Plot the modified radiation pattern using MATLAB.
g. Full-Wave Simulation in CST
Perform a full-wave simulation in CST to validate the results obtained in step (e) regarding the element-factor and ground effect.
h. Literature Review
Conduct a literature search to find any recent ideas or techniques for improving the performance of broadside arrays. Summarize any relevant findings from the literature.
Feel free to explore and adapt the provided code and simulation tools to achieve the desired broadside array pattern and validate your results. Enjoy working on the broadside array synthesis project!
