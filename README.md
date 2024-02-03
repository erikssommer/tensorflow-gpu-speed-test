# Tensorflow GPU speed test
Testing GPU speed using tensorflow 

## Setup for mac os (intel)

### Create conda environment
```bash
conda create --name metal python=3.8
conda activate metal
```

### Install tensorflow for mac os
```bash
SYSTEM_VERSION_COMPAT=0 python -m pip install tensorflow-macos
SYSTEM_VERSION_COMPAT=0 python -m pip install tensorflow-metal
```

### Install other packages
```bash
python -m pip install ipykernel
python -m pip install matplotlib
python -m pip install tensorflow-datasets
```
