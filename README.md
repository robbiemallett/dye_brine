# Data and code for Mallett et al. (In Review; Annals of Glaciology).

This repository contains the code and data required to reproduce all figures in a submission under review at AoG, preprinted here:

https://doi.org/10.31223/X5F976

The above DOI will be replaced with the AoG code upon publication (with "in review" changed to the year).

## Code Guide

All code is contained in Jupyter Notebooks within the /notebooks/ directory. The necessary Python virtual environment to run these notebooks can be found in the python_env.yml file. Instructions on how to build an environment based on this file can be found here: https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html

The filename system of the notebooks correspond to the figures that they generate. Supplementary figure S5 requires a separate module (ll_xy.py) that I have included in the directory for import.

## Data Guide

The .pnt files from the snow micropenetrometer are contained in /data/SMP/all_raw

The air temperature data from the Churchill airport station are contained in /data/weather

The wicking and sink heights are contained in /data/Brine Sink Heights.xlsx

The snow pit data from the field experiments are in /data/dye_pit.ods

The output of the temperature probe from the lab experiments are in /data/temperatureprobe_.csv

The Sentinel-2 geotiff used to make the supplementary map figure is in S2_geotiff (top level directory)

All photos in the manuscript are included in the top level directory /photos/



