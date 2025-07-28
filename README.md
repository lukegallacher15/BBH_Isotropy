The following notebooks contain various models for the BBH merger sky distribution, using hierarchical Bayesian modelling via GWPopulation.
The data_preprocessor notebook helps to clean up the raw posterior data from the LIGO O3 data release, which can be downloaded from Zenodo if needed.
The anisotropy_checker notebook lets you alter sky locations of the samples to test if the model can detect anisotropy.

Note: these models use GPU acceleration, and should be converted into scripts for the Condor server, rather than running on wiay. Otherwise, they may interfere with others' work.
