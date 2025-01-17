[![DOI](https://zenodo.org/badge/18718/EFerriss/HydrogenCpx.svg)](https://zenodo.org/badge/latestdoi/18718/EFerriss/HydrogenCpx)

FTIR spectra, baselines, peakfits, and python code for a project measuring hydrogen diffusion in clinopyroxene. The accompanying academic journal article has been accepted to *Contributions to Mineralogy and Petrology*. DOI: 10.1007/s00410-016-1262-8.

The key file is the python script [cpx_spectra.py](https://github.com/EFerriss/HydrogenCpx/blob/master/HydrogenCpx/cpx_spectra.py), which contains all of the data about the samples and FTIR spectra, including sample [IGSN](http://www.geosamples.org/igsnabout)s; sample thicknesses in each direction; details about each profile such as the thickness direction ('raypath'), the direction of the traverse ('direction'), which spectra belongs to each profile (the 'fname_list') and the positions of those measurements along the traverse ('positions_microns'). 

Note that these codes were written in python 2.7 using an earlier version of pynams (v0.1.0). The latest version of pynams along with working examples can be found in the [pynams github repository](http://github.com/EFerriss/pynams).

Please cite this code as
Ferriss, E., 2016, HydrogenCpx: Python code and FTIR spectra for measuring hydrogen diffusion in clinopyroxene, DOI: 10.5281/zenodo.48360, https://github.com/EFerriss/HydrogenCpx 
