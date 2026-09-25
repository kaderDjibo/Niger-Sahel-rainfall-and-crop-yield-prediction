#  AI-Powered Rainfall and Crop Yield Prediction for Niger and the Sahel

## Overview

This project predicts rainfall patterns and crop yield risk for Niger and the wider Sahel region using climate and agricultural indicators.

It is designed for development-impact use cases such as:

- Early warning for drought and food insecurity
- Agricultural planning
- Crop yield forecasting
- Humanitarian response planning
- Climate adaptation support for smallholder farmers

The project includes two machine learning tasks:

1. **Rainfall prediction**
   - Predicts seasonal rainfall in millimeters.

2. **Crop yield prediction**
   - Predicts crop yield, such as millet or sorghum yield in tons per hectare.

The project runs immediately with generated sample data, but can also be adapted to real data from sources such as CHIRPS, ERA5, FEWS NET, FAOSTAT, World Bank, national agriculture ministries, or local field surveys.

---

## Project Structure

```text
niger-sahel-rainfall-crop-ai/
├── README.md
├── requirements.txt
├── config.yaml
├── data/
│   ├── raw/
│   ├── processed/
│   └── sample/
├── models/
├── outputs/
│   ├── figures/
│   └── predictions/
├── src/
│   ├── make_sample_data.py
│   ├── preprocess.py
│   ├── train_rainfall_model.py
│   ├── train_crop_model.py
│   ├── predict.py
│   ├── evaluate.py
│   └── utils.py
└── app/
    └── simple_dashboard.py
