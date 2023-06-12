# Apunte Interactivo - Haskell
Este apunte es un fork del Jupyter Notebook que contiene el material del libro **Learn You a Haskell**.
El notebook original puede conseguirse desde aquí: [https://github.com/IHaskell/learn-you-a-haskell-notebook](https://github.com/IHaskell/learn-you-a-haskell-notebook).

> ¡Probalo online!
> Este notebook se puede probar online gracias a Binder.
> 
> <a href="https://mybinder.org/v2/gh/paradigmas-de-programacion/haskell-notebook/master?urlpath=lab/tree/apunte/00-apunte-paradigmas.ipynb"><img src="https://raster.shields.io/badge/ejecutar-apunte%20interactivo-green"/></a>

Con objetivo de documentar el uso, se deja el resto del README intacto.

# How to run on your local computer in Visual Studio Code

Visual Studio Code has a
[Notebook UI](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
which you can use to run Jupyter kernels instead of the browser-based
JupyterLab or classic Jupyter UI.

Clone this repository with `git` and `cd` into the cloned directory

```bash
git clone https://github.com/IHaskell/learn-you-a-haskell-notebook.git
cd learn-you-a-haskell-notebook
code .
```

There is a Docker
[Visual Studio Code devcontainer](https://github.com/microsoft/vscode-dev-containers)
configuration in the [`.devcontainer`](.devcontainer) directory.

When you open Visual Studio Code by running `code .`, a pop-up dialog will
tell you that “Folder contains a Dev Container configuration file. Reopen folder
to develop in a container.” Click the button labelled __Reopen in Container__.

You will then be able to open the `.ipynb` chapter files in the `notebook`
directory.
