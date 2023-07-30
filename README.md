# Bike Sharing Demand Prediction

![Bike Sharing](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.sciencedirect.com%2Fscience%2Farticle%2Fpii%2FS0968090X18306764&psig=AOvVaw2K_LSWx1OwDgjqaTt34zEs&ust=1690827066333000&source=images&cd=vfe&opi=89978449&ved=0CBEQjRxqFwoTCNiOheeDt4ADFQAAAAAdAAAAABAE)

## Introduction

Bike-sharing systems have gained tremendous popularity as an eco-friendly and convenient mode of transportation in urban areas. These systems allow users to rent bikes for short periods, promoting sustainable mobility and reducing traffic congestion. However, ensuring an optimal number of bikes available at different locations and times is crucial for a seamless user experience.

The "Bike Sharing Demand Prediction" project aims to forecast the demand for bikes in a bike-sharing system using machine learning Regression techniques. By accurately predicting bike rental demand, the service provider can efficiently manage their fleet, anticipate user needs, and optimize the overall system performance.

## Dataset

The dataset used in this project can be obtained from [here](https://drive.google.com/file/d/1dZ7p614gC_iwxHwcj-1N0Lc155AGMTJS/view?usp=sharing). It comprises historical bike rental information, capturing various attributes such as date, time, weather conditions, and the number of bikes rented during each hour. The data is split into training and testing sets to facilitate model development and evaluation.

The dataset includes the following features:

Date: date-month-year
Rented Bike count - Count of bikes rented at each hour
Hour - Hour of the day
Temperature-Temperature in Celsius
Humidity - Humidity in %
Windspeed - Windspeed in m/s
Visibility - Visibility in 10m
Dew point temperature - the temperature in Celsius
Solar radiation - Solar radiation in MJ/m2
Rainfall - Rainfall in mm
Snowfall - Snowfall in cm
Seasons - [Winter, Spring, Summer, Autumn]
Holiday - whether the day is considered a holiday [Holiday/No holiday]
Functional Day -whether the day is neither a weekend nor holiday[No(Non Functional Hours), Yes(Functional hours)]

## Installation

To run this project on your local machine, follow the steps below:

1. Copy the Colab NoteBook in your Drive.

2. Run the code in the file.


## Usage

Once the project and its dependencies are installed, you can explore the dataset, train machine learning models, and make predictions using Colab NoteBook.

The main files in this repository are:

- `bike_sharing_prediction.ipynb`: Jupyter Notebook containing a detailed step-by-step process of data preprocessing, model training, and evaluation.



Feel free to modify the code to suit your specific needs and experiment with different algorithms and techniques.

## Models

Several machine learning models have been implemented for bike demand prediction:

- **Linear Regression**: A simple and interpretable model used as a baseline for comparison.
- 
- **Random Forest**: An ensemble model capable of handling non-linear relationships and capturing complex patterns in the data.
- 
- **XGBoost**: A powerful gradient boosting algorithm known for its predictive accuracy and efficiency.

The model training code can be found in the Google Collab Notebook Provided in this repository.

## Evaluation

To assess the performance of each model, we utilize common regression metrics such as:

- **Mean Absolute Error (MAE)**: The average absolute difference between predicted and actual values.
  
- **Root Mean Squared Error (RMSE)**: The square root of the average squared difference between predictions and actual values, which penalizes larger errors more heavily.
  
- **R-squared (R2)**: A statistical measure indicating the proportion of variance in the target variable that is predictable from the input features.

The evaluation results for each model are presented in the Collab Notebook.

## Contributing

Contributions to this project are highly appreciated! If you encounter any issues or have ideas to enhance the models or codebase, please don't hesitate to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to use, modify, and distribute the code under the terms of this license.

---

We hope this comprehensive README provides you with all the necessary information to get started with your "Bike Sharing Demand Prediction" project. Should you require any further assistance or have questions, please feel free to reach out to us.

Happy predicting! :bike:
