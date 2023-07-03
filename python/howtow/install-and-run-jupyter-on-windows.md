# Install and Run Jupyter on windows

Make sure you follow all the steps on [Install Pyton On Windows](./install-and-run-on-windows)

## Install Jupyter
use the command 

```
pip list
```

to check if its already installed. You will see jupyter. If not run

```
pip install jupyter
```

## Check Kernel Specs
Enter the command

```
jupyter kernelspec list
```

On my machine kernel specs are in the following directory

* %LOCALAPPDATA%/Programs/Python/Python311/share/jupyter/kernels

## Install Jupyter Extension in VS Code
The test it by "Create: New Jupyter Notebook"

## Run Jupyter standalone
run the following from cmd prompt

```
jupyter notebook
```