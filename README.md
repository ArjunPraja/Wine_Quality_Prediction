# Wine Quality Prediction

This project is an example of using machine learning to predict the quality of white wine based on its attributes. It uses a Random Forest classifier to make predictions.

## Dataset

The dataset used for this project is "winequality_white.csv." It contains various attributes of white wine, and the goal is to predict the quality of wine based on these attributes. The "quality" column is used as the target variable.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn (sklearn)

## Getting Started

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the `wine_quality_prediction.py` script to train the model and make predictions on the test set.

## Usage

Once you have set up the project and installed the required dependencies, you can run the `wine_quality_prediction.py` script. It will load the dataset, preprocess the data by splitting it into features (X) and target (y), and scale the features using StandardScaler. Then, it trains a Random Forest classifier on the scaled features to predict wine quality.

The script will output the accuracy of the model on the test set and display a classification report and a confusion matrix.

## Customization

If you want to experiment with different models, preprocessing techniques, or hyperparameters, you can modify the `wine_quality_prediction.py` script accordingly. You might also explore different visualizations or additional analysis based on the data.


