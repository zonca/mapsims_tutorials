![Tests](https://github.com/simonsobs/mapsims_tutorials/workflows/Python%20package/badge.svg)

`mapsims` tutorials
===================

Notebooks on how to use [`mapsims`](https://github.com/simonsobs/mapsims) and [Simons Observatory's map based simulations](https://github.com/simonsobs/map_based_simulations).

## Setup at NERSC

* Login to [Jupyter@NERSC](https://jupyter.nersc.gov)
* Open a terminal
* Clone this repository:

        git clone https://github.com/simonsobs/mapsims_tutorials

* Run the kernel installation script:

        bash install_mbs_kernel_nersc.sh

* Refresh the browser page
* You should have now the "Simons Obs MBS" kernel


## Local setup

The only tricky dependencies of `mapsims` are `healpy` and `pysm3`.
It is easier to install them with Conda, but pip should work as well:

    conda install healpy pysm3

The tutorial requires `mapsims`, `so_noise_models` and `pixell`, they can be installed with:

    pip install -r requirements.txt
