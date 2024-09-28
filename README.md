# No-Code Classification Model Trainer

This project enables users to train and evaluate classification machine learning models without writing a single line of code. Built with Streamlit, the application provides an interactive interface to load datasets, preprocess data, select machine learning models, and evaluate the model’s performance. It supports multiple models including Logistic Regression, Support Vector Classifier, Random Forest, and XGBoost.

## Features
- **Dataset Handling**: Load CSV and Excel files for training.
- **Data Preprocessing**: Automatically handles missing values, numerical scaling, and categorical encoding.
- **Model Selection**: Choose from Logistic Regression, SVC, Random Forest, or XGBoost for model training.
- **Model Training**: Train your selected model with the preprocessed data.
- **Model Evaluation**: Provides test accuracy results for trained models.
- **Model Saving**: Trained models are saved in a pkl format for later use.

## Installation
1. **Clone the repository**:

  ```bash
  git clone https://github.com/mshaadk/No-Code-Classification-Model-Trainer.git
  ```

2. **Install the required dependencies**:

  ```bash
  pip install -r requirements.txt
  ```

3. **Run the application**:

  ```bash
  streamlit run main.py
  ```

## Usage
- **Select Dataset**: Upload your dataset in CSV or Excel format.
- **Data Preprocessing**: Choose a target column and a scaling technique.
- **Model Selection**: Select a machine learning model for training.
- **Model Training**: Click on "Train the Model" to initiate training.
- **Model Evaluation**: View the test accuracy and model performance.
- **Model Saving**: The trained model will be saved for later use in the trained_model/ folder.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE.txt) file for details.

## Collaborations
We welcome contributions and collaborations to enhance the project! 
