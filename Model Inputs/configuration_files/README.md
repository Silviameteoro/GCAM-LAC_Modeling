
This folder includes the GCAM configuration files used to initialize the simulations. Main files are:

1 - config-Ref_Imp.xml: For simulations of the Baseline: No-Climate impacts and Baseline: Combined impacts scenarios.

2 - config-Ref_Imp_hydro.xml: For simulations of the Baseline: Hydropower scenario.

3 - config-NoCCS_NoNewNuc.xml: For simulations of the NoCCS & NoNewNuc: No-Climate impacts and NoCCS & NoNewNuc: Combined impacts scenarios.

4 - config-NoCCS_NoNewNuc_hydro.xml: For simulations of the NoCCS & NoNewNuc: Hydropower scenario.

5 - config-FullTech.xml: For simulations of the FullTech: No-Climate impacts and FullTech: Combined impacts scenarios.

6 - config-FullTech_hydro.xml: For simulations of the FullTech: Hydropower scenario.

Each configuration file calls all other model input files needed for each scenario simulation. For example, the NoCCS & NoNewNuc scenarios require the fixed_nuclear_shwt_LAC_Uru.xml and one of the "batch_LAC_Imp" xml files depending on the scenario.  (**** Note that it is not necessary to download the configuration or the other addon files. When the source code is downloaded, these files are downloaded with the code. ****)
