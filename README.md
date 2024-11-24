# Investigating the role of neuroinflammation in Amyotrophic Lateral Sclerosis using hiPSC-Microglia

This repository contains the scripts used for image analysis in this thesis project.

To begin, create a conda environment. Use the following command to create a new environment from the environment.yml file:
```
conda env create -f environment.yml
```

The notebooks contain the scripts needed for automating puncta analysis and skeleton-spine density analysis. All you need to do is replace the input and output directories with the ones your images are stored in.

The data processing notebooks have custom codes created specifically for this project, e.g. names of the cell lines. Modify them or remove them before using the scripts for a different project.
