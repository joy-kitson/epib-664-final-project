# epib-664-final-project

## Setup
This project requires an up to date installation of the `R` programing language,
JupyterLab, and configuring a working `R` kernel for Jupyter. Instructions
for configuring all three can be found
[here](https://richpauloo.github.io/2018-05-16-Installing-the-R-kernel-in-Jupyter-Lab/).

Additionally, this project is configured by default to save all figures in
the `figs` directory, which is not included in the installation and should be
created at the top level directory of this repo prior to running the code
unless you wish to save the figures to another directory.

This code has several `R` packages as depencies. To install them, open up an
`R` session and run the following commands:

```
install.packages(mice)
install.packages(norm)
install.packages(ggplot2)
install.packages(psych)
install.packages(lmtest)
install.packages(tidyr)
```

## Running
In order to run this project, begin by starting a Jupyter ntoebook session.
This can be done by running the command
```jupyter notebook```
and opening up one of the links printed out by that command in a browser.

Once you have Jupyter open, select the `analysis.ipynb` notebook. This should
open up the notebook containing all the code. You may now run the code through
the Jupyter interface. To run the full notebook from scratch, select 'Kernel'
then 'Restart & Run All'.

If you wish to change which directory the final figures are saved to, you
simply set the variable `FIG_DIR` in the second input cell to point to the
desired location. Note that the directory you indicate should already exist.
