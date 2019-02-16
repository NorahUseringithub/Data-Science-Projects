# Project 3 - Ames Housing Data and Kaggle Challenges

Welcome to Project 3! It's time to start modeling. The goal for this project is
two-fold:

1. Creating and iteratively refining regression and classification models
2. Using [Kaggle](https://www.kaggle.com/) to practice the modeling process

You are tasked with creating two models with the highest possible accuracy based on the Ames Housing Dataset. Those models will predict the following:

- The price of a house at sale (regression)
- Whether a house sale was abnormal or not (classification)

The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses. While the two models you make will predict different targets (and will require different features, model choices, and hyperparameters), you will be able to use the rich knowledge you develop from generating one model to help inform the other (and vice versa!)

Secondly, we are hosting two competitions on Kaggle (one for the regression and one for the classification) to give you the opportunity to practice the following skills:

- Refining models over time
- Use of train-test split, cross-validation, and data with unknown values for the target to simulate the modeling process
- The use of Kaggle as a place to practice data science

## Set-up

Before you begin working on this project, please do the following:

1. Sign up for an account on [Kaggle](https://www.kaggle.com/)
2. **IMPORTANT**: Click these links ([Regression Challenge Sign Up](https://www.kaggle.com/t/652d47357d0c484b93045a47b86009ab) and [Classification Challenge Sign Up](https://www.kaggle.com/t/4a7340431eab4058a4da9b91f67fe8ea)) to **join** the competition (otherwise you will not be able to make submissions!)
3. Review the material on the [DSI-MiSK-02 Regression Challenge](https://www.kaggle.com/c/dsi-regression/overview)
4. Review the material on the [DSI-MiSK-02 Classification Challenge](https://www.kaggle.com/c/dsi-classification/overview)

## The Modeling Process

1. The train and test datasets for both challenges are the **same**, with the exception of the target that you are trying to predict.
2. The train dataset has all of the columns that you will need to generate and refine your models. The test dataset has all of those columns except for the two targets that you are trying to predict in your Regression and Classification models.
3. Generate your regression and classification models using the training data. We expect that within this process, you'll be making use of:
    - train-test split
    - cross-validation / grid searching for hyperparameters
    - strong exploratory data analysis to question correlation and relationship across predictive variables
    - code that reproducibly and consistently applies feature transformation (such as the preprocessing library)
4. Predict the values for your target columns in the test dataset and submit your predictions to Kaggle to see how your model does against unknown data.
    - **Note**: Kaggle expects to see your submissions in a specific format. Check each challenge's page to make sure you are formatting your files correctly!
