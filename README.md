# London Traffic Analytics: Predictive Modelling & Geospatial Insights
## Project Overview

This group consultancy project analyses traffic patterns across London using Department for Transport (DfT) datasets.

The objective was to:

- Identify congestion hotspots using spatial analysis

- Validate statistical relationships between road type and traffic intensity

- Develop a predictive machine learning model for traffic volume forecasting

- Deliver actionable insights to support urban planning and congestion management

## Project Type

Group consultancy project (4 members)

## My Contribution

I led the Geospatial Processing and Machine Learning components of the project.

### Geospatial Engineering

Built a GeoPandas pipeline to process spatial traffic datasets

Performed spatial joins between Traffic Count Points and the Major Road Database (MRDB)

Mapped AADF (Average Annual Daily Flow) values to London boroughs

Created hotspot visualisations to identify high-congestion zones

### Statistical Validation

Formulated and tested hypotheses (H1–H3) examining relationships between:

- Road classification

- Traffic intensity

- Spatial distribution of congestion

- Conducted statistical testing to validate findings

### Machine Learning Pipeline

Developed a gradient-boosted regression model (XGBoost / LightGBM).

Implemented time-aware train/test splitting.

Applied TimeSeries Cross-Validation to prevent data leakage.

Performed model evaluation using:

- MAE / RMSE

- Parity plots

- Error distribution analysis

- Applied SHAP for model interpretability to identify key traffic drivers

## Data Sources

- Department for Transport (DfT) – Local Authority Traffic Data

- Department for Transport – Traffic Count Point Data

- Major Road Network / Major Road Database (MRN / MRDB)

- AADF (Average Annual Daily Flow)

## Technical Stack

- Python
- GeoPandas
- Scikit-Learn
- XGBoost / LightGBM
- SHAP
- Matplotlib

## Results

Identification of high-density congestion hotspots across London boroughs.

Validated relationship between road type and traffic volume.

Interpretable ML model explaining key drivers of traffic intensity.
