![header](header.png)

# Predicting Hotel Booking Cancellations to Minimize Revenue Loss due to False Negative

## About
This repository contains the code and data files for building a classification model to predict booking cancellations in a Portuguese hotel. The goal of this model is to assist hotel managers in identifying reservations that are likely to be canceled (labeled as 1) versus those that will not be canceled (labeled as 0).

Given the significant cost associated with false negatives (missed cancellations), this project emphasizes minimizing these errors. To achieve this, we use the $F_2$ score as our primary evaluation metric, which places greater importance on recall, ensuring that potential cancellations are accurately identified.

By leveraging this model, hotel managers can better allocate resources, optimize inventory management, and reduce potential revenue loss due to unexpected cancellations.

## Data
This project utilizes a dataset containing booking information from a Portuguese hotel. The dataset can be accessed [here](https://github.com/LingAdeu/hotel-booking-cancelation-prediction/blob/main/data/dataset.csv).

## Getting Started
To replicate my analysis or explore the data further, kindly follow the following steps:
1. Clone this repository to your local machine.
```bash
git clone https://github.com/LingAdeu/hotel-booking-cancelation-prediction.git
```
2. Ensure that all necessary dependencies are installed, especially Python and Jupyter Notebook. All libraries are specified on file requirements.txt.
3. Run my Jupyter Notebook file (`*.ipynb`) in [notebook](https://github.com/LingAdeu/hotel-booking-cancelation-prediction/tree/main/notebook) folder to reproduce the analysis. This notebook contains the detailed implementation of data preprocessing, model training, and evaluation. Alternatively, kindly check this Jupyter Notebook Viewer URL to see the notebook.

## Folder Organization

    .
    ├── README.md                           <- The top-level README for using this project.
    ├── data
    │   ├── data_description.txt            <- Data description
    │   └── dataset.csv                     <- Dataset
    ├── docs                                <- Documents associated with this projects
    ├── image                               <- Images for this project
    │   └── flow.png
    ├── model                               
    │   └── final_model.pkl                 <- Final model 
    ├── notebook                            <- Jupyter notebook file for building the model
    │   └── notebook.ipynb
    └── requirements.txt                    <- The requirements file for reproducing the environment.
                                               Generated using `pip freeze > requirements.txt`

## Feedback
If there are any questions or suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>