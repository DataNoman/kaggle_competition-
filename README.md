# Kaggle Competition: [fly-high-with-fds]

This repository contains a Jupyter Notebook and a CSV dataset used to predict [Customer Satisfaction] for the [fly-high-with-fds] on Kaggle. The notebook includes Exploratory Data Analysis (EDA), data cleaning, and machine learning models, including Decision Tree, Random Forest, and Gradient Boosting Ensemble (GBE), to improve prediction accuracy.

---

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Notebook Structure](#notebook-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

The goal of this project is to predict [Satisfaction] based on various features in the dataset. By leveraging EDA, data cleaning, and machine learning models, the notebook demonstrates an end-to-end approach to solving this Kaggle competition.

## Dataset

- **Source**: [[Link to Kaggle dataset](https://www.kaggle.com/competitions/fly-high-with-fds/data)]
- **File**: `data.csv`
- **Description**: The dataset is a customer satisfaction survey. The customers were asked several questions about themselves and the service of the company. 22 feature columns correspond to answers to the questions and 1 target column (satisfaction). Values of columns can be numerical or categorical, discrete or continuous, and of varying range. The “train.csv” file contains your training set. Your job is to make predictions on the “test.csv” file and upload them as a CSV file. Check “sample_submission.csv” to get an idea of what the submission file should look like.
- **Data Cleaning**: Missing values, outliers, and inconsistencies were handled in the notebook.

## Notebook Structure

The Jupyter Notebook `notebook.ipynb` includes:

1. **Exploratory Data Analysis (EDA)**:
   - Visualizations and summary statistics to understand the data distribution, correlations, and key insights.

2. **Data Cleaning**:
   - Imputing missing values, encoding categorical variables, and normalizing numerical features.

3. **Feature Engineering**:
   - Creating new features, transforming existing ones, and selecting the most important features for modeling.

4. **Machine Learning Models**:
   - **Decision Tree**: Initial baseline model to establish a performance benchmark.
   - **Random Forest**: Enhanced performance with ensemble method and fine-tuned hyperparameters.
   - **Gradient Boosting Ensemble (GBE)**: Model used to achieve optimal predictions with boosting technique.

5. **Evaluation**:
   - Model performance is assessed using metrics such as accuracy, precision, recall, and F1-score. Cross-validation and hyperparameter tuning are applied for model improvement.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
   ```

2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter Notebook:

   ```bash
   jupyter notebook kaggle_competition_notebook.ipynb
   ```

2. Follow the notebook sections for detailed steps in EDA, data cleaning, model training, and evaluation.

3. Modify parameters, models, or add your own insights to improve the prediction performance.

## Results

Summary of the model performances:

GBE model achieved the highest accuracy, making it our best-performing model for this competition.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
