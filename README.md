![logo.png](logo.png)

# Graph-spa - A Spatiotemporal Graph Learning Approach for Dynamic Prediction of Acute Respiratory Failure Using High-Dimensional ICU Data
--- 
# Documentation

This document provides an overview and descriptions of the various files and directories within the project.
## Jupyter Notebooks

- **Figure_02_03_plots.ipynb**: Contains code to generate Figure 02 and Figure 03.
- **Figure_04_plot.ipynb**:     Contains code to generate Figure 04.
- **Graph-spa_training.ipynb**: Training code for Graph-spa model
- **Graph-spa_training_and_extraction.ipynb**:  Training code for Graph-spa model with the extraction of features graphs

## Python Files

- **layer_dev.py**: contains classes for each layer of the model; upgraded version of layer.py from https://github.com/liuxz1011/TodyNet
- **layer_dev_graph.py**: contains classes for each layer of the model with the extraction of features graphs from the temporal graph pooling layer; an upgraded version of layer.py from https://github.com/liuxz1011/TodyNet
- **loader.py**: modified data loader file resourced from https://github.com/ratschlab/HIRID-ICU-Benchmark
- **net_dev.py**: model adapted from https://github.com/liuxz1011/TodyNet 
- **net_dev_graph.py**: model adapted from https://github.com/liuxz1011/TodyNet with extraction of feature graphs

## Miscellaneous Files

- **varname_clean.csv**: Clean variable names from HiRID: modified from https://github.com/ratschlab/HIRID-ICU-Benchmark

## Directories

### matrix

contains numpy matrix for plotting Figure 04

### saved_models

example of a best-performing saved model 

### data
We do not have the authorization to share the HiRID ICU Benchmark dataset. Please contact https://github.com/ratschlab/HIRID-ICU-Benchmark and https://physionet.org/content/hirid/1.1.1/

