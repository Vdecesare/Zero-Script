# Zero-Script
Flex Analysis Method: Zero Script. The zero script exports mass intensities of each spot from the raw data into a .csv column format. For the negative controls, the zero script considers the area of the background noise detectable in the light ubiquitin mass window.
1. System requirements

The Zero script is a Flex Analysis method. It therefore relies on pre-installed Flex Analysis software and relative system requirements. 

2. Installation guide

Place Zero script in the "flexAnalysisMethods" Folder (Methods sub-folder). Follow instructions as for in Statistical Analysis for HT MALDI-TOF DUB Assay (De Cesare et al., Nature Protocols), 43 to 50 steps of Procedure (see below)

Statistical Analysis for HT MALDI-TOF DUB Assay

43. Open the Flex Analysis software and select the folder containing the raw data of interest. At least one spectrum needs to be opened to allow FlexAnalysis to perform all the subsequent analysis steps.
44. In the FlexAnalysis software, open the “Method” menu and select the “zero” script. 
45. Modify destination folder and result file name as desired, save modified script and use the batch process for analysing data. The zero script will export mass areas of each spot from the raw data into a .csv column format. For the negative controls, the zero script considers the area of the background noise detectable in the ubiquitin m/z window (See also Data Analysis and Statistical Analysis sections).
46. Copy and paste zero script output columns (Spectrum, Compound, m/z, S/N, Resolution and Area) into the Input sheet of the Baseline data check file. 
47. Convert Output zero deleted sheet (last sheet of Baseline data check file) to .txt plain format.
48. Drag text file onto the Grid .exe file. The script will produce a new file with GRID included in the file name. The GRID file will select ubiquitin and 15N ubiquitin area values and report them in the same position as spotted on the MALDI plate. 
49. Calculate ubiquitin over 15N ubiquitin area ratio.
50. Evaluate data quality by calculating Z’ scores (see Statistical Analysis). 

