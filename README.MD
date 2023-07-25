
This repository contains a port of the original Deep Dream Notebook from Caffe to PyTorch.

Credits:
- [Google Deep Dream Notebook](https://github.com/google/deepdream)
- <https://github.com/crowsonkb/pytorch-caffe-models>: port of the original caffe GoogLeNet weights to PyTorch


# Setup

## Requirements

- [conda](https://docs.conda.io/en/latest/miniconda.html)
- [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html)


## Setup conda environment & Jupyter Kernel

Create conda environment:

```sh
$ conda env create --file env.yml
```

Activate conda environment:

```sh
$ conda activate deepdream-pytorch
```

Install Jupyter kernel:

```sh
$ python -m ipykernel install --user --name=deepdream-pytorch
```


## Open the notebook

Now the `dream.ipynb` notebook can be opened in JupyterLab.
Make sure the `deepdream-pytorch` kernel is selected.
