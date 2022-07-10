# cordon-caulle-ash-vents
Resources and analysis accompanying the manuscript, "*In-conduit capture of sub-micron volcanic ash particles via turbophoresis and sintering.*"

### Jamie I. Farquharson[*](#linkhandle), Hugh Tuffen, Fabian B. Wadsworth, Jonathan M. Castro, Holly Unwin, C. Ian Schipper 
***
<a id="linkhandle"></a>* [ifarq89@googlemail.com](mailto:jifarq89@googlemail.com)

### Abstract
**Ash emission in explosive silicic eruptions can have widespread impacts for human health, agriculture, infrastructure, and aviation. Estimates of the total grainsize distribution (TGSD) generated during explosive magma fragmentation underpins eruption models and ash dispersal forecasts. Conventionally, the TGSD constrained via erupted deposits is assumed to match the TGSD produced at explosive fragmentation. Here we present observations from within the vent of a recent rhyolitic eruption (Cordón Caulle, Chile, 2011–2012), demonstrating that fine (<63 micron diameter) and ultra-fine (<2.5 micron diameter) ash particles are captured and sintered to fracture surfaces, and thus sequestered in the shallow subsurface, rather than emitted. We establish a conceptual model—uniquely contextualised through a combination of syn-eruptive observations and detailed post-eruption field investigation—in which turbophoresis (particle migration towards zones of lower turbulence) and rapid sintering create an inverse relationship between particle size and the probability of its subsurface capture. Such size-dependent capture efficiency preferentially removes submicron-diameter ash from the erupted componentry, decoupling the erupted size distribution from magmatic source conditions and potentially playing an important role in modulating eruption dynamics.**
***

This GitHub release (v1.0) is citable via its doi: <a href="https://zenodo.org/badge/latestdoi/401669554"><img src="https://zenodo.org/badge/401669554.svg" alt="DOI"></a>

This repository includes a ```data``` folder, containing ash plume and particle size distribution data relevant to this study, and energy dispersive X-ray geochemical data. In addition, the Jupyter notebook file, ```Farquharson-et-al-CC-ash-vents.ipynb``` contains the script used for data analysis and figure plotting. Figures are reproduced in the ```figs``` folder.
```
.
|
+-- Farquharson-et-al-CC-ash-vents.ipynb
|
+-- data
|   |
|   +-- _sizedist.csv
|   +-- AN1_sizedist.csv
|   +-- costa_data_bins.csv
|   +-- costa_data.csv
|   +-- EDX_reports
|   |   |
|   |   +-- site 4_Spectrum 1.txt
|   |   +-- site 4_Spectrum 2.txt
|   |   +-- site 4_Spectrum 3.txt
|   |   +-- site 4_Spectrum 4.txt
|   |   +-- site 4_Spectrum 5.txt
|   |   +-- site 4_Spectrum 6.txt
|   |   +-- site 4_Spectrum 7.txt
|   |   +-- site 4_Spectrum 8.txt
|   |   +-- site 4_Spectrum 9.txt
|   |   +-- site 4_Spectrum 10.txt
|   |   +-- site 5_Spectrum 11.txt
|   |   +-- site 5_Spectrum 12.txt
|   |   +-- site 5_Spectrum 13.txt
|   |   +-- site 5_Spectrum 14.txt
|   |   +-- site 5_Spectrum 15.txt
|   |   +-- site 5_Spectrum 16.txt
|   |
|   +-- plume_height.csv
|
+-- figs
|   |
|   +-- figure-1.pdf
|   +-- figure-2.pdf
|   +-- figure-3.pdf
|   +-- figure-4.pdf
|   +-- figure-5.pdf
|   +-- figure-6.pdf    
|    
+-- LICENSE
+-- manuscript.md
+-- README.md
```

***
### Usage
Python version >= 3.0 is required. The notebook calls numpy, matplotlib, datetime, pandas, scipy, and sklearn.
***
### Author
Dr Jamie I. Farquharson [jifarq89@googlemail.com](mailto:jifarq89@googlemail.com). 
***
### License
This project is licensed under Creative Commons Attribution 4.0 International license.

