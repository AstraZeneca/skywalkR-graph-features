# skywalkR-graph-features
![Maturity level-Prototype](https://img.shields.io/badge/Maturity%20Level-Prototype-red) [![DOI](https://zenodo.org/badge/426158485.svg)](https://zenodo.org/badge/latestdoi/426158485)


This repository contains example notebooks illustrating how to generate knowledge-graph based features. The same types of graph-derived features were used in [Gogleva et al, 2021 manuscript](https://www.biorxiv.org/content/10.1101/2021.07.23.453506v3) and [skywalkR app](https://github.com/AstraZeneca/skywalkR)
The repository contains two Jypyter notebooks: 
 - ``graph_features_Toy.ipynb`` - generate features based on a toy graph.
 - ``graph_features_Hetionet.ipynb`` - here we used [Hetionet graph](https://het.io/about/#whats-in-hetionet) as a representative example of reasonably complex biomedical graph;

### Set-up and installation instructions 

If not already installed on your setup, install Conda (eg. https://docs.conda.io/en/latest/miniconda.html ).

Run the following command to install RAPIDS-21.08 and the necessary package to run the notebook in a new Conda environment named `graphfeaturesnotebook`:

`conda env create -f rapids-notebook-req.yml`

Activate this environment with:

`conda activate graphfeaturesnotebook`

You can then package this environment in a Jupyter kernel:

`python -m ipykernel install --user --name=graphfeaturesnotebook`

The Jupyter kernel necessary to run this notebook should now be available in your favorite Jupyter instance.
