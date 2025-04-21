# LncRNA-MiRNA Interaction Prediction Based on Multi-source Heterogeneous Graph Neural Network and Multi-level Attention Mechanism

## Overview
The code for paper "LncRNA-MiRNA Interaction Prediction Based on Multi-source Heterogeneous Graph Neural Network and Mul-ti-level Attention Mechanism". The repository is organized as follows:
+ 'data/interaction' is the interaction data of mirna and lncrna with diseases, drugs and mRNA respectively
+ 'data/lncRNA(miRNA)' is the node attributes and topological features of lncRNA(miRNA)
+ 'code/feature' is the RNA feature extraction
+ 'code' contains the code for the LMI-MM

## Requirements
*pytorch ==2.0.3
*numpy == 2.0.1
*pandas == 2.2.3
*torch == 2.5.1
*sklearn == 1.5.2

## Quick Start
Here we provide a example to predict the lncRNA-miRNA interaction scores on dataset:

1.  Download and upzip our data and code files
2.  Run main.py (in file-- code/main.py)
