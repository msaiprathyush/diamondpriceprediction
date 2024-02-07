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
