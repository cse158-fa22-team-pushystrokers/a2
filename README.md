# CSE 158/258, Fall 2022: Assignment 2
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cse158-fa22-team-pushystrokers/a2.git/HEAD)
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/cse158-fa22-team-pushystrokers/a2) 

```sh
mamba install -c conda-forge cudatoolkit cudatoolkit-dev
```

```python
keras.backend.clear_session()
```

```sh
echo 'export XLA_FLAGS=--xla_gpu_cuda_data_dir=/opt/conda/pkgs/cuda-toolkit/' > $CONDA_PREFIX/etc/conda/activate.d/activate-cuda-toolkit.sh && chmod +x $CONDA_PREFIX/etc/conda/activate.d/activate-cuda-toolkit.sh
```

```sh
jupyter kernelspec list

```