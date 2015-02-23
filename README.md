# IVisual
VPython API for IPython Notebook

IVisual provides VPython visual API for inline use in an IPython Notebook. You might find it most useful for 
performing 3D visualizations of VPython visual simulations that can be viewed inline in an IPython Notebook.
Typical usage often looks like this in an IPython Notebook cell

from ivisual import *

s = sphere()

This will create a 3D window in the Notebook containing a sphere.

The goal of the IVisual project is to enable VPython programs to run seamlessly in an IPython Notebook. The IPython Notebook
is a popular software tool for doing interactive scientific computing. VPython is an interactive graphics module that makes
it unusually easy for users to perform 3D computational modeling and visualizations in Python. IVisual is a Python module
that can be imported into an IPython Notebook to bring VPython functionality into the notebook. Information about VPython and 
the IPython Notebook can be found at vpython.org, and ipython.org respectively.
