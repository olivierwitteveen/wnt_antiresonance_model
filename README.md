# Modeling anti-resonance in the Wnt pathway

Work performed by Bauer Group at TU Delft and Max Wilson lab in UCSB. 

## Reference
Anti-resonance in developmental signaling regulates cell fate decisions
Samuel J. Rosen, Olivier Witteveen, Naomi Baxter, Ryan S. Lach, Marianne Bauer, Maxwell Z. Wilson
bioRxiv 2025.02.04.636331; doi: [https://doi.org/10.1101/2025.02.04.636331](https://doi.org/10.1101/2025.02.04.636331).

## Overview
This repository contains the code used to perform the simulations. Here we compare the ODE model and hidden-variable model to the raw data from experiments, and analyze the anti-resonance predicted by the models. 

## Repository Structure
### Folders:
- `data/`: Data traces (TopFlash, b-cat) for exposure-time experiment. 
- `figures/`: Figures obtained from the simulations. 
- `hv_simulation/`: Contains simulations from the hidden variable model, stored in `.csv` files. They contain the concavity and anti-resonant frequencies predicted as a function of parameters of the model. 
### Notebooks
- `ode_model.ipynb`: Simulations from the ODE model in Fig. 2.
- `hv_model.ipynb`: Simulations from the hidden-variable model in Fig. 4. 

## Contact
For any questions or inquiries, please contact o.z.j.witteveen@tudelft.nl.
