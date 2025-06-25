# Predict the Fare of a Taxi Ride in Chicago, Illinois

<p>
  <img alt="Chicago Taxi Picture" src="imgs/chicago_taxi_pictures.jpeg"/>
</p>

[img source: Chicago Taxi Cabs Guide - Getting Around (Travel Guide) | Episode# 3](https://www.youtube.com/watch?v=-SOfiUWDFsM)

## Project Description

This project came out of the `Machine Learning Crash Course`: [Linear Regression](https://developers.google.com/machine-learning/crash-course/linear-regression)

The goal of the project is to take a real dataset to train a model to predict the fare of a taxi ride in Chicago, Illinois.

### What this Project Does Specifically

The project:

- Loads and inspects the taxi cab data
- Preprocesses/cleans the data
- Performs exploratory data analysis
- Creates a Deep Learning Keras built neural network to build the prediction model
- Conducts analysis of the predictive model results
- Makes any improvements

---

## Objective

The project contains the key elements:

- `Deep Learning` for neural networks building,
- `Git` (version control),
- `Jupyter` Python coded notebooks,
- `Keras` to build nodes and layers,
- `Matplotlib` visualization of spaces,
- `Numpy` for arrays and numerical operations,
- `Pandas` for dataframe usage,
- `Plotly` for visualization,
- `Python` the standard modules,
- `TensorFlow` to build nodes and layers,
- `Type` hinting using `Pylance`, and
- `uv` package management including use of `ruff` for linting and formatting

## Tech Stack

![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-FF0000?style=for-the-badge&logo=keras&logoColor=white)
![Matplotlib](https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)
![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## Getting Started

Here are some instructions to help you set up this project locally.

---

## Installation Steps

The Python version used for this project is `Python 3.11` to be compatible with TensorFlow.

Follow the requirements for using TensorFlow [here](https://www.tensorflow.org/install/pip#macos)

use `uv pip install tensorflow`

- Make sure to use python versions `Python 3.9–3.12
- pip version 19.0 or higher for Linux (requires manylinux2014 support) and Windows. pip version 20.3 or higher for macOS.
- Windows Native Requires Microsoft Visual C++ Redistributable for Visual Studio 2015, 2017 and 2019

### Clone the Repo

1. Clone the repo (or download it as a zip file):

   ```bash
   git clone https://github.com/beenlanced/ml_predict_taxi_fares.git
   ```

2. Create a virtual environment named `.venv` using `uv` Python version 3.11:

   ```bash
   uv venv --python=3.11
   ```

3. Activate the virtual environment: `.venv`

   On macOs and Linux:

   ```bash
   source .venv/bin/activate #mac
   ```

   On Windows:

   ```bash
    # In cmd.exe
    venv\Scripts\activate.bat
   ```

4. Install packages using `pyproject.toml` or (see special notes section)

   ```bash
   uv pip install -r pyproject.toml
   ```

### View Notebooks to see Exploratory Data Analysis and Predicative Model Construction

---

## Dataset

The dat used is a subset of data derived from the [City of Chicago Taxi Trips](https://www.google.com/url?q=https%3A%2F%2Fdata.cityofchicago.org%2FTransportation%2FTaxi-Trips%2Fwrvz-psew) dataset.

---

### Final Words

Thanks for visiting.

Give the project a star (⭐) if you liked it or if it was helpful to you!

You've `beenlanced`! 😉

---

## Acknowledgements

I would like to extend my gratitude to all the individuals and organizations who helped in the development and success of this project. Your support, whether through contributions, inspiration, or encouragement, have been invaluable. Thank you.

Specifically, I would like to acknowledge:

- As this work was a project for the Google `Machine Learning Crash Course`: [Linear Regression](https://developers.google.com/machine-learning/crash-course/linear-regression), a shout out to the folks at Google.

- [Hema Kalyan Murapaka](https://www.linkedin.com/in/hemakalyan) and [Benito Martin](https://martindatasol.com/blog) for sharing their README.md templates upon which I have derived my README.md.

- The folks at Astral for their UV [documentation](https://docs.astral.sh/uv/)

---

## License

This project is licensed under the Apache License - see the [LICENSE](./LICENSE) file for details
