## scRNA-seq analysis of bursal cell populations and their response to IBDV infection in chickens
Name: Poojitha Kolli

Programming Language: Python 

Date: Dec 7th 2023
### Discription:
   This repository contains a Python script for investigating the cellular diversity of immune and non-immune cells in the bursa of Fabricius (BF) of chickens infected with Infectious Bursal Disease Virus (IBDV) using single-cell RNA sequencing (scRNA-seq) data. Using the scanpy Python package, the workflow includes quality control, normalization, dimensionality reduction, batch correction, clustering, and cell type annotation based on marker genes. The dataset analyzed (GSE167377) covers control and IBDV-infected samples from 2- and 3-week-old chickens. Visualization using UMAP highlights the heterogeneity and response of BF cells to IBDV infection.

#### Required files:
GSE167377 dataset downloaded from GEO Database

integration_of_all_samples.py to analyse cellular diversity in all the samples from the dataset

#### Required packages: 
scanpy

pandas

numpy

bbknn

leidenalg

louvain

#### Installation

To install the dependencies, run the following commands:

```bash
pip install scanpy pandas numpy bbknn
conda install -y -c anaconda cmake
pip install leidenalg louvain
```

#### Execution:
1. Clone repository
2. Change working directory to location of files
          
           cd path/to files
          
3. Run
         
          integration_of_all_samples.py

4. Once execution is complete check output

