# rsvp_phasereset

Package/software requirements

- python v3.10 or later
- jupyter notebook v6.5.4
- pandas v2.3.1
- matplotlib v3.10.8
- scipy v1.15.3
- numpy v1.26.4
- seaborn v0.12.2

-Code tested on macOS Sonoma 14.5, run in virtual environment w/above packages installed
-jupyter notebook file includes a module to generate simulated data to run analysis code

Installation instructions
-download jupyter notebook file 
-create data directories for data/figure output and replace paths in code
-typical installation time < 5 min
-virtual environment optional

Demo
-Once directories are created, run the jupyter notebook file
-Expected output: 
	1) Excel sheets per subject, region, contact with phase data
	2) Figures per subject, region, freq_band with rayleigh z-statistic plotted, shading significant periods
	3) Figures per subject, region with ITPC over time
	4) Expected runtime < 5 min

How to run the software on your data: 
-import your data using the hierarchy dict specified in the code
-change directories to save on your device/drive
-run the analysis cells (can skip the simulation data generation cell)
