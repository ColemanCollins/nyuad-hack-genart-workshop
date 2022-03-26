# 2022 NYUAD HACK Workshop Day Six: QC + Generative art

## Getting set up

You'll need version of Python (<=3.8) and Java (<=17) installed as prerequisites. [Install Python 3 it from python.org](https://www.python.org/downloads/) and [use one of py5's recommended java install methods](https://py5.ixora.io/content/install.html#install-java) if you need to.

This setup guide will also be using conda for environment management and install, so [install anaconda or miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html) if you don't have it.

Once you have conda and reasonable versions of Python and Java, you can create a conda environment with all of your requirements from the provided yml file:

```
conda env create -n quantum-genart -f environment.yml
```

This will qiskit for doing quantum stuff, py5 for doing generative art stuff, and some supporting packages for things like saving your art out to different formats

Once that's all installed, activate your conda environment:

```
conda activate quantum-genart
```

fire up Jupyter

```
jupyter lab
```

and open up `START_HERE.ipynb` to get coding!

## TODO

Update this repository after the workshop with the slides as PDF or something
