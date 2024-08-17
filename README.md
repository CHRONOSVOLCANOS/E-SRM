# E-SRM
Raw data and MATLAB codes for the Expanded Snowmelt Runoff Model (E-SRM)

If using this, please cite: N/A @ 08/16/2024

This .zip file contains the data and MATLAB codes for the E-SRM,
  developed by Ninad Bhagwat (PhD student at Montana Technological University)
  LAST UPDATED: 08/16/2024

Contents:

  Input_data - This folder contains all the input data used by Ninad Bhagwat to develop
    and run the E-SRM. Some data is raw, while some is pre-processed to some extent.

  MATLAB - This folder contains all the MATLAB codes (last updated on 08/16/2024) to pre-process
    some data and use the E-SRM model.

  Output_for_verification - This folder contains all the outputs from MATLAB codes. Just to
    verify that the codes are working, and results are recreatable.

Instructions:

	1. To obtain hypsometric elevation of each zone in a watershed, along with 
	  area and fractional area of each zone, use 'Step_1_hypsometric_elevation_finder.m'.
	2. To obtain the fractional snow cover area for each zone from the 8-day
	  MODIS snow cover images (MOD10A2), use 'Step_2_MODIS_batch_process_8day_snowcover.m'.
	3. To calibrate the E-SRM, use 'Step_3_E_SRM_batch_calibration.m'.
	4. To validate the E-SRM, use 'Step_4_E_SRM_batch_validation.m'.

IMP: Integration between steps 3 and 4 is in progress.

Each MATLAB code has detail instructions on how to use it.

Contact: Ninad Bhagwat (nbhagwat@mtech.edu)
