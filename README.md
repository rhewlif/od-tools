# OD Tools

<b>A QGIS plugin to map and analyse closed basins, such as glacial overdeepenings, across a raster surface.</b>

The plugin is built on the method of contour tracking developed by Patton et al., 2015: https://doi.org/10.1016/j.geomorph.2015.01.003

<img style="text-align: center;" alt="Example output of mapped closed basins" src="https://github.com/user-attachments/assets/e724ffc1-d26e-435a-baf3-8ba8b4412d7d" />


<h2>Tools</h2>

<h3>1. Mapping</h3>

This tool maps closed basins across a DEM according to information derived via contouring. The only input required is a raster surface. Parameters can be tuned to adjust the sensitivity of the tracking algorithm. For example, minimum depths of basins to be mapped, min/max basin size, and break of slope sensitivity.

<h3>2. Classification</h3>

This tool calculates further metrics of the mapped basins, including volume, roundness and elongation. Geometric attributes are then used to classify the basins as elongated or circular.

Option classifications that distinguish between glacial/fluvial, age of last occupancy, and thermal state, can also be extracted depending on available input files.

<h2>Further information</h2>

The code is still in beta phase, and will be uploaded to the QGIS plugin repository in the near future.

For questions, contact the author: henry.patton@uit.no.
