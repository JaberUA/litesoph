.. _advanced:

Advanced Info
===============


.. image:: ./gs_advance.png
   :width: 800
   :alt: Advanced Info


SCF Convergence for the chosen engine
##########################################


**Maximum SCF iteration** : SCF calculations are performed upto this number (Default is 300.)

**Energy (in au)** : Give the appropriate total kinetic energy cutoff for the molecular system (Default:5e-7).

**Density** : Convergence threshold for density (Default:1e-6).

**Eigen States** : Consider this number of eigenstates for the convergence (Default:4e-8).

**Band Occupancy** : Eigen States are considered from these bands : *occupied*, *unoccupied* or *all* (Default: *occupied*).

**Smearing Function** : Consider this Smearing Function in SCF Convergence among these: *improved-tetrahedron-method*, *tetrahedron-method*, *fermi-dirac* and *marzari-vanderbilt* (Default is empty). 

**Smearing (eV)** : Give an appropriate Smearing (Default is 0.0).