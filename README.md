# Investigating the role of neuroinflammation in Amyotrophic Lateral Sclerosis using hiPSC-Microglia

This repository contains the scripts used for image analysis in this thesis project.

To begin, create a conda environment. Use the following command to create a new environment from the environment.yml file:
```
conda env create -f environment.yml
```

Next, create `data` folders to hold the input images, and `output` folders to receive the analysis outputs.

The notebooks contain the scripts needed for automating puncta analysis and skeleton-spine density analysis. All you need to do is replace the input and output directories with the ones your images are stored in.

Run the notebooks with the following prefixes in this order:
1. `analysis_`
2. `data_processing_`

Depending on the analysis, running the `analysis_` notebooks will give you measurements in `.csv` and processed images in `.tif` file formats.

Running the `data_processing_` notebooks will give you the final summary results in `.csv` format.

The `data_processing_` notebooks have custom codes created specifically for this project, e.g. the function `def classify_genotype(index):` which identifies the names of the cell lines. Modify them or remove them before using the scripts for a different project.


