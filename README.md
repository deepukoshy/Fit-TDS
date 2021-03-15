# Fit-TDS
This repository is a clone of the updated fit@TDS (fit@TDS 2.0) software. A python code aiming at the retrieving of material parameter from a TeraHertz time domain spectroscopy (TDS) measurements from a fit in the time domain.
Improvements over original fit@TDS as explained by the authors

New graphical user interface:
It is possible to preview the result before launching the optimization. This makes errors easier to spot.
For more clarity, everything happens in a single window with several tabs which represent the steps (initialisation, parameters, optimization). There is also a dedicated space for progression and error display.
It is possible to go back and change parameters and files: the user can correct errors or try different parameters without launching the software several times.

New Features:
Debye oscillator model is implemented.
It is possible to take into account the scattering (Rayleigh)
The user can change change optimization parameters (swarmsize and number of iterations). They also get an output file with informations about the optimization and the history of parameters values.

The code is explained in :


THz-TDS time-trace analysis for the extraction of material and metamaterial parameters 

Romain Peretti, Sergey Mitryukovskiy, Kevin Froberger, Aniss Mebarki, Sophie Eliet, Mathias Vanwolleghem, Jean-Francois Lampin, Melanie Lavancier and and Nabil Vindas 

IEEE Transactions on Terahertz Science and Technology, Volume 9, Issue 2 \n 

DOI: 10.1109/TTHZ.2018.2889227 

Or in Arxive :

https://arxiv.org/abs/1810.12567
