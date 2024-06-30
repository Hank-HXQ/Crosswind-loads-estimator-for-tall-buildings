# Crosswind-loads-estimator-for-tall-buildings
We developed a tool for rapid and accurate evaluation of crosswind loads on tall buildings.
This tool is an ANN-based model driven by a comprehensive aerodynamic database of tall buildings. The database is established by high-fidelity datasets from both wind tunnel tests and large-eddy simulations (LES), covering extensive building dimensions in three typical boundary layer wind fields.
Specifically, this tool is applicable to rectangular tall buildings with a side ratio (D/B) from 0.5 to 2 and a height from 150 m to 250 m.
# About the installation
The tool is compiled within MATLAB R2022b using MATLAB Compiler. The MATLAB Runtime (MCR) does not require a MATLAB license and can be used to run the MATLAB compiled program on computers which do not have MATLAB installed. 
1. for_redistribution folder: contains the files used to install the application and MATLAB Runtime.
2. for_redistribution_files_only folder: contains the files needed for redistribution of the application. These files can be distributed to the computers of users who have MATLAB Runtime. 
# About the input variables in the user interface
B\D\H are the building width\depth\height, respectively.
f0\ζ\ρ are the fundamental frequency\damping ratio\bulk density.
w0 is the basic wind pressure (10 minutes-averaged at 10 meters-height) from Chinese load code GB 50009-2012.
![image](https://github.com/Hank-HXQ/Crosswind-loads-estimator-for-tall-buildings/assets/88885046/fb53ab1a-6e1f-453f-91ac-a148e943ac3e)
# Wind profiles information
Terrain categories BL1\BL2\BL3 refer to three typical boundary layer wind fields. The mean velocity and turbulence intensity profiles are provided below.
![BCD剖面](https://github.com/Hank-HXQ/Crosswind-loads-estimator-for-tall-buildings/assets/88885046/117128fb-ae8f-44fd-8636-062720ffe7eb)

