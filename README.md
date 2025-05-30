# Advanced-Image-Processing-Pipeline
This is a comprehensive Python project that demonstrates an end-to-end image processing workflow. It features state-of-the-art techniques to grayscale, perform custom convolution filtering (including Gaussian smoothing), detect edges using the Sobel operator, and identify corners with the Harris Detector refined by NMS

# Advanced Image Processing Pipeline

[![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

## Overview
This repository provides a comprehensive implementation of an **advanced image processing pipeline** in Python. It covers several key steps:
- **Grayscale Conversion:** Transforming RGB images using perceptual weighting.
- **Custom Convolution:** Implementing a 2D convolution function from scratch with symmetric padding.
- **Gaussian Filtering:** Smoothing the image to reduce noise and prepare for feature detection.
- **Edge Detection:** Utilizing the Sobel operator to extract image gradients.
- **Harris Corner Detection:** Detecting and refining corner features with non-maximum suppression.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)
- [Author](#author)

## Features
- **Robust Preprocessing:** Convert images from RGB to grayscale using a perceptual luminance model.
- **Custom Filtering:** Apply convolution filters with custom implementations for flexibility and learning.
- **Smoothing & Noise Reduction:** Generate Gaussian kernels to smooth images effectively.
- **Edge & Feature Detection:** Use Sobel operators for edge detection and the Harris method for corner detection.
- **Optimization:** Enhance corner detection by performing Non-Maximum Suppression to extract only the most significant features.

## Project Structure

