# House Pricing Prediction

This project uses a house pricing dataset and a multiple linear regression model to predict property prices.

## What changed in v1.0.0

- The notebook now preprocesses the data by encoding categorical values and standardizing the feature columns.
- The model uses a broader feature set, including area, bedrooms, bathrooms, furnishing status, parking, basement, mainroad, guestroom, airconditioning, prefarea, and stories.
- Training is performed with gradient descent to learn the weights and bias for the regression model.
- The notebook now includes:
  - cost tracking during training
  - a visualization of the fitted regression relationship
  - predictions for multiple random examples

## Dataset

File: [house_pricing_dataset.csv](house_pricing_dataset.csv)

Columns:

- `price` (target)
- `area`
- `bedrooms`
- `bathrooms`
- `stories`
- `mainroad`
- `guestroom`
- `basement`
- `hotwaterheating`
- `airconditioning`
- `parking`
- `prefarea`
- `furnishingstatus`

## Workflow

1. Load the dataset from [house_pricing_dataset.csv](house_pricing_dataset.csv).
2. Clean and encode categorical values.
3. Standardize the selected features.
4. Train the linear regression model.
5. Visualize the fit and inspect prediction outputs.

## Files

- [main.ipynb](main.ipynb) — main analysis, model training, and visualizations
- [README.md](README.md) — project summary and workflow
