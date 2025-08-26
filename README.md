# Report - Comparative Analysis of Interaction Layers in Criminal Networks

University project for the course *Social Network Analysys*, Università di Bologna, *y.2024/2025*

**Professor**: Saverio Giallorenzo

**Students**: Angelo Greco, Francesca Mazzetti, Gianpiero Giuseppe Tovo, Giuseppe Scafa

========
## Overview

This project aims to perform a **comparative analysis** of interaction layers in a criminal network, specifically based on data from the Italian police operation "*Montagna*". We examine two interaction layers:

* In-person meetings network

* Phone calls network

We apply structural and centrality measures, as well as many others (homophily and assortativity tests, small-worldness analysis, community detection, core-periphery and scale-free analysis). These have all been applied in order to uncover similarities and differences in the networks’ structures and their key actors.

========
## Dataset and data preprocessing

In the `Dataset` folder, there are the networks obtained from the "Montagna" italian police operation. The 'Original' version is the one downloaded on [zenodo](https://zenodo.org/records/3938818)

All data preprocessing steps are performed in `DatasetCleaning.ipynb`, which cleans the edge lists for Meetings and Phone Calls network by removing self-loops and duplicate edges (which are then aggregated by weight).
It then applies similiar cleaning procedures to the 'Roles' file, and saves the resulting data in the 'Cleaned' dataset.

All operations in the main `Project.ipynb` file are applied on the 'Cleaned' dataset.