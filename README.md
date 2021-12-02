# cordon-caulle-ash-vents
Resources and analysis accompanying the manuscript, "*Capture of sub-micron volcanic ash particles in a shallow conduit via turbophoresis and sintering.*"

### [Jamie I. Farquharson](mailto:jifarq89@googlemail.com), Hugh Tuffen, Fabian B. Wadsworth, Jonathan M. Castro, C. Ian Schipper 

### Abstract
**Ash emission in explosive silicic eruptions can have widespread impacts for human health, agriculture, infrastructure, and aviation. Estimates of the total grainsize distribution (TGSD) generated during explosive magma fragmentation underpins eruption models and ash dispersal forecasts. Conventionally, the TGSD constrained via erupted deposits is assumed to match the TGSD produced at explosive fragmentation. Here we present observations from within the vent of a recent rhyolitic eruption (Cordón Caulle, Chile, 2011–2012), demonstrating that fine and ultra-fine ash particles are captured and sintered to fracture surfaces, and thus sequestered in the shallow subsurface, rather than emitted. We establish a conceptual model—uniquely contextualised through a combination of syn-eruptive observations and detailed post-eruption field investigation—in which turbophoresis (particle migration towards zones of lower turbulence) and rapid sintering create an inverse relationship between particle size and the probability of its subsurface capture. Such size-dependent capture efficiency preferentially removes submicron-diameter ash from the erupted componentry, decoupling the erupted size distribution from magmatic source conditions and potentially playing an important role in modulating eruption dynamics.**
***

This repository includes a ```data``` folder, containing ash plume and particle size distribution data relevant to this study, as well as Scanning Electron Microscope micrographs. In addition, the Jupyter notebook file, ```Farquharson-et-al-CC-ash-vents.ipynb``` contains the script necessary for data analysis and reproduction of the figures in the ```figs``` folder.
```
.
|
+-- Farquharson-et-al-CC-ash-vents.ipynb
|
+-- data
|   |
|   +-- AN1_sizedist.csv
|   +-- costa_data.csv
|   +-- plume_height.csv
|
+-- fig2a.png
+-- fig2b.png
+-- fig2c.png
|
+-- figs
    |
    +-- fig1.png
    +-- fig2.png
    +-- fig3.png
    +-- fig4.png
```

***
### Usage
Python version >= 3.0 is required. The notebook calls numpy, matplotlib, datetime, pandas, scipy, and sklearn.
