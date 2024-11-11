# Classification Project with Experiment and Final Analysis

This repository contains an end-to-end classification analysis project, including experimentation and final model implementation. The main focus of the project is to explore different classification models and optimize performance for a target outcome.

## Project Structure

- `comp.ipynb`: Jupyter notebook containing exploratory analysis and experimentation with different classification techniques and preprocessing methods. This notebook is intended for testing various approaches and selecting the best-performing models.
  
- `experiment.ipynb`: The final notebook, which implements the selected model(s) from the experimentation phase with optimized hyperparameters. This file is intended to produce the final results and performance metrics.

- `trial.ipynb`: The model with Logistic regression. Result is not bad. 

## Requirements

To run the notebooks, install the dependencies listed in the `requirements.txt` file. You can install these packages using:

```bash
pip install -r requirements.txt
```

## Key Libraries

pandas - for data manipulation
seaborn and matplotlib - for data visualization
scikit-learn - for model building and evaluation
optuna - for hyperparameter optimization
shap - for model interpretability

## Usage

Experiment Phase: Open and run experiment.ipynb to see the exploratory analysis, feature engineering, and model comparisons. This notebook includes different classification algorithms and preprocessing techniques.

## Final Model Implementation: 

Open and run comp.ipynb, which includes the final selected model(s) from the experimentation phase. This notebook will generate the optimized model outputs and provide the final evaluation metrics.

## Results

The results include Roc_auc_score and other performance metrics based on the final selected model. Details of each model's performance can be found in comp.ipynb.

## License

This project is licensed under the MIT License. See the LICENSE file for details.