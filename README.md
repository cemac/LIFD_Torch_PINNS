<div align="center">
<img src="https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/blob/main/images/LIFDlogo.png"></a>
<a href="https://www.cemac.leeds.ac.uk/">
  <img src="https://github.com/cemac/cemac_generic/blob/master/Images/cemac.png"></a>
  <br>
</div>

# Leeds Institute for Fluid Dynamics Machine Learning For Earth Sciences #

# Physics Informed Neural Networks


[![GitHub release](https://img.shields.io/github/release/cemac/LIFD_ENV_ML_NOTEBOOKS.svg)](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/releases)  [![GitHub top language](https://img.shields.io/github/languages/top/cemac/LIFD_Torch_PINNS.svg)](https://github.com/cemac/LIFD_Torch_PINNS) [![GitHub issues](https://img.shields.io/github/issues/cemac/LIFD_Torch_PINNS.svg)](https://github.com/cemac/LIFD_Torch_PINNS/issues) [![GitHub last commit](https://img.shields.io/github/last-commit/cemac/LIFD_Torch_PINNS.svg)](https://github.com/cemac/LIFD_Torch_PINNS/commits/master) [![GitHub All Releases](https://img.shields.io/github/downloads/cemac/LIFD_Torch_PINNS/total.svg)](https://github.com/cemac/LIFD_Torch_PINNS/releases) ![GitHub](https://img.shields.io/github/license/cemac/LIFD_Torch_PINNS.svg)

These set of notebooks explore Physics Informed Neural Networks to explore partial differential equations

This tutorial has been split into 3 tutorials.

## Recommended Background Reading

If you are unfamiliar with some of the concepts covered in this tutorial it's recommended to read through the background reading below either as you go through the notebook or beforehand. These links are also contained within the notebooks

* [Introduction to Neural Networks](https://victorzhou.com/blog/intro-to-neural-networks/)
* [Physics Guided Neural Networks](https://towardsdatascience.com/physics-guided-neural-networks-pgnns-8fe9dbad9414)
* [Physics-Informed Neural Networks:  A Deep LearningFramework for Solving Forward and Inverse ProblemsInvolving Nonlinear Partial Differential Equations](https://www.sciencedirect.com/science/article/pii/S0021999118307125)

## Quick look


### Quick start

If you're already familiar with git, anaconda and virtual environments the environment you need to create is found in PINN.yml and the code below to install activate and launch the notebook. The .yml file has been tested on the latest linux, macOS and windows operating systems.

This notebook is based on two papers: *[Physics-Informed Neural Networks:  A Deep LearningFramework for Solving Forward and Inverse ProblemsInvolving Nonlinear Partial Differential Equations](https://www.sciencedirect.com/science/article/pii/S0021999118307125)* and *[Hidden Physics Models:  Machine Learning of NonlinearPartial Differential Equations](https://www.sciencedirect.com/science/article/pii/S0021999117309014)* with the help of  Fergus Shone and Michael Macraild.

These tutorials will go through solving Partial Differential Equations using Physics Informed Neuaral Networks focusing on the Burgers Equation and a more complex example using the Navier Stokes Equation


```bash
git clone  --recurse-submodules -j8 git@github.com:cemac/LIFD_Torch_PINNS.git
cd LIFD_Torch_PINNS
conda env create -f PINN_pytorch.yml
conda activate PINN
jupyter-notebook
```


## Installation and Requirements

This notebook is designed to run on a laptop with no special hardware required therefore recommended to do a local installation as outlined in the repository [howtorun](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/blob/main/howtorun.md) and [jupyter_notebooks](https://github.com/cemac/LIFD_ENV_ML_NOTEBOOKS/blob/main/jupyter_notebooks.md) sections.


These notebooks require some additional data from the [PINNs](https://github.com/maziarraissi/PINNs) repository

If you have not already then in your gitbash or terminal please run the following code in the LIFD_ENV_ML_NOTEBOOKS directory via the terminal(Mac or Linux)  or git bash (windows)

```bash
git submodule init
git submodule update --init --recursive
```

**If this does not work please clone the [PINNs](https://github.com/maziarraissi/PINNs) repository into your Physics_Informed_Neural_Networks folder on your computer**


# Licence information #

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">LIFD_ENV_ML_NOTEBOOKS</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://cemac.leeds.ac.uk/" property="cc:attributionName" rel="cc:attributionURL">cemac</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Acknowledgements

