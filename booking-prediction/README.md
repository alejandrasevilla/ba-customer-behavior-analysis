# Booking Completion Prediction

This folder contains all files related to the predictive modeling of British Airways customer booking behavior.

## Files

- `holiday_booking_model.ipynb` – Notebook for data exploration, feature engineering, and machine learning pipeline.
- `BA_Review_Predict_Bookings.pptx` – Summary slide with model performance and business takeaways.

## Highlights

- Built a Random Forest model with `class_weight="balanced"` to handle class imbalance
- Feature engineering included log transforms and one-hot encoding for high-cardinality features
- Evaluated precision, recall, F1-score across different thresholds
- Analyzed feature importance using permutation impact on F1

## Performance

- F1 Score: 0.43
- Recall (Class 1): 0.63
- ROC AUC: 0.77

## Tools

`pandas` · `scikit-learn` · `matplotlib` · `seaborn` · `Jupyter`
