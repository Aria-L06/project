# LncRNA-MiRNA Interaction Prediction Based on Multi-source Heterogeneous Graph Neural Network and Multi-level Attention Mechanism

## Overview
The code for paper "LncRNA-MiRNA Interaction Prediction Based on Multi-source Heterogeneous Graph Neural Network and Multi-level Attention Mechanism". The repository is organized as follows:
+ 'data/interaction' is the interaction data of mirna and lncrna with diseases, drugs and mRNA respectively
+ 'data/lncRNA(miRNA)' is the node attribute-based and topological features of lncRNA(miRNA)
+ 'code/feature' is the RNA feature extraction
+ 'code' contains the code for the LMI-MM

## Requirements
*pytorch ==2.0.3
*numpy == 2.0.1
*pandas == 2.2.3
*torch == 2.5.1
*sklearn == 1.5.2

## Data source
In the dataset, we collected a total of 2,621 experimentally validated lncRNA–disease associations from the Lnc2Cancer v3.0 and LncRNADisease v3.0 databases; 3,221 miRNA–disease associations from HMDD v4.0 database; 2,146 lncRNA–miRNA interactions from ENCORI database; 345 small-molecule drug–lncRNA associations from DrugBank database; 1,854 small-molecule drug–miRNA associations from SM2miR v3.0, RNAInter v4.0, NoncoRNA, and ncDR databases; as well as 363 mRNA–lncRNA and 3,048 mRNA–miRNA associations from the RISE database. 

## Quick Start
Here we provide a example to predict the lncRNA-miRNA interaction scores on dataset:
1.  Download and upzip our data and code files
2.  The data path in the `code/utils.py` file has been updated to `Example/data`.
3.  Run main.py (in file-- code/main.py)
