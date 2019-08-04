# singularityFEniCS
Stable container for [FEniCS 2019.1.0](https://fenicsproject.org/download/) with necessary dependencies. For questions/concerns email [bhavesh.shrimali@gmail.com](mailto:bhavesh.shrimali@gmail.com)

## netgenNew.recipe (stable and working)
   * Status: Working
   * To `install`, first download and install [Singularity](https://sylabs.io/singularity/) and pull the image using `singularity pull [options] shub://bhaveshshrimali/singularitFEniCS:recipe` or download the recipe file and locally build using `singularity build [options] netgenNew.recipe`
   * Installs the open source meshing software [Netgen](https://ngsolve.org/) (it requires a `python3` installation beforehand) along with `DOLFIN 2019.1.0`.
   * To use simply shell in using `singularity shell` and run files. See the documentation above for more details on using on a HPC cluster.
