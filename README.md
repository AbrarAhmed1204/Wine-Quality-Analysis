# Wine Quality Prediction

## Overview
This repository contains code and resources for predicting the quality of red wine using machine learning techniques. The dataset used for this project is "red_wine.csv", which includes various features of red wine samples along with their corresponding quality ratings. The main focus of this project is to explore the data, perform analysis, and build a classification model using Random Forest algorithm to predict the quality of red wine.

## Dataset Description
The dataset "winequality_red.csv" consists of the following columns:
- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality (target variable)

## Files
- **winequality_red.csv:** This file contains the dataset with features and quality ratings of red wine samples.
- **Wine-Quality-Analysis.ipynb:** Jupyter notebook containing the code for data exploration, preprocessing, model training, and evaluation.
- **requirements.txt:** List of Python packages required to run the code in the Jupyter notebook.

## Data Exploration
In the Jupyter notebook, exploratory data analysis (EDA) is performed to gain insights into the dataset. This includes summary statistics, distribution plots, correlation analysis, and visualization of feature relationships. Understanding the data helps in preprocessing and selecting appropriate features for modeling.

## Modeling
A Random Forest classifier is trained on the dataset to predict the quality of red wine samples. Random Forest is chosen for its ability to handle both numerical and categorical features, as well as its robustness to overfitting. The model is evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score.

## Usage
To run the code in the Jupyter notebook, follow these steps:
1. Clone the repository to your local machine.
2. Ensure that Python and Jupyter notebook are installed.
3. Install the required Python packages using the command:

4. Open the Jupyter notebook "Wine_Quality_Analysis.ipynb" and execute the cells sequentially.

**Note:**
- The dataset "winequality_red.csv" should be placed in the same directory as the Jupyter notebook.
- Feel free to experiment with different machine learning algorithms, hyperparameters, and feature engineering techniques to improve the model's performance.

## Contributing
Contributions to this repository are welcome. If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any inquiries or questions, please contact [abrarahmed12.work@gmail.com](mailto:abrarahmed12.work@gmail.com).

## Acknowledgments
Special thanks to the creators of the dataset used in this project and to the open-source community for their valuable contributions to the field of machine learning.
