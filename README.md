# Quality Reports

## Getting Started

You should have [anaconda](https://www.anaconda.com/products/distribution) installed to use this repository.

- clone the repository 
`git clone https://github.com/cioos-atlantic/quality_reports`
`cd quality_reports`
- install the dependencies and activate the environment
`conda env update -f ./force/environment.yml --prune`
`conda activate quality`

If you are using VSCode IDE version 1.71 or higher, you can run a Jupyter notebook inside code.
Otherwise, you can launch the notebook yourself:

`jupyter notebook`


## Quality Reports on datasets

This repository will include reports created for each organization and dataset to assess high level data quality.

## General contents

- Jupyter Notebooks 
  - summary of data statistics
  - graphs/charts to highlight data presence/absence
- Data folder/output folder
- Conda environment.yml files to recreate environment locally
