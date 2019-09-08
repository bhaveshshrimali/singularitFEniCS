# singularityFEniCS
Stable container for [FEniCS 2019.1.0](https://fenicsproject.org/download/) with necessary dependencies. For questions/concerns email [bhavesh.shrimali@gmail.com](mailto:bhavesh.shrimali@gmail.com)

## netgenNew.recipe (stable and working)
   * Status: Working
   * To `install`, first download and install [Singularity](https://sylabs.io/singularity/) and pull the image using `singularity pull [options] shub://bhaveshshrimali/singularitFEniCS:recipe` or download the recipe file and locally build using `singularity build [options] netgenNew.recipe`
   * The recipe installs the open source meshing software [Netgen](https://ngsolve.org/) and `ffmpeg` on top of the latest stable `dolfin` docker image 
   * To use, simply `shell`-in using `singularity shell ... ` and run files as from the terminal. For more details and options, specifically for deploying it on a HPC cluster, see the singularity documentation above.
