# startup-success-predictor
This repository contains the Python code and dataset for predicting whether a startup will succeed or fail using various ML techniques. The model is trained on a dataset containing multiple features like funding, industry, location, and other relevant attributes.

## Project Description
The objective of this project is to build a supervised classification model to predict startup success. We are using a binary classification approach where each startup is classified as either successful or failed based on the input features.

## Dataset
The dataset used in this project is sourced from Kaggle and includes features such as startup name, funding amount, funding rounds, industry category, location, and several others.

Source: [Kaggle Dataset](https://www.kaggle.com/datasets/yanmaksi/big-startup-secsees-fail-dataset-from-crunchbase)

## Features
- Name: Name of the startup
- Status: Current status (operating, closed)
- Funding Total USD: Total funding received in USD
- Funding Rounds: Number of funding rounds
- Category Code: Industry category
- Location: City, state, and country
- Additional features include dates of first and last funding.

## Requirements
Python 3.8+
Libraries: pandas, numpy, sklearn, imblearn, seaborn

## Installation
Clone this repository and install the required Python packages:

```bash
git clone https://github.com/your-github-username/startup-success-predictor.git
cd startup-success-predictor
pip install -r requirements.txt
```

## Usage
Run the Jupyter Notebook to see the model building process and predictions:

## Model
The model pipeline includes preprocessing with scaling and encoding, handling imbalanced data with SMOTE, and classification using Logistic Regression, Decision Trees, and other algorithms as explored in the notebook.

## Evaluation
The model is evaluated using accuracy, precision, recall, and F1-score metrics. Detailed evaluation is provided in the notebook.

## Contributing
Contributions are welcome. Please open an issue first to discuss what you would like to change. For major changes, please open an issue first to discuss what you would like to change.

## License
MIT

