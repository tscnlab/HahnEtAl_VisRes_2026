<img src="https://github.com/tscnlab/Templates/blob/main/logo/logo_with_text-01.png" width="400"/>

# Overview

Repository for the publication: **Regulation of eye movements and pupil size in natural scenes**, publicly accessible under (https://doi.org/10.1016/j.visres.2026.108801)
Here we explain the Python script processing and any manual steps in sequential order to reproduce the analysis of the data

## Cloning the repository

This repository first needs to be cloned to a local directory on your machine

## Data

1. The data must be downloaded from the cloned "EyeMoveChar"-Repository. You should download all available datasets that are provided.
2. The downloaded data must then all be placed in the same location on your machine.

   2.1. Eye Movement Data: Here, a division of the whole-measurement data and initial-15s-data was performed. Depending on which code you would like to run, you only require one or the other. However, the scripts require all files to be downloaded from either "Data/Eye Movements/Initial 15s" or "Data/Eye Movements/Whole Measurement" to run smoothly.

   2.2. Light: No separation between whole measurement or initial measurement sequence was performed here. Please download the data from "EyeMoveChar/Data/Light/cleaned_summary/mcs15.csv" and "EyeMoveChar/Data/Light/cleaned_summary/pupil_luminance.csv" for running the script. Here, relevant data from unwieldly raw data is summarized for easier analysis. The raw data is provided as well in "EyeMoveChar/Data/Light/raw" (Note: The code does not run with the .gos-files provided by the light measurement device. To view the .gos-files the required software is provided by Gigahertz-Optik (https://www.gigahertz-optik.com/en-us/product/msc15/) upon purchasing their product).
   
   2.3. Post-measurement questionnaire: No separation between whole measurement or initial measurement sequence was performed here. Please download the data from" Data/Questionnaire/Post-measurement questionnaire/PMQ.csv"

3. Videos, images and metadata of each measurement are available on FigShare (Indoor scene 1: https://doi.org/10.6084/m9.figshare.30518291; Indoor scene 2: https://doi.org/10.6084/m9.figshare.30520733; Indoor scene 3: https://doi.org/10.6084/m9.figshare.30520892; Outdoor scene 1: https://doi.org/10.6084/m9.figshare.30520829; Outdoor scene 2: https://doi.org/10.6084/m9.figshare.30520925; Outdoor scene 3: https://doi.org/10.6084/m9.figshare.30520979).). This data is not required for running the provided scripts.

## Code

The notebooks in this repository were developed using Jupyter Notebook. All required Python packages are included in the Anaconda distribution. Installing Anaconda should therefore provide the necessary environmentto run the code.

1. Depending on your preference for analysis, download the codes "EyeMoveChar-BaseCode_VR.ipynb" to analyze the full duration of eye movement measurements and/or "EyeMoveChar_TOI_Bins.ipynb" for analysis of the initial three 5 seconds time binse of each measurement.
2. The manuscripts are quite large an require manual renaming of the path where the downloaded data is stored on you machine
3. Run the individual subscripts of each code one after another


