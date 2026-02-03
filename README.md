# PyTorch FP Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/CameronLarsonFLT/PyTorch_FP_Prediction/blob/main/PyTorch_FP.ipynb)

Train simple PyTorch regressors on **FPbase** fluorescent protein sequences to predict key photophysical properties from amino acid sequence.

## Features
- Pulls FP data from the FPbase API
- One-hot encodes protein sequences
- Trains a PyTorch regressor to predict:
  - `ex_max`, `em_max`, `brightness`, `pka`
- Saves training plots (loss + predicted vs observed)

## Run in Google Colab
Open the notebook in Colab:


## Notes
- FPbase API: https://www.fpbase.org/api/proteins/
- Intended as an educational / rapid-prototyping baseline model.
