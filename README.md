# CNN-Based Detection of Atmospheric Extreme Event Precursors
This project demonstrates a simplified prototype of applying Convolutional Neural Networks (CNNs) to identify atmospheric patterns that precede extreme weather events such as heat waves.
The work is inspired by research directions in physics-informed machine learning for climate predictability.

## Project Overview
Traditional extreme weather prediction relies on expensive numerical simulations.  
This project explores a complementary approach:
- Represent atmospheric fields as spatial images
- Train a CNN to recognize precursor patterns
- Output the probability of a future extreme event

This repository uses artificially created data that hopefully mimics:

- Mid-tropospheric circulation (Z500-like)
- Lower-tropospheric temperature (T850-like)

The model learns spatial features associated with blocking-like heatwave structures.


