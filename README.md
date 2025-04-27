# Titanic Survival Prediction

This project predicts the survival of passengers aboard the Titanic using machine learning techniques. It includes data preprocessing, feature engineering, model training, and evaluation.

## Project Overview

The notebook implements the following steps:
1. **Data Loading**: Load the Titanic dataset using `seaborn`.
2. **Exploratory Data Analysis (EDA)**: Analyze the dataset to understand the features and their distributions.
3. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Scale numerical features.
4. **Model Training**:
   - Train a Random Forest Classifier and Logistic Regression model using a pipeline.
   - Perform hyperparameter tuning using GridSearchCV.
5. **Model Evaluation**:
   - Evaluate the models using classification reports, confusion matrices, and feature importance visualizations.

## Requirements

The project requires the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install the required libraries using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-survival-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd titanic-survival-prediction
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Titanic_Survival_Prediction.ipynb
   ```
4. Run the cells sequentially to execute the analysis.

## Results

- The Random Forest Classifier and Logistic Regression models were trained and evaluated.
- The notebook includes visualizations for feature importance and confusion matrices.
- The test set accuracy and classification reports are displayed for both models.

## Project Structure

```
Titanic_Survival_Prediction/
├── Titanic_Survival_Prediction.ipynb  # Main notebook
├── README.md                          # Project documentation
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The Titanic dataset is provided by the `seaborn` library.
- Thanks to the open-source community for the tools and libraries used in this project.
