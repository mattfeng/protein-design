# openfold

## development notes
- starting from openfold commit [`15895ea94e7467d4565561f707fcd6b950d858be`](https://github.com/aqlaboratory/openfold/tree/15895ea94e7467d4565561f707fcd6b950d858be)


## setup

```bash
# Dependencies
conda install -c conda-forge pdbfixer
conda install -c conda-forge openmm

# Install GCC 12.1.0 for GLIBCXX 3.4.30 required by OpenMM
# source: https://github.com/openmm/openmm/issues/3943
conda install gcc=12.1.0

# Python dependencies
pip install ml_collections # https://github.com/google/ml_collections
pip install dm-tree        # https://github.com/google-deepmind/tree
```