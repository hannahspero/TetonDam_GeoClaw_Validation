# TetonDam_GeoClaw_Validation
## This repository links to the thesis work, "Validating GeoClaw for Simulating Teton Dam Failure by Comparison with HEC-RAS Results and Historical Observations" by Hannah Spero. ##
### Committee members: 
Dr. Donna Calhoun, Boise State Mathematics

Michael Schubert, HDR Engineering Inc.

Dr. Jim McNamara, Boise State Geosciences

## **Overview:** ## 

### Repository information: 
       (1) Metadata
       (2) Features
       (3) Plotting Lagrangian Particles
       (4)
       (5) Running the Simulation
###       
#### (1) Metadata (files available in repository) ####
       TetonLarge.topo sourced from: dds.cr.usgs.gov at 30 m resolution
       TetonLatLong.topo sourced from: dds.cr.usgs.gov at 10 m resolution
#### (2) Features ####
#### (3) Plotting Lagrangian particles ####
#### (4) Insert the information ####
#### (5) Running the simulation ####
##### Please reference Clawpack documentation for how to use the the GeoClaw Software to answer additional questions. 
##### General commands to run from a terminal window in Python or a WSL command line: #####
       (1) cd to the right directory depending on your file hierarchy
              (i) example: cd $clawpack/geoclaw/examples/tsunami/GeoClawPortAngelesWashington
       (2) $ make help (list of options)
       (3) $ make topo (calls on the topography for usage)
       (4) $ make data (uses setrun.py to make Fortrain input)
       (5) $ make exe (compiles the Fortran code)
       (5) $ make outputs (runs code and produces _output/ folder)
       (6) $ make plots (plots results in _plots/ folder)
       (7) $ make htmls (produces html verisons of files and README.txt)



