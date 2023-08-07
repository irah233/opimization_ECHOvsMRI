#Reorganization of Pressure Volume Loop and Strain Graphing from HeArt Project 

Simulator of mechanics in the heart based on [FEniCS](https://fenicsproject.org/) library.

<!-- TOC -->
  - [Installation and Running the code](#installation-and-running-the-code)
  - [Organization of the code](#organization-of-the-code)
  - [Simulation protocols](#simulation-protocols)

<!-- /TOC -->

The org.py is processing the pressure, volume, and strain value. The example is provided. There are two process methods 3D ECHO (with strain value) (in special format) and MRI (Magnetic Resonance Images) (no strain value). The ‘PIG 393485.txt’ is the echo file and ‘LV_Volume.txt’ is the MRI file. Also, the ‘LVpressure.mat’ is pressure data in a full cycle. When running the echo parts, the program will generate a folder with volume and multiple different strains in it.  

After the first successful running, it can generate a csv file which has pressure, volume, and time in it. If you would like to make some data changes, you can change inside, and the code will use the data in the csv file to run in second time.  

