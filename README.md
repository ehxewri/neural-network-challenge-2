# Neural Network Challenge - Employee Attrition and Department Fit Prediction

## Background
You are tasked with creating a neural network that HR can use to predict whether employees are likely to leave the company and identify the department that best fits each employee. This will be achieved using a branched neural network.

## Files
- Module 19 Challenge files (Download from the course platform)

## Setup
- Create a repository named `neural-network-challenge-2`.
- Clone the repository locally.
- Add `attrition.ipynb` to your repository.
- Push changes to GitHub.
- Work on `attrition.ipynb` in Google Colab.

## Instructions

### Part 1: Preprocessing
- **Import Data**: Load the dataset and inspect the first five rows.
- **Unique Values**: Determine the number of unique values in each column.
- **Create Target DataFrame**: Extract `attrition` and `department` columns into `y_df`.
- **Select Features**: Choose at least 10 columns for `X_df` excluding `attrition` and `department`.
- **Data Types**: Display data types in `X_df`.
- **Data Split**: Divide data into training and testing sets.
- **Convert to Numeric**: Ensure all X data are in numeric types, using encoders as necessary.
- **Scale Data**: Apply `StandardScaler` to the training and testing data.
- **Encode Outputs**: Use `OneHotEncoder` for `department` and `attrition` columns.

### Part 2: Model Building
- **Structure**: Build a non-sequential model with branched outputs.
- **Shared Layers**: Include at least two shared layers.
- **Branches**:
  - Department prediction branch with one hidden and one output layer.
  - Attrition prediction branch with one hidden and one output layer.
- **Compile**: Set up the model and compile it.
- **Training**: Train the model using the preprocessed data.
- **Evaluation**: Assess the model with testing data.

### Part 3: Summary
- **Accuracy Assessment**: Discuss if accuracy is the best metric for this model.
- **Activation Functions**: Justify the choice of activation functions for output layers.
- **Improvements**: Suggest ways to enhance the model.

## Hints and Considerations
- Ensure consistent preprocessing for training and testing data.
- Review branching neural network concepts as needed.

## Submission
Submit your GitHub repository URL through the course platform.

## Support
Utilize TA office hours, tutoring sessions, class Slack channel, and BCS Learning Assistants for help.

