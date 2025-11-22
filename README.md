OCT Mini Project

This mini-project explores basic analysis of a retinal OCT B-scan. The goal is to understand simple image-processing steps that help visualise retinal structure, which is directly relevant to structure–function work in vision science.

What This Project Does
1. Intensity Profile Extraction

Loads a retinal OCT B-scan

Takes the central horizontal scan line

Plots pixel intensity across the retina

Shows peaks and dips that correspond to major retinal layers

2. Sobel Edge Detection

Applies the Sobel operator to detect edges in the OCT image

Highlights retinal layer boundaries

Displays original vs edge-detected images side-by-side

These steps form the foundation of automated OCT analysis.

Project Structure
oct-mini-project/
│
├── data/
│   └── (OCT image used in the notebook)
│
├── src/
│   └── plot_results.py
│
├── oct_intensity_profile.ipynb   # main notebook with analysis
│
└── README.md

Why This Matters

The methods used here are the first steps toward:

automated layer boundary detection

retinal morphometry

structure–function analysis

clinical OCT processing

machine learning applications for retinal imaging

This mini-project shows practical skills in Python, scientific plotting, and basic computer vision applied to retinal data.

Tools Used

Python

NumPy

Matplotlib

SciPy

Summary

This is a simple but meaningful project demonstrating the basics of OCT image analysis, including intensity profiling and edge-based visualisation of retinal layers. It serves as a foundational step toward deeper quantitative retinal imaging research.
