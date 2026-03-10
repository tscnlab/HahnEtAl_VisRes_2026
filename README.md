<img src="https://github.com/tscnlab/Templates/blob/main/logo/logo_with_text-01.png" width="400"/>

# Workflow description 
Here we explain the PYTHON script processing and any manual steps in sequential order. 

## Base code
This Python script is used to extract all the necessary data from the respective files in the "data" folder. In order to run the script successfully, all the files need to be downloaded 
and the script updated (source names) to direct it to the correct files. Run the individual subscripts one after another.

### Light data
The files that could be exported are in a .gos-format, which is not common and tricky to open with anything but the software used for the spectroradio meter MCS15 by Gigahertz Optik. 
The code das not run with the .gos-files and is instead fed with a summary file (mcs15.csv) that summarizes all light measurement data for every participant. Another file (pupil_luminance.csv) is used to plot the relationship between pupil size (mm) and luminance (lux).

### Eye movement data
The eye movement data analysis runs on the raw data .csf-files extracted by the Tobii Pro Glasses 3. The 5-second-interval analysis is performed with raw data that was extracted from five 
second long times of interst (TOI). The code of these TOI-analysis is similarly structures as the "whole measurement"-analysis.

### Post-measurment questionnairs
The post-measureent questionnaire data is summarized in a single table 
