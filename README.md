# NoiseMitigator
This is the repository for the code that uses a new Baysian noise model to mitigate noise in the simulation of the one-dimensional Z2 model.

The submit.ipynb contains the job submission file that obtains the bitstrings from the simulation of one-dimensional Z2 theory. In this repo, we use the Torino backend.

In the Torino53 folder, Subtraction_test.ipynb tests the noise mitigation in one of the Trotter step. It produces many useful plots as a form of sanity check. Then in Subtraction_bulk_new.ipynb, the mitigation technique is applied to all Trotter steps to obtain the final results.
