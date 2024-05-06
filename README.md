# AlajVAE: Molecule Design Using Variational Autoencoders

AlajVAE is a deep generative model for drug discovery that leverages the power of Variational Autoencoders (VAE) to generate molecular graphs. This project aims to address the challenges of drug design by providing a method to generate new molecular structures with desirable properties. The name "Alaj" (علاج) means treatment and medicine in Persian, highlighting the project's focus on medical innovations.

*This project was done for fulfilling the requirements for the degree of Bachelor of Science in Computer Engineering at Amirkabir University of Technology, and was supervised by Dr. Amin Gheibi.*

## Overview

Graphs are a natural data structure for representing molecular structures. AlajVAE innovatively uses graph-based VAEs to learn and generate new molecules, which can significantly enhance the drug discovery process by exploring the vast chemical space more efficiently. By generating molecular graphs directly, AlajVAE overcomes the limitations of SMILES strings and offers a more accurate and flexible approach to molecular design.

This repository contains: 

- `AlajVAE.ipynb`: The main notebook containing the implementation of the AlajVAE model.
- `AlajVAE Paper.pdf`: The final report of the project containing literature review, detailed explanation of the model, its features, and the results of the experiments.
- `AlajVAE Presentation.pdf`: The presentation slides used for the final presentation of the project.
- `ENZYMES`: The dataset used to train and test the model. ENZYMES is a dataset of protein tertiary structures obtained from (Borgwardt et al., 2005) consisting of 600 enzymes from the BRENDA enzyme database (Schomburg et al., 2004). More information about the dataset can be found in `ENZYMES/README.txt`.





