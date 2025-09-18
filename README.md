## This repository contains files of the equilibrated brain cell membrane (BCM)

# For broader applications of the pre-equilibrated BCM, you may wish to merge it with molecules of interest. Before doing so, be sure to verify the coordinates of the lipid identified as chain G / resname CER160.

### The reason is that in VMD, the GLPA lipid’s resname appears as CER160, whereas in the corresponding PDB file it is written simply as CER1. As a result, when using VMD’s Merge Structures module, the program cannot correctly process these lipids and will place all GLPA lipid atoms at the origin (0.00 0.00 0.00).

The BCM is equilibrated at 300 K and 100 ns of production runs after a series of equilibration runs.
The file production_100ns.pdb contains the system’s coordinates after completing a 100 ns production run.

Number of lipids: 400

Temperature: 300 K

Equilibration: 100 ns of production runs after a series of equilibration runs

Force Filed: Charmm36m

* Composition:

   | Upper leaflet         |Lower leaflet  |
  | ------------- | ------------- |
   | 19 GLPA               | 0  |
   | 0                     | 29 POPS |
   | 22 SSM                | 12 SSM |
   | 22 POPE               | 43 POPE |
   | 48 DPPC               | 27 DPPC |
   | 89 CHOL               | 89 CHOL |

![Chemical structure of lipids of BCM]([[https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png]([https://github.com/HuixiaLuScienceRocks/equilibrated_brain_cell_membrane/blob/main/FIG-LIPIDS.png](https://github.com/HuixiaLuScienceRocks/equilibrated_brain_cell_membrane/blob/main/FIG-LIPIDS.png))]([https://github.com/HuixiaLuScienceRocks/Poster-Thessaloniki/blob/main/FAR_binds_into_SII.gif](https://github.com/HuixiaLuScienceRocks/equilibrated_brain_cell_membrane/blob/main/FIG-LIPIDS.png
)))

For details on the interactions between the FDA-approved drug Temozolomide and BCM, please refer to this source:

#### Ge, Yanhong, Huixia Lu, and Jordi Martí. "Influence of local ordering in the permeation of Temozolomide through the brain plasmatic membrane." Biophysical chemistry (2025): 107457.
