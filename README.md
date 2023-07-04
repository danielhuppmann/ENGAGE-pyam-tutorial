# ENGAGE Capacity Building Workshop: the pyam package

![License](https://img.shields.io/github/license/danielhuppmann/ENGAGE-pyam-tutorial)
[![python](https://img.shields.io/badge/python-≥3.8,<3.12-blue?logo=python&logoColor=white)](https://github.com/IAMconsortium/pyam)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

Copyright 2022-2023 Daniel Huppmann; this repository is released under the [MIT License](LICENSE). 

## Overview

<img src="./_static/ENGAGE.png" height="100" align="right" alt="ENGAGE logo" />

This repository holds a [Jupyter notebook](tutorial-notebook.ipynb) for a live-demo
of the **pyam** package given as part of the *hands-on tutorial sessions*
of the **NAVIGATE-ENGAGE Summer School 2023 on Integrated-Assessment Modeling**.
This workshop was organized as part of the Horizon 2020 project ENGAGE
([link](https://www.engage-climate.org/navigate-engage-summer-school-2023/)).

The Jupyter notebook is based on the advanced assignment
of the [Modelling Lab](https://github.com/danielhuppmann/climate-risks-academy-2021),
which was part of the *Climate Risks Academy 2021* organized by
the European University Institute (EUI) Florence School of Banking and Finance
in cooperation with Oliver Wyman.

The **slides for the related presentation** are available
at https://doi.org/10.5281/zenodo.8112529 (ZENODO).

## Tutorial data source

The scenario data used in this tutorial notebook is taken from
the **NGFS Scenario Ensemble**, Phase 3, see Richters et al, 2022 ([link](https://www.ngfs.net/sites/default/files/medias/documents/ngfs_climate_scenarios_for_central_banks_and_supervisors_.pdf.pdf)).  

The data was downloaded from the following scenario database:
> **Emissions scenario database of the European Scientific Advisory Board on Climate Change, hosted by IIASA**  
> Release 2.0  
> European Scientific Advisory Board on Climate Change, 2023  
> doi: 	https://doi.org/10.5281/zenodo.7660150  
> url: 	https://data.ece.iiasa.ac.at/eu-climate-advisory-board  

## The pyam package

<img src="https://github.com/IAMconsortium/pyam/raw/main/docs/logos/pyam-logo.png" 
width="133" height="100" align="right" alt="pyam logo" />

This tutorial uses the Python package **pyam**, an open-source community toolbox for
analysis & visualization of scenario data.
The package was developed to facilitate working with timeseries scenario data
conforming to the format developed by the
[Integrated Assessment Modeling Consortium (IAMC)](https://www.iamconsortium.org).
The package is used in ongoing assessments by the IPCC and in many model comparison
projects at the global and national level, including several Horizon 2020 projects.

[Read the docs](https://pyam-iamc.readthedocs.io) for more information!

## Getting started

To run the notebooks on your machine, please install Python version 3.7 or higher.
To install the required packages and dependencies, download or git-clone this repository
and run the following command in the root folder:

```
pip install -r requirements.txt
```

Then, you can start a Jupyter notebook using

```
jupyter notebook
```

## Funding acknowledgement

<img src="./_static/EU-logo-300x201.jpg" width="80" height="54" align="left" alt="EU logo" />
This project has received funding from the European Union’s Horizon 2020 research
and innovation programme under grant agreement No. 821471 (ENGAGE).
