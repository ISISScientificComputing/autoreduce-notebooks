# Autoreduce Notebooks

This repository contains some helper notebooks for calculating plots for presentations and statistics.

# Running jupyter

`pip install jupyter` and run the Jupyter server with `jupyter notebook`.

# Adding a conda environment as a Jupyter kernel

You need to `pip install ipykernel` and then register the conda environment. Replace `<conda_env_name>` with the actual name of the environment from `conda list`.

```
python -m ipykernel install --user --name=<conda_env_name>
```
