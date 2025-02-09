# Deep Generative Models: Complexity, Dimensionality, and Approximation

Simulations repo with full implementation details for "Deep Generative Models: Complexity,
Dimensionality, and Approximation." All experiments were run on a single machine with an RTX 4080 GPU (16 GB VRAM), however, all simulations as presented should not use anywhere near that much memory. The code is provided in notebooks with output saved.  

## Files
All source code for generating figures and performing experiments for the main paper and appendix can be found in /simulations/.


## Main Dependencies 
The main dependencies to run the notebooks are listed below:

    - torch
    - ot (python optimal transport, https://pythonot.github.io) 
    - numpy
    - matplotlib
    - scipy

## References

Simulations presented here are adapted from examples provided in the POT package (https://pythonot.github.io/auto_examples/backends/plot_wass2_gan_torch.html#sphx-glr-auto-examples-backends-plot-wass2-gan-torch-py) 
