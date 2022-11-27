# Bayesian inference for a phenomenological Supernovae model 

A jupyter notebook evaluating MCMC and VI to perform bayesian inference on the parameters of the Bazin Supernovae model. 

In this simple example a SNe light curve is first simulated using the Bazin model. A well-calibrated inference method should be able to recover the parameters from which the light curve was simulated.

The [NumPyro](https://num.pyro.ai/en/stable/index.html) library is used to perform inference and the HoloViews library is used for visualizations.

See a rendered version of the notebook at: https://phuijse.github.io/bayesian_bazin/
