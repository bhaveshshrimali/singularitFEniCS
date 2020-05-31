# singularityFEniCS
Stable container for [FEniCS 2019.1.0](https://fenicsproject.org/download/) with necessary dependencies. For questions/concerns email [bhavesh.shrimali@gmail.com](mailto:bhavesh.shrimali@gmail.com)

## netgenNew.recipe (stable and working)
   * Status: working
   * To `install`, first download and install [Singularity](https://sylabs.io/singularity/) and pull the image using `singularity pull [options] shub://bhaveshshrimali/singularitFEniCS:recipe` or download the recipe file and locally build using `singularity build [options] netgenNew.recipe`
   * The recipe installs the open source meshing software [Netgen](https://ngsolve.org/) and `ffmpeg` on top of the latest stable `dolfin` docker image 
   * To use, simply `shell`-in using `singularity shell ... ` and run files as from the terminal. For more details and options, specifically for deploying it on a HPC cluster, see the singularity documentation above.

## singularityMixedFEniCS.recipe (stable and working)
   * Status: working
   * A docker layer with Cecile Daversin's [mixed-dimensional](https://bitbucket.org/fenics-project/dolfin/src/027d9cc4c80adc7d8e9080fb3cc15714ff1ca910/?at=cecile%2Fmixed-dimensional) branch and Netgen installed. 

## singularityMultiphenics.recipe (stable and working)
   * Status: working
   * A similar layer as above save that this one builds on top of Francesco Ballrain's [multiphenics](https://gitlab.com/multiphenics/multiphenics) library.

## fenics.recipe (testing)
   * Status: experimental
   * Contains the development version of dolfin with `NetGEN/NGSolve` along with `Gmsh-SDK`