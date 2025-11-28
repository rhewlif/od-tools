# OD Mapper

<b>A QGIS plugin to map and analyse closed basins, such as glacial overdeepenings.</b>

The plugin is built on the method of contour tracking developed by Patton et al., 2015: https://doi.org/10.1016/j.geomorph.2015.01.003

<img style="text-align: center;" alt="Methodology of using contours to map overdeepenings, searching for breaks of slope" src="https://github.com/user-attachments/assets/a775c232-a472-4ed2-bb95-a661a39366dd" />

Identification of closed-depression perimeters and their nestings using the contour tracking method. (A) Linear transects drawn from each elevation minima intersect with contours. The length change between adjacent contours is calculated to identify abrupt increases in contour length that indicate that a contour is beyond the contour that defines the closed-depression perimeter. 
(B) Parent and child depressions are identified using multiple passes of the contour-tracking algorithm and using a threshold contour-length increase of > 90%, corresponding to a break of slope associated with the depression boundary. 
(C) Parent and child depressions are classified using a top-down approach.

The code is still in beta phase, and will be uploaded to the QGIS plugin repository in the near future.

For questions, contact the author: henry.patton@uit.no.
