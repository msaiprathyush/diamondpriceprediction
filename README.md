# Diamond Price Prediction

## Introduction

The goal of this project is to predict the price of given diamonds using regression analysis. The dataset contains various attributes of diamonds, such as carat weight, cut quality, color, clarity, dimensions, etc., which are used as independent variables to predict the price of the diamonds.

## Dataset Description

The dataset consists of the following attributes:

- **id**: Unique identifier of each diamond
- **carat**: Carat weight of the diamond
- **cut**: Quality of diamond cut
- **color**: Color grade of the diamond
- **clarity**: Clarity grade of the diamond
- **depth**: Height of the diamond (in millimeters) measured from the bottom tip (culet) to the top surface (table)
- **table**: Percentage of the diamond's width relative to its overall width
- **x**: Length of the diamond (in millimeters)
- **y**: Width of the diamond (in millimeters)
- **z**: Depth of the diamond (in millimeters)

## Target Variable

- **price**: Price of the given diamond

## Repository Structure

The repository contains the following files and directories:

- **assets**: Directory containing images for README.md.
- **src**: Directory containing source code for the project.
- **requirements_dev.txt**: List of Python packages required for development.
- **setup.py**: Script for installing the project as a local package.
- **app.py**: Main application script.
- **Dockerfile**: Dockerfile for creating a dockerized container.
- **README.md**: Overview of the project and usage instructions.

## Usage

To run the project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required Python packages by running:
   ```bash
   pip install -r requirements_dev.txt
3. Install source code as local package using:
   ```bash
   python setup.py install
4. Run Script using:
   ```bash
   python app.py
5. Alternatively, you can use Dockerfile to create a dockerized container and run the application.
Access the model by navigating to localhost:8000/predict in your web browser.
Fill the UI with the required values and click on submit to get the estimated price for the diamond.


## Screenshots

![Home_page](https://github.com/msaiprathyush/diamondpriceprediction/assets/122264714/24f838c9-f737-4511-8ca7-d4a6bb0d3ec0)

![Airflow](https://github.com/msaiprathyush/diamondpriceprediction/assets/122264714/9b667b59-e1ec-4464-b5de-06f436efac67)
![result](https://github.com/msaiprathyush/diamondpriceprediction/assets/122264714/a18929b8-2284-43d6-a891-bf7af1bd696c)


License
This project is licensed under the MIT License.

Acknowledgements
We would like to acknowledge the creators of the dataset for making it publicly available for research purposes.
