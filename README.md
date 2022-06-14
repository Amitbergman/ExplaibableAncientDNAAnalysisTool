# exML - explainable DNA analysis tool

This project includes a python system to classify a dataset of DNA reads (either ``.bam`` or ``.fasta`` files) and output the estimated proportion of different species in the dataset.
It also provides explanations to the output that make it more interpretale and resolve ambiguities in the output.

## Getting Started

These instructions will give you a copy of the project up and running on your local machine.

### Prerequisites

Requirements for running the GUI and the system on your **linux machine** (you can use [WSL](https://docs.microsoft.com/en-us/windows/wsl/install) if you have a windows machine): 
- [python](https://www.python.org/)
- [Jupyter notebooks](https://jupyter.org/)
- [biopython](https://biopython.org/)
- [SHAP](https://shap.readthedocs.io/en/latest/index.html)
- [pysam](https://pysam.readthedocs.io/en/latest/api.html)
- [joblib](https://joblib.readthedocs.io/en/latest/)
- [bioconda](https://bioconda.github.io/)

### Run the project

1. Clone this repo ``git clone https://github.com/Amitbergman/ExplaibableAncientDNAAnalysisTool.git``
2. Run ``Jupyter lab`` in root directory.
3. Run the ``Demo`` notebook for a step by step demonstration.
4. Run the ``GUI`` notebook for the GUI that interacts with the system. 
5. Choose a dataset to analyze from the datasets under the data directory.

## Authors
  - **Amit Bergman**
