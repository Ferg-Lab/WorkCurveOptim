# Work curve optimization using CMA-ES for optical matter control

Preliminary write-up of the methods performed here can be found via the editable overleaf link here: https://www.overleaf.com/2569423381jyqmbfyxvggr

A PDF version of this write-up can also be found in `manuscript.pdf` located within this repo.

`src` directory contains code for performing the optimization

Running `python submit.py` sets up experiments with different hyperparameters and executes them on midway3. The parameters defined in `submit.py` allow you to choose which parameters to screen over such as the target seperations to optimize for, the starting points of the particles, the regularization factors, etc.. (see the `args` variable defined in `submit.py` for the range of possible different parameters)

The `Analysis_*.ipynb` scripts show some examples of how to analyze the outputs from the submission files and visualize the results. The results of the experiments were too large to upload to github, but can be found at the following path: `/scratch/midway3/kirills/WorkCurveOptim/Experiments`

The `Control.ipynb` notebook shows how using learned beam parameters to perform an experiment that executes and switches between different beams states to control optical matter dimer seperations.



