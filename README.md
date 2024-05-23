![header](header.png)

# Predicting Hotel Booking Cancellations to Minimize Revenue Loss due to False Negative

## About
This repository contains code and notebooks for building a classification model to predict booking cancellations in a Portuguese hotel. The model aims to identify bookings with a higher likelihood of cancellation (labeled as 1) compared to bookings that will not be cancelled (labeled as 0).

Project Goals
Develop a classification model to predict hotel booking cancellations.
Prioritize minimizing false negatives (missed cancellations) due to their higher cost compared to false positives.

## Data
This project utilizes a dataset containing booking information from a Portuguese hotel. 

## Methods
The project uses a classification approach to predict booking cancellations. The focus is on minimizing False Negative Rate (FNR) due to its higher cost implication compared to False Positive Rate (FPR).

The following steps outline the general approach:

Data Preprocessing: Clean and prepare the data for modeling, including handling missing values, encoding categorical variables, and feature engineering.
Model Training and Evaluation: Train various classification models and evaluate their performance using F2 score as the primary metric. F2 score balances precision and recall, making it suitable for our objective of minimizing both false positives and false negatives.
Model Selection: Select the model with the best F2 score for predicting booking cancellations.

## Results
The project achieved an F2 score of 0.72 using a Gaussian Naive Bayes model.

Additional Information:

The notebooks containing the detailed implementation of data preprocessing, model training, and evaluation can be found in the notebooks directory.
<b>Note</b>: Consider including hyperparameter tuning details or experiments with other classification models in this section or a separate file.

## Future Directions
Explore additional feature engineering techniques to improve model performance.
Investigate the use of cost-sensitive learning algorithms to explicitly address the imbalanced cost of classification errors.
Deploy the model into a production environment to predict cancellations and improve hotel revenue management.

## Getting Started
To replicate my analysis or explore the data further, kindly follow the following steps:
1. Clone this repository to your local machine.
```bash
git clone https://github.com/LingAdeu/hotel-booking-cancelation-prediction.git
```
2. Ensure that all necessary dependencies are installed, especially Python and Jupyter Notebook. All libraries are specified on file requirements.txt.
3. Run my Jupyter Notebook file (`*.ipynb`) in [notebook](https://github.com/LingAdeu/hotel-booking-cancelation-prediction/tree/main/notebook) folder to reproduce the analysis.

## Folder Organization

    .
    ├── README.md                           <- The top-level README for using this project.
    ├── data
    │   ├── data_description.txt
    │   └── dataset.csv                     <- Dataset
    ├── docs                                <- Documents associated with this projects
    ├── image                               <- Images
    │   └── flow.png
    ├── model                               <- Final model 
    │   └── final_model.pkl
    ├── notebook                            <- Jupyter notebook file for building the model
    │   └── notebook.ipynb
    ├── requirements.txt                    <- The requirements file for reproducing the environment.
    |                                          Generated using `pip freeze > requirements.txt`
    └── src

## Feedback
If there are any questions or suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>