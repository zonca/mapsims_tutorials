How to create a kernel at NERSC for mapsims
===========================================

Load the last Anaconda python:

    module load python

Create a conda environment and install all the packages that requires compilation:

    conda create -c conda-forge --prefix mbs python=3.7 astropy healpy pysm3 numba h5py libsharp=*=*openmpi* mpi4py ipykernel

Activate it with:

    source activate /full/path/to/mbs

Clone the `mapsims_tutorials` repository and:

    pip install -r requirements.txt

Install the kernel with:

    python -m ipykernel install --user --name python-mbs --display-name "Python MBS"
