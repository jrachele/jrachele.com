---
tags: projects
title: REDCRAFT
description: REDCRAFT is a software suite that will computationally determine protein structure from Residual Dipolar Couplings.
image: img/redcraft_logo.png
link: https://redcraft.readthedocs.io
permalink: false
---
Over the course of two years, I have worked on REDCRAFT, a project created by Homayoun Valafar at the University of South Carolina in 2003.

The project is a C++ project that outputs PDB files based on RDC files provided in the universal [<u>NEF</u>](https://www.nature.com/articles/nsmb.3041) format

As far as what I have done specifically:

+ Created UI in Qt5 (C++) to leverage REDCRAFT's command line utilities
+ Updated REDCRAFT to C++11 and to CMake, building REDCRAFT/REDCAT libraries and GUI simultaneously
+ Updated documentation to be generated on commit, using *readthedocs.io*
+ Introduced unit tests and helped set up Continuous Deployment pipeline