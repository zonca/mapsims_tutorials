`mapsims` tutorials
===================

Notebooks on how to use [`mapsims`](https://github.com/simonsobs/mapsims) and [Simons Observatory's map based simulations](https://github.com/simonsobs/map_based_simulations).

## Setup at NERSC

Work in progress

## Local setup

The only tricky dependencies of `mapsims` are `healpy` and `pysm3`.
It is easier to install them with Conda, but pip should work as well:

    conda install healpy pysm3

The tutorial only requires `mapsims`, it can be installed via PyPI:

    pip install mapsims

The notebooks on CAR pixelization also require `pixell`:

    pip install pixell
