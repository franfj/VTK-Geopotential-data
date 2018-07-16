# VTK-Geopotential-data

The idea is to represent geopotential data from a concrete instant of time and draw it over the cartography to visualize the necessary property values by using OpenGL or the VTK library.

In order to perform this kind of visualizations with the provided geopotential data two techniques were proposed: transfer function , and the isocontours construction.

![Example](https://raw.githubusercontent.com/franfj/VTK-Geopotential-data/master/exampleTransferFunction.PNG)

In order to run SciVis_FranRodrigo.ipynb, open it with Jupyter notebooks and click on "restart kernel, and then re-run the whole notebook", or run every notebook's cell in order.

Interaction keyshorts:

- The 'q' key exists the render, and restart the Python kernel.

- The 'a' key adds/removes the parallels/meridians/points from the render.

- The 's' key in the transfer function mode, changes the range of colours.

- The 'z' and 'x' keys change the GeoPotential file.

- The 'n' and 'm' keys change the number of divisions in IsoContour mode.

- The 'c' key switches between IsoContour mode and Mixed Visualization mode.
