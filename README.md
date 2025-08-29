# Quadruped_Project
My attempt at building the NovaSM3 by Chris Locke. This is a recreation of Spot from Boston Dynamics. This repository contains stl files that I created on my own along with progress pictures towards the build and code for arduino. This project is not yet complete. 

To view uploaded stl files, simply click on each file for a preview of the 3D model. These files are available for download to be used for 3D printing. The step files are not currently available on this repository. Converting the stl files to a mesh in Autodesk Fusion will likely create too many faces to convert to a solid model and meshmixer will improperly adjust the tolerances. 

See https://novaspotmicro.com/ for credit to the NovaSM3. 

UPDATES BELOW (in ascending chronological order): 
- All 3D parts have been printed and parts sourced. 
  Slots for M3 nuts were the incorrect size and needed to be widened to fit the hardware. (reminder for updating the step files)
  The frame and legs have been assembled with servos installed. 
  35kg servos were placed in the tibia because it will need more torque to lift the body and be able to stand. 
![Quadruped_Frame_Assembled](https://github.com/user-attachments/assets/31a06d35-3dda-4e32-92d0-ba1e593fc390)

- Added first step file to test. Dimensions were slightly off so I will need to rework it. 

- Added custom stl files for both right and left leg covers (not pictured in my first 3D print). 
  I changed the tolerance to nominal (+0.2mm) for M3 screws because the 3D printed prototype was cracking after inserting components. 
  Future files will be in stl format so you can preview it directly in the git repository. I will be changing the previous files.

- Uploaded new head cover file which is likely the most complicated component in the project. 

- Created and uploaded both the front and rear base cover components. The rear is longer. Also moved all stl files into a folder.
