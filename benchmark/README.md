# Using Kipoi for Benchmarking

## Setup
Kipoi requires conda to manage model dependencies. Make sure you have either anaconda (download page) or miniconda (download page) installed. If you are using OSX, see Installing python on OSX. Maintained python versions: >=3.6<=3.10.

- Install [miniconda](https://conda.io/miniconda.html) or [anaconda](https://conda.io/miniconda.html).
- Make sure you have the following packages installed:
  - conda:
    - `conda install -y -c conda-forge jupyterlab`
    - `conda install -y nb_conda datrie`
  - pip:
    - `pip install numpy pandas matplotlib seaborn snakemake kipoi>=0.6.0`
- Clone this repository: `git clone https://github.com/kipoi/examples.git && cd examples`

### Verify Kipoi

Run:

- `kipoi ls`

This will list all the models and checkout the model source to `~/.kipoi/models`.

### Install the common environment

- `kipoi env create shared/envs/kipoi-py3-keras2-tf1`

## Run

Activate the environment

- `source activate kipoi-shared__envs__kipoi-py3-keras2-tf1`

Save MCMC model and Gibbs sampling model according to steps in [contributing models](https://kipoi.org/docs/tutorials/contributing_models/).

Run the benchmarking notebook tf_binding_models.ipynb.


## References
- [kipoi.org](http://kipoi.org) - Main website
- [kipoi.org/docs](http://kipoi.org/docs) - Documentation
- [Kipoi paper](https://doi.org/10.1038/s41587-019-0140-0)
```
@article{kipoi,
  title={The Kipoi repository accelerates community exchange and reuse of predictive models for genomics},
  author={Avsec, Ziga and Kreuzhuber, Roman and Israeli, Johnny and Xu, Nancy and Cheng, Jun and Shrikumar, Avanti and Banerjee, Abhimanyu and Kim, Daniel S and Beier, Thorsten and Urban, Lara and others},
  journal={Nature biotechnology},
  pages={1},
  year={2019},
  publisher={Nature Publishing Group}
}
```