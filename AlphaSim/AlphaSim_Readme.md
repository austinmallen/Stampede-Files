********
AlphaSim
********

AlphaSim is a software package developed by a group called AlphaGenes at the Roslin Institute in Scotland. AlphaSim was created for simulating sequence, genotypic, phenotypic, and pedigree data in a wide range of population types. More general questions about AlphaSim can be answered at the AlphaGenes website: `www.alphagenes.roslin.ed.ac.uk/alphasuite/alphasim <www.alphagenes.roslin.ed.ac.uk/alphasuite/alphasim>`_


The version of AlphaSim that has been ported to the Agave API has been specifically configured to simulate genotypic and phenotypic data with a large number of SNPs for Maize populations.

The Agave API port of AlphaSim accepts no inputs, as the program reads data from a structured input file called AlphaSimSpec.txt. The version of AlphaSimSpec that is included in the Agave app has been configured for Maize.

When run, AlphaSim produces three directories - Chromosomes, Selection, and SimulatedData - containing the simulated data generated according to the specifications in the AlphaSimSpec file. 
