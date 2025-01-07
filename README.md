# Improving Exoplanetary Observations: Machine Learning Techniques for Spectrum Analysis and Uncertainty Quantification

## Overview
This project aims to enhance the analysis of exoplanetary atmospheres by integrating machine learning techniques with traditional data processing methods. The primary goal is to accurately extract subtle spectral signatures from noisy astronomical data, providing reliable atmospheric spectra and uncertainty quantifications.

## Background
Understanding the chemical composition, thermal dynamics, and potential habitability of exoplanets is crucial for planetary science. During planetary transits, starlight passing through an exoplanet's atmosphere imprints spectral patterns that reveal important atmospheric properties. However, extracting these signals from noisy data is challenging.

## Methodology
Our approach involves a multi-stage process:

1. **Data Cleaning and Calibration**: Initial steps include data cleaning and calibration to reduce detector-specific distortions and temporal variations.
2. **Exploratory Data Analysis (EDA)**: EDA helps detect patterns and irregularities in the complex spectrophotometric data.
3. **Machine Learning Models**: We employ a combination of linear regression, Gaussian Process Regression, and Convolutional Neural Networks (1D and 2D) to enhance the detrending process and accurately extract atmospheric spectra.

## Key Features
- **Robust Signal Extraction**: The framework effectively isolates faint exoplanetary signals from complex noise.
- **Uncertainty Quantification**: Provides strong uncertainty assessments, crucial for reliable scientific conclusions.
- **Scalability and Flexibility**: Suitable for various observational datasets, facilitating extensive exploration of exoplanet atmospheres.

## Results
Our findings indicate that the combined use of these methods significantly improves the precision and trustworthiness of exoplanet spectrum analysis. The 1D-CNN and 2D-CNN model, in particular, achieved a high score of 0.999, demonstrating its effectiveness in predicting atmospheric spectra.

## Future Directions
As observational technologies and algorithms advance, this framework is expected to evolve, further enhancing our understanding of planetary systems and their ability to support life.

## Acknowledgments
We acknowledge the contributions of all team members and the guidance provided by our mentor. This project was supported by the machine learning course at the Pittsburgh Institute, Sichuan University.


