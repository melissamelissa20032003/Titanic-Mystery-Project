First Machine Learning Project: Titanic Mystery
Project Description:

The goal of this project is to predict the survival of passengers aboard the Titanic using machine learning techniques. The project utilizes the Titanic passenger dataset, which includes features such as name, age, ticket price, and more. By analyzing this data, we aim to determine who survived and who did not during this tragic event.
Explanation:

This project is completed as part of a machine learning course from Kaggle website. It is based on the tutorial provided by Alexis Cook, which served as a valuable resource and guide throughout the project.

The project involves three main files: testing_data, training_data, and a submission file.

    Training Data: The training_data file contains the dataset we use to train our machine learning model. We extract the target feature, which represents the survivors in this tragic accident. Using Python, we create a DataFrame from the training_data by converting it into a Python list. This DataFrame is used in the model fitting process.
 
 
 
 Model Fitting: We utilize the RandomForestClassifier algorithm, available in the scikit-learn library (imported as from sklearn.ensemble import RandomForestClassifier). This classifier creates multiple decision trees, specifying the depth and setting the random_state to 1. Setting a specific random_state ensures consistent results across runs. The RandomForestClassifier is used to predict the survival outcomes.

    Generating Submission File: Using the testing_data, we obtain the predictions for survival. These predictions are written to the submission file. The submission file consists of two columns: PersonID and a binary value indicating whether the person survived or not.

By following this process, we aim to accurately predict survival outcomes based on the given Titanic passenger data.
Prerequisites:

    Python
    pandas
    scikit-learn

Installation:

    Clone the repository.
    Install the required dependencies by running pip install -r requirements.txt.

Usage:

    Ensure the training_data and testing_data files are in the correct directory.
    Run the project script, main.py.
    Once the script finishes execution, check the generated submission file for the predicted survival outcomes.

Contribution Guidelines:

We welcome contributions to enhance this project. If you would like to contribute, please follow these steps:

    Fork the repository.
    Create a new branch for your feature or bug fix.
    Make the necessary changes and additions.
    Open a pull request, describing your changes and the purpose behind them.

License:

This project is licensed under the MIT License.
Acknowledgments:

We would like to express our gratitude to Alexis Cook for her tutorial on Kaggle, which served as a valuable resource and guide for completing this project.
Contact Information:

For any questions, feedback, or concerns regarding this project, please reach out to Melissa Boutlendj at melissaboutlendj@gmail.com.
