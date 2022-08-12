# 6DOF-Parallel-Manipulator-Simulation-in-SimMechanics
This is a Multi-Body simulation of 6 degrees of freedom parallel manipulator. Actuator control signals are given to the linear actuators to create a desired output motion of the end manipulator i.e. upper plate. This simulation can be easily used to check for the type of control signal required to create a particular motion of parallel manipulator prior to hardware implementation. It can also be used to decide the hardware specification of actuators for any particular application.
Before running the simulink file, following steps needed to be ensured:
  1. Download the CAD files along with the simulink file.
  2. Open simulink file in Matlab2020 and then go to each and every 'Solid File' in Simulink. 
  3. For each Solid File, check the File Name. Select the cad file (which you've downloaded) corresponding to the name given in 'File Name' of that Solid File. e.g. If File Name is F1.SAT, choose F1.SAT from the downloaded CAD files, if File Name is F4_S.SAT, choose the corresponding file from the downloaded CAD files, and so on. Do this for each and every Solid File. 
  4. After updating File Name for each and every Solid File, press on Simulink RUN button, to run a pre-specified motion.
To run your own motion, change the inputs to the 'IK; MATLAB FUNCTION Block.
![Mechanics Explorers - Mechanics Explorer-Corrected 2022-08-12 09-09-51 (online-video-cutter com)](https://user-images.githubusercontent.com/72562461/184288298-9e11bc08-5d21-4dd9-bebb-fc4839482cdd.gif)
