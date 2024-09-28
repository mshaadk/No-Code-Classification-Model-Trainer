This project enables users to train and evaluate machine learning models without writing a single line of code. Built with Streamlit, the application provides an interactive interface to load datasets, preprocess data, select machine learning models, and evaluate the model’s performance. It supports multiple models including Logistic Regression, Support Vector Classifier, Random Forest, and XGBoost.

Features
Dataset Handling: Load CSV and Excel files for training.
Data Preprocessing: Automatically handles missing values, numerical scaling, and categorical encoding.
Model Selection: Choose from Logistic Regression, SVC, Random Forest, or XGBoost for model training.
Model Training: Train your selected model with the preprocessed data.
Model Evaluation: Provides test accuracy results for trained models.
Model Saving: Trained models are saved in a pkl format for later use.
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/username/nocode-ml-trainer.git
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Run the application:

bash
Copy code
streamlit run main.py
Usage
Select Dataset: Upload your dataset in CSV or Excel format.
Data Preprocessing: Choose a target column and a scaling technique.
Model Selection: Select a machine learning model for training.
Model Training: Click on "Train the Model" to initiate training.
Model Evaluation: View the test accuracy and model performance.
Model Saving: The trained model will be saved for later use in the trained_model/ folder.
Tech Stack
Streamlit: For building the user interface.
scikit-learn: For model training and preprocessing.
XGBoost: For gradient boosting classification.
Pandas: For data manipulation.
Pickle: For saving the trained models.
License
This project is licensed under the MIT License. See the LICENSE file for details.

txt
Copy code
MIT License

Copyright (c) 2024 Mohamed Shaad

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
Collaborations
We welcome contributions and collaborations to enhance the project! Here are ways you can get involved:

Report Bugs: If you find any issues, feel free to open an issue on the GitHub repository.
Feature Requests: Have ideas to improve the project? Let us know through an issue or a pull request.
Contribute Code: Fork the repository, make your changes, and submit a pull request.
Documentation: Help improve the documentation by adding examples, tutorials, or updating existing sections.
Testing: Assist with testing the platform across various datasets and scenarios.
How to Collaborate:
Fork the repository and clone it to your local machine.
Create a branch for your feature or bug fix:
bash
Copy code
git checkout -b feature-branch
Commit your changes:
bash
Copy code
git commit -m "Add new feature"
Push your changes to the branch:
bash
Copy code
git push origin feature-branch
Open a pull request with a detailed description of your contribution.
Future Enhancements
Add more advanced preprocessing options.
Expand model library to include deep learning models.
Provide additional metrics like precision, recall, F1-score.
Allow users to download the trained model directly.
