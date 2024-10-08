Expanded Snowmelt Runoff Model (E-SRM)

If using this, please cite: N/A @ 09/21/2024

This repository contains the data and MATLAB codes for the Expanded SRM (E-SRM),
  developed by Ninad Bhagwat (PhD student at Montana Technological University)
  LAST UPDATED: 09/21/2024

Contents:
  Input_Canyon_Ferry_Steps_1_2 - Contains the input data for Canyon Ferry watershed to run Steps 1 and 2.

  Input_Morony_Steps_1_2 - Contains the input data for Morony watershed to run steps 1 and 2.

  Input_Steps_3_4_each_scenario - Contains all the input data for Canyon Ferry and Morony watersheds to run the E-SRM. (E-SRM has many scenarios, see 'Scenarios' folder).

  Steps_1_2_code_output - Contains the MATLAB codes (last updated on 09/21/2021) to run Steps 1 and 2, and the outputs from these codes.

  Scenarios - I have 3 scenario folders (Scenario 1, 2, 3). Each folder has respective code and output for verification. 
    The instructions for each scenario are provided in a NOTEPAD file. The input for all scenarios is same and is provided 
    in 'Input_data folder'.

Instructions:
	1. To obtain hypsometric elevation of each zone in a watershed, along with 
	  area and fractional area of each zone, use 'Step_1_hypsometric_elevation_finder.m'.
	2. To obtain the fractional snow cover area for each zone from the 8-day
	  MODIS snow cover images (MOD10A2), use 'Step_2_MODIS_batch_process_8day_snowcover.m'.
	3. Steps 3 and 4 have multiple scenarios. Each scenario is accompined with its own MATLAB
	   code and NOTEPAD instructions. Follow the instructions from the NOTEPAD.

ALL THE RESULTS WERE RECREATABLE AS OF 09/02/2021.

Contact: Ninad Bhagwat (nbhagwat@mtech.edu)
