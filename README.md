# Zero-Script
Flex Analysis Method: Zero Script. The zero script exports mass intensities of each spot from the raw data into a .csv column format. For the negative controls, the zero script considers the area of the background noise detectable in the light ubiquitin mass window.
1. System requirements

The Zero script is a Flex Analysis method. It therefore relies on pre-installed Flex Analysis software and relative system requirements. 

2. Installation guide

Place Zero script in the "flexAnalysisMethods" Folder (Methods sub-folder). Follow instructions as for in De Cesare et al., Nature Protocols, 4.1 to 4.4 (see below)

4.1) Open Flex Analysis software and select folder containing the raw data of interest
4.2) In the Flex Analysis software open the “Method” menu and select the “zero” script 
4.2) Modify destination folder and result file name as desired, save modified script and use the batch process for analyzing data. The zero script will export mass areas of each spot from the raw data into a .csv column format. For the negative controls, the zero script considers the area of the background noise detectable in the light ubiquitin mass window.
4.4) Convert zero script results from .csv file to .txt plain format.

Use .txt file as input for GRID script.
