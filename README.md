## GUM-Compliant PM2.5 Measurement Calibration for Low-Cost Optical Particle Counters

##  Overview
This repository provides the implementation for PM2.5 sensor calibration using Machine Learning models combined with GUM-based uncertainty quantification.
The work focuses on improving the reliability of low-cost optical particle counters (OPCs) by calibrating their measurements against reference-grade instruments.

The framework integrates machine learning models with Guide to the Expression of Uncertainty in Measurement (GUM) principles to produce accurate PM2.5 estimates along with quantified measurement uncertainty.

## Dataset
The study uses the QUANT dataset, which contains air quality sensor data used for calibration and evaluation.

Dataset link:
https://doi.org/10.1038/s41597-024-03767-2

##  Models Used
-The following models are implemented and evaluated:

1. XGBoost
2. LightGBM
3. Random Forest
4. Ensemble Model (NNLS – Non-Negative Least Squares)
## How to Run

1. Open the notebook in Google Colab.
2. Upload or connect the dataset.
3. Run all notebook cells sequentially.
4. The code will reproduce the calibration results and figures reported in the paper.

## Results

⦁ The repository reproduces the experimental results presented in the paper, including:

⦁ PM2.5 calibration performance

⦁ Model comparison

⦁ Ensemble prediction results

⦁ Uncertainty estimation following GUM methodology   

##  Authors
- Kavita
- Anirudh
- Vishal
- Savita Yadav
