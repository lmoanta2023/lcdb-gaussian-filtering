# What is the Effect of Gaussian Filtering Applied Before Curve Fitting?
Liviu Moanta

code used for the thesis *What is the Effect of Gaussian Filtering Applied Before Curve Fitting?*\
BSc Computer Science and Engineering, TU Delft, 2025

## About
This project explores how applying Gaussian filters to learning curves affects curve fitting. Learning curves show how machine learning models improve as we use more training data.

This is part of the [Research Project 2025](https://github.com/TU-Delft-CSE/Research-Project) of [TU Delft](https://www.tudelft.nl/).

## Experiments done
- Raw vs. filtered learning curves with different sigma values.
- Fitted curves for raw vs. filtered data.
- Mean Squared Error (MSE) comparisons for extrapolation and interpolation.
- Boxplots comparing MSEs for raw and filtered data.
- Histogram differences between filtered and raw MSEs.
- Identification of noisy vs. smooth datasets.

### How to run
1. Install `numpy`, `scipy`, `matplotlib`, `h5py`, `sklearn`.
 2. Load the LCDB dataset and export to hdf5.

---

**Dataset**: All learning curves come from the dataset of [LCDB](https://github.com/fmohr/lcdb).

