Name: Marcelia Chintya Hartakaadi
ID: 1101223073

## Regression: California Housing Price Prediction
- File: Regresi_Marcelia_Chintya_(1101223073).ipynb
- Dataset: 20,640 samples, 13 features
- Baseline: Linear MLP, RMSE $74,599
- Final model: MLP with 2 hidden layers (64 neurons), ReLU, L2 regularization, early stopping
- Result: RMSE $55,618, improvement 25.4%

## Classification: Wine Producer Identification
- File: classification_Marcelia_Chintya_(1101223073).ipynb
- Dataset: 178 samples, 13 chemical features, 3 classes
- Model: 1D CNN (16 filters -> 32 filters -> GAP -> Dropout -> Dense 32 -> Dense 3 softmax)
- Test performance: F1 macro = 1.0, accuracy = 100%
- Cross-validation (5 folds): F1 macro = 0.949 (+/- 0.022)
