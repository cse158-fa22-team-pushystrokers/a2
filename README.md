# CSE 158/258, Fall 2022: Assignment 2

```sh
mamba install -c conda-forge cudatoolkit cudatoolkit-dev
```

```python
keras.backend.clear_session()
```

```sh
echo 'export XLA_FLAGS=--xla_gpu_cuda_data_dir=/opt/conda/pkgs/cuda-toolkit/' > $CONDA_PREFIX/etc/conda/activate.d/activate-cuda-toolkit.sh && chmod +x $CONDA_PREFIX/etc/conda/activate.d/activate-cuda-toolkit.sh
```