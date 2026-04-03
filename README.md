# PIGE-Analysis (F-Analysis-App)

MATLAB app to streamline **PIGE `.spe`** analysis (Peaslee Group, UND). Applies background by fitting a **smooth curve** across the spectrum.

## Repository note

Application source may ship as a MATLAB **`.mlapp`** or project archive in releases; this repo currently documents usage for the distributed app build.

## Usage
1. Place all .spe or .n24 files in a single folder
2. Press load defaults
3. Paste the full directory of your folder into the appropriate text box and press enter. (NO QUOTATION MARKS WIN10 USERS)
4. Wait for spectra to be loaded in.
5. Adjust any other parameters as necessary. Specifically modify the index number until you have selected a spectra with a stable current value. 
6. Press Run and wait for all files to be analyzed.
7. Check for the report file (\*.xlsx) in the folder.

## Troubleshooting
If the analysis gets stuck on a particular file, remove it and re-run the analysis. 
If the values in the analysis file aren't what you expected or the counts are unusually low, it is likely that the channel numbers provided were too far from the peak locations. Please switch on the plotting rocker-switch and re-run the analysis. Observe the spectra to see if this is the case. 
