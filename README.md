# pka_reparam_2025
data and ff params for: "Improving pKa prediction accuracy with reparametrized force fields and free energy calculations"

## modified_ff
**charmm36m-075**: all side chains and common counterions scaled to 0.75.

**amber14sbq-075**: adapts the backbone partials from amber99sb-star-ildn-q [1]. These partials give more accurate relative free energy values in proteins [2,3]. The residue side chains are also charge scaled to 0.75. We also adapt the terminal capping group so custom terminal residues are not required (i.e., GLU, DGLU, and NGLU) (this is the same strategy used in CHARMM36m). Common counterions scaled to 0.75.

1. Residue-Specific α-Helix Propensities from Molecular Simulation. Robert B. Best, et al. Biophys. J. 102(2) 1462-1467 (2012)
2. Accurately Predicting Protein pKa Values Using Nonequilibrium Alchemy. Carter J. Wilson, et al. J. Chem. Theory Comput. 19, 21, 7833–7845 (2023)
3. Improving pKa Predictions with Reparameterized Force Fields and Free Energy Calculations. Carter J. Wilson, et al. J. Chem. Theory Comput. (2025)
