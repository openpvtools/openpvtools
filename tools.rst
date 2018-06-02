.. _tools:

Open Source PV Modeling Tools
=============================

The table below shows a summary of the open source PV modeling tools known to the authors as of this writing. Here, we briefly describe each tool.

PVLib Matlab is a general purpose PV modeling toolkit for the Matlab platform. It is primarily developed at Sandia National Laboratories, but contains contributions from members of the PV Performance Modeling Collaborative (PVPMC; see www.pvpmc.org). PVLib Matlab includes extensive documentation and extensive examples.

PVLib Python is a general purpose PV modeling toolkit written in Python. PVLib Python originated as a port of PVLib Matlab and contains many of the Matlab project’s features. The PVLib Python and Matlab projects are developed independently, but some developers contribute to both projects. PVLib Python is a dependency of other open source tools. PVLib Python includes extensive function-level documentation, and a collection of examples in its online documentation and Jupyter notebooks.

System Advisory Model is a popular desktop application for PV, CSP, wind, and financial modeling. It is developed at the National Renewable Energy Laboratory. SAM has a MIT license for commercial entities and a GPL 3 license for national labs, universities, and non-profits. The SAM Simulation Core (SSC) is the computational library for SAM. NREL has also developed the SAM SDK for writing scripts to interact with SAM and the SSC.

rdtools is a library for PV degradation analysis. It is developed at NREL and written in Python. It includes a Jupyter notebook with an example analysis. rdtools uses PVLib Python.

PVFree is a web application and API for obtaining PV modeling parameters.

SolarUtils is a package that contains Python wrappers for NREL’s solar position and spectral decomposition packages (written in C). It was developed by SunPower.

Pecos is a performance monitoring tool originally developed for PV but with applications to other systems. Pecos includes online documentation and examples. Pecos uses PVLib Python. It is developed at Sandia and written in Python.

SolPy is a general purpose PV modeling tool.

PVMismatch is a tool for IV curves for modules with heterogeneous cells. It is developed at SunPower and written in Python.

photovoltaic is a general purpose PV modeling package. It is developed at Arizona State University for educational use. It is written in Python.

feedinlib is a tool for PV time series modeling. It is part of the Open Energy Modelling Framework.

CASSYS is a simulation tool for grid-tied PV systems. CASSYS is developed by Canadian Solar O&M Inc. The user interface is a Microsoft Excel spreadsheet, and the calculations are run by a program. CASSYS includes a user guide, a model-description document (useful for general PV modeling), and a comparison to PVSyst document.


.. csv-table:: Table of Open Source PV Tools. A * denotes that the project is under active development.
   :file: openpvtools.csv
   :delim: ,
   :header-rows: 1
   :widths: 10, 10, 20, 20, 20, 10, 10
   :stub-columns: 1
