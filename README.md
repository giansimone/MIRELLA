# MIRELLA
`MIRELLA` is the repository that contains the Python code that supports the findings of the study: 'MIRELLA:  A mathematical model explains the effect of miRNA (MI) REgulation on intracellular resource aLLocAtion.'

# Repo Contents 
+ [Notebooks](./notebooks/)
+ [Docs](./docs/)

# System Requirements
## Hardware Requirements
`MIRELLA` does not require any specific hardware to run the code using Python.

## OS Requirements
`MIRELLA` does not require any specific OS to run the code. The package has been tested on macOS Monterey v12.6.

## Software Dependencies
+ Standard Python Libraries
+ Scientific Python Libraries: `SciPy`, `NumPy`, `Pandas`, `Seaborn`


# Installation Guide

+ Using `pip`
1. Clone the repository  `git clone https://github.com/giansimone/MIRELLA.git`.
2. Create a virtual environment `python3 -m venv mirella_venv`
3. Activate the virtual environment `source mirella_venv/bin/activate`
4. Navigate to the repo `cd ./MIRELLA/`
5. Install the dependencies `pip install -r requirements.txt`.

+ Using `conda`
1. Clone the repository  `git clone https://github.com/giansimone/MIRELLA.git`.
2. Navigate to the repo `cd ./MIRELLA/`
3. Create a conda environment `conda env create -f environment.yml`

# Demo
See the [Instructions for Use](#instructions-for-use) section.

# Instructions for Use

+ Use the notebook `1_Notebook_Ribosome_Reallocation.ipynb` to generate the simulations shown in **Fig. 2c**, **Fig. 3a,b**, and **Supplementary Fig. S7**.
+ Use the notebook `2_Notebook_RNase_Realloaction.ipynb` to generate the simulations shown in **Fig. 4b**, **Supplementary Fig. S4**, and **Supplementary Fig. S5**.
+ Use the notebook `3_Notebook_SI.ipynb` to generate the computational analysis shown in **Supplementary Fig. S3**, and **Supplementary Fig. S6**.

# License
This code is licensed under the **MIT License**.
