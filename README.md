# AMICAL

(**A**perture **M**asking **I**nterferometry **C**alibration and **A**nalysis **L**ibrary)

[![version](http://img.shields.io/badge/AMICAL-v1.0-orange.svg?style=flat)](https://github.com/SydneyAstrophotonicInstrumentationLab/AMICAL.git)

## Install from source (for conda-based systems)

It is recommended (though not mandatory) to create a separate environment with `conda create -n <env_name>`.
Then, within your Conda env (`conda activate <env_name>`):

```bash
# Firstly, clone AMICAL repository on your computer
git clone https://github.com/SydneyAstrophotonicInstrumentationLab/AMICAL.git

cd AMICAL/

# Install AMICAL
pip install .
```

## What can AMICAL do for you ?

See [example_NIRISS.py](example_NIRISS.py).

## Acknowledgements

This work is mainly a modern Python translation of the very well known (and old) IDL pipeline used to process and analyze Sparse Aperture Masking data. This pipeline, called "Sydney code", was developed by a lot of people over many years. Credit goes to the major developers, including Peter Tuthill, Mike Ireland and John Monnier. Many forks exist across the web and the last IDL version can be found [here](https://github.com/AnthonyCheetham/idl_masking). We hope that this brand new user-friendly Python version will be used in the future with the development of the AMI mode included with cutting edge instruments as JWST/NIRISS, VLT/SPHERE or VLT/VISIR (among others). ENJOY!
