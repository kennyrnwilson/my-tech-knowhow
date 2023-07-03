# How to Install and Run Polyglot on windows 

First follow all the instruction [here](../../python/howtow/install-and-run-jupyter-on-windows.md) then make sure you add the polyglot Visual Studio code addin. TO be able to run [hello-polyglot-python.ipynb](./hello-polyglot-python.ipynb) you need to know what kernel-specs are installed. 


We need to ensure the value of the --kernel-spec parameter in the 

```#!connect jupyter --kernel-name mykernel --kernel-spec <value>``

equals one of the kernelspec returned by the command

```
jupyter kernelspec list
```