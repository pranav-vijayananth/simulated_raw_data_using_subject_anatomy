# simulated_raw_data_using_subject_anatomy

As part of my research project, I simulated raw EEG data using subject-specific anatomical head models. The project demonstrates the use of MNE-Python to create realistic synthetic EEG signals by modeling neural activity propagation through a head model, incorporating standard electrode configurations. My goal with this notebook was to generate and analyze simulated EEG data for research purposes and to better study signal characteristics or testing analysis pipelines.


## Overview 
- The notebook constructs a forward model to simulate EEG signals based on a realistic head model derived from subject anatomy. Key steps include:
- Head Model Creation: Builds a multi-layer head model (scalp, skull, brain) to represent anatomical structures.
- Electrode Configuration: Places electrodes using the standard 10-20 system for realistic scalp measurements.
- Source Activity Simulation: Defines neural sources (e.g., dipoles) with specified activity patterns to mimic brain signals.
- Forward Modeling: Computes how neural activity projects to scalp electrodes, incorporating tissue conductivity.
- Signal Generation: Produces synthetic EEG time series with added noise to reflect real-world conditions.
- Visualization: Generates plots of electrode positions, head model geometry, and simulated EEG waveforms.
- Signal Realism: The generated EEG data captures expected patterns, such as amplitude variations and spatial distributions, consistent with anatomical constraints.
- Electrode Accuracy: The 10-20 system placement aligns with standard EEG setups, ensuring relevance for practical applications.
- Noise Integration: Adding realistic noise levels demonstrates the impact of environmental and physiological artifacts on EEG signals.
- Visualization Insights: Plots reveal clear relationships between source locations, head model properties, and scalp-recorded signals, aiding in the validation of the simulation.
