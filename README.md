# balto_gui
An Interactive GUI for BALTO in a Jupyter notebook

This respository creates a GUI (graphical user interface) for the BALTO (Brokered Alignment of Long-Tail Observations) project. BALTO is funded by the NSF EarthCube program. The GUI aims to provide a simplified and customizable method for users to access data sets of interest on servers that support the OpenDAP data access protocol. This interactive GUI runs within a Jupyter notebook and uses the Python packages: <b>ipywidgets</b> (for widget controls), <b>ipyleaflet</b> (for interactive maps) and <b>pydap</b> (an OpenDAP client).

The Python source code to create the GUI and to process events is in a module called <b>balto_gui.py</b> that must be found in the same directory as this Jupyter notebook.

This is an <b>accordion-style GUI</b>, which allows you to switch between GUI panels without scrolling in the notebook.

You can run the notebook in a browser window without installing anything on your computer, using something called Binder. Look for the Binder icon below and a link labeled "Launch Binder".

To run this Jupyter notebook without Binder, it is recommended to install Python 3.7 from an Anaconda distribution and to then create a conda environment called balto. Instructions for how to create a conda environment are given in Appendix 1 of version 2 of the notebook.

Version 2<br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mariutzica/balto_gui/1751af240e6aeb023cd897072e59a020dcadaa25?filepath=BALTO_GUI_v2.ipynb)
<br>

Version 1<br>
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mariutzica/balto_gui/a272d2bee1ea3d1be25e26d4402565cb74f9a63c?filepath=BALTO_GUI.ipynb)

