# Predicting Customer Churn within Waze

![Waze Logo](waze_logo.png)

Welcome to the README for the "Predicting Customer Churn within Waze" data science project. In this project, we build regression and machine learning models to predict customer churn within the Waze navigation app. Waze is a community-driven navigation app that provides real-time road alerts, live traffic updates, and interactive maps, helping millions of users reach their destinations efficiently.

## Project Overview

Customer churn prediction is crucial for maintaining user engagement and improving user experience within Waze. By leveraging machine learning techniques, we aim to predict when users might stop using the app and identify factors influencing their decision to churn.

## Installation

To run this project, you will need the following dependencies:

- pandas
- numpy
- matplotlib.pyplot
- seaborn
- scipy
- sklearn
- xgboost
- pickle

You can create a Conda environment with the required dependencies using the following command:

```
conda create -n waze_churn_prediction python=3.11
conda activate waze_churn_prediction
conda install pandas numpy matplotlib seaborn scipy scikit-learn xgboost
```

## Data Preparation

We used a public Waze dataset for this project. You can download the raw dataset from the `waze_dataset.csv` file in our GitHub repository. The data was loaded into a Pandas DataFrame for data exploration, analysis, and machine learning.

## Project Structure

- `waze_dataset.csv`: Raw dataset used for analysis.
- `inspect_and_analyze_data.ipynb`: Initial data inspection and exploration.
- `exploratory_data_analysis.ipynb`: In-depth exploratory data analysis.
- `hypothesis_testing_and_data_exploration.ipynb`: Hypothesis testing and further data exploration.
- `regression_modeling.ipynb`: Regression analysis for feature relationships.
- `machine_learning_modeling.ipynb`: Machine learning model development and evaluation.

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/dvlanl/waze_data_science_project.git
   cd waze_data_science_project
   ```

2. Set up the Conda environment and install dependencies (see the Installation section).

3. Open the Jupyter notebooks in the order mentioned above to explore the project step by step.

## Model Training and Evaluation

We employed various machine learning techniques to predict customer churn. The notebooks cover data preprocessing, feature engineering, model training, and evaluation using metrics like accuracy, precision, recall, and F1-score.

## Results and Future Work

The project has led to valuable insights into predicting customer churn within Waze. However, the model's performance suggests that further improvements are needed for practical decision-making. Future work could involve incorporating additional drive-level information, fine-tuning model parameters, and exploring more granular user interactions with the app.

## Contributions

We welcome contributions from the community. If you're interested in contributing, please fork this repository, make your changes, and submit a pull request.

## Contact Information

For questions or feedback, feel free to reach out to me at dylanxlam@gmail.com.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

We'd like to acknowledge the Waze community for providing the dataset and the open-source libraries that supported this project.

---
