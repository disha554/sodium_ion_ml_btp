# Machine Learning-Guided Design and Optimisation of Layered Oxide Cathodes for Sodium-Ion Batteries

## Project Overview

This project explores the application of machine learning to analyse and optimise layered transition-metal oxide cathode compositions for sodium-ion batteries.

A literature-derived dataset was developed using information extracted from research publications. The data was processed to create machine-learning-ready datasets, which were subsequently used to develop predictive models and investigate promising cathode compositions.

The project aims to identify composition-related trends and support data-driven screening of candidate cathode materials.

## Objectives

- Develop a structured database of layered oxide cathode materials from research literature.
- Clean and preprocess the collected data for machine learning applications.
- Develop predictive models for initial specific capacity and capacity retention.
- Evaluate and compare the performance of multiple machine learning models.
- Use SHAP analysis to interpret model predictions and identify influential features.
- Explore candidate cathode compositions through Bayesian optimisation and Pareto-based analysis.

## Project Workflow

1. **Literature Data Collection:** Extract relevant electrochemical and material information from research publications.
2. **Data Preprocessing:** Clean the database, handle missing values and prepare model-specific datasets.
3. **Feature Engineering:** Prepare relevant input features for predictive modelling.
4. **Model Development:** Train and evaluate multiple machine learning models.
5. **Model Interpretation:** Apply SHAP analysis to understand feature contributions.
6. **Optimisation:** Explore promising compositions using Bayesian optimisation and Pareto analysis.

## Repository Contents

| File | Description |
|---|---|
| `Final_Sodium_ML_Project.ipynb` | Main project notebook containing data processing, modelling, interpretation and optimisation workflows |
| `README.md` | Project overview and documentation |

## Dataset and Results

The original literature-derived database, cleaned dataset, model-ready datasets, model benchmarking results, optimisation outputs and supporting figures are archived separately in OneDrive.

**OneDrive Archive:** https://iitracin-my.sharepoint.com/:f:/g/personal/disha_a_ch_iitr_ac_in/IgDXRBd9ZFHhT4yjjgxuMwTwAaoqvnX1a1TfkmZtnWW_yFc?e=ii48uL

## Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Scikit-learn
- Machine Learning and ensemble modelling techniques
- SHAP for model interpretation
- Bayesian optimisation and Pareto analysis

*The exact software dependencies should be confirmed from the imports used in the final notebook.*

## Reproducibility

The main computational workflow is provided in the Jupyter Notebook. The associated datasets and generated results are available through the OneDrive archive linked above.

The notebook should be executed using the corresponding archived datasets and the required Python libraries.

## Important Notes

- The dataset is derived from published research literature.
- Model predictions and optimisation outputs are computational results and should not be interpreted as experimental validation.
- Any estimated energy-density values depend on the assumptions used in the analysis.

## Acknowledgements

This work was carried out as part of the B.Tech. Project (CHP400A) at the Department of Chemical Engineering, Indian Institute of Technology Roorkee, under the guidance of Dr.Ashish Yadav.

## Author

Disha Agarwal
Department of Chemical Engineering  
Indian Institute of Technology Roorkee
