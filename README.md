# Mushroom Classification Project

![Mushroom Image](mushroom.jpg)

This project involves analyzing and classifying mushrooms based on various features. It demonstrates the use of data preprocessing, exploratory data analysis, and machine learning to predict whether a mushroom is edible or poisonous.

## Project Structure

- *Jupyter Notebook*: The main code is in mushroom.ipynb, which includes data loading, preprocessing, model building, and evaluation.
- *Dataset*: The dataset used contains information about mushrooms, with features such as cap shape, color, odor, and more.

## Features of the Project

1. *Data Preprocessing*:
    - Handled missing values.
    - Encoded categorical variables.
    - Scaled numeric features (if any).

2. *Exploratory Data Analysis (EDA)*:
    - Visualized data distributions.
    - Identified correlations between features.

3. *Machine Learning Modeling*:
    - Built and trained a classification model.
    - Evaluated the model using metrics like accuracy, precision, recall, and F1 score.

## Installation

1. Clone the repository:
    bash
    git clone https://github.com/mohamedelsayadd/mushroom_classification.git
    cd mushroom-classification
    

2. Install dependencies:
    bash
    pip install -r requirements.txt
    

## Usage

1. Open the Jupyter Notebook:
    bash
    jupyter notebook mushroom.ipynb
    

2. Run the cells step by step to:
    - Load and preprocess the dataset.
    - Perform EDA.
    - Train and evaluate the machine learning model.

## Dataset

- The dataset includes features such as:
    - Cap shape
    - Cap surface
    - Odor
    - Habitat
    - Population
- The target variable is whether the mushroom is *edible* or *poisonous*.

## Results

- The trained model achieved:
    - *Accuracy*: 0.96
    - *Precision*: 95
    - *Recall*: 96
    - *F1 Score*: 95

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and make changes as you'd like. Submit a pull request for review.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/uciml/mushroom-classification).
