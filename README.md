# Used_Car_Price_Prediction
## Used Car Prediction System
This project implements a used car prediction system using machine learning and data preprocessing techniques. The dataset used for this project contains various features related to different car models, such as car specifications, price, engine details, and more. The goal of this system is to predict the price of a used car based on these features.

## Table of Contents
1.Installation
2.Usage
3.Data Description
4.Data Preprocessing
5.Model Development
6.Results
7.Contributing
8.License
# Installation
Clone this repository to your local machine:

bash
Copy
git clone https://github.com/yourusername/used-car-prediction-system.git

Install the required dependencies:

bash
Copy
pip install -r requirements.txt

# Usage

Data Loading: The dataset (output.csv) is loaded into a Pandas DataFrame.
Preprocessing: Missing values are handled and columns are renamed as necessary for consistency.
Feature Engineering: Features like city-mpg are converted into more useful units like city-L/100km.
Data Analysis and Visualization: Visualizations are generated using matplotlib and seaborn to explore the relationships between car features and prices.
Model Training: Machine learning models can be trained to predict the price of the car.

The following Python libraries are used in this project:
pandas
numpy
matplotlib
seaborn
scipy

## Data Description
The dataset contains the following columns:

symboling: A numerical rating of the car's risk (higher values indicate a higher risk).
normalized-losses: A measure of how much loss the car has after depreciation.
make: The manufacturer of the car.
fuel-type: The type of fuel the car uses (e.g., gas, diesel).
aspiration: The engine aspiration type (e.g., standard, turbo).
num-of-doors: The number of doors in the car.
body-style: The style of the car's body (e.g., sedan, convertible).
drive-wheels: Type of drive (e.g., rear-wheel drive, front-wheel drive).
engine-location: The location of the car's engine (e.g., front).
wheel-base, length, width, height: Physical dimensions of the car.
curb-weight: The weight of the car.
engine-type: Type of engine used in the car.
num-of-cylinders: Number of cylinders in the car's engine.
engine-size: The size of the engine.
fuel-system: Type of fuel system used in the car.
bore, stroke: Engine parameters related to the engine's dimensions.
compression-ratio: Ratio of the cylinder volume.
horsepower: The power output of the car's engine.
peak-rpm: The maximum revolutions per minute of the engine.
city-mpg, highway-mpg: Mileage in miles per gallon for city and highway driving.
price: The price of the car (target variable).

# Data Preprocessing
## Missing Values:
The dataset was inspected for missing values, and the dataset contains no missing or null values after cleaning.

# Data Transformation:
city-mpg was converted to city-L / 100km by applying the formula:
city-L / 100km = 235 / city-mpg.
Data Types:
The data types of columns were examined, ensuring all data is in the correct format (e.g., numerical or categorical).

# Model Development
Several machine learning models (e.g., linear regression, decision trees) can be trained to predict the car price based on the features provided. The model evaluation will be carried out using metrics such as R², Mean Absolute Error (MAE), and others.

# Results
The performance of the trained model can be evaluated using various metrics, which are discussed in the Jupyter notebooks provided. Visualizations help to understand feature importance and the model's prediction accuracy.

Contributing
Feel free to fork this repository and submit pull requests if you have improvements or fixes! For any issues or feature requests, please open an issue.

License
This project is licensed under the Ishan License - see the LICENSE file for details.
