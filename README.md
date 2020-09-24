# Santos da Silva et al. (2020)

This repository contains modeling data (source code link and information, model input and output files) used in the analysis reported in the manuscript entitled “Power sector investment implications of climate impacts on renewable resources in Latin America and the Caribbean”, currently under review in Nature Communications. 

1) Source Code

This analysis employed the GCAM-LAC model (a research branch of the open-source Global Change Analysis Model ─ GCAM). The source code of the specific version used in this study is available at:

Silvia R. Santos da Silva, Mohamad Hejazi, Gokul Iyer, Thomas B. Wild, Matthew Binsted, Fernando Miralles-Wilhelm, … Chris R. Vernon. (2020, September 24). Silviameteoro/GCAM-LAC: GCAM-LAC_v5.1.3_Santos_da_Silva_et_al_2020 (Version GCAM-LAC_v5.1.3_Santos_da_Silva_et_al_2020). Zenodo. http://doi.org/10.5281/zenodo.4048788

2) System Requirements for the source code installation

Any recent 64-bit operating system including but not necessarily limited to Windows 10, Mac OSX 10.14, and Linux

Additional software and libraries include:
Java 8+
C++ compiler to compile source code with C++14 standard support such as GCC 5+ or Microsoft Visual Studio 2015+
R 3.3+ for running the GCAM data system
The boost C++ library 1.56+
Xerces C++ library 3.1.1+

No non-standard hardware, however it is recommended that the user has 8 GB RAM. 

3) Installation Guide

The C++ source code is compiled according to these guidelines:

http://jgcri.github.io/gcam-doc/gcam-build.html

After compiling the source code, it is necessary to install the GCAM data system (written in R). Instructions to install the GCAM data system are available at:

https://github.com/JGCRI/gcamdata/wiki

Installation time should take about 15-20 minutes to compile the C++ code and another 30 minutes to build the GCAM data system.

4) Instructions to run the model

Instructions to run the model can be found at (item 2 onwards) :

http://jgcri.github.io/gcam-doc/user-guide.html

Additional material can be found here: http://www.globalchange.umd.edu/data/gcam/GCAM_tutorial_2019.pdf

5) Outputs

Model outputs from each scenario is stored in an XML database. Each database requires about 2GB of space. Given that all databases produced for this study require more than 100 GB of space, this dataset is not hosted here. However, in the folder "Model Outputs" we provide all specific parameters used in this analysis. 



