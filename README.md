# AstroVision

AstroVision is an AI-powered astronomy and astrophysics project developed using Python and deep learning techniques to analyze astronomical data and classify celestial objects from telescope imagery. The project focuses on combining astronomy with machine learning to automate the detection, classification, and analysis of objects such as stars, galaxies, and quasars using real astronomical datasets and FITS image files.

The system processes astronomical image data, extracts meaningful features, and applies convolutional neural networks (CNNs) for object classification. Along with classification, AstroVision also performs scientific estimations such as brightness, flux, distance calculations, and real-world object size estimation using metadata available in FITS headers.

This project demonstrates the practical integration of:

* Artificial Intelligence
* Deep Learning
* Computer Vision
* Astronomical Data Processing
* Scientific Computing

---

## Features

* Classification of celestial objects:

  * Stars
  * Galaxies
  * Quasars

* Processing and visualization of astronomical FITS images

* Deep learning model built using CNN architecture

* Data preprocessing and normalization pipeline

* HDF5 dataset conversion for efficient training

* Estimation of:

  * Flux
  * Magnitude
  * Distance
  * Real object size in parsecs

* Visualization of predictions and astronomical images

* Scientific workflow for astronomical image analysis

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* Astropy
* HDF5
* FITS Image Processing
* Convolutional Neural Networks (CNN)

---

## Dataset & Data Processing

The project works with astronomical datasets obtained from telescope archives such as:

* MAST (Mikulski Archive for Space Telescopes)

The raw FITS files are:

1. Downloaded from astronomical archives
2. Preprocessed and normalized
3. Converted into HDF5 format
4. Used for training and evaluation of the CNN model

The preprocessing stage improves model performance by preparing the image data for efficient deep learning training.

---

## Workflow

1. Load astronomical FITS images
2. Extract metadata from FITS headers
3. Preprocess and normalize image data
4. Convert datasets into HDF5 format
5. Train CNN model on labeled astronomical objects
6. Predict celestial object classes
7. Estimate scientific parameters
8. Visualize outputs and predictions

---

## Objectives

The primary objective of AstroVision is to explore how Artificial Intelligence can assist modern astronomy by:

* Automating celestial object classification
* Reducing manual astronomical analysis
* Improving large-scale space data processing
* Combining scientific computation with deep learning techniques

---

## Applications

* Astronomical object detection
* Space research automation
* Telescope image analysis
* Scientific data classification
* AI-assisted astrophysics research
* Educational astronomy projects

---


---

## Project Highlights

* Combines AI and astronomy into a single intelligent system
* Uses real astronomical image formats (FITS)
* Implements scientific calculations alongside deep learning
* Demonstrates practical astrophysics data analysis using machine learning

---


