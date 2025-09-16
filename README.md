## This repository contains files of the equilibrated brain cell membrane (BCM)

# For broader applications of the pre-equilibrated BCM, you may wish to merge it with molecules of interest. Before doing so, be sure to verify the coordinates of the lipid identified as chain G / resname CER160.

### The reason is that in VMD, the GLPA lipid’s resname appears as CER160, whereas in the corresponding PDB file it is written simply as CER1. As a result, when using VMD’s Merge Structures module, the program cannot correctly process these lipids and will place all GLPA lipid atoms at the origin (0.00 0.00 0.00).

And BCM is equilibrated at 310 K and 100 ns of production runs after a series of equilibration runs.
The file production_100ns.pdb contains the system’s coordinates after completing a 100 ns production run.
The composition of BCM provided here, please check this reference:

#### Ge, Yanhong, Huixia Lu, and Jordi Martí. "Influence of local ordering in the permeation of Temozolomide through the brain plasmatic membrane." Biophysical chemistry (2025): 107457.
