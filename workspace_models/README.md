## Contents
- echo_state_network: The model trying to explain CB by comparing the prediction error signals of ESN in CB and non-CB timings.
    - See the README at the subfolder for knowing the detail. 
- mcmc_model: The model trying to explain CB by comparing the prediction error signals of Bayesian model in CB and non-CB timings.
    - See the README at the subfolder for knowing the detail. 
- kalman_filter: The model trying to explain CB by comparing the Kalman Gain in CB and non-CB timings.
    - kf_cb.ipynb: simulation code for CB signal
    - kf_control.ipynb: simulation code for non-CB signal
- epsilon_machine: WIP.
- vector_image_compression_rate: Predicting whether CB happens or not by comparing the data size of vector images before/after CB.