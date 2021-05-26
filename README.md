# ML_6th_Dimension
Work published as [arXiv:2103.14039](https://arxiv.org/pdf/2103.14039.pdf), by Adriana Dropulic, Bryan Ostdiek, Laura Chang, Hongwan Liu, Timothy Cohen, and Mariangela Lisanti

For any questions, please email dropulic at princeton dot edu.

# Abstract:
The Gaia satellite will observe the positions and velocities of over a billion Milky Way stars. In the early data releases, the majority of observed stars do not have complete 6D phase-space information. In this Letter, we demonstrate the ability to infer the missing line-of-sight velocities until more spectroscopic observations become available. We utilize a novel neural network architecture that, after being trained on a subset of data with complete phase-space information, takes in a star’s 5D astrometry (angular coordinates, proper motions, and parallax) and outputs a predicted line-of-sight velocity with an associated uncertainty. Working with a mock Gaia catalog, we show that the network can successfully recover the distributions and correlations of each velocity component for stars that fall within ∼ 5 kpc of the Sun. We also demonstrate that the network can accurately reconstruct the velocity distribution of a kinematic substructure in the stellar halo that is spatially uniform, even when it comprises a small fraction of the total star count.

# MachineLearningStellarRV.ipynb

Contains an outline of the compound network structure described in the work cited above. We provide the outline of the definition of the training, validation, and test sets, in addition to the network structure and training procedure. 
