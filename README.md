# COVID-19 analysis

Mainly Italy.

# Contribute

If you spot any inaccuracy please file [an issue on GitHub](https://github.com/alexamici/covid-19-notebooks/issues)

Contributions in the form of a Pull Request are welcomed as long as they are scientifically sound.

# Development

If you don't have *conda* installed, install [miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/): 

Clone the repo and set up the conda environment:

```
git clone https://github.com/alexamici/covid-19-notebooks.git
cd covid-19-notebooks
conda env create -f envirnoment.yaml
```

Activate the COVID19 environment and start up the notebook server:

```
conda activate COVID19
jupyter notebook
```