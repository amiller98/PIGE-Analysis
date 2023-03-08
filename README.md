# F-Analysis-App
A MATLAB app built to streamline the analysis of PIGE *.spe data collected by the Peaslee Group at UND

USAGE
1. Place all *.spe files in a single folder
2. Fill in the relevant fields above the Directory text box (if you're unsure of what to do, press "load defaults"). Note that the CHANNEL NUMBER for each peak is what is requested.
3. Paste the full directory of your folder into the appropriate text box
4. Press run and wait for all files to be analyzed.
5. Check for the report file (*.xlsx) in the folder.

TROUBLE SHOOTING
If the analysis is stuck on a particular file, check the file and ensure that it isn't a blank spectra.
If the values in the analysis file aren't what you expected or the counts are unusually low, it is likely that the channel numbers provided were too far from the peak locations. Please switch on the plotting rocker-switch and re-run the analysis. Observe the spectra to see if this is the case. 
