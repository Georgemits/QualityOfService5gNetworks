
# Quality of Service in 5G Networks

This repository contains the work on Quality of Service (QoS) in 5G networks, including data preprocessing, modeling, and analysis.

## Table of Contents
- [Overview](#overview)
- [Files](#files)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project aims to analyze and classify the QoS in 5G networks using various machine learning models. The work includes data preprocessing steps, implementation of different models, and the evaluation of their performance.

## Files
- `CODE_montelopoiisi_RANDOMFOREST.txt`: Random Forest model code.
- `CODE_montelopoiisi_XGBoost.txt`: XGBoost model code.
- `CODE_montelopoiisi_XGBoost_v2.txt`: Improved XGBoost model code.
- `CODE_proepeksergasia.txt`: Data preprocessing code.
- `PROEPEKSERGASIA.csv`: Initial dataset.
- `PROEPEKSERGASIA_EXCEL.csv`: Processed dataset.
- `QOS5G.pptx` and `QOS5Gv2.pptx`: Presentations.
- `Quality Of Service 5G Classification.docx`: Project documentation.
- `README.md`: This README file.

## Data Preprocessing
The dataset was preprocessed to handle missing values, normalize data, and perform feature engineering to prepare for modeling.

## Modeling
The models implemented include:
- **Random Forest**: For classification of QoS parameters.
- **XGBoost**: For enhanced performance and accuracy.
- **Improved XGBoost**: Further optimization of the XGBoost model.

## Results
The results of the models are documented and compared in the `Quality Of Service 5G Classification.docx` file.

## Installation
To run the code, ensure you have Python installed along with the following libraries:
```bash
pip install pandas numpy scikit-learn xgboost
```

## Usage
Run the preprocessing script first:
```bash
python CODE_proepeksergasia.txt
```
Then, execute the model scripts as needed:
```bash
python CODE_montelopoiisi_RANDOMFOREST.txt
python CODE_montelopoiisi_XGBoost.txt
python CODE_montelopoiisi_XGBoost_v2.txt
```

## License
This project is licensed under the MIT License.
